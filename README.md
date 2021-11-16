# loopsreview



//Execute the code to see the issue
#include <iostream>
#include <string>
using namespace std;
int main()
{
int y;
cout << "Enter a number you want the table of: " << endl;
cin >> y;
while (cin.fail())
{ cout << "Invalid command enter the number again: " << endl;
  cin.clear();
  cin.ignore(1000,'\n');
cin >> y;
}
for (int x = 0; x <= 10; x++)
{ cout << y << " x " << x << " = " << y * x << endl;
}
}
     
                                                   
 Falling star                                                  
 #include <iostream>
using namespace std;


int main() {

	int i = 1;
	int j = 1;
	while (i <= 5) {
		j = i;
		while (j <= 5) {
			cout << "*";
			j++;
		}
		cout << endl;
		i++;
	}
  return 0;
  }
  
  #include <iostream>
using namespace std;

//Rising star
int main() {
  int i=5;
	int j = 1;
	while (i >= 1) {
		j = i;
		while (j <= 5) {
			cout << "*";
			j++;
		}
		cout << endl;
		i--;
	}
	return 0;
}
                
 //Falling and rising star
                #include <iostream>
using namespace std;


int main() {

	int i = 1;
	int j = 1;
	while (i <= 5) {
		j = i;
		while (j <= 5) {
			cout << "*";
			j++;
		}
		cout << endl;
		i++;
	}
	 i=5;
	 j = 1;
	while (i >= 1) {
		j = i;
		while (j <= 5) {
			cout << "*";
			j++;
		}
		cout << endl;
		i--;
	}

	return 0;
}
                
                
//Factorial               
#include<iostream>
using namespace std;


int main() {
	int fac=1;
	int num;
	cout << "Enter any number (Not zero)" << endl;
	cin >> num;
	while (cin.fail()) {
		cout << " Any number not any alphabet." << endl;
		cin.clear();
		cin.ignore(1000, '\n');
		cin >> num;
	}
	for (int a = 1;a <= num; a++) {
		fac = fac * a;
	}
	cout << "The factorial is " << fac << endl;
	return 0;
} 
