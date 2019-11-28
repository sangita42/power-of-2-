#include<bits/stdc++.h>
using namespace std;
int main()
{
int t;
cin>>t;
while(t--)
{
long long int n;
cin>>n;
int count=0;
while(n)
{
if(n&1)
{
count++;
}
n>>=1;
}
if(count==1)
{
cout<<"YES"<<endl;
}
else{
    cout<<"NO"<<endl;
    }
    
}
return 0;
}
