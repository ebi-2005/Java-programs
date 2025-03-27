
import java.util.Scanner;

public class WelcomeMessage {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Please enter your name: ");
        String name = scanner.nextLine();
        System.out.println(String.format("Welcome %s to Skill Development Training", name));
        scanner.close();
    }
}
