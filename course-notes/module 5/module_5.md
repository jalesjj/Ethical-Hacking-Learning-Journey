# MODULE 5 - Dasar-Dasar Perintah Linux

Modul ini membahas perintah-perintah dasar Linux, mulai dari menampilkan tanggal, kalender, memahami opsi dan argumen, menggunakan manual (man page), hingga mengenali jenis command di Linux.

---

## 1. Melihat Tanggal Saat Ini
Gunakan perintah:
```bash
date
```
Perintah ini akan menampilkan tanggal, bulan, tahun, jam, dan zona waktu saat ini.  
<img width="380" height="69" alt="image" src="https://github.com/user-attachments/assets/ebe5ad69-58b6-452b-b8d9-f1b3425d8060" />

---

## 2. Melihat Kalender
Gunakan perintah:
```bash
cal
```
atau
```bash
ncal
```
- `cal` menampilkan kalender dalam format standar.
  
  <img width="306" height="264" alt="image" src="https://github.com/user-attachments/assets/d0ecfaef-f1fa-441f-adb6-26f7e4511a29" />

- `ncal` menampilkan kalender dalam format vertikal yang lebih ringkas.
  
  <img width="278" height="267" alt="image" src="https://github.com/user-attachments/assets/ba491dad-c098-4d4a-81cb-97e2a7638824" />

---

## 3. Menampilkan Kalender Satu Tahun Penuh
Gunakan perintah:
```bash
cal 2020
```
Perintah ini akan menampilkan semua bulan dalam satu tahun penuh.  
<img width="940" height="618" alt="image" src="https://github.com/user-attachments/assets/2d18979a-9f7d-4647-a5d7-47dbba3b9124" />

---

## 4. Menampilkan Bulan Tertentu
Gunakan format:
```bash
ncal <bulan> <tahun>
```
Contoh:
```bash
ncal july 2020
```
akan menampilkan kalender bulan Juli 2020.  
<img width="370" height="261" alt="image" src="https://github.com/user-attachments/assets/1e956d03-5674-4940-bab8-5bb98e355959" />]

---

## 5. Memahami Option, Parameter, dan Argument
- **Option** → Modifikasi perilaku perintah. Contoh: `-A` (after), `-B` (before).
- **Parameter** → Nilai yang diberikan ke option. Contoh: `-A1` artinya tampilkan 1 bulan setelah bulan ini.
- **Argument** → Data utama yang diproses perintah. Contoh: `juli 2004`.

Contoh penggunaan:
```bash
ncal -A1 -B1 july 2004
```
Artinya: tampilkan 1 bulan setelah dan 1 bulan sebelum Juli 2004.  
[<img width="702" height="261" alt="image" src="https://github.com/user-attachments/assets/3fde7bf5-d86d-4a1f-9ccd-3f58ec0d4e1c" />

---

## 6. Membaca Manual Perintah (Man Page)
Gunakan:
```bash
man ncal
```
Navigasi:
- Gunakan **panah atas/bawah** untuk scroll.
- Gunakan `/kata` untuk mencari teks tertentu. Contoh: `/ -w` akan mencari opsi `-w`.
- Tekan **q** untuk keluar.

**Bagian Penting dalam Man Page**:
- **SYNOPSIS** → Ringkasan format penggunaan.
- **DESCRIPTION** → Penjelasan detail fungsi.
- **OPTIONS** → Daftar opsi yang tersedia.
- **SECTION** → Menunjukkan kategori perintah (1–9).

Contoh:
```bash
man ncal
```
Akan menampilkan `CAL(1)`, artinya `cal` adalah command di section 1 (perintah eksekusi).  
<img width="940" height="677" alt="image" src="https://github.com/user-attachments/assets/d2f686ac-34fd-4694-b5fe-50d5cab23459" />

---

## 7. Mencari Perintah Terkait
Gunakan:
```bash
man -k passwd
```
Perintah ini akan menampilkan semua entri manual yang terkait dengan kata "passwd".  
<img width="181" height="91" alt="image" src="https://github.com/user-attachments/assets/e910de7c-99b1-42c3-b4ac-62fc977c9a1b" />

---

## 8. Jenis-Jenis Command di Linux
Secara umum, command di Linux terbagi menjadi 4 jenis:

1. **Executable Program**  
   - File biner yang dieksekusi langsung.  
   - Lokasi umum: `/bin`, `/usr/bin`, `/usr/local/bin`.

2. **Built-in Shell Command**  
   - Perintah bawaan shell (contoh: `cd`).  
   - Tidak memiliki man page, gunakan `help` untuk melihat informasinya:
     ```bash
     help cd
     ```

3. **Alias**  
   - Nama yang mewakili perintah tertentu.  
   - Dibuat manual menggunakan:
     ```bash
     alias ll='ls -l'
     ```

4. **Function**  
   - Sekumpulan perintah yang didefinisikan di shell dan dieksekusi bersama.

Untuk mengetahui jenis sebuah command:
```bash
type <namacommand>
```
Contoh:
```bash
type ncal
```
<img width="394" height="119" alt="image" src="https://github.com/user-attachments/assets/48e42dc1-c965-4173-9073-867bf8d1a0fc" />

---

## 9. Tips Tambahan
- Gunakan `clear` atau `Ctrl + L` untuk membersihkan layar terminal.
- Gunakan `history` untuk melihat daftar perintah yang pernah dijalankan.
- Gunakan `!!` untuk mengulang perintah terakhir.

---

## Catatan Akhir
Memahami dasar-dasar perintah Linux adalah pondasi untuk administrasi sistem, scripting, dan penggunaan lanjutan. Latihan rutin sangat dianjurkan agar terbiasa dengan opsi dan argument masing-masing command.
