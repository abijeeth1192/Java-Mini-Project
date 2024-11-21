week 1
Write a program to find whether the given input number is Odd.
If the given number is odd, the program should return 2 else It should return 1.
import java.util.*;
class prog
{
    public static void main(String args[]){
    int n;
    Scanner Scan = new Scanner(System.in);
    n = Scan.nextInt();
    if(n%2==0)
    System.out.println("1");
    else
    System.out.println("2");
    
        
    }
}

Write a program that returns the last digit of the given number. Last digit is being referred to the least significant digit i.e. the digit in the ones (units) place in the given number.
The last digit should be returned as a positive number.
For example,
if the given number is 197, the last digit is 7
if the given number is -197, the last digit is 7

import java.util.*;
class prog
{
    public static void main(String args[]){
    int n;
    Scanner S=new Scanner(System.in);
    n=S.nextInt();
    if(n<0)
       System.out.println(-1*(n%10));
    else
       System.out.println(n%10);
    }
}

ohit wants to add the last digits of two given numbers.
For example,
If the given numbers are 267 and 154, the output should be 11.
Below is the explanation:
Last digit of the 267 is 7
Last digit of the 154 is 4
Sum of 7 and 4 = 11
Write a program to help Rohit achieve this for any given two numbers.
Note: Tile sign of the input numbers should be ignored.

i.e.

if the input numbers are 267 and 154, the sum of last two digits should be 11
if the input numbers are 267 and -154, the slim of last two digits should be 11
if the input numbers are -267 and 154, the sum of last two digits should be 11
if the input numbers are -267 and -154, the sum of last two digits should be 11

mport java.util.*;
class prog
{
    public static void main(String args[]){
    int n , m ;
    Scanner S = new Scanner(System.in);
    n=S.nextInt();
    m=S.nextInt();
    n = (n<0)?-1*n:n;
    m = (m<0)?-1*m:m;
    System.out.println((n%10)+(m%10));
    
        
    }
}
