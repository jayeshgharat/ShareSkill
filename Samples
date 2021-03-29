//package office;

import java.util.Arrays;
import java.util.Scanner;

public class Samples {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter Number of Samples");
		int samp = sc.nextInt();
		
		int sarr[] = new int[samp];
		int median =0;
		
		for(int i=0;i<samp;i++) {
			System.out.println("Enter "+(i+1)+" Sample:");
			int no = sc.nextInt();
			
			sarr[i]=no;
			
		}
		System.out.println(Arrays.toString(sarr));
		Arrays.sort(sarr);
		System.out.println(Arrays.toString(sarr));
		int arrLen = sarr.length;
		System.out.println(arrLen);
		
		if(arrLen%2==1) { //odd
			median = sarr[(samp+1)/2-1];
		} else {
			median = ( sarr[samp/2-1] + sarr[samp/2] ) /2;
		}
		
		System.out.println("Median :" +median);

	}

}
