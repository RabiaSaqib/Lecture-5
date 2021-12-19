# Lecture-5


//Lecture 5 - Biography - Part 1

#include <iostream>
using namespace std;

int main()
{
string name = "Rabia";
int age = 15;
string home_town = "Ajman";


	cout << "My name is : " << name << endl;
	cout << "My age is : " << age << endl;
	cout << "My home town is ; " << home_town << endl;

	return 0;
}
*/




/*
//Lecture 5 -Biography -Part 2

#include <iostream>

using namespace std;

string name = "Rabia";
int age = 15;
string home_town = "Ajman";

int main()
{
	
	cout << "Enter your name : " << endl;
	cin >> name;
	cout << "Enter your age : " << endl;
	cin >> age;
	cout << "Enter your Home town : " << endl;
	cin >> home_town;


	return 0;
}

  
  
  
  
#include <iostream>
#include <string>

using namespace std;

int main()
{
	int f;
	double c;
	cout << "Enter temperature in Ferenhite : " << endl;
	cin >> f;

	c = (f - 32) * 5 / 9;

	cout << "Temperature in Celcius : " << c << endl;


	return 0;

}
	
	

	
	
/*
//Temperature C to F
#include <iostream>
#include <string>
using namespace std;

int main()
{
	double x, y;
	cout << "Enter the temperature in celcius to be converted into Fahrenheit \n";
	cin >> x;
	y = (x * 1.8) + 32;
	cout << "The temperature in Fahrenheit is: " << y << endl;
}

*/

	
	
	
	
	/*
//Circles
#include <iostream>
#include <string>
using namespace std;

int main()
{
	double r, a, c;
	cout << "Enter the radius to calculate the area and circumference of the circle \n";
	cin >> r;
	a = 3.14 * r * r;
	c = 2 * 3.14 * r;
	cout << "The area of the circle is: \n " << a << endl;
	cout << "The circumference  of the circle is: \n " << c << endl;
}
*/

	
	
	
	
	//Rectangle Triangle and Squares

#include <iostream>
#include <string>
using namespace std;

int main()
{
	double length, width, rect, tri, sq;
	cout << "\n Calculating the area of Rectangle, Triangle and Square shapes\n";
	cout << "Enter the length:\n";
	cin >> length;
	cout << "\nEnter the width : \n";
	cin >> width;

	rect = length * width;
	tri = (length * width) * 0.5;
	sq = length * length;

	cout << "\nThe area of rectangle : \n" << rect;
	cout << "\nThe area of triangle: \n" << tri;
	cout << "\nThe area of  square: \n" << sq;
}

	
	
	
	
	
	
