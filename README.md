# 🧪 Memristor – by Bluefox192
> **Simulasi, eksperimen, dan eksplorasi elemen dasar keempat**

![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)
![Focus: SPICE | Neuromorphic](https://img.shields.io/badge/focus-simulasi%20%7C%20memristor%20%7C%20neuromorphic-lightblue.svg)
![Status: Exploratory](https://img.shields.io/badge/status-exploratory-orange.svg)
![DIY Potential](https://img.shields.io/badge/DIY-in%20progress-important.svg)
![Python Model](https://img.shields.io/badge/python-model-green.svg)
[![FPGA](https://img.shields.io/badge/FPGA-optional-lightgrey.svg)]()


Eksplorasi mendalam tentang **memristor** – komponen pasif hipotetik yang menghubungkan **muatan dan fluks magnetik** – melalui pendekatan simulasi, teori, dan potensi realisasi DIY dalam sistem analog, FPGA, dan neuromorfik.

---

## 🧠 Tujuan Proyek

- 🧪 Memodelkan karakteristik I–V khas memristor
- 🧮 Menyimulasikan memristor via **SPICE**, **Python**, dan tool numerik
- 🧷 Mengeksplorasi realisasi fisik atau semi-fisik (FPGA, mikrokontroler)
- 🧬 Memahami peran memristor dalam sistem **edge AI** dan **komputasi neuromorfik**
- 🛠️ Membuka jalur untuk eksperimen **DIY memristor emulator**

---

## 🔬 Eksperimen Saat Ini

- ✅ Simulasi karakteristik I-V dengan LTSpice (model HP dan Biolek)
- ✅ Implementasi model Python (nonlinear + plotting dengan Matplotlib)
- ⏳ Evaluasi noise, hysteresis, dan switching behavior
- ⏳ Integrasi model dengan simulator neuromorfik (mis. Brian2/NEST)

---

## 🛠️ Rencana Ke Depan

| Target | Status | Catatan |
|--------|--------|---------|
| 🛒 Pembelian CH341A dan eksperimen flash (paralel) | 🔄 | Untuk dump dan modifikasi sistem neuromorfik nanti |
| 🧱 Desain emulator memristor berbasis op-amp & MOSFET | 🧠 Ide | Replika sederhana memristor fisik |
| ⚡ Uji integrasi ke FPGA | 🔲 | Gunakan LUT untuk meniru memristansi |
| 🧠 Simulasi di sistem neuromorfik sederhana | 🔲 | Input dari sensor ke "neuron" berbasis memristor |
| 📷 Dokumentasi open hardware | 🔲 | PCB & 3D printable frame untuk eksperimen edukatif |
| 📝 Tulisan teknis & eksperimen terbuka | 🔲 | Siapkan log, dataset, dan analisis publik |

---

## 📁 Struktur Direktori

```

/memristor
├── spice/        → File LTSpice dan varian model
├── models/       → Implementasi Python dan fungsi dasar
├── plots/        → Output grafik simulasi dan analisis
├── docs/         → Artikel, referensi, dan literatur pendukung
└── hardware/     → Desain rangkaian emulator (akan datang)

```

---

## 🧰 Tools yang Digunakan

- 🧪 **LTSpice / NgSpice** – simulasi I-V & analisis waktu
- 🐍 **Python** – model matematis (ODE) dan plotting
- 🧠 **Jupyter Notebook** – visualisasi interaktif
- 🔩 *(Planned)*: Op-amp, resistor variabel, MOSFET, PCB
- 🔧 *(Planned)*: FPGA/CPLD (mis. iCE40), CH341A

---

## 🤝 Kontribusi

Semua ide, feedback, dan kontribusi sangat disambut, terutama dalam bidang:

- Model numerik memristor
- DIY hardware & sirkuit emulator
- FPGA simulation of passive analog behavior
- Neuromorphic computing

Silakan buka [issue](https://github.com/Bluefox192/memristor/issues) atau kirim pull request!

---

## ⚠️ Etika & Tujuan

Proyek ini ditujukan untuk edukasi, eksplorasi ilmiah terbuka, dan sebagai jembatan menuju riset neuromorfik berbasis hardware.

> Semua eksperimen dilakukan dengan tanggung jawab & dokumentasi penuh.

---

## 📚 Referensi

- Strukov, D. B., et al. *The Missing Memristor Found*. Nature 453, 80–83 (2008).  
- Biolek, Z., et al. *SPICE Model of Memristor with Nonlinear Dopant Drift*. Radioengineering (2009).  
- Yakopcic, C., et al. *Memristor Device Modeling and Circuit Design for Read and Write Operations*. IEEE Trans. on Computers (2013).  
- Chua, L. *Memristor—The Missing Circuit Element*. IEEE Trans. Circuit Theory (1971).  
- Pershin, Y. V. & Di Ventra, M. *Memory Effects in Complex Materials and Nanoscale Systems*. Advances in Physics (2011).

---

## 📄 Lisensi

Lisensi: [MIT License](LICENSE)  
© 2025 [Bluefox192](https://github.com/Bluefox192)

---

> *"Not all circuits remember. But some do."*  
> — Eksplorasi memristor bukan hanya tentang komponen, tapi tentang **memori fisik** dari dunia nyata.

---
