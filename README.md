# Factorial-of-a-number-using-while-loop-Recursion-
Public class Factorial {

Public static void (string [] args){

int fact = 1;

while (num>0) {

fact* = num;

num- -;

}

return fact;

}

public static int fact Recur (int num) {

if (num= = 0 || num == 1) {

return 1;

}

return num* factRecur (num-1);

}

Public static void main(String []args){

System.out.println("Enter number: ");

int w= fact while (num);

System.out.println("Factorial of + num+" using while loop: +w);

int R= fact Recur (num);

System.out.println("Factorial of"+ num+ "using Recursion: "+R);

}

}

Output:

Enter number: 15

Factorial of 5 using while loop is 20

Factorial of 5 using Recursion is 120
