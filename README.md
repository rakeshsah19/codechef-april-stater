# codechef-april-stater
/*april stater:Problem Code:CCISLAND*/
#include <bits/stdc++.h>
using namespace std;

int main(){
    int t;
    cin>>t;
    while(t--){
        int x,y,xr,yr,d;
        cin>>x>>y>>xr>>yr>>d;
        if((d*xr<=x)&&(d*yr<=y)){
            std::cout << "YES" << std::endl;
        }
        else{
            cout<<"NO"<<endl;
        }
    }
    return 0;
}
