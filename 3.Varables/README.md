A variable is a name given to a storage area that the c progam can manupulate.

Each vaiable has a specific type, which determines the size and layout of the memory allocated to that variable

The basic variable types are listed below:

1. char: Typically a single octet (1 byte). It is an integer type.

2. int: The most natural size of integer for the machine.

3. float: A single-precision floating point value.

4. double: A double-precision floating point value.

5. Represents the absence of type


Variable definition:
A variable definition, specifies a data type, contains a list of one or more variables of that type, and tells the cocmpiler where and how much storage to create for the variable, as follows:

type variable_list;

Here, type must be a valid C data type including char, w_char, int, float, double, bool, or any other user-defined object.

The variable_list of one or more identifier names separated by commas. See example below:

int i, j, k;
char c, ch;
float f, salary;
double d;

In the above example, the line int i, j, k; declares and defines variables i, j, and k; which instruct the compiler to create variables named i, j, and k; of the int type

Variables can also be initialized by an equal sign followed by a constant expression. See example below

extern int d = 3, f = 5;
int d = 3, f = 5;


Variable Declaration:
This provides assurance to the compiler that there exits a variable with the given type and name so that the compiler can proceed for further compilation without requiring the complete detail about the variable. 
A variable declaration is useful when using multiple files and you define your variable in one of the files which will be available at the time of linking the program.
Although a variable can be declared multiple times in your C program, it can only be defined once in a file, a function, or a block of code.
