//# Problem-UTKPLC-
//December long challenge 2021 codechef , div-3 , Problem: UTKPLC  
#include<iostream>
using namespace std;
int main(){
int t;
cin>>t;
while (t--){
    char first, second, third;
    char x,y;
    cin>>first>>second>>third;
    cin>>x>>y;
    if(x == first && y == second )
        cout<<x<<endl;
    else if (x==second && y==third)
        cout<<x<<endl;
     else if (x==first && y==third)
         cout<<x<<endl;
    else if (y==first && x==second)
        cout<<y<<endl;
    else if (y==first && x==third)
        cout<<y<<endl;
    else if (y==second && x==third)
        cout<<y<<endl;
}
return 0;
}
