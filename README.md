# DoWhile
import java.util.Scanner;
public class DoWhileLoop
{
	public static void main(String[] args)
	{
	Scanner input = new Scanner(System.in);

	int num1;
	int num2;
	int sum = 0;

		do{
		System.out.print("Enter a number or 0 to stop: ");
		num1 = input.nextInt();

		System.out.print("Enter a number or 0 to stop: ");
		num2 = input.nextInt();

		if (num1 != 0 || num2 != 0){
		sum = num1 + num2;
		System.out.printf("the sum is %d%n", sum);
		}
		
		}while (num1 != 0 && num2 != 0);

	}
}
