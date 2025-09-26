# SeascooterController
# ⚡ Investigasi Eksperimental Injeksi Frekuensi Tinggi (HFI)  
### untuk Startup Motor PMSM Low Saliency pada Aplikasi Underwater Thruster 🌊⚙️

---

## 📖 Ringkasan
Repositori ini berisi **firmware dan dokumentasi eksperimen** mengenai penerapan  
**High-Frequency Injection (HFI)** untuk meningkatkan **performa startup sensorless**  
pada **Permanent Magnet Synchronous Motor (PMSM) low saliency**, khususnya  
untuk **underwater thruster**.  

🔹 Permasalahan: metode berbasis **back-EMF** tidak efektif di kecepatan rendah.  
🔹 Solusi: **HFI** mampu mendeteksi posisi rotor meskipun perbedaan saliency sangat kecil (**Ld ≈ Lq**).  

---

## ✨ Fitur Utama
- Implementasi **High-Frequency Signal Injection** pada firmware kontrol PMSM.  
- Dirancang untuk **surface-mounted PMSM low saliency**.  
- Optimisasi startup **underwater thruster** dengan beban dinamis.  
- Kode sumber + konfigurasi + dokumentasi eksperimen lengkap.  

---

## 🗂️ Struktur Repositori
todo


---

## ⚙️ Persyaratan
- **Mikrokontroler/Platform**: STM32 / VESC  
- **Compiler/IDE**: PlatformIO  
- **Motor**: PMSM low-saliency (surface-mounted, underwater thruster)  

---

## 🚀 Cara Penggunaan
1. Clone repositori:
   ```bash
   git clone https://github.com/nuxarch/SeascooterController
2. Buka proyek di platformIO VSCODE
3. Sesuaikan parameter motor di folder pin
4. Build & flash firmware ke board kontrol.
5. Lakukan pengujian eksperimen startup

Journal-Todo 
"Investigasi Eksperimental Injeksi Frekuensi Tinggi untuk Performa Startup pada Motor PMSM Low Saliency untuk Aplikasi Underwater Thruster", 2025.
