
import java.util.Scanner;
public class Madlibs {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		Scanner scan = new Scanner(System.in);
		
		System.out.print("Enter an action verb (without 'ing'): ");
		String avone = scan.nextLine();

		System.out.print("Enter an adjective : ");
		String aone = scan.nextLine();

		System.out.print("Enter an adjective: ");
		String atwo = scan.nextLine();

		System.out.print("Enter an adjective: ");
		String athree = scan.nextLine();
		
		System.out.print("Enter an action verb (without 'ing'): ");
		String avtwo = scan.nextLine();
		
		System.out.println("You bolt up in a cold sweat. It's 2am. Images of good men you've killed have been haunting your dreams recently.");
		System.out.println("Ah, the joys of being a murderer.");
		
		System.out.println("You " + avone + " to the living room and pick up a " + aone + " copy of the news.");
		System.out.println("BANANA KILLER STRIKES AGAIN");
		System.out.println("The media has begun to pick up on your " + atwo + " killing spree: "
				+ "secretly planting banana peels on the street, only for unsuspecting pedestrians to slip on them and fall to their deaths. "
				+ "Oh, the horror.");
		System.out.println("Cackling wickedly, you  " + avtwo + " into your basement dungeon and continue peeling bananas "
				+ "for your next endeavor.");
		System.out.println("Life is good.");

	}

}

