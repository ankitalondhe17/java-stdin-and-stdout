/*# java-stdin-and-stdout
In this challenge, you must read 3 integers from stdin and then print them to stdout. Each integer must be printed on a new line. To make the problem a little easier, a portion of the code is provided for you in the editor below.
Input Format

There are  lines of input, and each line contains a single integer.

Sample Input

42
100
125
Sample Output

42
100
125*/

import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
  Scanner sc = new Scanner(System.in);
  
  int a = sc.nextInt();
  System.out.println(a);
  
  int b = sc.nextInt();
  System.out.println(b);
  
  int c = sc.nextInt();
  System.out.println(c);
    }
}
