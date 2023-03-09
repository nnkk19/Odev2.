import java.util.Scanner;
public class KdvTutarı {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		double tutar,kdvtutar,kdvoran=0.18,kdvliTutar;
		Scanner inp= new Scanner(System.in);
		
		System.out.println(" Ucret tutarı giriniz");
		tutar= inp.nextDouble();
		
		kdvtutar= tutar*kdvoran;
		kdvliTutar= tutar+kdvtutar;
		
		System.out.println(" KDVSİZ tutarı giriniz " +tutar);	
		System.out.println("KDV tutarı giriniz "+ kdvtutar);
		System.out.println(" KDV oranı  giriniz "+ kdvoran);
		System.out.println(" KDVLİ tutarı giriniz "+ kdvliTutar);
	}

}
