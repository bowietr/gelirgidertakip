# Cüzdanım — Gelir Gider Takibi

Mobil uyumlu, kurulumsuz çalışan gelir–gider takip uygulaması. Veriler kullanıcının tarayıcısında `localStorage` ile saklanır.

## GitHub Pages ile yayınlama

1. GitHub'da yeni ve herkese açık bir depo oluşturun.
2. Bu klasördeki tüm dosya ve klasörleri deponun ana dizinine yükleyin.
3. GitHub deposunda **Settings → Pages** bölümünü açın.
4. **Build and deployment** altında **Deploy from a branch** seçin.
5. Branch olarak `main`, klasör olarak `/ (root)` seçip kaydedin.
6. Birkaç dakika sonra Pages adresi aynı ekranda görünür.

## Mobil uygulama gibi kullanma

- iPhone/iPad: Safari → Paylaş → **Ana Ekrana Ekle**
- Android: Chrome → Menü → **Ana ekrana ekle / Uygulamayı yükle**

## Dosyalar

- `index.html`: Uygulamanın tamamı
- `manifest.webmanifest`: PWA bilgileri
- `sw.js`: Çevrimdışı kullanım önbelleği
- `icons/`: Uygulama ikonları

## Önemli

Veriler sunucuya gönderilmez. Tarayıcı verileri silinirse kayıtlar da silinir; bu nedenle uygulama içindeki JSON yedekleme özelliğini düzenli kullanın.
