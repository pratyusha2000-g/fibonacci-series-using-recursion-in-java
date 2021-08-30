# fibonacci-series-using-recursion-in-java
public class Main
{
	public static void main(String[] args) 
	{
	    int a=0,b=1,i=3;
	 System.out.println("FIBONACCI SERIES ");
	 System.out.print(a+" "+b+" ");
	 fibonacci(a,b,i);
	}
	
	public static void fibonacci(int a,int b,int i)
	{
	    int c=0;
	    if(i<=10)
	    {
	        c=a+b;
	        System.out.print(c+" ");
	        a=b;
	        b=c;
	        i++;
	        fibonacci(a,b,i);
	    }
	}
}
