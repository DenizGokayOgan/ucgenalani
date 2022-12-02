import java.util.Scanner;
public class Main {

    public static void main(String[] args) {
        int a,b,c, u;
        double Alan ;
        Scanner klavye = new Scanner(System.in);
        System.out.print("Üçgenin birinci kenarını giriniz: ");
        a = klavye.nextInt();
        System.out.print("Üçgenin ikinci kenarını giriniz: ");
        b = klavye.nextInt();
        System.out.print("Üçgenin ücüncü kenarını giriniz: ");
        c = klavye.nextInt();

        u= (a+b+c)/2;
        Alan = Math.sqrt(u * (u-a) * (u-b) * (u-c));


        System.out.println("Ucgenin alani: "+Alan);
    }
}