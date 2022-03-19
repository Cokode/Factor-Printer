# Factor-Printer
This program prints out all factors that divides the number wholly without remainder including the number itself.

public class FactorPrinter {

    public static void main(String[] args) {
        printFactors(-675);
    }

    public static void printFactors(int number) {
        if (number < 1) {
            System.out.println("Invalid Value");
        }

        int i = 0;
        while(i < number) {
            i = i + 1;
            if(number % i == 0){
                System.out.println(i);
            }
        }
    }
}

