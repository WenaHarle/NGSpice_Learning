### **Modul Pembelajaran Ngspice Dasar**

#### **1. Pengenalan Ngspice**
- 1.1 Apa itu Ngspice?
- 1.2 Keunggulan dan Fitur Utama
- 1.3 Perbedaan Ngspice vs. SPICE Lainnya
- 1.4 Aplikasi Ngspice dalam Rangkaian Elektronika

#### **2. Instalasi dan Persiapan**
- 2.1 Instalasi di Windows (MSYS2/Standalone)
- 2.2 Instalasi di Linux (Ubuntu/Debian)
- 2.3 Instalasi di macOS (Homebrew/MacPorts)
- 2.4 Verifikasi Instalasi (Tes Hello World)

#### **3. Dasar Simulasi Rangkaian**
- 3.1 Struktur File Input Ngspice (.cir/netlist)
- 3.2 Komponen Dasar (Resistor, Kapasitor, Induktor, Sumber)
- 3.3 Node dan Ground
- 3.4 Contoh Sederhana: Voltage Divider
- 3.5 Menjalankan Simulasi dari CLI

#### **4. Jenis Analisis Dasar**
- 4.1 Analisis DC (Titik Operasi)
- 4.2 Analisis Transien (Rangkaian RC/RL)
- 4.3 Analisis AC (Respons Frekuensi)
- 4.4 Contoh: Filter RC Low-Pass

#### **5. Kontrol Simulasi dan Output**
- 5.1 Perintah `.OP`, `.DC`, `.TRAN`, `.AC`
- 5.2 Menyimpan Hasil dengan `.PRINT` dan `.PLOT`
- 5.3 Troubleshooting Konvergensi Simulasi

#### **6. Komponen dan Model Lanjutan**
- 6.1 Dioda dan Transistor (Model SPICE)
- 6.2 Op-Amp dan Subcircuit
- 6.3 Parameter Sweep (`.STEP`)
- 6.4 Sumber Tegangan/Arus Terkontrol (VCCS, CCCS)

#### **7. Integrasi dengan Tools Lain**
- 7.1 Menggambar Netlist dengan gEDA/KiCad
- 7.2 Simulasi GUI dengan `ngspice-shared`
- 7.3 Analisis Data dengan Python (NumPy/Matplotlib)

#### **8. Troubleshooting Umum**
- 8.1 Error Sintaks Netlist
- 8.2 Masalah Konvergensi
- 8.3 Praktik Terbaik untuk Netlist yang Efisien

#### **9. Studi Kasus dan Proyek**
- 9.1 Rangkaian Penguat Sederhana (Common Emitter)
- 9.2 Rangkaian Osilator RC
- 9.3 Simulasi MOSFET Inverter
- 9.4 Proyek Akhir: Rangkaian Power Supply Sederhana

#### **10. Referensi dan Sumber Belajar**
- 10.1 Dokumentasi Resmi Ngspice
- 10.2 Forum dan Komunitas
- 10.3 Buku dan Tutorial Terkait

#### **Lampiran**
- A. Daftar Perintah Ngspice
- B. Tabel Model Komponen
- C. Contoh File Netlist Lengkap
- D. Glosarium Istilah
