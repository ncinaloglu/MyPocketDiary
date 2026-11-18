MY POCKET DIARY / CEP GÜNLÜĞÜM — V2

KURULUM / GÜNCELLEME:
1. ZIP dosyasını çıkarın.
2. GitHub: https://github.com/ncinaloglu/MyPocketDiary
3. Add file > Upload files ile index.html, sw.js, manifest.webmanifest, icon-192.png, icon-512.png dosyalarını repo KÖKÜNE yükleyin.
4. Aynı adlı dosyaları yenileriyle değiştirin ve Commit changes seçin.
5. GitHub Actions > Pages build and deployment başarıyla bitince adresi açın:
   https://ncinaloglu.github.io/MyPocketDiary/
6. Eski sürüm görünürse sayfayı yenileyin, biraz sonra tekrar açın veya Safari'de ana ekran uygulamasını kapatıp yeniden başlatın.

ÖNEMLİ VERİ NOTU:
- Güncellemeden ÖNCE V1 uygulamasında Ayarlar > Yedeği indir seçin.
- V2, aynı cihaz/tarayıcıda duran cep-gunlugum-v1 kayıtlarını otomatik içeri almayı dener.
- iPhone Safari ve ana ekrana eklenen uygulama ayrı depolama alanları kullanabilir. Bu durumda otomatik aktarım olmaz; V1 yedeğini V2'den içeri yükleyin.
- Tarayıcı geçmişini / site verilerini silmeyin. Kod güncellemesi normalde verileri silmez.
- Otomatik bulut yedekleme ve cihazlar arası eşitleme YOKTUR. Düzenli .json yedeği indirin.

BİLDİRİMLER:
- V2 açıkken veya yeniden açıldığında zamanı gelen hatırlatıcıyı gösterir; bir kaydın aynı tarihine ait uyarıyı tekrar tekrar göndermez.
- iOS'ta web bildirimleri genellikle ana ekrana ekli uygulama ve izin gerektirir. V2'de arka plan push gönderimi yoktur.
- Uygulama tamamen kapalıyken zamanında bildirim garantisi YOK. Bunun için bir sunucu + Web Push aboneliği / yetkilendirme gerekir.

V2 İÇERİK:
- V1 verisini taşıma, saklama doğrulaması, son sürüm öncesi yedek, JSON yedek içeri alma/indirme
- Bugün, geciken, yaklaşan filtreleri, önemli işaretleme, saatlik erteleme
- Günlük / haftalık / aylık tekrar, tekrar eden görevin tamamlanmasında sonraki tarih
- Notları tamamlandı olarak işaretlememe, XSS güvenli metin işleme, bildirim tekrarı engelleme
- Güncellenmiş çevrimdışı önbellek sürüm yönetimi

GÜVENLİK: Özel notlarınızı veya JSON yedek dosyanızı Public GitHub reposuna ASLA yüklemeyin.
