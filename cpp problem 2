#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */ 
    vector<int> a(4),b(4),c(4),d(4);
     for(int i=0;i<4;i++){
         cin>>a[i]>>b[i]>>c[i];
         
     }
    for(int i=0;i<4;i++)
    {
        for(int j=0;j<3;j++)
        {
            if(b[j]>b[j+1])
            {
                swap(a[j],a[j+1]);
                swap(b[j],b[j+1]);
                swap(c[j],c[j+1]);
            }
        }
    }
    int p=0;
    for(int i=0;i<4;i++)
    {
        if(i==0)
            d[i]=0;
        else
           d[a[i]-1]=p-b[i];
        p+=c[i];
    }
    for(int i=0;i<3;i++)
    {
        cout<<"P"<<i+1<<" "<<"(WT="<<d[i]<<"), ";
    }
    cout<<"P"<<4<<" "<<"(WT="<<d[3]<<")";
    return 0;
}
