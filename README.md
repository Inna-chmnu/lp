#include <iostream>
#include "math.h"
using namespace std;
int main()
{
	float a, b, c, x;
	double f;
	bool pr = true;
	cout << "Enter a,b,c,x\n";
	cin >> a >> b >> c >> x;
	if (x < 1 && c != 0)
	{         f = a * pow(x, 2) + b / c;
	}
	else 
		if (x < 1 && c == 0)
		{         f = x - a / pow(x - c, 2);
		}
		else
		{         f = pow(x, 2) / pow(c, 2);
		}
	cout << "f = " << f;

}
