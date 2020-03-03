//hello_world
//test program
#include <iostream>
#include <string>

using std::string;
using std::cout;
using std::endl;
using std::cin;

int main() {
	cout << "What is your first name?" << endl;
	string name;
	cin >> name;
	cout << "Hello " << name << endl;

	return 0;
}
