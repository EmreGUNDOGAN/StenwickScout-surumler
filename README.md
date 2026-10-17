<p align="center"><strong>STENWICK SCOUT</strong><br>Bir sonraki oyununu bul.</p>

<p align="center"><a href="https://github.com/EmreGUNDOGAN/StenwickScout-surumler/releases/latest"><strong>Windows için indir ↓</strong></a></p>

Steam keşfi, kişisel kanal analizi, anahtar talepleri ve yayın planı için yerel çalışma alanı.

## Windows kurulumu

Releases sayfasından `StenwickScout-Setup-1.0.2.exe` ve istersen `.exe.sha256` dosyasını indir. Eski taşınabilir programı kapat, kurulumu aç ve Başlat menüsünden Stenwick Scout'u çalıştır. Python ayrıca kurulmaz. Stenwick Scout kendi Windows penceresinde açılır; normal kullanımda tarayıcı sekmesi açılmaz. Mevcut tasarım korunur. İlk açılış büyütülmüştür; son pencere boyutu ve konumu sonraki açılışta hatırlanır.

Program dosyaları Program Files altında; verilerin `%APPDATA%\StenwickScout` klasöründedir. Kurulum ve kaldırma kullanıcı verilerini silmez. Daha önce bu klasöre taşınmış Google bağlantıları aynı Windows hesabıyla kullanılabilir.

## Masaüstü pencere

Başlık çubuğu ve küçült/büyüt/kapat düğmeleri bulunan bir Windows penceresidir. İkinci açılış mevcut pencereyi öne getirir. Kapat düğmesi varsayılan olarak pencereyi tepsiye indirir. Tam çıkış tepsi menüsünden yapılır. Ayarlardan bu davranış kapatılabilir; Windows ile başlama varsayılan kapalıdır. Google girişleri, Steam ve küratör betiği varsayılan tarayıcıda açılır. WebView2 Runtime gerekir; setup varlığını kontrol eder.

## Güncellemeler

Yeni sürüm Ayarlar yanında görünür. **Güncelle** demeden kurulum indirilmez. Onaydan sonra önce yedek alınır; kurulum SHA-256 ile doğrulanır. Kurulum yönetici izni ister ve uygulamayı yeniden açar. Yenile sürerken güncelleme başlamaz.

## Bu depo

Bu depo kurulum dosyalarını, SHA-256 kayıtlarını ve sürüm açıklamalarını yayınlar. Kaynak kod deposu özeldir. GitHub token'ı, Google erişim dosyaları veya kullanıcı veritabanı bu depoya konmaz. Uygulamanın güncelleme kontrolü GitHub hesabı gerektirmez.

Kurulum imzasızdır; Windows yayıncıyı doğrulayamaz. Sürümün özellikleri ve doğrulama sınırları release açıklamasındadır.

<p align="center">made with ♥ by stenwick</p>
