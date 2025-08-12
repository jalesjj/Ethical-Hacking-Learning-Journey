## module 6. Membaca Manual Perintah (Man Page)
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
