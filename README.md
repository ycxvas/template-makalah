# Template Makalah Standar Kampus Indonesia

Template Microsoft Word (`.docx`) untuk makalah mahasiswa, dengan format umum kampus di Indonesia. Penomoran bab, subbab, tabel, gambar, dan daftar isi sudah otomatis, jadi kamu tinggal menulis.

> Pedoman tiap kampus atau dosen bisa berbeda. Cocokkan dengan panduan penulisan kampusmu sebelum mengumpulkan.

## Isi repositori

| File | Keterangan |
|---|---|
| `Template_Makalah.docx` | Template makalah (sampul, kata pengantar, daftar isi, Bab I-III, daftar pustaka, lampiran, panduan) |
| `README.md` | Panduan pemakaian dan daftar shortcut |

## Cara pakai

1. Unduh `Template_Makalah.docx` dari repositori ini (tombol **Download raw file**, atau **Code > Download ZIP**).
2. Buka di Microsoft Word 365 (Windows, Mac, atau web). Kalau Word bertanya apakah isi dokumen perlu diperbarui, pilih **Yes** agar daftar isi dan nomor terisi.
3. Ganti semua teks dalam `[kurung siku]` dengan isi makalahmu.
4. Hapus halaman **Panduan Format dan Penulisan** di bagian paling akhir setelah selesai.
5. Tekan `Ctrl+A` lalu `F9` untuk memperbarui daftar isi dan semua nomor sebelum mengumpulkan.

## Format yang sudah terpasang

| Pengaturan | Nilai |
|---|---|
| Kertas | A4 |
| Margin | Kiri 4 cm, atas 3 cm, kanan 3 cm, bawah 3 cm |
| Huruf | Times New Roman 12 pt |
| Spasi | 1,5 (daftar pustaka 1) |
| Paragraf | Rata kiri-kanan, awal paragraf menjorok 1,25 cm |
| Nomor halaman | Tengah bawah. Romawi kecil (i, ii) untuk kata pengantar dan daftar isi, Arab (1, 2) mulai Bab I. Sampul tanpa nomor |
| Judul bab | Kapital, tebal, rata tengah, mulai halaman baru |
| Subbab | Tebal, rata kiri |
| Daftar pustaka | Contoh gaya APA, urut abjad, baris kedua menjorok (hanging indent) |

## Struktur makalah

```
Halaman sampul
Kata pengantar
Daftar isi
BAB I   PENDAHULUAN
        1.1 Latar Belakang
        1.2 Rumusan Masalah
        1.3 Tujuan Penulisan
        1.4 Manfaat Penulisan
BAB II  PEMBAHASAN
        2.1 ... dst.
BAB III PENUTUP
        3.1 Kesimpulan
        3.2 Saran
Daftar pustaka
Lampiran
```

## Fitur otomatis

| Fitur | Cara kerja |
|---|---|
| Nomor bab (BAB I, II, III) | Dari gaya **Heading 1** |
| Nomor subbab (1.1, 1.2, ...) | Dari gaya **Heading 2** |
| Judul tanpa nomor (Kata Pengantar, Daftar Pustaka, Lampiran) | Gaya **JudulBab** |
| Daftar isi | Dibuat dari Heading 1, Heading 2, dan JudulBab |
| Nomor tabel dan gambar | Berurutan di seluruh makalah (Tabel 1, 2, 3; Gambar 1, 2, 3) |
| Rujukan di dalam teks ("lihat Tabel 1") | Cross-reference, ikut berubah kalau nomor berubah |
| Nomor halaman | Mengikuti bagian dokumen |

Fitur yang masih manual: isi daftar pustaka dan kutipan di dalam teks. Untuk yang otomatis, gunakan **References > Citations & Bibliography** di Word atau aplikasi seperti Zotero.

### Memperbarui semua nomor

Setelah menambah, menghapus, atau mengubah judul, tabel, atau gambar: tekan `Ctrl+A` lalu `F9`. Kalau hanya daftar isi: klik kanan daftar isi, pilih **Update Field**, lalu **Update entire table**.

### Menambah isi baru

- **Subbab baru:** tulis judulnya, beri gaya **Heading 2**.
- **Bab baru:** beri gaya **Heading 1** (bernomor). Untuk bab tanpa nomor, pakai gaya **JudulBab**.
- **Paragraf biasa:** gaya **Isi** (menjorok 1,25 cm). Gaya **Isi Tanpa Indent** untuk paragraf yang tidak menjorok.
- **Tabel atau gambar baru:** salin baris keterangan yang sudah ada, lalu ubah judulnya. Nomornya menyesuaikan setelah `Ctrl+A`, `F9`.
- **Menyebut nomor tabel atau gambar di teks:** **References > Cross-reference**, pilih tipe **Bookmark**.

## Shortcut keyboard

Daftar ini untuk Word di Windows dan Mac. Tanda `-` berarti tidak ada shortcut bawaan, gunakan menu di ribbon. Shortcut bisa berbeda antarversi Word, jadi cek di **File > Options > Customize Ribbon > Keyboard shortcuts** kalau ada yang tidak berfungsi.

### Gaya dan struktur

