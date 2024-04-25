*Hollow Diamond Pattern in C++ with recursion*
This C++ program generates a hollow diamond pattern based on user input. It consists of two functions: one for printing the regular diamond pattern and another for printing the inverted diamond pattern.

How to Use
Clone the Repository:

bash
Copy code

git clone https://github.com/your-username/hollow-diamond-pattern.git
Compile the Code:

bash
Copy code
g++ main.cpp -o hollow_diamond
Run the Program:

bash
Copy code
./hollow_diamond
Enter the Number of Rows:

The program will prompt you to enter the number of rows for the hollow diamond pattern.
View the Output:

The program will then display the hollow diamond pattern based on the provided input.
Code Explanation
print_hollow_diamond(int num): Main function that calls the inverted pattern function followed by the regular pattern function.

print_pattern(int num, int i, char char1, char char2, char char3, char char4): Function to print a single iteration of the regular diamond pattern.

print_inverted_pattern(int num, int i, char char1, char char2, char char3, char char4): Function to print a single iteration of the inverted diamond pattern.

print(int n, char ch): Helper function to print a character ch n times.

Example
cpp
Copy code
#include<iostream>
using namespace std;

// ... (code)

int main() {
    int num;
    cout<<"\n ENTER THE ROWS = ";
    cin>>num;

    print_hollow_diamond(num);

    return 0;
}
Author:
*Abdul Ahad*
Feel free to contribute, report issues, or suggest improvements! 🚀
