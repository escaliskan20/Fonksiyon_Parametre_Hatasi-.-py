#  Fonksiyon Parametreleri – Doğru Kullanım Örneği

##  Amaç
Bu proje, **Python fonksiyon parametrelerinin doğru kullanımı** ile ilgili yaygın hataları göstermek ve doğru yöntemleri öğretmek için hazırlanmıştır.  
Özellikle yeni başlayanların **sabit isim kullanmaması**, **değişkenleri doğru şekilde göndermesi** gerektiğini öğrenmesi hedeflenmiştir.

---

## 🔹 Örnek Hatalı Kullanım
```python
def selam_ver(Nezir):
    print("Merhaba", Nezir)

selam_ver(Nezir)

Burada Nezir sabit bir isim olarak parametreye yazılmış ve tanımlı değil.
selam_ver(Nezir) çağrısı hataya yol açar, çünkü Nezir değişkeni yok.

## 🔹 Doğru kullanım


def selam_ver(isim):
    print("Merhaba", isim)

isim = input("Adınızı girin: ")
selam_ver(isim)

Fonksiyon parametresi değişken adı olmalı (örnek: isim).
Kullanıcıdan alınan değer isim değişkenine atanır ve fonksiyona gönderilir.

Bu yöntem esnek ve doğru bir uygulamadır.
