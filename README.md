write a code to print "HAPPY BIRTHDAY" for using LOOPS of n ?
input n=7;
output =
H
A
P
P
Y
B
I
R
T
H
D
A
Y

code: 

import java.util.Scanner;
public class main
{
	public static void main(String[] args)
	{
		int n = 7;
		
		for ( int i = 1; i <= n ; i++ )
		{
			for ( int j = 1; j <= n ; j++)
			{
				if( j == 1 || j==n || i == n/2+1 )
				{
				System.out.print( "H" + " ");
				}
				else
				{
					System.out.print("  ");
				}
			}
			System.out.println();
		}//H
		
		System.out.println();
		
		for ( int k = 1; k <= n ; k++ )
		{
			for ( int l = 1; l <= n ; l++)
			{
				if( l == 1 || l==n || k == n/2+1 || k == 1 )
				{
				System.out.print( "A" + " ");
				}
				else
				{
					System.out.print("  ");
				}
			}
			System.out.println();
		}//A
		
		System.out.println();
		
		for ( int i = 1; i <= n ; i++ )
		{
			for ( int j = 1; j <= n ; j++)
			{
				if( j == 1 || i == 1 || i == (n/2+1) || (j==n && i <= n/2))
				{
				System.out.print( "P" + " ");
				}
				else
				{
					System.out.print("  ");
				}
			}
			System.out.println();
		}//P
		
		System.out.println();
		
		for ( int i = 1; i <= n ; i++ )
		{
			for ( int j = 1; j <= n ; j++)
			{
				if( j == 1 || i == 1 || i == (n/2+1) || (j==n && i <= n/2) )
				{
				System.out.print( "P" + " ");
				}
				else
				{
					System.out.print("  ");
				}
			}
			System.out.println();
		}//P
		
		System.out.println();
		
		
		for ( int i = 1; i <= n ; i++ )
		{
			
			for ( int j = 1; j <= n ; j++)
			{
				if( j == n || i == n || i == n/2+1 || ( j == 1 && i < (n/2)+1 ) )
				{
				System.out.print( "Y" + " ");
				}
				else
				{
					System.out.print("  ");
				}
			}
			System.out.println();
		}//Y
		System.out.println();
		
		for ( int i = 1; i <= n ; i++ )
		{
			for ( int j = 1; j <= n ; j++)
			{
				if( i == 1 || i == n || i == n/2+1 || j==1 || j==n )
				{
				System.out.print( "B" + " ");
				}
				else
				{
					System.out.print("  ");
				}
			}
			System.out.println();
		}//B
		System.out.println();
		
		for ( int i = 1; i <= n ; i++ )
		{
			for ( int j = 1; j <= n ; j++)
			{
				if( i == 1 || i == n || j == n/2+1)
				{
				System.out.print( "I" + " ");
				}
				else
				{
					System.out.print("  ");
				}
			}
			System.out.println();
		}//I
		System.out.println();
		
		for ( int i = 1; i <= n ; i++ )
		{
			for ( int j = 1; j <= n ; j++)
			{
				if( j == 1 || i == 1 || i == (n/2+1) || (j==n && i <= n/2) || ( j == n && i == n) || ( j == n-1 && i== n - 1 ) || ( j == n-2 && i == n-2)  )
				{
				System.out.print( "R" + " ");
				}
				else
				{
					System.out.print("  ");
				}
			}
			System.out.println();
		}//R
		
		System.out.println();
		
		for ( int i = 1; i <= n ; i++ )
		{
			for ( int j = 1; j <= n ; j++)
			{
				if( i == 1 || j == n/2+1)
				{
				System.out.print( "T" + " ");
				}
				else
				{
					System.out.print("  ");
				}
			}
			System.out.println();
		}//T
		System.out.println();
		
		for ( int i = 1; i <= n ; i++ )
		{
			for ( int j = 1; j <= n ; j++)
			{
				if( j == 1 || j==n || i == n/2+1 )
				{
				System.out.print( "H" + " ");
				}
				else
				{
					System.out.print("  ");
				}
			}
			System.out.println();
		}//H
		System.out.println();
		
		for ( int i = 1; i <= n ; i++ )
		{
			for ( int j = 1; j <= n ; j++)
			{
				if( (i == 1 && j!=n) || ( i == n && j != n ) || j == 1 || (j == n && i !=1 && i != n))
				{
				System.out.print( "D" + " ");
				}
				else
				{
					System.out.print("  ");
				}
			}
			System.out.println();
		}//D
		System.out.println();
		
		for ( int k = 1; k <= n ; k++ )
		{
			for ( int l = 1; l <= n ; l++)
			{
				if( l == 1 || l==n || k == n/2+1 || k == 1 )
				{
				System.out.print( "A" + " ");
				}
				else
				{
					System.out.print("  ");
				}
			}
			System.out.println();
		}//A
		
		System.out.println();
		
		for ( int i = 1; i <= n ; i++ )
		{
			
			for ( int j = 1; j <= n ; j++)
			{
				if( j == n || i == n || i == n/2+1 || ( j == 1 && i < (n/2)+1 ) )
				{
				System.out.print( "Y" + " ");
				}
				else
				{
					System.out.print("  ");
				}
			}
			System.out.println();
		}//Y
		System.out.println();
			
	}
}
	
