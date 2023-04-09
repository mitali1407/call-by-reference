# call-by-reference


Actual parameters: The parameters that appear in function calls.
Formal parameters: The parameters that appear in function declarations.

![image](https://user-images.githubusercontent.com/110607289/230778516-823decbf-0298-4cd5-9827-821e6e181fea.png)


The call by reference method of passing arguments to a function copies the address of an argument into the formal parameter. 
Inside the function, the address is used to access the actual argument used in the call. 
It means the changes made to the parameter affect the passed argument.

To pass a value by reference, argument pointers are passed to the functions just like any other value. 

It shows that the change has reflected outside the function as well, unlike call by value where the changes do not reflect outside the function.

![image](https://user-images.githubusercontent.com/110607289/230778552-4ba1b90e-9635-4305-91fe-1d53950336e4.png)
