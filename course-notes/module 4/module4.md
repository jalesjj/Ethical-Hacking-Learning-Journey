# MODUL 4 - Kali Linux

## 1. Membuka VMware Workstation
1. Pilih **Player → File → Open**.  
   <img width="638" height="215" alt="image" src="https://github.com/user-attachments/assets/c4040b67-b9cf-4c72-8fcc-c75cb2e41471" />
2. Pilih file Kali Linux Anda yang berekstensi `.vmx`, lalu klik **Open**.
3. Jika RAM di atas 4GB:
   - Klik **Edit Virtual Machine Settings**.
   - Atur RAM menjadi **4GB**, lalu klik **OK**.  
     <img width="733" height="742" alt="image" src="https://github.com/user-attachments/assets/038af7d2-4999-4c02-a2d0-27e774fbfe31" />
4. Klik tombol **Start** (ikon segitiga) untuk menjalankan VM. 
5. Tunggu sampai muncul form login, lalu masukkan:
   - **Username**: `root`
   - **Password**: `toor` 
6. Jika tampilan hanya layar hitam polos:
   - Ketik `power → restart guest`.  
---

## 2. Pengenalan Kali Linux Secara Mandiri
Pelajari antarmuka dan fitur Kali Linux sesuai kebutuhan Anda. 

---

## 3. Mengenal Terminal
Perintah dasar:
- `pwd` → Menampilkan posisi direktori saat ini.
- `ls` → Menampilkan daftar isi direktori.
- `ls -l` → Menampilkan isi direktori dalam format daftar vertikal.
- `ls -a` → Menampilkan isi direktori termasuk file tersembunyi.  

---

## 4. Menginstall Aplikasi Melalui Terminal
Langkah:
```bash
apt-get update
apt-get install namaaplikasi
