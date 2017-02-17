# ArithmeticMethods
Cree una aplicación denominada ArithmeticMethods cuyo método main tenga dos variables enteras. Asigne valores a las variables. A su vez, pase cada valor a Los métodos llamados.

package arithmeticmethods;

/**
 *
 * @author AudiGS
 */
public class ArithmeticMethods {
    
 
     public static void main(String[]args){
          
         Integer a= 1;
         Integer b= 2;
         displayNumberPlus10 (a,b);
         displayNumberPlus100 (a,b);
         displayNumberPlus1000 (a,b);
          
     }
      
     public static void displayNumberPlus10(Integer n1, Integer n2){
         System.out.println((n1+10)+" "+(n2+10));
          
     }
      
     public static void displayNumberPlus100(Integer n1, Integer n2{
         System.out.println((n1+100)+" "+(n2+100));
          
     }
      
     public static void displayNumberPlus1000(Integer n1, Integer n2)
         System.out.println((n1+1000)+" "+(n2+1000));
          
     }
      
 }
