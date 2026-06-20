# blockchain-network-forensics
# Blockchain untuk Bukti Digital Jaringan (PCAP)

## 📋 Identitas
| **NIM** | 23040700004 |
|---------|-------------|
| **Nama** | Muhammad Sultan Arif |
| **Kelas** | [A&B] |
| **Mata Kuliah** | [BLOCKCHAIN] |

---

## 📖 Deskripsi Tugas
Tugas ini bertujuan untuk mengimplementasikan sistem blockchain sederhana untuk menjaga **integritas** dan **chain of custody** bukti digital jaringan. Sistem mencakup:

1. **Akuisisi Data Jaringan** - Menggunakan Wireshark untuk menangkap lalu lintas jaringan
2. **Perhitungan Hash SHA-256** - Setiap file PCAP dihitung hash-nya sebagai sidik jari digital
3. **Simulasi Blockchain** - Blockchain sederhana untuk menyimpan metadata bukti digital
4. **Validasi Blockchain** - Memverifikasi integritas seluruh blockchain
5. **Deteksi Perubahan** - Bonus: mendeteksi perubahan 1 byte pada file PCAP

---

## 🛠️ Tools yang Digunakan
| Tools | Fungsi |
|-------|--------|
| **Wireshark** | Akuisisi lalu lintas jaringan |
| **Python 3.x** | Pemrograman utama |
| **Scapy** | Membaca dan memanipulasi file PCAP |
| **Google Colab** | Platform eksekusi kode |
| **GitHub** | Penyimpanan repository |

---

## 📁 Struktur Repository
📁 23040700004_Muhammad Sultan Arif/
├── 📁 evidence/
│ ├── PCAP01_23040700004.pcapng (30 paket)
│ ├── PCAP02_23040700004.pcapng (50 paket)
│ ├── PCAP03_23040700004.pcapng (70 paket)
│ ├── PCAP04_23040700004.pcapng (90 paket)
│ └── PCAP05_23040700004.pcapng (100 paket)
├── 📁 sourcecode/
│ └── blockchainpcap.py
├── 📁 screenshot/
│ ├── hashingresult.png
│ ├── blockchainresult.png
│ └── validation_result.png
├── 📁 report/
│ └── laporan.pdf
└── README.md
