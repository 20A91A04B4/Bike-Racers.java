package pack1;

import java.io.*;
public class Bike_Racers {

	public static void main(String[] args)throws Exception
	{
		BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
		int racer1_Speed,racer2_Speed,racer3_Speed,racer4_Speed,racer5_Speed;
		int sum;
		float avg_Speed;
		System.out.println("Enter five Racers speeds");
		racer1_Speed=Integer.parseInt(br.readLine());
		racer2_Speed=Integer.parseInt(br.readLine());
		racer3_Speed=Integer.parseInt(br.readLine());
		racer4_Speed=Integer.parseInt(br.readLine());
		racer5_Speed=Integer.parseInt(br.readLine());
		sum=racer1_Speed+racer2_Speed+racer3_Speed+racer4_Speed+racer5_Speed;
		avg_Speed=(float)sum/5;
		System.out.println("Average speed is:"+avg_Speed);
		System.out.println("The Qualified Racers are:");
		if(racer1_Speed>avg_Speed)
			System.out.println("Racer1");
		if(racer2_Speed>avg_Speed)
			System.out.println("Racer2");
		if(racer3_Speed>avg_Speed)
			System.out.println("Racer3");
		if(racer4_Speed>avg_Speed)
			System.out.println("Racer4");
		if(racer5_Speed>avg_Speed)
			System.out.println("Racer5");
		
	}

}



