#Abhinav_JavaAssignment1
#Control Structure - Eligible for vote
import java.util.Scanner;
public class Abhinav_Assignment1_1 {
	public static void main(String args[]){
	Scanner IntAge= new Scanner(System.in);
	String option;
	do
	{
		System.out.println("Hello User! Enter your age");
		int age = IntAge.nextInt();
	if (age>=18 && age<=120)
		System.out.println("You are eligible to vote");
	else if (age>150)
		System.out.println("You have entered incorrect age");
	else
		System.out.println("You are not eligible");
	System.out.println("Enter Y to again insert age");
	option = IntAge.next();
	}
	while(option.equalsIgnoreCase("Y"));
	IntAge.close();
	}
}
