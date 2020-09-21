# FizzBuzz
program to print Fizz-Buzz instead of integers multiples of 3, 5 upto 100
//writing a program that prints the number from 1 to 100
//but which is divisible by 3 prints Fizz and whic is divisible by 5 print Buzz
//the numbers divisible by both print FizzBuzz
import java.util.*;
class FizzBuzz 
{
public static void main(string[] args)
{
int i;
//for loop 100 times
for(i=1;i<=100;i++)
{
if(i%15==0)
System.out.println("FizzBuzz");
//no. which is divisible by 5 print Buzz instead of number
else if(i%5==0)
System.out.println("Buzz");
else if(i%3==0)
//number divisible by 3 print Fizz instead of number
System.out.println("Fizz");
//print the no. 
else
System.out.println(""+i);
}
}
}
