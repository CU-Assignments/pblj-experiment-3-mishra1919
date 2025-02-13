import java.util.Scanner;

public class SquareRootCalculator {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        try {
            System.out.print("Enter a number: ");
            double num = scanner.nextDouble();
            if (num < 0) {
                throw new IllegalArgumentException("Square root of a negative number is not real.");
            }
            System.out.println("Square root: " + Math.sqrt(num));
        } catch (Exception e) {
            System.out.println("Invalid input: " + e.getMessage());
        } finally {
            scanner.close();
        }
    }
}
