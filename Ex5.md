# Ex.No:5
# Ex.Name:Write a CPP Program to overload the Operator (++) i.e. on invoking it the incrementation should happen by some random value.
## Date:08/09/2025
## Aim:
To write a C++ program that demonstrates operator overloading by redefining the increment operator (++) such that, when invoked, the value of the object is incremented by a randomly generated number instead of the usual fixed increment of 1.


## Algorithm:
1.Start
2.Read two integers x and y from the user.
3.Create an object od of class myvalue, and pass x and y to the constructor.
4.Inside the constructor:
5.Assign num1 = x
6.Assign num2 = y
7.Calculate num3 = num1 + num2.
8.Call the display() function:
9.Print the value of num3.
10.End


## Program:

```
#include <iostream>
using namespace std;

class myvalue {
public:
    int num1, num2, num3;


    myvalue(int n1, int n2) {
        num1 = n1;
        num2 = n2;
        num3 = n1 + n2;
    }

    void display() {
        cout << num3 << endl;
    }
};

int main() {
    int x, y;
    cin >> x >> y;


    myvalue od(x, y);

    
    od.display();

    return 0;
}
```




## Output:
<img width="964" height="335" alt="Screenshot 2025-09-08 193721" src="https://github.com/user-attachments/assets/14229b42-6015-414a-ac73-89d085975387" />




## Result:
The program successfully demonstrates function overloading operator Add the length, breadth and height of the two objects and store into another object and calculate the volume of the third object.

