#include <iostream>
 #include<bits/stdc++.h>
using namespace std;

int main(int argc, char** argv)
{
int i,j,m,n,a[100];
cin>>m>>n;
for(i=0;i<m+n;i++)
{
    cin>>a[i];
}
sort(a,a+(m+n));
for(i=0;i<m+n;i++)
{
    if(a[i]!=a[i+1])
    {
        cout<<a[i]<<" ";
    }
}
}
