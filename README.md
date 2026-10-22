# Arabic Quest — Arabica Town Deluxe

Prototype game pembelajaran bahasa Arab berbasis HTML, CSS, dan JavaScript. Tidak membutuhkan framework atau proses build.

## Fitur
- Peta kota interaktif dan karakter yang bisa bergerak.
- Avatar, nama karakter, dan pilihan outfit.
- NPC memberi misi untuk empat maharah: Istima', Kalam, Qira'ah, Kitabah.
- Urutan soal dan opsi jawaban diacak setiap sesi.
- XP, koin, level, statistik, dan penyimpanan progres melalui localStorage.
- Toko virtual: beli dan pasang dekorasi rumah menggunakan koin.
- Daily Quest yang melacak latihan semua empat maharah per hari dan bonus yang dapat diklaim sekali sehari.
- Final Boss gabungan empat maharah; raih minimal 80 XP untuk membuka tantangan. Skor minimal 3/4 membuka Dunia Andalusia (penanda progres).
- Text-to-speech untuk contoh bahasa Arab jika browser mendukung.

## Menjalankan lokal
Buka `index.html` dengan browser modern, atau gunakan VS Code dengan ekstensi Live Server.

## Deploy ke Netlify dari GitHub
1. Buat repository GitHub.
2. Upload `index.html`, `README.md`, dan `netlify.toml` ke root repository.
3. Di Netlify pilih **Add new site / Import an existing project**, lalu hubungkan repository.
4. Branch `main`, Build command kosong, Publish directory `.`.
5. Deploy. Commit baru ke GitHub akan memicu deploy otomatis.

## Catatan
Ini prototipe 2D bergaya simulator kota, bukan game 3D penuh. Progres dan daily quest tersimpan di browser lokal; tidak tersinkron lintas perangkat. Fitur suara tergantung dukungan browser dan perangkat. Dunia Andalusia saat ini merupakan status unlock/progres yang dapat dikembangkan menjadi peta baru.
