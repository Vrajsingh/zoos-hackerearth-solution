google-site-verification: google0d3c9f5114f86493.html

# zoos-hackerearth-solution
My cpp zoos hackerearth solution

#include<iostream>
#include<string>
using namespace std;
int main()
{
int x=0, y=0;
 char ch[20]={};
 int len = sizeof(ch)/sizeof(ch[0]);
 cin.getline(ch,len);
 for( int i=0 ; i<len ; i++ )
 {
    if( ch[i]=='z' )
    x = x + 1;
    else if( ch[i] == 'o')
    y = y + 1;
    else
    break;
 }
 if(y == 2*x)
 cout<<"Yes"<<endl;
 else
 cout<<"No"<<endl;
 return 0;
}



by VISHAL RAJ

