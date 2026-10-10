<div align="center">

# 🌐 Praktikum Sistem Terdistribusi & Terdesentralisasi

### Dokumentasi Praktikum · Tugas · Implementasi Program

**Program Studi S1 Informatika**  
Universitas Teknologi Digital Indonesia

<br>

[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/ciaxzs/prak-dis-dec)
[![Language](https://img.shields.io/badge/Language-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://www.microsoft.com/windows)

<br>

Repositori dokumentasi dan implementasi praktikum mata kuliah  
**Sistem Terdistribusi dan Terdesentralisasi.**

</div>

---

## 📑 Daftar Isi

- [📖 Tentang Repositori](#-tentang-repositori)
- [🎯 Ruang Lingkup Pembelajaran](#-ruang-lingkup-pembelajaran)
- [🛠️ Teknologi dan Tools](#️-teknologi-dan-tools)
- [📚 Daftar Modul Praktikum](#-daftar-modul-praktikum)
- [📂 Struktur Direktori](#-struktur-direktori)
- [🚀 Panduan Penggunaan](#-panduan-penggunaan)
- [👩‍💻 Profil Mahasiswa](#-profil-mahasiswa)
- [📜 Lisensi](#-lisensi)

---

## 📖 Tentang Repositori

Repositori ini digunakan untuk menyimpan, mengelola, dan mendokumentasikan hasil kegiatan praktikum mata kuliah **Sistem Terdistribusi dan Terdesentralisasi** pada Program Studi S1 Informatika, Universitas Teknologi Digital Indonesia.

Dokumentasi di dalam repositori mencakup materi praktikum, kode program, hasil implementasi, serta laporan dan bukti pengerjaan setiap modul.

Melalui praktikum ini, mahasiswa diharapkan dapat memahami konsep komunikasi antarkomponen, pertukaran data melalui jaringan, serta implementasi layanan yang melibatkan interaksi antara beberapa komponen perangkat lunak.

Repositori ini juga menjadi dokumentasi perkembangan pembelajaran dan tempat menyimpan hasil pekerjaan praktikum secara terstruktur menggunakan Git dan GitHub.

## 🎯 Ruang Lingkup Pembelajaran

Berikut beberapa topik yang direncanakan menjadi bagian dari eksplorasi pembelajaran dalam repositori ini:

| No. | Topik | Gambaran Umum |
|:---:|---|---|
| 01 | Socket Programming | Komunikasi antaraplikasi menggunakan TCP dan UDP. |
| 02 | Client-Server Architecture | Pertukaran permintaan dan respons antara client dan server. |
| 03 | Remote Procedure Call (RPC) | Pemanggilan prosedur pada layanan atau sistem lain. |
| 04 | RESTful API | Pertukaran data melalui layanan berbasis HTTP. |
| 05 | Message Queue | Komunikasi asinkron dan pertukaran pesan antarlayanan. |
| 06 | Peer-to-Peer (P2P) | Konsep komunikasi antarnode dalam jaringan peer-to-peer. |
| 07 | Sistem Terdesentralisasi | Arsitektur sistem tanpa ketergantungan penuh pada satu pusat. |
| 08 | Consensus Mechanisms | Konsep kesepakatan antarpartisipan dalam sistem terdistribusi. |
| 09 | Blockchain Fundamentals | Dasar struktur blockchain dan konsep smart contract. |
| 10 | Containerization | Pengemasan aplikasi dan lingkungan eksekusi menggunakan container. |

*Catatan: Daftar di atas merupakan gambaran ruang lingkup pembelajaran, bukan pernyataan bahwa seluruh topik telah dipraktikkan atau diselesaikan.*

## 🛠️ Teknologi dan Tools

Teknologi yang digunakan disesuaikan dengan kebutuhan setiap modul praktikum.

| Kategori | Teknologi / Tools | Kegunaan |
|---|---|---|
| Bahasa Pemrograman | Python | Implementasi program praktikum. |
| Version Control | Git | Mengelola perubahan kode dan dokumentasi. |
| Repository Hosting | GitHub | Menyimpan dan mendokumentasikan hasil praktikum. |
| Code Editor | Visual Studio Code | Menulis dan mengelola kode program. |
| Terminal | PowerShell / Terminal | Menjalankan perintah dan menguji program. |
| Komunikasi Jaringan | TCP / UDP / HTTP | Mendukung komunikasi antarkomponen sesuai kebutuhan modul. |

Teknologi tambahan dapat digunakan apabila diperlukan oleh materi praktikum berikutnya.

## 📚 Daftar Modul Praktikum

Tabel berikut digunakan untuk mencatat perkembangan pengerjaan praktikum.

| Modul | Topik / Materi | Status | Dokumentasi |
|:---:|---|:---:|---|
| 01 | Pengenalan Sistem Terdistribusi dan Konsep Networking | DONE | [📂 Pertemuan 01](./Pertemuan-01/) |
| 02 | Socket Programming (TCP/UDP Client-Server) | DONE | [📂 Pertemuan 02](./Pertemuan-02/) |
| 03 | Remote Procedure Call (RPC) / RMI | DONE | [📂 Pertemuan 03](./Pertemuan-03/) |
| 04 | RESTful API dan Inter-Service Communication | DONE | [📂 Pertemuan 04](./Pertemuan-04/) |
| 05 | Message Queue dan Event-Driven Architecture | IN PROGRESS | [📂 Pertemuan 05](./Pertemuan-05/) |
| 06 | Peer-to-Peer (P2P) Protocol Architecture | PENDING | [📂 Pertemuan 06](./Pertemuan-06/) |
| 07 | Ujian Tengah Semester / Evaluasi | PENDING | [📂 Pertemuan 07](./Pertemuan-07/) |
| 08 | Sistem Terdesentralisasi dan Consensus Mechanisms | PENDING | [📂 Pertemuan 08](./Pertemuan-08/) |
| 09 | Basic Blockchain Architecture dan Smart Contracts | PENDING | [📂 Pertemuan 09](./Pertemuan-09/) |
| 10 | Containerization dengan Docker dan Distributed Nodes | PENDING | [📂 Pertemuan 10](./Pertemuan-10/) |

### 📌 Keterangan Status

- ✅ **DONE** — Praktikum telah diselesaikan.
- 🟡 **IN PROGRESS** — Praktikum sedang dikerjakan.
- ⚪ **PENDING** — Praktikum belum dikerjakan.

> **Penting:** Sesuaikan status dan tautan modul dengan kondisi repositori yang sebenarnya. Nama folder pada tabel harus sama dengan nama folder yang tersedia di GitHub.

## 📂 Struktur Direktori

Struktur direktori berikut merupakan contoh organisasi repositori untuk memisahkan setiap modul praktikum.

```text
prak-dis-dec/
│
├── .github/
│   └── workflows/
│
├── Pertemuan-01/
│   ├── README.md
│   ├── server.py
│   ├── client.py
│   └── images/
│
├── Pertemuan-02/
│   └── README.md
│
├── Pertemuan-03/
│   └── README.md
│
├── Pertemuan-04/
│   └── README.md
│
├── Pertemuan-05/
│   └── README.md
│
├── Pertemuan-06/
│   └── README.md
│
├── Pertemuan-07/
│   └── README.md
│
├── Pertemuan-08/
│   └── README.md
│
├── Pertemuan-09/
│   └── README.md
│
├── Pertemuan-10/
│   └── README.md
│
├── docs/
│   └── README.md
│
├── .gitignore
├── LICENSE
└── README.md
```

### 📁 Fungsi Direktori

| Direktori / File | Keterangan |
|---|---|
| `.github/` | Konfigurasi GitHub dan workflow jika digunakan. |
| `Pertemuan-XX/` | Direktori untuk menyimpan pekerjaan setiap pertemuan. |
| `README.md` | Dokumentasi materi, langkah praktikum, hasil, dan kesimpulan. |
| `images/` | Tempat menyimpan screenshot bukti praktikum. |
| `docs/` | Dokumentasi tambahan apabila diperlukan. |
| `.gitignore` | Menentukan file atau direktori yang tidak perlu dilacak Git. |
| `LICENSE` | Informasi lisensi repositori jika lisensi telah ditetapkan. |

*Struktur di atas adalah contoh. Pertahankan struktur yang benar-benar digunakan pada repositori dan sesuaikan dokumentasinya apabila diperlukan.*

## 🚀 Panduan Penggunaan

### 1. Clone Repositori

Pastikan Git telah terpasang pada komputer. Buka PowerShell atau terminal, kemudian jalankan:

```powershell
git clone https://github.com/ciaxzs/prak-dis-dec.git
```

Masuk ke direktori repositori:

```powershell
cd prak-dis-dec
```

Perintah tersebut akan mengunduh salinan repositori ke komputer sehingga file dapat dipelajari dan dikelola secara lokal.

### 2. Buka Repositori di Visual Studio Code

Jika Visual Studio Code telah terpasang, jalankan:

```powershell
code .
```

Perintah ini membuka direktori repositori yang sedang aktif di Visual Studio Code.

### 3. Masuk ke Direktori Praktikum

Sebagai contoh, untuk membuka modul pertama:

```powershell
cd Pertemuan-01
```

Pastikan direktori tersebut memang tersedia di repositori. Jika nama folder berbeda, gunakan nama folder yang sebenarnya.

### 4. Jalankan Program

Apabila modul menggunakan program Python dengan file `server.py` dan `client.py`, ikuti urutan berikut.

**Terminal pertama — Jalankan server:**

```powershell
python server.py
```

**Terminal kedua — Jalankan client:**

```powershell
python client.py
```

Server perlu dijalankan terlebih dahulu agar client dapat mengirimkan permintaan kepadanya.

> **Catatan:** Perintah tersebut merupakan contoh untuk modul yang memang memiliki kedua file tersebut. Nama file, argumen, dependensi, dan urutan eksekusi harus disesuaikan dengan instruksi pada masing-masing modul.

### 5. Periksa Perubahan Git

Setelah melakukan perubahan pada kode atau dokumentasi, periksa status repositori:

```powershell
git status
```

Tambahkan file yang ingin disimpan ke Git:

```powershell
git add .
```

Buat commit dengan pesan yang menjelaskan perubahan:

```powershell
git commit -m "Memperbarui dokumentasi praktikum"
```

Kirim perubahan ke GitHub:

```powershell
git push
```

Pastikan perubahan sudah tersimpan di branch yang benar dan tidak ada masalah sinkronisasi dengan repositori remote.

## 👩‍💻 Profil Mahasiswa

<div align="center">

### Odilia Valensia Pradevi Putri

Mahasiswa S1 Informatika  
Universitas Teknologi Digital Indonesia

</div>

| Informasi | Keterangan |
|---|---|
| Nama | Odilia Valensia Pradevi Putri |
| Program Studi | S1 Informatika |
| Perguruan Tinggi | Universitas Teknologi Digital Indonesia (UTDI) |
| GitHub | [@ciaxzs](https://github.com/ciaxzs) |
| Repositori Praktikum | [prak-dis-dec](https://github.com/ciaxzs/prak-dis-dec) |

Repositori ini merupakan dokumentasi akademik untuk menyimpan hasil pembelajaran, implementasi program, dan laporan praktikum selama perkuliahan.

## 📜 Lisensi

Repositori ini digunakan untuk keperluan pembelajaran dan dokumentasi akademik.

Jika repositori menggunakan MIT License, informasi lisensi dapat dilihat pada file [`LICENSE`](./LICENSE).

Penggunaan dan distribusi kode tetap mengikuti ketentuan lisensi yang benar-benar tercantum dalam repositori.

---

<div align="center">

**Dibuat untuk mendokumentasikan proses belajar dan pengembangan keterampilan di bidang Informatika.**

<br>

*Odilia Valensia Pradevi Putri · S1 Informatika · UTDI*

</div>