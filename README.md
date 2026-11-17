# Landing Page Profil Interaktif - Yogo Prasetyo

Landing page profil pribadi profesional bertema kontras tinggi **Cyber Yellow & Pitch Black (Kuning & Hitam)** berbasis HTML5, Tailwind CSS, Google Fonts (*Plus Jakarta Sans* & *JetBrains Mono*), dan Web Audio API. Dibuat khusus untuk menampilkan keahlian nyata dalam rekayasa sistem *Internet of Things* (IoT) dan pemenuhan tugas individu **Digital Kewirausahaan IT**.

---

## Fitur Unggulan & Interaktivitas Halaman

1. **Top Telemetry Ticker Ribbon:**
   - Menampilkan status langsung *NODE-01: ONLINE (ESP32)*, nilai suhu, kadar kelembapan tanah, latensi ping jaringan, dan status sinyal Wi-Fi yang berfluktuasi secara real-time.
   - Tombol toggle efek audio *Web Audio API* (On/Off).

2. **Hero Section dengan Interactive ESP32 Microcontroller Deck:**
   - Efek pengetikan dinamis (*typing animation*) keahlian (*Firmware Engineer*, *IoT Systems*, dll.).
   - Modul simulator mikrokontroler interaktif di sisi kanan:
     - **Slider Kelembapan Tanah:** Menggeser kadar air tanah di bawah 40% akan langsung memicu peringatan kritis, status pompa air otomatis menyala, dan alarm buzzer aktif.
     - **Tombol Toggle LED D2:** Pengunjung dapat menyalakan/mematikan lampu indikator mikrokontroler dengan efek visual dan audio.
     - **Tombol Test Buzzer:** Menguji suara alarm frekuensi tinggi (1.4 kHz).

3. **Proyek IoT, Otomasi & Simulasi (Penjelasan Teknis Komprehensif):**
   - Filter tab kategori (*Semua*, *ESP32 & Sensor*, *Smart Otomotif*, *Assistive Tech*).
   - Fokus murni pada penjelasan teknis, alur sistem, arsitektur perangkat, dan pemecahan masalah nyata:
     - **Proyek 1:** *LAPORAN PRAKTIKUM SENSOR KELEMBAPAN TANAH MENGGUNAKAN SENSOR SOIL MOISTURE* (Akuisisi analog, otomasi pompa relai, peringatan alarm lokal & bot Telegram).
     - **Proyek 2:** *RANCANG BANGUN SMART RIDE MODE SYSTEM BERBASIS MICROKONTROLER UNTUK OPTIMASI RESPON THROTTLE MOTOR LISTRIK* (Logika kendali 3-mode: Race, Normal, Rain, dan simulasi Wokwi).
     - **Proyek 3:** *Sistem pendeteksi benda untuk orang buta dengan sensor lidar dan buzzer* (Kolaborasi industri bersama AM TECHNOLOGY Jogja, pemindaian optik LiDAR dan feedback akustik buzzer).
     - **Proyek 4:** *Rangkaian monitoring jadwal sholat mushola berbasis web dengan esp32 sebagai server* (Arsitektur web server ESP32 lokal, sinkronisasi online, integrasi Smart TV/LCD, perancangan layout PCB).

4. **Tech Arsenal & Ekosistem Kerja:**
   - Pembagian sistematis: *Embedded & IoT*, *Web Monitoring Dashboard*, dan *Cloud & Integrasi Telemetri*.

5. **Tentang Saya & Latar Belakang:**
   - Informasi akademik di D3 Teknologi Informasi, Politeknik Negeri Madiun, serta pengalaman magang di startup IoT AM TECHNOLOGY Jogja.

6. **Interactive WhatsApp Message Builder (Call to Action):**
   - Pengunjung dapat memilih topik diskusi (Proyek IoT, Web Dashboard, Peluang Kerja, atau Santai).
   - Pengunjung dapat mengetik nama/instansi mereka.
   - Preview pesan terformat otomatis secara real-time dan langsung terhubung ke tautan resmi WhatsApp Click-to-Chat `+62 882-1092-1402`.
   - Tombol *Salin Nomor* dengan feedback interaktif instan.

---

## Cara Membuka / Preview di Laptop
Cukup klik ganda file `index.html` untuk langsung membukanya di browser (Google Chrome, Microsoft Edge, Mozilla Firefox, dll.).

---

## Cara Mendapatkan Link Publik (Untuk Dikumpulkan di Spreadsheet)

### Opsi 1: Netlify Drop (Paling Cepat & Tanpa Koding, ±10 Detik)
1. Buka browser dan kunjungi: [https://app.netlify.com/drop](https://app.netlify.com/drop)
2. Tarik (*drag and drop*) folder `landing-page-yogo` ke halaman tersebut.
3. Dalam hitungan detik, Netlify akan memberikan URL publik (misal: `https://yogo-portfolio.netlify.app`).
4. Salin link tersebut dan masukkan ke spreadsheet tugas Anda.

### Opsi 2: GitHub Pages
1. Buat repository baru di GitHub bernama `landing-page-profil`.
2. Push repository lokal ini:
   ```bash
   git remote add origin https://github.com/<username-github>/landing-page-profil.git
   git branch -M main
   git push -u origin main
   ```
3. Di GitHub: Masuk ke **Settings** > **Pages** > Pada *Branch*, pilih `main` dan klik **Save**.
4. Website akan live di: `https://<username-github>.github.io/landing-page-profil`.
