# Array
#include <iostream>

using namespace std;

　

int main()

{

int one, two, three, four;

one= 001;

two= 002;

three= 003;

four= 004;

int *ptr1;

ptr1 = &one; // &one indicates that the address

cout << "The value of one is " << one << endl << endl; //initialize all the four interger variables to any four numbers

cout << "The value of two is " << one << endl << endl; //write the cout statement to see values for each variable

cout << "The value of three is " << one << endl << endl; //compile and run. get the output on a piece of paper

cout << "The value of four is " << one << endl << endl;

cout << "The value of *ptr1 is " << *ptr1 << endl << endl;

cout << "The value of &one is " << &one << endl << endl;

cout << "The value of ptr1 is " << ptr1 << endl << endl;

　

　

int number[] ={ 100, 200, 300};

for (int i=0; i<3; i++){ //use for loop to display the contents of array

int ptr1 = number; // ptr1 is a pointer variable that points to an int

cout << number [i];

}

cout << "The first element of the array is: " << *number << endl; //display the value of array

cout << "The second element in the array is : " << * (number +1) << endl; //initialize all the four interger variables to any four numbers

cout << "The thirs element in the array is: " << * (number +2) << endl;


return 0;

}　

//initialize all the four interger variables to any four numbers

//write the cout statement to see values for each variable

//compile and run. get the output on a piece of paper

//write the cout statement to see address for each such as &one, &two etc.

//compile and run. get the output on a piece of paper

//look at the difference between two addresses and note them down

//How much space an int var can hold?

// Are they same or different? Find what are same and what are different?

//Complete with the other variables as well.

//Change the name of the four variable names to five, six, seven and eight

//Compile, run and see if any difference

//intiatize the pointer with array

//ptr1 is the address of the first element

//display the first element and it's address

//display the second element and it's address

//display the third element and it's address

//compile and run
