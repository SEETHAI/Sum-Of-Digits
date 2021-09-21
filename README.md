# Sum-Of-Digits
Java Program To Print Sum Of Digits
package sumofdigits;

/**
 *
 * @author CMD
 */
import java.util.Scanner;
public class SumOfDigits {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        int m,n;
        int Sum=0;
        Scanner s=new Scanner(System.in)
        System.out.print("Enter the value:");
        m=s.nextInt();
        while(m>0)
        {
            n=m%10;
            sum=sum+n;
            m=m/10;
        }
        System.out.println("Sum Of Digits:"+Sum);
            
        }
        // TODO code application logic here
    }
    
}
