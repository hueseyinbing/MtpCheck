MtpCheck / MtpAnk Front Office Tool

Genel
MtpAnk Front Office, otel resepsiyon operasyonlarını kolaylaştırmak için geliştirilmiş hafif bir web uygulamasıdır.
Tamamen HTML tabanlı çalışır ve herhangi bir backend gerektirmez. Bu nedenle:
	•	iOS
	•	Android
	•	macOS
	•	Windows
	•	Linux
üzerinde tarayıcı üzerinden çalışabilir.

Uygulama özellikle Front Office çalışanlarının günlük operasyonlarını hızlandırmak amacıyla tasarlanmıştır.

Amaç
Bu uygulama aşağıdaki operasyonları kolaylaştırmak için geliştirilmiştir:
	•	Resepsiyon işlemlerini hızlı kayıt altına almak
	•	Otel operasyonlarında kullanılan formları oluşturmak
	•	Girilen bilgileri PDF olarak export etmek
	•	Mobil cihazlarda hızlı erişim sağlamak
	•	Kurulum gerektirmeyen basit bir operasyon aracı sunmak

Özellikler
1. Tamamen Web Tabanlı
Uygulama yalnızca:
HTML
CSS
JavaScript
kullanılarak geliştirilmiştir.
Backend veya veritabanı gerektirmez.

2. PDF Oluşturma
Uygulama içinde oluşturulan veriler:
	•	otomatik olarak
	•	tek tuşla
PDF dosyasına dönüştürülebilir.
Kullanılan kütüphane:
	•	html2pdf.js

3. Mobil Uygulama Gibi Kullanım
Proje PWA benzeri davranacak şekilde hazırlanmıştır.
Apple meta tagleri:
apple-mobile-web-app-capable
apple-mobile-web-app-status-bar-style
apple-touch-icon
Bu sayede iPhone kullanıcıları:
Safari → Share → Add to Home Screen
yaparak uygulamayı native app gibi kullanabilir.

4. Modern UI
Arayüzde kullanılan teknolojiler:
	•	Glassmorphism tarzı tasarım
	•	Responsive layout
	•	Modern fontlar
Kullanılan font:
Plus Jakarta Sans

5. Icon Sistemi
Iconlar:
Font Awesome
üzerinden yüklenir.
Bu sayede:
	•	butonlar
	•	menüler
	•	aksiyonlar
görsel olarak daha anlaşılır hale gelir.
Kullanılan Teknolojiler
Teknoloji	Amaç
HTML5	Uygulama yapısı
CSS3	Tasarım
JavaScript	İşlevsellik
html2pdf.js	PDF oluşturma
Font Awesome	Iconlar
Google Fonts	Typography

Proje Yapısı
MtpCheck/
│
├── index.html
├── logo.jpg
└── README.md
index.html
Ana uygulama dosyasıdır.
Tüm UI ve JS logic burada bulunur.

Kurulum
Bu proje için herhangi bir kurulum gerekmez.
Repo klonlamak yeterlidir.
git clone https://github.com/hueseyinbing/MtpCheck.git
Klasöre gir:
cd MtpCheck
Uygulamayı çalıştır:
index.html
Tarayıcıda açman yeterlidir.

Local Development
Eğer local server ile çalıştırmak istersen:
Python
python3 -m http.server
sonra:
http://localhost:8000

Node
npx serve

Kullanım
1️⃣ Uygulamayı aç
index.html
2️⃣ Form veya operasyon alanını doldur.
3️⃣ Gerekli bilgileri gir
4️⃣ PDF oluştur
Sistem:
html2pdf.js
kullanarak sayfayı PDF’e dönüştürür.

Mobil Kullanım
iPhone için:
	1.	Safari ile aç
	2.	Share butonuna bas
	3.	Add to Home Screen
Artık uygulama native app gibi çalışır.

Avantajları
	•	Kurulum gerektirmez
	•	Offline çalışabilir
	•	Platform bağımsız
	•	Hızlı
	•	Hafif

Sınırlamalar
Bu proje:
	•	backend içermez
	•	database içermez
	•	veri kalıcı saklanmaz
Tüm işlemler tarayıcı içinde gerçekleşir.

Gelecek Geliştirmeler
Planlanan geliştirmeler:
	•	LocalStorage veri saklama
	•	Otel check-in modülü
	•	Check-out raporu
	•	Günlük resepsiyon raporu
	•	Export Excel
	•	Cloud sync
  
Katkıda Bulunma
Repo fork edilerek geliştirilebilir.
git fork
git clone
git commit
git push
Pull request gönderilebilir.
