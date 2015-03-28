# -Tut5-Poly-

#include <iostream>
#include <cmath>
using namespace std;

//Circle
int main () 
{

    float radius;
    float circumference;
    float area;

    cout << "Please enter the radius of a circle: ";
    cin >> radius;
    cout << "\n";

    circumference = 2 * pi * radius;
    area = pi * radius * radius;

    return circumference;
    return area;

} 


//Rectangle
int main () 
{

    float length;
    float width;
    float perimeter;
    float area;

    cout << "Please enter the length of a rectangle: ";
    cout << "Please enter the width of a rectangle: ";
    cin >> length;
    cin >> width;
    cout << "\n";

    perimeter = 2 * (length+width);
    area = length * width;

    return area;
    return perimeter;

} 

//Triangle
int main () 
{

    float base;
    float height;
    float perimeter;
    float area;
    float side1;
    float side2;

    cout << "Please enter the base of a triangle: ";
    cout << "Please enter the side1 of a triangle: ";
    cout << "Please enter the side2 of a triangle: ";
    cout << "Please enter the height of a triangle: ";
    cin >> height;
    cin >> side1:
    cin >> base;
    cout << "\n";

    perimeter = side1+side2+base;
    area = (base * height)/2;

    return area;
    return perimeter;

} 

