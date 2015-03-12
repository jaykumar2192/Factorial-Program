# Factorial-Program
//Program to find factorial of a no till any range.
import java.util.*;  
import java.math.*; 
class Solution{
public static void main(String[] args) {  
     
     Scanner in = new Scanner(System.in);
       int N = in.nextInt();
       int k =0;
        for (int i = 0; i < N; i++) {
            k = in.nextInt();
            BigInteger result = BigInteger.ONE;
            for (int j = 2; j <= k; j++)
        result = result.multiply(BigInteger.valueOf(j));
            System.out.println(result);
        }

}
}
