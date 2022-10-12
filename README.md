# Calculator
An easy 'switch' type calculator in Java

public class Calculator {
    public static void main(String [] args) {
        double firstnumber = 10;
        double secondnumber = 5;
        char sign = '+';
        double result = 0;
        switch (sign) {
            case '+' -> result = firstnumber + secondnumber;
            case '-' -> result = firstnumber - secondnumber;
            case '%' -> result = firstnumber / secondnumber;
            case '*' -> result = firstnumber * secondnumber;
            default -> System.out.println("The sign you put is wrong, the program is unable to work!");
        }
        System.out.println("Result: " + firstnumber + " " + sign + " " + secondnumber + " = " + result);
    }
}