| Fungsi | Windows | Mac |
|---|---|---|
| Heading 1 (judul bab) | `Ctrl+Alt+1` | `Cmd+Option+1` |
| Heading 2 (subbab) | `Ctrl+Alt+2` | `Cmd+Option+2` |
| Heading 3 | `Ctrl+Alt+3` | `Cmd+Option+3` |
| Kembali ke gaya Normal | `Ctrl+Shift+N` | `Cmd+Shift+N` |
| Buka kotak terapkan gaya | `Ctrl+Shift+S` | - |
| Naik / turun level heading | `Alt+Shift+Kiri` / `Alt+Shift+Kanan` | - |
| Pindahkan paragraf ke atas / bawah | `Alt+Shift+Atas` / `Alt+Shift+Bawah` | - |
| Buka panel navigasi (lompat antar heading) | `Ctrl+F` | `Cmd+F` |

### Daftar isi, nomor, dan field

| Fungsi | Windows | Mac |
|---|---|---|
| Pilih seluruh dokumen | `Ctrl+A` | `Cmd+A` |
| Perbarui semua field (daftar isi, nomor, rujukan) | `F9` | `Fn+F9` |
| Tampil / sembunyikan kode field | `Alt+F9` | `Option+Fn+F9` |
| Sisipkan footnote | `Ctrl+Alt+F` | `Cmd+Option+F` |
| Sisipkan cross-reference | - (References > Cross-reference) | - |
| Sisipkan keterangan tabel / gambar | - (References > Insert Caption) | - |
| Sisipkan page break | `Ctrl+Enter` | `Cmd+Enter` |

### Format teks dan paragraf

| Fungsi | Windows | Mac |
|---|---|---|
| Tebal | `Ctrl+B` | `Cmd+B` |
| Miring (istilah asing) | `Ctrl+I` | `Cmd+I` |
| Garis bawah | `Ctrl+U` | `Cmd+U` |
| Rata kiri-kanan (justify) | `Ctrl+J` | `Cmd+J` |
| Rata tengah | `Ctrl+E` | `Cmd+E` |
| Rata kiri | `Ctrl+L` | `Cmd+L` |
| Rata kanan | `Ctrl+R` | `Cmd+R` |
| Spasi 1 | `Ctrl+1` | `Cmd+1` |
| Spasi 1,5 | `Ctrl+5` | `Cmd+5` |
| Spasi 2 | `Ctrl+2` | `Cmd+2` |
| Hanging indent (daftar pustaka) | `Ctrl+T` | - |
| Tampil / sembunyikan tanda format | `Ctrl+Shift+8` | `Cmd+8` |
| Ulangi tindakan terakhir | `F4` atau `Ctrl+Y` | `Cmd+Y` |

### Review dan pencarian

| Fungsi | Windows | Mac |
|---|---|---|
| Cari | `Ctrl+F` | `Cmd+F` |
| Cari dan ganti | `Ctrl+H` | `Ctrl+H` |
| Aktifkan track changes | `Ctrl+Shift+E` | `Cmd+Shift+E` |
| Sisipkan komentar | `Ctrl+Alt+M` | `Cmd+Option+A` |

### Membuat shortcut sendiri untuk gaya

Kamu bisa menempelkan shortcut ke gaya di template ini (misalnya **Isi**, **JudulBab**, atau **Keterangan**):

1. Buka **Home > Styles** (panah kecil di pojok kanan bawah grup Styles).
2. Klik panah di samping nama gaya, pilih **Modify**.
3. Klik **Format > Shortcut key**, tekan kombinasi tombol yang kamu mau, lalu klik **Assign**.
4. Pilih **New documents based on this template** supaya shortcut ikut tersimpan.

Contoh usulan, silakan sesuaikan: `Ctrl+Alt+0` untuk **JudulBab**, `Ctrl+Alt+9` untuk **Isi**, `Ctrl+Alt+8` untuk **Keterangan**. Cek dulu agar tidak bentrok dengan shortcut lain.

## Tips penulisan

- Gunakan bahasa Indonesia baku sesuai PUEBI dan kalimat yang efektif.
- Gunakan kata "penulis", bukan "saya", "kami", atau "aku".
- Cetak miring istilah asing dan nama ilmiah.
- Kutipan memakai gaya yang diminta dosen, misalnya APA: (Nama, Tahun) atau (Nama, Tahun, hlm. 12). Parafrase dengan kata sendiri.
- Setiap sumber di dalam teks harus ada di daftar pustaka, dan sebaliknya.
- Rumusan masalah, tujuan, pembahasan, dan kesimpulan harus sejalan, baik jumlah maupun urutannya.
- Periksa kemiripan (plagiarisme) sesuai aturan kampus sebelum dikumpulkan.

## Kompatibilitas

- Microsoft Word 365 (Windows, Mac, web). Versi perpetual lama (Office 2019 ke bawah) mungkin tidak menampilkan semua fitur dengan benar.
- Dibuka di LibreOffice atau Google Docs bisa berjalan, tetapi daftar isi, nomor otomatis, dan nomor halaman romawi mungkin tidak tampil sama. Disarankan memakai Word.

## Kontribusi

Saran dan perbaikan dipersilakan lewat *issue* atau *pull request*. Kalau kampusmu punya format berbeda (margin, gaya sitasi, urutan bagian), silakan buat versi sendiri dan bagikan.
