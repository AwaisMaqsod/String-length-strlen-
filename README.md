//String-length-strlen-
//length of a string in classes , c++ Oop 
#include<iostream>
#include<cstring>
using namespace std;
class stringg{
	public:
		char st1[20],st2[20];
		int len1,len2;
		
		void get_Data(){
			cout<<"Enter 1st string : "<<endl;
			cin>>st1;
			cout<<"Enter 2nd String : "<<endl;
			cin>>st2;
			}
				void set_Data(){
			len1=strlen(st1);
			cout<<"Length of st1 : "<<len1<<endl;
			len2=strlen(st2);
			cout<<"Length of st2 : "<<len2<<endl;
			}
};

int main(){
	stringg tt;
	tt.get_Data();
	tt.set_Data();
	
	return 0;
}
