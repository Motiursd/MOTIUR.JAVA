import java.util.*;

public class fillwater {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        boolean[] full = new boolean[3];

        for (int i = 0; i < 3; i++) {
            System.out.println("Enter the status of bottle " + (i + 1) + " (0 for empty, 1 for full):");
            while (true) {
                int input = sc.nextInt();
                if (input == 0) {
                    full[i] = false;
                    break;
                } else if (input == 1) {
                    full[i] = true;
                    break;
                } else {
                    System.out.println("Invalid input, please enter 0 or 1:");
                }
            }
        }

        sc.close();

        int emptyCount = 0;
        for (int i = 0; i < 3; i++) {
            if (!full[i]) {
                emptyCount++;
            }
        }
        if (emptyCount >= 2) {
            System.out.println("Water fill time");
        } else {
            System.out.println("It's not time to fill water");
        }
    }
}
