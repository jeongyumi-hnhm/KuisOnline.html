# WEBSITE KUIS ONLINE ILMUAN ISLAM TERKENAL

## Penjelasan Singkat Project
Project ini adalah website kuis online dengan tema ilmuan Islam terkenal, dilengkapi form pendaftaran nama dan email sebelum mengikuti kuis. Dibuat menggunakan HTML, CSS, dan Vanilla JavaScript (tanpa framework/library). Kuis terdiri dari 6 soal pilihan ganda (lebih dari minimal yang diminta), dengan validasi input pendaftaran dan jawaban, perhitungan skor (+20 per jawaban benar), serta tampilan status kelulusan (lulus jika skor ≥70).


## Alur Logika / Algoritma
1. **Tahap Pendaftaran**:
   - Pengguna mengisi nama dan email pada form.
   - Sistem melakukan validasi: nama tidak boleh kosong, email harus sesuai format.
   - Jika valid, form disembunyikan dan area kuis ditampilkan beserta sapaan nama pengguna.

2. **Inisialisasi Kuis**:
   - Fungsi `initQuiz()` dijalankan untuk menampilkan soal pertama secara dinamis.

3. **Proses Pengerjaan Kuis**:
   - Fungsi `displayQuestion()` menampilkan nomor soal, teks soal, dan 4 opsi jawaban.
   - Pengguna memilih opsi jawaban (ditandai dengan warna berbeda melalui `selectOption()`).
   - Tombol "Jawab" menjalankan `checkAnswer()`: jika tidak ada pilihan, muncul pesan peringatan; jika benar, skor bertambah.

4. **Navigasi Soal**:
   - Setelah jawaban diperiksa, sistem menampilkan soal berikutnya atau pindah ke halaman hasil jika semua soal selesai.

5. **Tampilan Hasil**:
   - Fungsi `showResult()` menampilkan nama peserta, skor akhir, dan status kelulusan.
   - Tombol "Ulangi Kuis" menjalankan `resetQuiz()` untuk mengembalikan kuis ke kondisi awal tanpa menghapus data nama dan email.


## Cara Menjalankan
1. Simpan semua file dalam satu folder.
2. Buka `index.html` dengan browser web apa saja.
3. Isi nama lengkap dan email yang valid, lalu klik "Mulai Kuis".
4. Jawab setiap soal dan klik "Jawab" untuk melanjutkan.
5. Setelah selesai, lihat hasilnya. Klik "Ulangi Kuis" jika ingin mencoba lagi.
