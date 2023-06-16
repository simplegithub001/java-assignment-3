# java-assignment-3
import java.util.Scanner;

public class DivisibilityTest {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter an integer: ");
        int number = scanner.nextInt();

        for (int i = 0; i <= 9; i++) {
            if (number % i == 0) {
                System.out.println("The number is divisible by " + i);
            }
        }

        scanner.close();
    }
}
