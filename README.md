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
  1. Sayı al (n)
  2. Eğer n <= 1 ise
    2.1. Yaz "Asal sayı değildir"
    2.2. Bitir
  3. Değilse
    3.1. i = 2
    3.2. Asal = True
    3.3. Döngü (i <= n / 2)
      3.3.1. Eğer n % i == 0 ise
        3.3.1.1. Asal = False
        3.3.1.2. Döngüden çık
      3.3.2. i = i + 1
    3.4. Döngü sonu
    3.5. Eğer Asal ise
      3.5.1. Yaz "Asal sayıdır"
    3.6. Değilse
      3.6.1. Yaz "Asal sayı değildir"
Bitir

# 4. Seviye: Zor


Bir dizideki (array) elemanların tekrar edip etmediğini kontrol eden bir programın pseudo kodunu yazın.

Başla
  1. Diziyi al (dizi)
  2. Boş bir set oluştur (görülenler)
  3. TekrarEden = False
  4. Her eleman için dizi içinde (eleman)
    4.1. Eğer eleman görülenler içinde ise
      4.1.1. TekrarEden = True
      4.1.2. Döngüden çık
    4.2. Aksi halde
      4.2.1. elemanı görülenlere ekle
  5. Eğer TekrarEden ise
    5.1. Yaz "Dizide tekrar eden elemanlar var"
  6. Aksi halde
    6.1. Yaz "Dizide tekrar eden eleman yok"
Bitir



