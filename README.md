# FizzBuzz
import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
        int n = 100;
        
        for(int i = 1; i <= n; i++){
            if(i % 5 == 0 && i % 3 == 0)
            System.out.println("FizzBuzz");
            else if(i % 5 == 0)
            System.out.println("Buzz");
            else if(i % 3 == 0)
            System.out.println("Fizz");
            else
                System.out.println(i + " ");  
        }
    }
}
