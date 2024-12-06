# Bakso Lezat Website

Website **Bakso Lezat** adalah platform online untuk mempromosikan usaha mikro kecil (UMK) di bidang kuliner bakso. Website ini dirancang menggunakan **HTML**, **CSS**, dan **Bootstrap** untuk memberikan pengalaman yang menarik dan responsif kepada pengguna.

## Fitur Utama

- **Beranda:** Menampilkan informasi singkat tentang usaha Bakso Lezat, termasuk deskripsi, gambar, dan testimoni pelanggan.
- **Menu:** Daftar menu bakso lengkap dengan harga dan gambar.
- **Tentang Kami:** Informasi tentang sejarah dan visi misi usaha Bakso Lezat.
- **Kontak:** Formulir kontak untuk pelanggan yang ingin memesan atau memberikan feedback.

## Teknologi yang Digunakan

- **HTML5**: Untuk struktur halaman.
- **CSS3**: Untuk gaya dan desain visual.
- **Bootstrap 5**: Untuk membuat tampilan responsif dan cepat.
- **JavaScript**: (Opsional) Untuk animasi atau interaktivitas tambahan.

## Cara Menggunakan

1. **Kloning Repository**:
   ```bash
   git clone https://github.com/username/bakso-lezat.git
   ```
2. **Buka File `index.html`:**
   - Gunakan browser modern (Google Chrome, Firefox, Edge) untuk membuka file `index.html`.
3. **Kustomisasi:**
   - Edit konten langsung di file HTML jika perlu menyesuaikan informasi bisnis Anda.

## Animasi Saat Scroll

Website ini menggunakan **AOS (Animate On Scroll)** untuk memberikan animasi halus pada elemen yang terlihat saat pengguna melakukan scroll. Berikut cara integrasinya:

- Tambahkan CDN AOS:
  ```html
  <link
    href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css"
    rel="stylesheet"
  />
  <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>
  ```
- Inisialisasi AOS:
  ```html
  <script>
    AOS.init({
      duration: 1000,
      once: true,
    });
  </script>
  ```
- Gunakan atribut `data-aos` pada elemen HTML:
  ```html
  <div data-aos="fade-up">Animasi saat scroll!</div>
  ```

## Kontribusi

Jika Anda ingin berkontribusi untuk pengembangan website ini:

1. Fork repository.
2. Buat branch fitur baru.
3. Kirim pull request setelah selesai.

## Lisensi

Website ini dilisensikan di bawah [MIT License](LICENSE). Anda bebas menggunakannya untuk keperluan pribadi atau komersial.

---

**Nikmati sajian bakso terbaik bersama Bakso Lezat!**
