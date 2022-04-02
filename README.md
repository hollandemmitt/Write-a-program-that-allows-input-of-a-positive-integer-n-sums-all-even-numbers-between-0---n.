# Write-a-program-that-allows-input-of-a-positive-integer-n-sums-all-even-numbers-between-0---n.
Write a program that allows input of a positive integer n, sums all even numbers between 0 - n.
import java.util.Scanner;

public class BaiTapJavaCoBan6 {
    public static void main(String[] args)
    {
       int n;
       int sum = 0;
       System.out.println("Integer:");
       Scanner sc = new Scanner(System.in);

       n = sc.nextInt();

       for (int i = 0; i <= n; i++) // iterates all elements from 0-n
       if (i % 2 == 0) // if it is even
          sum += i; // Add to the total.
          System.out.println(sum);
    }
}
