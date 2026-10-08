# ⚙️ Simulator Siklus Carnot & Indikator Termodinamika Kimia Interaktif

[![GitHub Pages](https://img.shields.io/badge/Demo-Live%20Simulation-success?style=for-the-badge&logo=github)](https://chariz6969.github.io/simulasi-siklus-carnot/)
[![HTML5 Canvas](https://img.shields.io/badge/Stack-HTML5%20Canvas%20%2B%20JS-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://chariz6969.github.io/simulasi-siklus-carnot/)
[![Universitas Sriwijaya](https://img.shields.io/badge/Institusi-Universitas%20Sriwijaya-blue?style=for-the-badge)](https://unsri.ac.id/)

> **Media Pembelajaran Interaktif Mandiri (Standalone & Zero-Dependency)** yang dirancang untuk mengatasi miskonsepsi kronis mahasiswa pada konsep Siklus Carnot, kesetimbangan kuasi-statik, dan fungsi keadaan termodinamika kimia.

🌐 **Akses Simulasi Online (Langsung di Browser):**  
👉 **[https://chariz6969.github.io/simulasi-siklus-carnot/](https://chariz6969.github.io/simulasi-siklus-carnot/)**

---

## 👨‍🎓 Identitas Pengembang & Proyek Akademik
* **Nama Mahasiswa**: Rasya Putra Sagala
* **Nomor Induk Mahasiswa (NIM)**: 06101182429009
* **Kelas / Program Studi**: A Indralaya / S-1 Pendidikan Kimia
* **Mata Kuliah**: Termodinamika Kimia (GKM3106)
* **Dosen Pengampu**: Dr. Sanjaya, M.Si. / Rahmat Zikri, S.Si., M.Si.
* **Institusi**: Fakultas Keguruan dan Ilmu Pendidikan, Universitas Sriwijaya (2026)

---

## 🚀 Fitur Unggulan Media Pembelajaran

### 1. Integrasi Tiga Sudut Representasi Kimia (*Johnstone's Triangle*)
* **Level Sub-Mikroskopis**: 90 partikel gas ideal independen dengan kecepatan translasi yang terkalibrasi secara mikroskopis sesuai distribusi Maxwell-Boltzmann ($v_{\text{rms}} \propto \sqrt{T}$). Partikel berpendar merah hangat pada temperatur tinggi $T_{\text{H}}$ dan melambat berwarna biru sejuk pada temperatur rendah $T_{\text{C}}$.
* **Level Makroskopis**: Model fisik silinder berdinding isolator transparan dengan piston mekanik kuasi-statik ($P_{\text{int}} = P_{\text{ext}} \pm dP$) dan mekanisme *Moving Thermal Base Platen* (pergantian fisik antara Reservoir Panas, Dudukan Insulator $k = 0$, dan Reservoir Dingin).
* **Level Simbolik / Grafik**: Pembacaan telemetri digital real-time ($T(t), P(t), V(t), q_{\text{H}}, q_{\text{C}}, W_{\text{net}}, \eta, \Delta S$) yang tersinkronisasi ke indikator grafik.

### 2. Dual Thermodynamic Indicator Scope ($P-V$ dan $T-S$)
* **Bidang $P-V$**: Memvisualisasikan perbedaan kemiringan turunan parsial kurva isotermal solid $(\partial P/\partial V)_T = -P/V$ versus kurva adiabatik putus-putus $(\partial P/\partial V)_S = -\gamma P/V$ yang $40\%$ lebih curam.
* **Bidang $T-S$**: Membuktikan secara visual bahwa siklus Carnot bertransformasi menjadi persegi panjang ortogonal sempurna, di mana luas area tertutup identik dengan kerja mekanik netto:
  $$\oint P\,dV = \oint T\,dS = (T_{\text{H}} - T_{\text{C}})(S_{\text{B}} - S_{\text{A}}) = W_{\text{net}}$$

### 3. Mode *Phase-Locked Guided Inquiry* & *Deep-Dive Phase Inspector*
* Animasi otomatis berhenti dengan presisi di setiap batas akhir fase untuk memberi jeda refleksi kognitif sebelum beralih ke tahap berikutnya.
* Panel inspektor membedah setiap fase melalui 4 pilar: Dinamika Partikel Mikroskopis, Mekanika Piston Makroskopis, Neraca Energi & Entropi Eksak, serta Karakteristik Kurva Grafik.
* Dilengkapi *Anti-Misconception Alert System* yang menyasar langsung kelemahan konsep peserta didik.

### 4. Mesin Analisis Sensitivitas Turunan Parsial Efisiensi
* Bar komparator dinamik yang membuktikan rasio analitis turunan parsial:
  $$\left|\frac{\partial \eta}{\partial T_{\text{C}}}\right| = \frac{1}{T_{\text{H}}} \quad \text{dan} \quad \left|\frac{\partial \eta}{\partial T_{\text{H}}}\right| = \frac{T_{\text{C}}}{T_{\text{H}}^2} \implies \frac{|\partial \eta/\partial T_{\text{C}}|}{|\partial \eta/\partial T_{\text{H}}|} = \frac{T_{\text{H}}}{T_{\text{C}}}$$
* Memberikan bukti eksperimen virtual bahwa mendinginkan reservoir dingin sebesar $1\text{ K}$ dua kali lipat lebih efektif menaikkan efisiensi dibanding memanaskan reservoir panas sebesar $1\text{ K}$.

### 5. Preset Studi Kasus Soal HOTS
* **Preset 1 (Soal 1 UTS)**: Gas diatomik $N_2$ ($T_{\text{H}} = 800\text{ K}, T_{\text{C}} = 400\text{ K}, \gamma = 1{,}40$).
* **Preset 2 (Pembangkit Uap Modern)**: Uap panas lanjut ($T_{\text{H}} = 823\text{ K}, T_{\text{C}} = 300\text{ K}$).
* **Preset 3 (Siklus Kriogenik)**: Pendingin gas ($T_{\text{H}} = 500\text{ K}, T_{\text{C}} = 250\text{ K}$).

---

## 🛠️ Arsitektur & Spesifikasi Teknis
* **100% Zero-Dependency**: Murni dibangun dengan standar web asli (HTML5 Canvas 2D API, Vanilla JavaScript ES6+, dan CSS3 Modern).
* **Bebas Dependensi Eksternal**: Tanpa jQuery, tanpa React, tanpa Three.js, dan tanpa CDN.
* **Ukuran Berkas Sangat Ringan**: Ukuran berkas $< 65\text{ KB}$, dapat dimuat instan pada peramban web modern apa pun.
* **Luring Penuh (*Offline-First*)**: Berkas dapat diunduh dan dibuka langsung tanpa memerlukan sambungan internet.

---

## 📖 Cara Menjalankan Secara Lokal
1. Klon repositori ini:
   ```bash
   git clone https://github.com/Chariz6969/simulasi-siklus-carnot.git
   ```
2. Buka berkas `index.html` menggunakan peramban web apa pun (Google Chrome, Microsoft Edge, Mozilla Firefox, Safari).

---

## 📜 Lisensi & Etika Akademik
Hak Cipta © 2026 **Rasya Putra Sagala**.  
Karya ini dikembangkan sebagai luaran Proyek Ujian Tengah Semester (UTS) Mata Kuliah Termodinamika Kimia, Program Studi Pendidikan Kimia, Fakultas Keguruan dan Ilmu Pendidikan, Universitas Sriwijaya. Bebas digunakan untuk tujuan pendidikan dan pembelajaran non-komersial.
