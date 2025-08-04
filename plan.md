# 🧠 MEMRISTOR RESEARCH & DIY PLAN

## 📌 Tujuan
Meneliti dan mengembangkan memristor dari dasar teori, simulasi SPICE, hingga tahap eksperimental dan potensi realisasi chip dalam bentuk DIY/maker lab.

## 📅 Roadmap Umum

### 1. 🧠 Pemahaman Teori
- [✓] Studi paper seminal *Leon Chua 1971* & *HP Labs 2008*
- [✓] Pelajari fisika semikonduktor: switching, hysteresis, dan resistive switching
- [ ] Bandingkan memristor dengan Flash, NAND, dan ReRAM
- [ ] Pelajari jenis-jenis memristor: TiO₂-based, ECM, VCM, ferroelectric

### 2. 🧪 Simulasi (SPICE / Python / Verilog-A)
- [ ] Simulasi switching model TiO₂ (linear + nonlinear drift)
- [ ] Simulasi behavior hysteresis (Python: `mu_v`, `Ron`, `Roff`, dll)
- [ ] Simulasi SPICE untuk rangkaian neuromorfik sederhana
- [ ] Visualisasi interaktif (Jupyter + `ipywidgets`)
- [ ] Benchmark terhadap SRAM/NAND dari segi latency, power, retention

### 3. 🔧 Eksperimen & DIY Lab
- [ ] Rancang eksperimen resistive switching (TiO₂, Ag₂S, atau CuO)
- [ ] Buat thin film secara manual: drop-casting / spin coating / sol-gel
- [ ] DIY photolithography (mask, UV exposure, etching)
- [ ] Karakterisasi: multimeter, SMU (Source Measure Unit), oscilloscope
- [ ] Gunakan PCB/FPC untuk koneksi antar elektroda

### 4. 🧬 Reproduksi Lab Sederhana (referensi: Sam Zeloof)
- [ ] Bangun mini clean box (HEPA filter + chamber)
- [ ] Rancang sputtering/evaporator skala kecil (magnetron atau resistive heating)
- [ ] Buat mask alignment DIY (menggunakan kamera + laser pointer)
- [ ] Gunakan FPGA/MCU untuk stimulus sinyal switching

### 5. 🧠 AI & Neuromorphic Target
- [ ] Simulasi jaringan saraf dengan memristor sebagai sinaps
- [ ] Benchmark inference di edge device (drone / robot)
- [ ] Evaluasi arsitektur komputasi in-memory
- [ ] Coba integrasi dengan FPGA untuk sistem hybrid

### 6. 🚀 Finalisasi & Rilis
- [ ] Rancang board memristor tester open-source
- [ ] Publish makalah atau jurnal mandiri
- [ ] Dokumentasi lengkap di GitHub: schematic, PCB, simulasi
- [ ] Video edukasi / vlog eksperimen

---

## 🧰 Tools dan Stack yang Digunakan

| Tool           | Keterangan                        |
|----------------|-----------------------------------|
| Python         | Simulasi & plotting               |
| Ngspice/Xyce   | Simulasi sirkuit SPICE            |
| KiCad          | PCB design & layout               |
| GHDL/Verilog   | Jika ingin integrasi dengan FPGA  |
| Jupyter        | Visualisasi interaktif            |
| GitHub Actions | CI & tracking tugas otomatis      |

---

## ⏳ CI/Automation
Untuk tracking harian dan otomatisasi task, file `tasks.yml` akan digunakan. Notifikasi bisa diberikan melalui terminal (CLI) lokal via GitHub CLI + crontab atau `act`.

---

## ✅ Contoh Tugas Harian (Tasks.yaml)

```yaml
- task: Baca paper HP Labs 2008
  status: todo
- task: Simulasi nonlinear drift (Python)
  status: in-progress
- task: Uji switching TiO₂
  status: todo
