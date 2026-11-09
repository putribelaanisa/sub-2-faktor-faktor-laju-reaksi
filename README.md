# Faktor-Faktor yang Memengaruhi Laju Reaksi

Materi interaktif Kimia SMA/MA Kelas XI, Bab Laju Reaksi, Subbab 2. Halaman ini membahas empat faktor yang memengaruhi laju reaksi (konsentrasi, luas permukaan, suhu, dan katalis), dilengkapi lima simulasi, rumus beserta contoh soal, animasi penerapan, cek cepat, dan latihan pilihan ganda kompleks.

## Isi halaman

- **Simulasi 1: Laboratorium virtual Na₂S₂O₃ + HCl.** Tampak samping (partikel) dan tampak atas (tanda X), empat perlakuan, stopwatch, tabel data, dan grafik konsentrasi terhadap 1 per t.
- **Rumus hubungan laju dan waktu** (v berbanding terbalik dengan t) beserta contoh soal.
- **Simulasi 2: Potong kubus.** Volume tetap, sedangkan luas permukaan total bertambah.
- **Simulasi 3: Keping dan serbuk pualam.** Balon mengembang oleh gas CO₂, disertai grafik volume terhadap waktu.
- **Simulasi 4: Teori tumbukan dan suhu.** Model A₂ + B₂ → 2AB dengan sisi aktif dan penghitung tumbukan 10 detik terakhir.
- **Rumus pengaruh kenaikan suhu** terhadap laju dan waktu, beserta dua contoh soal.
- **Simulasi 5: Diagram energi tanpa dan dengan katalis.**
- Animasi penerapan (memasak, pembakaran kertas, perkaratan besi, pembusukan buah, kembang api), kartu faktor, rangkuman, dan 10 soal latihan dengan skor.

## Struktur file

```
sub-bab-2/
├── index.html
└── README.md
```

Seluruh CSS, JavaScript, ornamen, dan ikon tab sudah berada di dalam `index.html`. Font dimuat dari Google Fonts. Proyek ini tidak memerlukan `package.json`, proses build, atau `vercel.json`.

## Deploy ke Vercel

### Periksa dua hal ini sebelum mengunggah

1. **Nama file harus persis `index.html`.** Browser sering menambahkan angka saat mengunduh, misalnya `index (1).html`. Ganti namanya kembali menjadi `index.html`. Hal yang sama berlaku untuk `README.md`.
2. **`index.html` harus terlihat langsung di halaman utama repositori GitHub**, bukan di dalam folder.

### Lewat GitHub

1. Buat repositori baru, lalu pilih **Add file → Upload files**.
2. Seret `index.html` dan `README.md` (filenya saja, bukan foldernya), lalu tekan **Commit changes**.
3. Pastikan daftar file di repositori menampilkan `index.html` tanpa tambahan angka.
4. Di [vercel.com](https://vercel.com), pilih **Add New → Project** dan impor repositori tersebut.
5. Biarkan **Framework Preset: Other**, kosongkan Build Command dan Output Directory, lalu tekan **Deploy**.

Untuk revisi berikutnya, ganti `index.html` di GitHub. Vercel akan men-deploy ulang secara otomatis.

## Jika muncul 404: NOT_FOUND

Deploy yang berhasil tetapi menampilkan 404 hampir selalu berarti Vercel tidak menemukan `index.html`.

| Yang terlihat di GitHub | Cara memperbaiki |
|---|---|
| `index (6).html` atau nama lain | Klik file → ikon pensil → ubah nama menjadi `index.html` → Commit changes |
| Ada folder dan `index.html` di dalamnya | Di Vercel: Settings → Build and Deployment → Root Directory, isi dengan nama folder, lalu Redeploy |
| `index.html` tidak ada | Unggah ulang dan pastikan menekan **Commit changes** |

## Mencoba di komputer sendiri

Buka `index.html` dengan klik dua kali. Halaman berjalan langsung di browser tanpa server.
