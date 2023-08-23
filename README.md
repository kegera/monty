
# Monty

Monty is a program that implements stacks and queues using the LIFO (Last-In, First-Out) and FIFO (First-In, First-Out) principles, respectively.

## Installation

To run the Monty program, you need to have a C compiler installed on your system. You can follow these steps to compile and run the program:

1. Clone the repository:

git clone https://github.com/kegera/monty.git 

2. Navigate to the project directory:

cd monty

3. Compile the program using the provided Makefile:

4. Run the program with a Monty file:

./monty file.m
Replace   file.m   with the path to your Monty file.

## Usage

Monty accepts Monty files, which contain a series of instructions to be executed. Each instruction is written on a new line and can be one of the following:

-   push <int>  : Pushes an integer onto the stack.
-   pop  : Removes the top element of the stack.
-   swap  : Swaps the top two elements of the stack.
-   add  : Adds the top two elements of the stack.
-   sub  : Subtracts the top element of the stack from the second top element.
-   mul  : Multiplies the top two elements of the stack.
-   div  : Divides the second top element of the stack by the top element.
-   mod  : Computes the remainder of the division of the second top element by the top element.
-   pchar  : Prints the ASCII value of the top element of the stack.
-   pstr  : Prints the string starting at the top of the stack.
-   rotl  : Rotates the stack to the top.
-   rotr  : Rotates the stack to the bottom.
-   stack  : Sets the format of the data to a stack (LIFO).
-   queue  : Sets the format of the data to a queue (FIFO).

## Examples

Here are a few examples of Monty files:

push 1
push 2
push 3
pall
This will push three integers onto the stack and then print all the elements in the stack.

queue
push 1
push 2
push 3
pall
This will set the format to a queue, push three integers onto the queue, and then print all the elements in the queue.

## Contributing

If you'd like to contribute to Monty, feel free to submit a pull request. Please make sure to follow the project's coding style and guidelines.


