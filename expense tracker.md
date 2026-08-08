import java.util.Scanner;

public class ExpenseTracker {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        System.out.print("Enter food expense: ");
        double food = sc.nextDouble();

        System.out.print("Enter travel expense: ");
        double travel = sc.nextDouble();

        System.out.print("Enter shopping expense: ");
        double shopping = sc.nextDouble();

        double total = food + travel + shopping;

        System.out.println("\n--- Expense Summary ---");
        System.out.println("Food: " + food);
        System.out.println("Travel: " + travel);
        System.out.println("Shopping: " + shopping);
        System.out.println("Total Expense: " + total);

        sc.close();
    }
}