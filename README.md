import java.util.Random;
import java.util.Scanner;

public class randomNumber {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Random i = new Random();

		System.out.print("Type a no: ");
		Scanner sc = new Scanner(System.in);
		int num = sc.nextInt();
		if (num == 0) {
			System.out.println("Entered no. has to be greater then 0");
		} else
			System.out.println("Random no greater then 0 and less then" + " " + num + " is " + i.nextInt(num));
	}

}
