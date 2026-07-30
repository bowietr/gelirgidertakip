# Personel Hedef Takip PWA

Bu klasördeki dosyaların tamamını GitHub deponuzun ana dizinine yükleyin.

Dosyalar:
- index.html
- manifest.webmanifest
- service-worker.js
- icons/icon-180.png
- icons/icon-192.png
- icons/icon-512.png

GitHub Pages:
1. Yeni bir public repository oluşturun.
2. Bu klasördeki dosyaları yükleyin.
3. Repository > Settings > Pages bölümüne girin.
4. Source: Deploy from a branch.
5. Branch: main, klasör: /(root).
6. Save düğmesine basın.

## V7 mobil optimizasyon
- iPhone 13 ve dar ekranlarda yatay taşma kaldırıldı.
- Kartlar tek sütuna alındı.
- Hedef seviyeleri tablosu mobil kart görünümüne çevrildi.

## V8 Prim güncellemesi
- Pozisyon seçimi eklendi.
- Mağaza %80 prim koşulu eklendi.
- Aktif çarpan ve tahmini prim hesaplaması eklendi.
- Hedef seviyelerinde prim karşılıkları gösterildi.

## V9 — Tema ve kullanım sayacı
- Hesapla butonu kaldırıldı; girişler değiştikçe hesaplama otomatik yapılır.
- Sıfırla butonu korunmuştur.
- Aydınlık ve karanlık tema arasında geçiş eklenmiştir.
- Seçilen tema telefonda saklanır.
- Uygulamanın kaç kez açıldığı ve önceki son açılış zamanı gösterilir.
- Tema ve sayaç bilgileri Sıfırla işleminden etkilenmez.

## V10 — Karanlık mod prim görünürlüğü
- Prim kartlarındaki açık renkli yazılar düzeltildi.
- Sarı, yeşil ve kırmızı prim kutuları için yüksek kontrastlı karanlık tema renkleri eklendi.
- Tahmini prim, aktif çarpan ve sonraki seviye değerleri karanlık modda net okunur hale getirildi.

## V11 — Prim kartları karanlık tema düzeltmesi
- Aktif prim çarpanı, tahmini prim ve sonraki prim seviyesi kartlarının beyaz arka planı kaldırıldı.
- Kart arka planları karanlık temada koyu lacivert yapıldı.
- Kart açıklamaları açık gri, sonuç değerleri beyaz yapıldı.
- CSS seçicileri prim bölümündeki farklı kart sınıflarını da kapsayacak şekilde genişletildi.
