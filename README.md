<p align="center"><strong>STENWICK SCOUT</strong><br>Bir sonraki oyununu bul.</p>

<p align="center"><a href="https://github.com/EmreGUNDOGAN/StenwickScout-surumler/releases/latest"><strong>Windows için indir ↓</strong></a></p>

Steam keşfi, kişisel kanal analizi, anahtar talepleri ve yayın planı için yerel çalışma alanı.

## v1.1.0 — Kendi sonuçlarından öğrenen model

Oyun başına ilk uygun videonun sonuçlarından öğrenen deneysel model, günlük karar/tahmin kaydı ve veri sağlığı kontrolleri. Model yeterli yeni sınama kanıtı olmadan ana puanı değiştirmez. Ayrıntılar ve doğrulama sınırları [v1.1.0 sürüm notlarında](https://github.com/EmreGUNDOGAN/StenwickScout-surumler/releases/tag/v1.1.0).

## v1.2.0 — Daha okunur, daha denetlenebilir Scout

Sekmeli model günlüğü ve dışa aktarım, insan onaylı kanal önerileri, düzenlenmiş radar içgörüleri, kompakt talepler ve ayrıntılı haftalık rapor. Geri/ileri gezinme, global arama ve kaynak güncelliği. Modelin devreye alma şartları korunur. Ayrıntılar ve doğrulama sınırları [v1.2.0 sürüm notlarında](https://github.com/EmreGUNDOGAN/StenwickScout-surumler/releases/tag/v1.2.0).

## Windows kurulumu

Releases sayfasından `StenwickScout-Setup-1.2.0.exe` ve istersen `.exe.sha256` dosyasını indir. Eski taşınabilir programı kapat, kurulumu aç ve Başlat menüsünden Stenwick Scout'u çalıştır. Python ayrıca kurulmaz. Stenwick Scout kendi Windows penceresinde açılır; normal kullanımda tarayıcı sekmesi açılmaz. Mevcut tasarım korunur. İlk açılış büyütülmüştür; son pencere boyutu ve konumu sonraki açılışta hatırlanır.

Program dosyaları Program Files altında; verilerin `%APPDATA%\StenwickScout` klasöründedir. Kurulum ve kaldırma kullanıcı verilerini silmez. Daha önce bu klasöre taşınmış Google bağlantıları aynı Windows hesabıyla kullanılabilir.

## Masaüstü pencere

Başlık çubuğu ve küçült/büyüt/kapat düğmeleri bulunan bir Windows penceresidir. İkinci açılış mevcut pencereyi öne getirir. Kapat düğmesi varsayılan olarak pencereyi tepsiye indirir. Tam çıkış tepsi menüsünden yapılır. Ayarlardan bu davranış kapatılabilir; Windows ile başlama varsayılan kapalıdır. Google girişleri, Steam ve küratör betiği varsayılan tarayıcıda açılır. WebView2 Runtime gerekir; setup varlığını kontrol eder.

## Güncellemeler

Yeni sürüm Ayarlar yanında görünür. **Güncelle** demeden kurulum indirilmez. Onaydan sonra önce yedek alınır; kurulum SHA-256 ile doğrulanır. Kurulum yönetici izni ister ve uygulamayı yeniden açar. Yenile sürerken güncelleme başlamaz.

## Bu depo

Bu depo kurulum dosyalarını, SHA-256 kayıtlarını ve sürüm açıklamalarını yayınlar. Kaynak kod deposu özeldir. GitHub token'ı, Google erişim dosyaları veya kullanıcı veritabanı bu depoya konmaz. Uygulamanın güncelleme kontrolü GitHub hesabı gerektirmez.

Kurulum imzasızdır; Windows yayıncıyı doğrulayamaz. Sürümün özellikleri ve doğrulama sınırları release açıklamasındadır.

<p align="center">made with ♥ by stenwick</p>
