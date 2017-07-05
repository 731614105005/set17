# set17
 import java.io.*;
 import java.util.*;
 public class Amstrong
 {
   public static void main(String args[])
   {
    Scanner sc=new Scanner(System.in);
     int n=sc.nextInt();
     int a,b,c=0;
     b=n;
     while(n>0)
     {
       a=n%10;
       n=n/10;
       c=c+a*a*a;
       }
       if(c==b)
       {
         System.out.println("Amstrong");
         }
         else
         {
           System.out.println("not an amstrong");
           }
           }
         }
