# Vücut Kitle İndeksi Hesaplama 
Patika.dev > Java101 > Ödev1 - Vücut Kitle İndeksi Hesaplama
 
## Java ile kullanıcıdan boy ve kilo değerlerini alıp bir değişkene atayın. Aşağıdaki formüle göre kullanıcının "Vücut Kitle İndeks" değerini hesaplayıp ekrana yazdırın.
### Formül
Kilo (kg) / Boy(m) * Boy(m)
 
		import java.util.*;
		public class odev1 {

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
