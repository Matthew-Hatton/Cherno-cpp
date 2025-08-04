Code, notes, and resources for Cherno's C++ course (https://www.youtube.com/watch?v=18c3MTX0PK0\&list=PLlrATfBNZ98dudnM48yfGUldqGD0S4FFb\&ab\_channel=TheCherno).



### **### NOTES ###**

#### Welcome to C++



Why might someone want to use C++?

* Useful for when we want to have control over our hardware
* We can control every actions our CPU executes
* Good for wide platform support. All OS's on PC/MAC and phones, games consoles etc.

#### 

#### How does C++ work?

* Anything that starts with a '#' is called a pre-processor statement

 	- First thing a compiler does when it receives a source file is it pre-			processes all your pre-processor statement

 	- Include finds a file (header), and pastes all into session

* Main function is the entry point. Executes lines in order
* Main function is a special case where we actually don't have to return anything
* '<<' is a function. We push our text into cout and that makes it print.
* Configuration is a set of rules that apply to a particular project
* Every cpp file gets compiled into an obj file, then linker comes in and attaches all obj files and glues them together into one exe file
* Functions from other files can be used in our main function by using a function declaration. The linker will then find the function obj file and attach all obj's together
