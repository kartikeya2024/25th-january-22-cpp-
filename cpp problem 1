#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */ 
    vector<int> a(4),d(4,0);
     for(int i=0;i<4;i++){
         cin>>a[i];
         
     }
   
    for(int i=1;i<4;i++)
    {
        d[i]+=d[i-1]+a[i-1];
    }
    for(int i=0;i<3;i++)
    {
        cout<<"P"<<i+1<<" "<<"(WT="<<d[i]<<"), ";
    }
    cout<<"P"<<4<<" "<<"(WT="<<d[3]<<")";
    return 0;
}
