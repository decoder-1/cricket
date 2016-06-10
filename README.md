package cricket;
//A program which predicts a cricket match between two teams.
import java.util.*;
class cricket_predict
{
	public static void main()
	{
		int a;
		//no. of balls= no. of overs * 6
		System.out.println("Enter no. of overs");
		a=in.nextInt();
		int balls=a*6;
		for(int i=1;i<=balls;i++)
		{
			double ran=Math.random();
			
			int ran2=(int)ran*10;
			if(ran2<=6)
			{//later
				
