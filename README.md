"# codingAssignment1" 
public class App {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		//Variables
		double price = 12.35;
		int price2 = 2;
		int wallet = 25;
		int wallet2 = 6;
		double numberOfFriends = 10.0;
		double numberOfFriends2 = 25.0;
		double age = 20.0;
		double age2 = 30.0;
		String firstName = "Jose";
		String lastName = "Corral";
		char middleInitial = 'P';
		String fullName = firstName + " " + middleInitial + " " + lastName;
		String firstName2 = "Robin";
		String lastName2 = "Hood";
		char middleInitial2 = 'G';
		String fullName2 = firstName2 + " " + middleInitial2 + " " + lastName2;
		double newWallet = wallet-price;
		int newWallet2 = wallet2-price2;
		double friendsPerYear = numberOfFriends/age;
		double friendsPerYear2 = numberOfFriends2/age2;
		//Execution
		System.out.println("The item price is $" + price);
		System.out.println("My wallet holds $" + wallet);
		System.out.println("I have " + numberOfFriends + " friends");
		System.out.println("I am " + age + " years old");
		System.out.println("My first name is " + firstName);
		System.out.println("My middle initial is " + middleInitial);
		System.out.println("My last name is " + lastName);
		System.out.println("The second item is worth $" + price2);
		System.out.println("The other wallet holds $" + wallet2);
		System.out.println("She has " + numberOfFriends2 + " friends");
		System.out.println("She is " + age2 + " years old");
		System.out.println("His first name is " + firstName2);
		System.out.println("His middle initial is " + middleInitial2);
		System.out.println("His last name is " + lastName2);
		System.out.println();
		System.out.println("My wallet now holds $" + newWallet);
		System.out.println("I have made " + friendsPerYear + " friends a year");
		System.out.println("My full name is " + fullName);
		System.out.println("The other wallet now holds $" + newWallet2);
		System.out.println("She has made " + friendsPerYear2 + " friends a year");
		System.out.println("His full name is " + fullName2);
				
		

	}

}
