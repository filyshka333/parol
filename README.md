#include <iostream>
using namespace std;
int main () 
{
	setlocale(LC_ALL, "Russian");
	int passworld;
	while(1){
		cout << "\nВведите пароль : ";
		cin >> passworld;
		{
			if (passworld == 1337){
				cout << "\nВерный пароль\n-----------------\n";
			}
			else {
				cout << "\nПопробуйте еще  раз\n-----------------\n";
			}
		}
	}
		
	return 0;
}
