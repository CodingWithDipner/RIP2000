# RIP2000
problem from codechef

Problem

Chef had collected N notes of Rs. 2000 to pay his total college fees. However, the government banned Rs. 2000 notes.


Chef wants to pay the same amount using Rs.500 notes only. Find the number of notes Chef needs.

# Input Format

Each test case consists of a single integer N - the number of notes of Rs. 2000 that Chef has collected.

# Output Format

Output a single integer - the number of Rs. 500 notes needed.

# Constraints
-> 1 <= N <= 100

# CODE


   	import java.util.Scanner;

	public class RIP2000 {
    		public static void main(String[] args) {
        		Scanner sc=new Scanner(System.in);

        		System.out.print("Enter the No.of 2000Rs notes : ");
		
			int N=sc.nextInt();
			System.out.println(N*4);
    		}
	}
