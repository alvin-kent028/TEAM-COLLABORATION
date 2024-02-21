package calculator;

import java.util.Scanner;
    
public class CALCULATOR {

    public static void main(String[] args) {
    
         int numOne;
         int numTwo;
         int result;
         
          Scanner s = new Scanner(System.in);
            
          System.out.print(" ENTER FIRST NUMBER:  ");
          numOne = s.nextInt();
          
          System.out.print(" ENTER SECOND NUMBER:  ");
          numTwo = s.nextInt();
          
          result = numOne * numTwo;
         
          System.out.println();
          System.out.println(numOne + " * " + numTwo + " = " + (numOne * numTwo));
          
    }
     
}
