import java.util.Scanner;

class Array {
 int ne=0,no=0;
	public void find() {
		Scanner input = new Scanner(System.in);
		int arr[] = new int[5];
		System.out.println("Enter elements of array:");
		for(int i=0;i<arr.length;i++)
		{
			arr[i]=input.nextInt();
		}
		for(int i=0;i<arr.length;i++)
		{
			if(arr[i]%2==0)
				ne++;
			else
				no++;
		}
		System.out.println("number of even elements are:"+ne+" and number of odd elements are:"+no);
	}
}
public class Jala {
	public static void main(String[] args) 
		{
			Array obj = new Array();
			obj.find();
		}
}
