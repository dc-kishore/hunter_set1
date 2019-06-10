import java.io.*;
import java.lang.*;
import java.util.*;

class hunterset1{
    
	public static void main (String[] args) {
	   Scanner sc=new Scanner(System.in);
	    int n=sc.nextInt();
	    int a[]=new int[n];
	    int b[]=new int[n];
	    int j=0,flag=0;
	    for(int i=0;i<n;i++)
	    a[i]=sc.nextInt();
	    Arrays.sort(a);
	    for(int i=0;i<n-1;i++)
	    {
	            if(a[i]==a[i+1])
	            {
	           
	            b[j++]=a[i];
	            //System.out.println(b[j++]);
	            }
	    }
	    if(flag==0)
	    for(int i=1;i<=j;i++)
	    {
	        if(b[i]!=b[i-1])
	     System.out.print(b[i-1]+" ");
	    }
	    else
	    System.out.print("unique");
	}
}
