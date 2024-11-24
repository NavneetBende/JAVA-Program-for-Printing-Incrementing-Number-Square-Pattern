Printing Incrementing Number Square Pattern:
In this problem we’re going to code a Java Program for printing increment number star pattern. Take a number input from user as enter row and col and store it in variable named as row and col after that take a for loop start from i=1 to i<=row and then take a j loop start from j=1 to j<=col that will print i after that write line change statement

Numbered Square Pattern
Algorithm:
Take number of rows/columns as input from the user and save it in any variable (‘row’ and ‘col’ in this case).
Run a loop ‘row’ number of times to iterate through the rows. From i=1 to i<=row.  The loop should be structured as for(int i=1 ; i<=row ; i++)
Run a nested loop inside the previous loop to iterate through the columns. From  j=1 to j<=col. The loop should be structured as for (int j = 1; j <= col; j++)
Inside the nested loop print ‘i’ to print the incremented value in each column of a row.
Inside the main loop print a newline to move to the next line after a row System.out.println(); 
Code in Java:
import java.util.Scanner;
public class Pattern1 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter row and col");
		int row = sc.nextInt();
		int col = sc.nextInt();

		for(int i=1 ; i<=row ; i++) {
			for (int j = 1; j <= col; j++) 
				System.out.print(i);
			System.out.println();
		}
		
	}

}
