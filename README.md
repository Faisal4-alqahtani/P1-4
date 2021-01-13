P1-4
package P1to4;
import java.util.Scanner;
public class P4 {
	public static void Msg1() {
		 System.out.println("I am a successful and optimistic person.” Always repeat this phrase");
	}

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner input = new Scanner(System.in);
		Scanner reader = new Scanner(System.in);
		 System.out.println("Choose a number from 1 to 4, a message will be lost for you");
		 double Msg = reader.nextDouble();
		 if(Msg == 1)
			 Msg1();
		 else if(Msg == 2)
			 System.out.println("I’ll be someday I want");
		 else if(Msg == 3)
			 System.out.println( "You may feel tired one day, but never give up");
		 else if(Msg == 4 )
			 System.out.println("a flower does not think of competing to the flower next to it. it just blooms ");
		 else 
			 System.out.println("There are no more words");
		 String phrase;
		 System.out.println("If you have a phrase you can tell me ");
		 phrase = input.nextLine();
		 System.out.println("Thanks");
