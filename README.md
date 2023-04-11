# PBO2022
package pertemuan4;
import java.util.Scanner;
public class Pertemuan4 {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        
        int nilaiC;
        
        System.out.println("Penjumlahan");
        
        System.out.print("Variable A : ");
        int nilaiA = input.nextInt();
        System.out.print("Variable B : ");
        int nilaiB = input.nextInt();
        
        nilaiC = nilaiA + nilaiB;
        
        System.out.println();
        System.out.println("Variable A + Variable B = Variable C");
        System.out.println("Variable A adalah: " + nilaiA);
        System.out.println("Variable B adalah: " + nilaiB);
        System.out.println("Variable C adalah: " + nilaiC);
        
        System.out.println();
        System.out.println("Alfin nur hasan,21201164"); 
    }
}
