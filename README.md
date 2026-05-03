# PALINDROME NUMBER
class palindrme {
    public static void main(String[] args)
{
    int num = 121;
    int rev = 0;
    int temp = num;

    while(num > 0) {
       rev = rev * 10 + num%10;
       num = num / 10;
      }
      if(temp == rev)
    System.out.println("palimdrone");
    else
    System.out.println(" Not palimdrone");//

  # MULTIPICATION TABLE(create table 1 to n)
  public class MultiplicationMatrix {
    public static void main(String[] args) {
        int n = 5;

        for(int i = 1; i <= n; i++) {
            for(int j = 1; j <= n; j++) {
                System.out.print(i * j + " ");
            }
            System.out.println();
        }
    }
}

#  Calculator using switch case.
import java.util.Scanner;

public class Calc {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int a, b;
        char op;

        System.out.print("Enter first number: ");
        a = sc.nextInt();

        System.out.print("Enter operator (+ - * /): ");
        op = sc.next().charAt(0);

        System.out.print("Enter second number: ");
        b = sc.nextInt();

        switch(op) {
            case '+':
                System.out.println("Answer = " + (a + b));
                break;

            case '-':
                System.out.println("Answer = " + (a - b));
                break;

            case '*':
                System.out.println("Answer = " + (a * b));
                break;

            case '/':
                System.out.println("Answer = " + (a / b));
                break;

            default:
                System.out.println("Wrong operator");
        }

        sc.close();
        # MERGE SORT ARRAY

          given two integer arrays nums1 and nums2, sorted in non-decreasing order, and two integers m and n, representing the number of elements in nums1 and nums2 respectively.
          
class Solution {
    public void merge(int[] nums1, int m, int[] nums2, int n) {
int m = 5, n = 3;
int nums1 = m;
int nums2 = n;

for(int i = 0; i <= m; i++) {
    for(int j = 0; j <= n; j++) {
        System.out.println(i + " " + j);
    }
}
        
    


    
