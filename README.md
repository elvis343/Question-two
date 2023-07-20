# Question-two
public class BreakStatements {
    public static void main(String[] args) {
        outerLoop: 
        for (int i = 1; i <= 3; i++) {
            for (int j = 1; j <= 3; j++) {
                System.out.println("i = " + i + ", j = " + j);
                if (i == 2 && j == 2) {
                    break outerLoop;
                }
            }
        }

        System.out.println(); // Print a new line for clarity
        for (int i = 1; i <= 3; i++) {
for (int j = 1; j <= 3; j++) {
                System.out.println("i = " + i + ", j = " + j);

                if (i == 2 && j == 2) {
                    break;
                }
            }
        }
    }
}
