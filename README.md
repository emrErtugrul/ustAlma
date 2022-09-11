# ustAlma


import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner inp=new Scanner(System.in);
        int x,y;
        int z,total=1;

        System.out.println("Üssü Alınacak Sayı : ");
        x=inp.nextInt();
        System.out.println("Üs olacak sayı : ");
        y=inp.nextInt();
        for (z=1;z<=y;z++){
            total*=x;
        }
        System.out.println(total);
    }
}
