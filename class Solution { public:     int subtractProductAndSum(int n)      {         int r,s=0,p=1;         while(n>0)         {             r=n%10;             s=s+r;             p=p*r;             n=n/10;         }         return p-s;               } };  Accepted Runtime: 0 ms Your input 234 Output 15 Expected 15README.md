# c-programsclass Solution {
public:
    int subtractProductAndSum(int n) 
    {
        int r,s=0,p=1;
        while(n>0)
        {
            r=n%10;
            s=s+r;
            p=p*r;
            n=n/10;
        }
        return p-s;      
        }
};

Accepted
Runtime: 0 ms
Your input
234
Output
15
Expected
15
