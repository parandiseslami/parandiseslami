#include <iostream>
using namespace std;

class user_info{
	public:
		int user_id=1234
		string name='medisa';
		string last_name='asghari'
};

class user_acount{
	int user_id=1234;
	int password=123456;
	int account_balance=12200;
};

int main(){
	int user_id,pass;
	cout<<"please enter your user id"<<endl;
	cin>>user_id;
	cout<<"please enter your password"<<endl;
	cin>>pass;
	int function;
	cout<<"availabe functions are :"<<endl<<"please enter the number of function that you want to do:"<<endl;
	
	cin>>function;
	switch (function){
		case1:
			//withdraw money
			cout<<"please enter the amount of money that you ant to take:";
			int amount;
			cin>>amount;
			user_account balance;
	}
}
