# Codechef-CGYM
#include <iostream>
using namespace std;

int main() {
	// your code goes here
	int X, Y, Z,T;
	cin >> T;
	for (int i = 0; i < T; i++) {
		cin >> X >> Y >> Z;
		if (Z < X)
			cout << 0 << endl;
		if (Z >= X && Z < X + Y)
			cout << 1 << endl;
		if (Z >= X + Y)
			cout << 2 << endl;
	}
	return 0;
}
