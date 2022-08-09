# 어러벼
/*//3-8
import java.util.Scanner;

public class Hello {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc = new Scanner(System.in);
		System.out.print("정수 몇개? ");
		int number = sc.nextInt();
		int[] array = new int[number];

		for (int i = 0; i < array.length; i++) {
			array[i] = (int) (Math.random() * 100 + 1);

			for (int j = 0; j < i; j++) {
				if (array[i] == array[j])
					i--;
			}
		}

		for (int i = 0; i < array.length; i++) {
			System.out.print(array[i] + " ");
			if ((i + 1) % 10 == 0)
				System.out.println();
		}
	}

}
