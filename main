import java.util.Scanner;

public class TaxableIncomeCalculator {

public static void main(String[] args) {
Scanner scanner = new
Scanner(System.in);
System.out.println("Enter your
annual income:");
double income =
scanner.nextDouble();
double tax = calculateTax(income);
System.out.printf("Your taxable
income is $%.2f and your tax payable is $%.2f.%n", income, tax);
}

public static double calculateTax(double
income) {
double tax;
if (income <= 500000) {
tax = 0;
} else if (income > 500000 &&
income <= 1000000) {
tax = (income - 500000) * 0.1;
} else if (income > 1000000 &&
income <= 2000000) {
tax = 50000 + (income - 1000000)
* 0.2;
} else {
tax = 250000 + (income -
2000000) * 0.3;
}
return tax;
}
