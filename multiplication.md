import java.util.Scanner;
public class Multiply_Two_num1{
public static void main(String args[]){
Scanner sc=new Scanner(System.in);
System.out.println("Enter the first number: ");
int num1=sc.nextInt();
System.out.println("Enter the second number: ");
int num2=sc.nextInt();
sc.close();
int product=num1*num2;
System.out.println("The product of numbers: "+product);
}
}
