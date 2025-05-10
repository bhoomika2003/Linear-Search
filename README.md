# Linear-Search
import java.util.Scanner;

public class Search {
	public static void main(String[] args) {
		Scanner a = new Scanner(System.in);
		int arr[] = new int[5];
		System.out.println("enter the value for array");
		for(int i =0; i<arr.length;i++) {
			arr[i] =a.nextInt();
		}
		
		System.out.println("enter the vaule key");
		int key = a.nextInt();
		for(int i = 0;i<arr.length;i++) {
			if(arr[i] == key) {
				System.out.println("element is found in postion "+i);
				System.exit(i);
			}
		}
		System.out.println("element not found");
	}

}
