# Ex.No:1
# Ex.Name:Write A CPP Program to allocate memory dynamically for a double array. (Note: p_array = new type [size]; )
# Date:08/09/2025
## Aim:
To write a C++ program that demonstrates dynamic memory allocation for a variable using the new operator. The program allocates memory at runtime for a double variable, stores user input, and displays the value


## Algorithm:
1.Start
2.Define a class var_space.
3.Inside the class, define the function allocateSpace():
4.Use the new operator to dynamically allocate memory for a double variable.
5.Accept a double value from the user and store it in the allocated memory.
6.Print the stored value.
7.In the main() function:
8.Create an object of the class var_space.
9.Call the function allocateSpace() using the object.
10.End

## Program:

```
#include <iostream>
using namespace std;

class var_space
{
public:
    void allocateSpace()
    {
        double *val = new double;
        
        cin >> *val;
        cout << "Float Value is : " << *val << endl;
        
    }
};

int main()
{
    var_space obj;
    obj.allocateSpace();    
}
```



## Output:
<img width="840" height="201" alt="Screenshot 2025-09-08 194644" src="https://github.com/user-attachments/assets/808f7cd0-99a1-4946-927f-78dca471f4fc" />




## Result:
The program dynamically allocates memory for a double type variable at runtime, accepts input from the user, and successfully displays the stored value.


