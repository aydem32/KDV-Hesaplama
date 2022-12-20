import java.util.Scanner;

public class KDVTutari {

    public static void main (String[] args) {
        Scanner SayiAl = new Scanner(System.in);

        int sayi;
        int KDVsiz;
        double KDVli;
        double KDVTutar;
        System.out.println("Bir Sayı Giriniz");
        sayi = SayiAl.nextInt();
        KDVsiz = sayi;
        System.out.println("KDVSiz Sayı = "+ KDVsiz);
        KDVTutar =  (sayi * 0.18);
        System.out.println("KDV Tutarı ="+KDVTutar);
        KDVli = KDVTutar + KDVsiz;
        System.out.println("KDVli Fiyat = "+ KDVli);



    }


}
