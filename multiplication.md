import java.util.Scanner;
public static void main(String args[]){
Scanner sc=new Scanner(System.in);
System.out.println("Enter the first number: ");
int num1=sc.nextInt();
System.out.println("Enter the second number: ");
int num2=sc.nextInt();
sc.close();
int sum=num1+num2;
int product=num1*num2;
System.out.println("the sum is:"+sum);
System.out.println("The product of numbers: "+product);
}
}
