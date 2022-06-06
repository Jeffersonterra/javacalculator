import java.util.Scanner;

public class calculator {

    public static void main(String args[]) {
        Scanner leitor = new Scanner(System.in);
        double x, y, answer;
        int z;
        answer = 0;
        y = 0;
        do {
            System.out.println("Input the first number: ");
            x = leitor.nextDouble();
            System.out.println("Choose the number of the operation: ");
            System.out.println("1- Addition (+) ");
            System.out.println("2- Subtraction (-) ");
            System.out.println("3- Multiplication (*) ");
            System.out.println("4- Division (/) ");
            z = leitor.nextInt();
            System.out.println("Input the second number: ");
            y = leitor.nextDouble();
            switch (z) {
                // addition in case one
                case 1:
                    answer = x + y;
                    System.out.println("The answer is: " + answer);
                    break;
                // subtraction in case two
                case 2:
                    answer = x - y;
                    System.out.println("The answer is: " + answer);
                    break;
                // multiplication in case three
                case 3:
                    answer = x * y;
                    System.out.println("The answer is: " + answer);
                    break;
                // division in case four
                case 4:
                    answer = x / y;
                    System.out.println("The answer is: " + answer);
                    break;
                default:
                    System.out.printf("System will now close. ");
                    z = 0;
                    break;

            }
        } while (z != 0);
        leitor.close();
    }

}
