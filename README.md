# Pseudo-Code-Sorular-
 # Veri Bilimi Eğitimi: Algoritmalar Modülü Ödevi 
 
# 1. Seviye: Basit
Kullanıcıdan iki sayı alarak bu sayıları toplayan bir programın pseudo kodunu yazın.

1. BAŞLA 
2. A sayısını oku  
3. B sayısını oku  
4. TOPLAM=A+Bişlemini yap 
5. TOPLAMdeğerini ekrana yaz
6. BİTİR


# 2. Seviye: Orta
Soru: 1'den 100'e kadar olan sayıları toplayan bir programın pseudo kodunu yazın.

1.    BAŞLA
2.    Toplam = 0
3.    Sayac = 1
4.    Sayac>100 ise, GİT 8
5.    Toplam = Toplam + Sayac
6.    Sayac = Sayac + 1
7.    GİT 4
8.    toplam YAZ
9.    BİTİR   



# 3. Seviye: İleri

Kullanıcıdan alınan bir sayının asal olup olmadığını bulan bir programın pseudo kodunu yazın.

Başla
  Sayı al (n)
  Eğer n <= 1 ise
    Yaz "Asal sayı değildir"
    Bitir
  Değilse
    i = 2
    Asal = True
    Döngü (i <= n / 2)
      Eğer n % i == 0 ise
        Asal = False
        Döngüden çık
      i = i + 1
    Döngü sonu
    Eğer Asal ise
      Yaz "Asal sayıdır"
    Değilse
      Yaz "Asal sayı değildir"
Bitir



