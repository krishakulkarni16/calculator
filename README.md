#include<iostream>
 using namespace std;
int main(){
  int a,b;
char n;
  cout<<"enter a operator"<<endl;
  cin>>n;
  cout<<"enter 1st no:"<<endl;
  cin>>a;
   cout<<"enter 2nd no:"<<endl;
  cin>>b;
if(n=='+') {
    cout<<(a+b)<<endl;
}else if( n=='-'){
    cout<<(a-b)<<endl;
    }
   else if (n=='*'){
    cout<<(a*b)<<endl;
   }
   else if(n=='/'){
    cout<<(a/b)<<endl;
   }
   else if (n=='%'){
    cout<<(a%b)<<endl;
   }
   else{
    cout<<"invalid"<<endl;
   }
return 0;
    }
