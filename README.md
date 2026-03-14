# java-test-0005-final-15338-rachana
Final Project Assignment - This repository contains the complete final project code and documentation.
public class Pattern {
    public static void main(String[] args) {
       int number = 1;
       for (int i = 1; i <= 5; i++) {         
            for (int j = 1; j <= i; j++) {      
                System.out.print(number + " ");
                number++;
            }
            System.out.println();               
        }
    }
}
