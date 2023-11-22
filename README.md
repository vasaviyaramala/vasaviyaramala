import java.util.Scanner;

public class SurveySystem {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Welcome to the Survey!");
        System.out.println("Please answer the following question:");
        System.out.println("What is your favorite color?");
        
        String response = scanner.nextLine();
        
        System.out.println("You answered: " + response);

        // Close the scanner when done
        scanner.close();
    }
}
