# Add-two-matrices-Java_interview_practice
Java program to add the elements of two-dimensional array
package add_Two_Matrices;

/**
 *
 * @author Dinesh Nanda
 */
 
public class Add_Two_Matrices {

    public static void main(String[] args) {

        int a[][] = {{1, 3, 4}, {2, 4, 3}, {3, 4, 5}};
        int b[][] = {{1, 3, 4}, {2, 4, 3}, {1, 2, 4}};

        int c[][] = new int[a.length][b.length];

        for (int i = 0; i < a.length; i++) {
            for (int j = 0; j < b.length; j++) {

                c[i][j] = a[i][j] + b[i][j];
                System.out.print(c[i][j] + " ");
            }
            System.out.println();
        }
    }

}
