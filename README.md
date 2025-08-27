Fonksiyon Parametre Hatası - Mini proje

def selam_ver(Nezir) : 
    print("Merhaba" , Nezir) 

isim = input("Adınızı girin : ") 
selam_ver(Nezir) 
# hatalı kullanım 

• Fonksiyon parametrelerinde sabit bir isim (Nezir) kullanamazsın, bunun yerine değişken adı kullanılır (isim gibi). 
• selam_ver(Nezir) burada Nezir tanımlı bir değişken değil, kullanıcıdan aldığın isim değişkenini göndermelisin.

Doğru hali: 

def selam_ver(isim) : 
    print("Merhaba" , isim) 

isim = input("Adınızı girin : ") 
selam_ver(isim) 
# doğru çalışır 

Çıktı: 

Adınızı girin : Nezir 
Merhaba Nezir



# Konu
• "fonksiyon parametrelerinde sabit bir isim kullanmanın hatalı olduğunu gösteren mini proje. 
kullanıcıdan alınan değişken doğru şekilde fonksiyona gönderiliyor. " 
