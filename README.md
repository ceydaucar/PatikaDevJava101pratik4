# PatikaDevJava101pratik4
import java.util.*;
public class pratik4 {

	public static void main(String[] args) {
		// Yeni bir tarayıcı(scanner) oluştur.
		Scanner sc = new Scanner(System.in);
		
		// Kullanıcıdan boy ve kilo değerini al.
		System.out.println("Lütfen boyunuzu (metre cinsinden) giriniz: ");
		double boy = sc.nextDouble();
		
		System.out.println("Lütfen kilonuzu giriniz: ");
		double kilo = sc.nextDouble();
		
		// Formülü oluştur.
		double vki = kilo / (boy * boy);
		
		// Hesaplamayı yazdır.
		System.out.println("Vücut Kitle Endeksiniz: " + vki);
	}

}
