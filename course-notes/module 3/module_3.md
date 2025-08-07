# MODUL 3 - Ruang Kerja untuk Hacker

Modul ini menjelaskan bagaimana menyiapkan ruang kerja yang aman dan efektif untuk mempelajari teknik hacking secara virtual menggunakan virtual machine.

---

## Tujuan

Membuat lingkungan virtual yang aman dan terkendali untuk latihan teknik hacking tanpa merusak sistem komputer utama.

---

## 7. Komponen Ruang Kerja Hacker

- **Hacking Machine**  
  Perangkat yang digunakan untuk melakukan eksperimen hacking (misalnya: Kali Linux).

- **Target Machine**  
  Sistem atau perangkat yang akan dijadikan target untuk diuji coba (misalnya: Metasploitable).

- **Website dan Jaringan untuk Di-hack**  
  Lingkungan virtual seperti DVWA atau jaringan internal.

- **Virtualization Tools**  
  Digunakan untuk menjalankan beberapa sistem operasi secara bersamaan dalam satu komputer fisik.

---

## Keuntungan Virtualisasi

- Menghindari kerusakan sistem utama.
- Dapat menginstall banyak OS tanpa partisi harddisk.
- Setiap mesin virtual bersifat independen dan terisolasi.
- Aman untuk eksperimen teknik hacking.

---

## Tools yang Digunakan

- **VMware Workstation Pro** (pengganti VMware Player).
- **Kali Linux** (sebagai hacking machine).
- **7-Zip** (untuk ekstrak file ISO/VMDK jika diperlukan).

---

### Ruang Kerja Hacker

Gunakan virtual machine untuk membuat beberapa mesin dalam satu komputer. Virtual machine akan menjadi:

- Tempat uji coba teknik hacking.
- Lingkungan aman dan terkendali.

---

### Install VMware

> ⚠️ **Catatan penting Agustus 2025:**
>  
> VMware Workstation Player sudah **tidak tersedia** sebagai produk terpisah. Sebagai gantinya, Broadcom (pemilik baru VMware) menyediakan **VMware Workstation Pro versi 17.5.2 atau lebih tinggi** secara **gratis untuk penggunaan personal**.

#### Cara Install VMware:
1. Daftar akun di: [https://support.broadcom.com](https://support.broadcom.com)
2. Lengkapi data profil (nama, negara, email, organisasi).
3. Tunggu proses **screening** (biasanya 10 menit - 24 jam).
4. Setelah lolos screening, buka menu:
   - `VMware Cloud Foundation → My Downloads`
   - Cari: **Workstation Pro**
5. Download versi **Windows/Linux** sesuai sistemmu.
6. Install seperti biasa. Saat diminta lisensi, pilih:
   - **“Use Free for Personal Use”**
7. Selesai! VMware siap digunakan untuk membuat mesin virtual seperti Kali Linux dan lainnya.

---

### Pengenalan Linux

Pelajari dasar-dasar Linux, termasuk:
- Command Line Interface (CLI)
- Struktur file system Linux
- Perintah dasar seperti `cd`, `ls`, `cp`, `mv`, `rm`, dll.

---

### Instal Kali Linux dan 7-Zip

- Download ISO Kali Linux dari situs resminya: ([https://www.kali.org](https://zsecurity.org/download-custom-kali/))
- Buat mesin virtual baru di VMware, lalu pasang ISO tersebut.
- Install **7-Zip** untuk ekstrak file .7z/.iso jika diperlukan.

---

## Selesai

Lingkungan hacking virtual sekarang sudah siap digunakan!  
