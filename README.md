Bu betik, bir Amazon ürün veri kümesini temizleme, keşfetme ve görselleştirme adımlarını gerçekleştirir.

## Gerçekleştirilen Görevler:

# 1. Veri Temizleme:

Eksik Değerleri Ele Alma:
rating sütunundaki eksik değerler, ortalama değer ile dolduruldu.
rating_count sütunundaki 2 eksik değer içeren satırlar silindi (veya 1 ile doldurulabilir).
Yinelenenleri Kaldırma: Veri kümesinde yinelenen satır bulunmadığı doğrulandı.
Veri Türlerini Düzeltme:
discount_percentage sütunu ondalık sayıya çevrildi (% işareti kaldırılarak).
rating sütunu sayısal türe çevrildi ('|' karakteri içeren satır ortalama ile doldurularak).
Veri Kümesindeki Tutarsızlıkları Giderme: rating sütunundaki '|' karakteri sorunu çözüldü.
# 2. Veri Keşfi:

Sayısal Sütunların Temel İstatistiklerini Analiz Etme: describe() fonksiyonu kullanılarak sayısal sütunların özet istatistikleri incelendi.
Anahtar Değişkenlerin Dağılımlarını Görselleştirme: (Henüz kodda görselleştirme yapılmamış, ancak bu adım planlanmış)
Verideki Desenleri ve Eğilimleri Belirleme: (Bu adım, görselleştirmeler ve analizler tamamlandığında gerçekleştirilecek)
# 3. Anahtar Soruları Yanıtlama:

En Çok Satan Ürünleri Belirleme: (Henüz kodda bu analiz yapılmamış)
En Popüler Ürün Kategorilerini Belirleme: (Henüz kodda bu analiz yapılmamış)
Derecelendirmeler ile Diğer Değişkenler Arasındaki İlişkiyi Keşfetme: (Henüz kodda bu analiz yapılmamış)
# 4. Görselleştirme:

Bulguları Göstermek için Bilgilendirici Grafikler ve Çizelgeler Oluşturma: (Henüz kodda görselleştirme yapılmamış, ancak bu adım planlanmış)
Amaç: Ürün performansı, müşteri tercihleri ve fiyatlandırma stratejileri hakkında iş kararlarını bilgilendirmek için içgörüler elde etmektir.

## Kodda Kullanılan Kütüphaneler:

numpy
pandas
seaborn (Henüz kullanılmamış ama import edilmiş)
matplotlib.pyplot (Henüz kullanılmamış ama import edilmiş)
Veri Kümesi:

/Users/haticecakir/Downloads/amazon.csv dosyasından okundu.
Temizlenmiş veri kümesi /Users/haticecakir/Desktop/Veri Bilimi Dosyalar/temizlenmis_amazon.csv dosyasına kaydedildi.
Notlar:

Kod, veri temizleme adımlarını tamamlamıştır.
Veri keşfi ve görselleştirme adımları henüz tamamlanmamıştır.
Yinelenen product_id değerleri incelenmiş ve farklılıkların nedenleri araştırılmıştır.
