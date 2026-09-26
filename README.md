# 🎵 Repositori Tugas & Praktikum Sinyal dan Sistem (STM)

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-Signal_Processing-8CA0D7?style=for-the-badge&logo=scipy&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

Selamat datang di repositori resmi dokumentasi dan pengerjaan tugas mata kuliah **Sinyal dan Sistem (STM)**. Repositori ini berfungsi sebagai tempat penyimpanan, analisis visualisasi sinyal, pengolahan audio digital, pemrosesan frekuensi, serta dokumentasi eksperimen praktikum secara terstruktur.

---

## 👤 Profil Pengguna / Identitas Mahasiswa

| Parameter | Informasi |
| :--- | :--- |
| **Nama Lengkap** | **Hafiz Akbar** |
| **NIM** | `123140123` *(atau 121140001)* |
| **Kode Kelas** | `IF25-40305` |
| **Mata Kuliah** | Sinyal dan Sistem (STM) |
| **Program Studi** | Teknik Informatika |
| **Repositori Utama** | `stm-if25-40305-123140123` |

---

## 📂 Struktur Repositori

Struktur direktori repositori disusun secara modular untuk memisahkan setiap tugas per modul/pertemuan:

```text
stm-if25-40305-123140123/
├── README.md                                 # Halaman ringkasan profil & daftar tugas (File Ini)
├── 02_audio_noise_statis/                    # Direktori Tugas 2: Analisis Audio & Noise Statis
│   ├── tugas_audio_noise_statis.ipynb        # Jupyter Notebook analisis sinyal & eksekusi kode
│   ├── tugas_audio_noise_statis.pdf          # Ekspor PDF dokumentasi notebook (cadangan visual)
│   ├── audio_original.wav                    # Berkas audio rekaman asli berita + noise
│   ├── audio_downsampled_naive.wav           # Audio hasil downsampling tanpa anti-aliasing
│   ├── audio_downsampled_clean.wav           # Audio hasil resampling dengan anti-aliasing (Decimation)
│   └── README.md                             # Catatan ringkas perangkat, spesifikasi audio, & sumber noise
└── ... (folder tugas pertemuan berikutnya)
```

## 🛠️ Lingkungan Pengembangan & Prasyarat

Untuk menjalankan dan mereplikasi eksperimen pada repositori ini, pastikan modul/pustaka Python berikut telah terpasang:

### 1. Requirements Pustaka Python
- **Python** `>= 3.10`
- **NumPy**: Manipulasi matriks & array sinyal diskrit
- **SciPy**: Modul `scipy.signal` untuk konvolusi & filter anti-aliasing
- **Matplotlib**: Visualisasi waveform domain waktu & spektrogram
- **Librosa / SoundFile**: Pemrosesan & I/O berkas audio WAV
- **Jupyter Lab / Notebook**: Lingkungan eksekusi interaktif

### 2. Panduan Instalasi & Membuka Notebook
```bash
# 1. Clone repositori ini
git clone https://github.com/username/stm-if25-40305-123140123.git
cd stm-if25-40305-123140123

# 2. (Opsional) Buat & aktifkan virtual environment
python -m venv venv
# Windows:
venv\Scripts\activate
# Linux/macOS:
source venv/bin/activate

# 3. Install pustaka pendukung
pip install numpy scipy matplotlib librosa soundfile jupyter

# 4. Jalankan Jupyter Notebook
jupyter notebook
```

---

## 📌 Catatan Akademis & Lisensi

- Semua berkas dalam repositori ini dibuat untuk memenuhi tugas mata kuliah **Sinyal dan Sistem (STM)**.
- Kode dan dokumentasi dapat digunakan sebagai referensi pembelajaran akademis dengan tetap mencantumkan atribusi.

---
<div align="center">
  <sub>Dikelola oleh <b>Hafiz Akbar</b> — Kode Kelas IF25-40305</sub>
</div>
