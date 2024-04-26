# Python-ile-Nesne-Mesafe-Olcme
2 adet nesnenin yol üzerinde ne kadar ilerlediğini gösteren program

Konu: Real time kameradaki çift nesneyi level kontrollü mesafelerinin tespitini yapmak.
Sonuçlar excel dosyasına yazılacak.
Derin öğrenme kullanmadan düzlem üzerinde doğrusal olarak hareket eden iki farklı
nesneyi tespit edip başlangıç noktasına olan uzaklığı hesaplayan ve belirli seviyelere
geldiğinde ise excel’e çıktı alan uygulamayı geliştirdik.
Düzlem olarak A4 kağıdını tercih ettik. Bu kağıdı 7’şer cm aralıklarla seviyeler
belirlenip dikey çizgilerle gösterildi. Ardından belirli yükseklikten telefon kamerası
yardımıyla anlık görüntüleri elde ettik. Bu anlık görüntüleri saniyede bir tane ekran görüntüsü
(1 FPS) alınarak algoritma içine dahil edilmiştir.
Alınan ekran görüntülerinin boyutu 480x640 piksel olarak yeniden ayarlandı.
Ardından gerekli işlemler yapıldı (gerekli işlemler kodlarda anlatılacaktır.).
Canlı olarak kayıt almak için telefonu bilgisayarın kamerası olarak tanıtmak amacıyla
DroidCam adlı uygulama kullanıldı.
