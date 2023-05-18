# Hesap Makinesi
## Ödev :
* Videodaki hesap makinesini **switch case** yapısını kullanarak yapınız.

```
import java.util.Scanner;

public class HesapMakinesi {
    public static void main(String[] args){
        int n1,n2,select;

        Scanner input = new Scanner(System.in);

        System.out.print("İlk Sayıyı Giriniz :");
        n1=input.nextInt();
        System.out.print("İkinci Sayıyı Giriniz :");
        n2=input.nextInt();
        System.out.print("1-Toplama :\n2-Çıkarma :\n3-Çarpma :\n4-Bölme :\nBir İşlem Seçiniz :");
        select=input.nextInt();

        switch(select){
            case 1:
                System.out.print("Toplam :"+(n1+n2));
                break;
            case 2:
                System.out.print("Fark :"+(n1-n2));
                break;
            case 3:
                System.out.print("Çarpım :"+(n1*n2));
                break;
            case 4:
                switch(n2){
                    case 0:
                        System.out.print("Bir Sayı 0'a Bölünemez...");
                        break;
                    default:
                        System.out.print("Bölüm :"+(n1/n2));
                }
                break;
            default:
                System.out.print("Hatalı İşlem Girdiniz...");
        }
    }
}
```
***
# Patika Linkim :
***
<a href="https://academy.patika.dev/profile">Patika Profilim</a>