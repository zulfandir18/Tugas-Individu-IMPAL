# Tugas-Individu-IMPAL
import java.util.Scanner;

public class JenisSegitiga {

  
    public static void main(String[] args) {
        Scanner nilai= new Scanner (System.in);
        int sisiA, sisiB ,sisiC ;
  
        System.out.print ("sisiA= ");
        sisiA = nilai.nextInt ();
        System.out.print ("sisiB= ");
        sisiB = nilai.nextInt ();
        System.out.print ("sisiC= ");
        sisiC = nilai.nextInt ();

        if ((sisiA == 0) || (sisiB == 0) || (sisiC == 0)) {
        System.out.println("Bukan Segitiga");
        } else {
        if ((sisiA == sisiB) && (sisiC == sisiA))
        System.out.println("Segitiga Sama Sisi");
        else
        if ((sisiA == sisiB) || (sisiA == sisiC) || (sisiB == sisiC))
        System.out.println("Segitiga Sama Kaki");
        else
        System.out.println("Segitiga Bebas");
        }
    }
} 
