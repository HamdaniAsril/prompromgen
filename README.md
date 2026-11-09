<p align="center"><img src="logo.svg" width="72" alt="PromPromGen logo"></p>

<h1 align="center">PromPromGen</h1>
<p align="center"><b>Prompt Promosi Generator</b> — ubah brief desain jadi prompt AI gambar yang siap pakai.</p>

<p align="center"><a href="https://hamdaniasril.github.io/prompromgen/">Buka aplikasinya →</a></p>

---

PromPromGen membantu menyusun prompt untuk materi promosi: spanduk, baliho, X-banner, poster, flyer, menu, post feed, story, thumbnail YouTube, dan banner web. Hasilnya bisa ditempel ke ChatGPT, Gemini, Ideogram, Flux, atau Midjourney.

## Fitur

- **10 jenis materi** dengan pilihan ukuran masing-masing, orientasi, dan ukuran custom. Rasio dihitung otomatis.
- **13 gaya visual** dan **11 skema warna**. Palet setiap skema dipratinjau dari warna utama yang kamu pilih.
- **Pratinjau kanvas langsung**: proporsi, warna, susunan teks, dan area aman sesuai jenis materi.
- **Prompt anti-slop**: peran art director, konteks jarak pandang, teks wajib ditulis persis, aturan hierarki dan grid, daftar larangan "gaya AI" yang generik, serta pemeriksaan ulang oleh AI sendiri.
- **Dua format**: Lengkap (untuk ChatGPT, Gemini, Ideogram, Flux) dan Midjourney (satu paragraf + `--ar`).
- Mode terang/gelap, nyaman di mobile, isian tersimpan otomatis di browser.

## Menjalankan secara lokal

Tidak perlu build. Buka `index.html` di browser, atau jalankan server statis:

```bash
python3 -m http.server 8765
```

## Teknologi

Satu file HTML + CSS + JavaScript murni, tanpa framework dan tanpa backend. Prompt disusun dari template di browser, jadi tidak ada data yang dikirim ke server.
