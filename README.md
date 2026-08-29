# Personal Portfolio Website - MyApp

Ini adalah repositori untuk website portofolio pribadi saya. Website ini dirancang dengan gaya modern, minimalis, dan futuristik, menampilkan profil singkat saya dan beberapa proyek *web application*.
Website ini dideploy menggunakan Vercel.

##  Fitur Utama

- **Desain Modern & Futuristik:** Menggunakan palet warna *deep navy* dan tema *glassmorphism* untuk elemen kartu.
- **Latar Belakang Partikel Animasi:** Latar belakang dinamis dengan bintik-bintik putih melayang yang memberikan kesan interaktif.
- **Navigasi Melayang:** Menu bar sticky yang responsif untuk navigasi cepat antar bagian (Profil, Website).
- **Modal Foto:** Fitur pop-up untuk melihat foto profil dalam resolusi penuh dengan latar belakang redup.
- **Responsif:** Dioptimalkan untuk tampilan di berbagai perangkat, mulai dari desktop hingga smartphone.

##  Teknologi yang Digunakan

- **HTML5:** Struktur konten website.
- **Tailwind CSS (CDN):** Framework CSS utility-first untuk *styling* cepat dan responsif.
- **JavaScript (Vanilla):** Untuk logika modal foto, *smooth scrolling*, dan sistem latar belakang partikel animasi.
- **Font Google (Plus Jakarta Sans):** Tipografi modern dan bersih.
- **Vercel:** Platform untuk deployment dan hosting statis.

##  Struktur Konten

Website ini dibagi menjadi beberapa bagian utama:

1.  **Profil:** Menampilkan badge indikator status, foto profil (dengan fitur modal), nama lengkap, dan deskripsi diri singkat.
2.  **Website:** Daftar *featured* proyek aplikasi web yang telah diselesaikan.

##  Proyek Web yang Ditampilkan

Bagian "Website" menampilkan 3 aplikasi web unggulan saya:

1.  **Anti-Scam URL:** Sistem deteksi URL phishing untuk meningkatkan keamanan pengguna internet.
2.  **Wisata Nganjuk:** Panduan dan daftar lokasi wisata menarik di Kabupaten Nganjuk.
3.  **VT Downloader:** Alat untuk mengunduh video TikTok tanpa tanda air (*watermark*).

Setiap kartu proyek menyertakan deskripsi singkat dan tombol langsung untuk membuka aplikasi tersebut.

##  Menjalankan Secara Lokal

Jika Anda ingin melihat atau mengembangkan website ini di komputer lokal Anda:

1.  **Clone repositori ini:**
    git clone [https://github.com/USERNAME_ANDA/REPOS_ANDA.git](https://github.com/USERNAME_ANDA/REPOS_ANDA.git)
    cd REPOS_ANDA
2.  **Buka file `index.html`** langsung di browser Anda, atau gunakan ekstensi VS Code seperti **Live Server** untuk preview yang lebih baik.
3.  *(Opsional)* Menggunakan Node.js/npx:
    npx serve .

##  Deployment
Website ini secara otomatis dideploy ke Vercel setiap kali ada perubahan yang didorong ke branch `main`.
Untuk melakukan deployment secara manual menggunakan Vercel CLI:
vercel --prod
