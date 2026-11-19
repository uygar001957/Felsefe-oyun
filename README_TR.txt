PHILOSOPHY QUEST PWA – TELEFONDAN KURULUM

1) ZIP'i telefonuna indir ve Dosyalar uygulamasından çıkar.
2) PWA'nın kurulabilmesi için dosyaların HTTPS adresinde yayınlanması gerekir. ZIP'i doğrudan açmak tek başına ana ekrana kurulabilir PWA oluşturmaz.
3) En kolay yöntemlerden biri GitHub Pages:
   - Chrome'da github.com adresini açıp ücretsiz hesap oluştur/giriş yap.
   - Yeni public repository oluştur; adı: philosophy-quest
   - Add file > Upload files ile ZIP'ten çıkardığın dosyaların tamamını yükle (klasörün içindeki dosyalar: index.html, app.js, style.css, manifest.webmanifest, sw.js, icon.svg).
   - Commit changes.
   - Repository Settings > Pages > Deploy from a branch > main > /(root) > Save.
   - Yayınlanan https://KULLANICIADI.github.io/philosophy-quest/ adresini Chrome'da aç.
4) Chrome menüsü ⋮ > Ana ekrana ekle veya Uygulamayı yükle.
5) Uygulama açılınca kitapları işaretle. İlerleme aynı tarayıcı/cihazda saklanır.

ÖNEMLİ:
- Bu bir PWA'dır; Android ana ekranında uygulama simgesi olur, gerçek Android widget'ı değildir.
- Veriler yalnızca bu cihazdaki tarayıcı depolamasında tutulur. Tarayıcı verisini silersen ilerleme kaybolabilir.
- Kitapların sayfa sayısı baskıya göre değişir; satın almadan önce kontrol et.
