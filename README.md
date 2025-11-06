import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
	  Scanner in=new Scanner(System.in);
	  int t=in.nextInt();
	  for(int i=0;i<t;i++){
	      int n=in.nextInt();
	      if(n%2 == 0 || n == 1){
	          System.out.println("YES");
	      }
	      else{
	          System.out.println("NO");
	      }
	  }// your code goes here

	}
}
