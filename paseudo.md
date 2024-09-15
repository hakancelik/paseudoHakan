## Açıklama:
Bu program, kullanıcıdan iki sayı alır ve bu sayıları toplar. Ardından, toplamı ekrana yazdırır.
1. Seviye: Basit

```
Başlangıç:
   Sayı1 = Kullanıcıdan sayı al
   Sayı2 = Kullanıcıdan sayı al
   Toplam = Sayı1 + Sayı2
   Toplamı ekrana yazdır
Son:
```

## Açıklama:
Bu program, 1'den 100'e kadar olan sayıları toplar ve toplamı ekrana yazdırır.

2. Seviye: Orta

```
Başlangıç:
   Toplam = 0
   i = 1
   While i <= 100:
      Toplam = Toplam + i
      i = i + 1
   Ekrana "Toplam: " + Toplam yazdır
Son:
```

## Açıklama:
Bu program, kullanıcıdan alınan bir sayının asal olup olmadığını kontrol eder. Eğer sayının asal olduğunu tespit ederse, "Asal" mesajını ekrana yazdırır. Aksi takdirde, "Asal Değil" mesajını ekrana yazdırır.

3. Seviye: İleri

```
Başlangıç:
   Sayi = Kullanıcıdan sayı al
   AsalMı = True
   i = 2
   While i < Sayi:
      Eğer Sayi % i == 0:
         AsalMı = False
         Çıkış döngüsü
      i = i + 1
   Eğer AsalMı == True:
      Ekrana "Asal" yazdır
   Aksi takdirde:
      Ekrana "Asal Değil" yazdır
Son:
```

## Açıklama:
Bu program, kullanıcıdan alınan bir dizinin elemanlarının tekrar edip etmediğini kontrol eder. Eğer tekrar eden elemanlar varsa, bunları "Tekrar edenler" mesajı ile birlikte ekrana yazdırır. Eğer hiçbir tekrar yoksa, "Hiçbir tekrar yok" mesajını ekrana yazdırır.

4. Seviye: Zor

```
Başlangıç:
   Dizi = Kullanıcıdan dizi al
   Uzunluk = Dizinin uzunluğu
   TekrarEdenler = Boş dizi
   i = 0
   While i < Uzunluk:
      Eğer Dizi[i] Dizi[0:i] içinde değil:
         Dizi[i] TekrarEdenler dizisine ekle
      i = i + 1
   Eğer TekrarEdenler boş değil:
      Ekrana "Tekrar edenler: " + TekrarEdenler yazdır
   Aksi takdirde:
      Ekrana "Hiçbir tekrar yok." yazdır
Son:
```
