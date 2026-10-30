# Random_Code

import java.util.Scanner;

class sum 
{
   void  towsum(int arr[], int n , int target)
   {

    for(int i = 0 ; i < n ; i++)
    {
        if (arr[i]+arr[i+1]==target) 
        {
            System.out.println("tow sum = " + arr[i] + " And " + arr[i+1]);

            break;
        }

        
        
    }
   }
}
public class TwoSum {
    public static void main(String args[])
    {
        sum s = new sum();
        int arr[] = {2,5,3,7,3,5,6};
        int n = arr.length -1;

        Scanner sc = new Scanner(System.in);

        System.out.println("Enter your value =");

        int target = sc.nextInt();
        s.towsum(arr, n, target);
    }
}
