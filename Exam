import java.util.Scanner;

public class exam {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.println("Enter number of sections");
        int section = sc.nextInt();

        System.out.println("Enter number of students per section");
        int studentperSection = sc.nextInt();

        System.out.println("Enter number of students passed");
        int totalStudentspassed = sc.nextInt();

        int totalStudents = section * studentperSection;

        double passPercentage = (double) totalStudentspassed / totalStudents * 100;

        if (passPercentage >= 50) {
            System.out.println("YES");
        } else {
            System.out.println("NO");
        }
        
        sc.close();
    }
}
