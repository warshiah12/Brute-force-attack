# Brute-force-attack
[ while-loop program ]
#include<iostream>
using namespace std;
int main()
{
	string passcode = "246"; //declaring variable 'passcode' with datatype string and initialising value to it
	string userpass;       //declaring variable with datatype string
	while (passcode !=userpass )   /*while condition checks whether the userinput is equal to the passcode or not.
								   if it's not equal to passcode then it will ask the user to enter the 
								   password again until the correct password is entered*/
	{
		cout << "Please enter the passcode: ";
		cin >> userpass;
	}
	
	cout << "Bingo!" << endl;
	cin.get();
	return 0;

}
