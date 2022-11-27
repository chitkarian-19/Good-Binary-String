# Good-Binary-String

Problem Link: https://www.codechef.com/problems/GOODBINSTR?tab=statement

```cpp
/* package codechef; // don't place package name! */

import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner sc = new Scanner(System.in);
		int t=sc.nextInt();
		StringBuilder op=new StringBuilder("");
		
		while(t-->0){
		    
		    String s = sc.next();
		    if(s.charAt(0)==s.charAt(s.length()-1)){
		        op.append((s.length()-2)+"\n");
		    }
		    else{
		        op.append("2\n");
		    }
		}
		
		System.out.print(op.toString());
		
	}
}


```
