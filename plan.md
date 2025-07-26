# Memristor DIY Project Plan 🚀

🧠 *"Bukan sekadar meniru industri, tapi menciptakan jalur baru dari garasi kita sendiri."*

## 🎯 Visi

Membangun pemahaman mendalam dan eksperimen nyata terkait memristor dari skala makro hingga potensial integrasi ke sistem cerdas dan embedded (AI, drone, robotik), dimulai dari pendekatan DIY dan eksplorasi terbuka.

---

## 📌 Tahapan Proyek

### ⚙️ 1. Pemahaman Teori dan Literatur
- [ ] Pelajari paper seminal HP Labs 2008: "The missing memristor found"
- [ ] Bandingkan teknologi memristor vs ReRAM, Flash, dan NVM lain
- [ ] Pelajari model matematis memristor (Strukturnya: TiO₂, Schottky Barrier, doped/undoped)
- [ ] Eksplorasi aplikasi: edge-AI, neuromorphic computing, programmable analog
- [ ] Kumpulkan jurnal dan review (taruh di `references.md`)

### 🔬 2. Simulasi dan Model
- [ ] Buat simulasi dasar I-V memristor dengan Python (Sudah ada dasar)
- [ ] Tambahkan slider interaktif (misal resistivitas, tegangan input)
- [ ] Coba simulasikan logic gate berbasis memristor
- [ ] Buat model jaringan memristor (untuk CNN mini misalnya)

### 🧪 3. Eksperimen Fisik Skala Makro
- [ ] Rancang skema rangkaian sederhana (misal dengan TiO₂ paste)
- [ ] Buat prototipe dengan plat kaca, elektrode Al/Cu, dan larutan TiO₂
- [ ] Uji IV curve menggunakan oscilloscope / ADC + Python plotting
- [ ] Cek histeresis dan memory effect

### 🛠️ 4. Persiapan DIY Lab dan Tools
- [ ] Sederhanakan photolithography: LED UV, resin/bahan photoresist
- [ ] Coba mask printing (transparansi)
- [ ] Buat mini spin coater dari motor
- [ ] Mulai eksperimen sputtering/evaporasi sederhana
- [ ] Amankan ventilasi dan APD!

### 🧭 5. Rencana Jangka Menengah
- [ ] Kembangkan PCB dengan footprint untuk memristor (pakai socket dulu)
- [ ] Buat rangkaian ADC-memristor-MCU atau FPGA kecil
- [ ] Rancang logic gate / array memristor untuk inference ringan (AI kecil)
- [ ] Bandingkan dengan LUT di FPGA — tunjukkan keunggulan hybrid analog

---

## 🧭 Arah Besar

> Bila berhasil, proyek ini membuka jalan untuk:
- Platform open-hardware AI edge dengan memristor sebagai core
- Simulasi & eksperimen untuk riset neuromorphic computing dari rumah
- Potensi start-up berbasis *green nano-device* dan low-power AI
- Pengetahuan praktikal: dari photolithography, sputtering, hingga devkit IoT

---

## 🧑‍💻 Kontak dan Update
- Blog: [`https://github.com/Bluefox192/memristor`](https://github.com/Bluefox192/memristor)
- Kontak: via Issues/Discussions GitHub
- [ ] Rencana buat demo video: *IV hysteresis curve from homemade memristor*

---

## 📚 Referensi Utama (juga ada di `references.md`)
- Strukov, Dmitri B., et al. *"The missing memristor found."* Nature 2008.
- Yang, J. J., et al. *"Memristive switching mechanism for metal/oxide/metal nanodevices."* Nature Nano 2008.
- IEEE ReRAM tutorial (2023)
