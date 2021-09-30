#include <iostream>
using namespace std;
int prime(int x);
int main ()
{   
    int n;
    cout<<" Enter a positive integer \n";
    cin>>n;
    int p;
    for(p=2;p<=(n/2);p++)
    {
        int m=(n-p);
        if(prime(p)==1 && prime(m)==1)
        {
            cout<<n<<" = "<<p<<" + "<<m<<endl;
        }
    }
    return 0;
}
int prime (int x)
{   
    int m=(x/2);
    for(int i=2;i<=m;i++)
     {
         if((x%i)==0)
      {
         return 0;
         break;
       } 
      } 
      return 1;

}
