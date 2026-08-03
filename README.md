# ADL EKSPER — Statik Web Site (GitHub Pages)

Bu repo GitHub Pages ile direkt yayınlanabilecek statik site içindir. Tailwind CSS Play CDN kullanılarak hızlıca kurulmuştur.

İçerik:
- index.html, paketler.html, hakkimizda.html, subeler.html, iletisim.html
- assets/ içinde logo, favicon ve görseller (kendiniz ekleyin)
- sitemap.xml ve robots.txt

Kullanım — hızlı deploy:
1. Yeni bir GitHub repo oluşturun (ör. adl-eksper-site).
2. Bu dosyaları repo köküne ekleyin ve commit/push yapın:
   git add .
   git commit -m "Initial static site"
   git push origin main
3. GitHub → Repository Settings → Pages bölümüne gidin.
   - Branch: `main`
   - Folder: `/ (root)`
   - Save ve Publish (birkaç dakika içinde site canlı olur).
4. sitemap.xml içindeki URL'leri kendi kullanıcı/repo'nuz ile güncelleyin.
5. İletişim formu için Formspree veya benzeri bir servis kullanın (iletisim.html form action alanını güncelleyin).

Notlar:
- Görselleri optimize edin (WebP/modern formatlar önerilir).
- Daha profesyonel üretim için Tailwind'i build sürecine dahil edip CSS'i minimize edebilirsiniz.
- Admin panel ve backend isterseniz Next.js + Express + Postgres ile bir sonraki adımı hazırlayabilirim.
