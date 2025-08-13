# Panduan Instalasi JDK & Alice 3 (Beginner Friendly)

Panduan ini membantu kamu menginstall **JDK** dan **Alice 3** versi terbaru dengan cara yang sederhana.

---

## 1. Pilih Versi JDK yang Cocok
- **Rekomendasi:** Gunakan **JDK 21 (LTS)** atau **JDK 24**.
- Tersedia untuk **Windows**, **macOS**, dan **Linux**.
- Alice 3 versi terbaru (**3.9.0.2**, rilis Juni 2025) sudah kompatibel dengan Java modern.  
  Jadi, **JDK 21** sudah lebih dari cukup.

---

## 2. Unduh JDK dari Sumber Resmi
- Buka situs resmi Oracle: [https://www.oracle.com/java/technologies/downloads/](https://www.oracle.com/java/technologies/downloads/)
- Pilih installer sesuai OS kamu:
  - **Windows**: `jdk-24_windows-x64_bin.exe`
  - **macOS**: `jdk-24_macos-x64_bin.dmg`
  - **Linux**: `jdk-24_linux-x64_bin.tar.gz`
- **Jangan** unduh dari situs tidak resmi, supaya aman dan dapat versi terbaru.

---

## 3. Instal dan Atur Variabel Lingkungan (Environment Variables)
1. Jalankan installer → klik **Next** → **Install** → **Finish**.  
   Pastikan kamu punya **hak administrator**.
2. Setelah instalasi:
   - **JAVA_HOME** → arahkan ke folder instalasi JDK  
     Contoh: `C:\Program Files\Java\jdk-21`
   - Tambahkan `...\jdk-21\bin` ke **PATH**  
     Agar perintah `java` dan `javac` bisa digunakan di Terminal atau Command Prompt.

---

## 4. Verifikasi Pemasangan
Buka **Terminal** atau **Command Prompt**, lalu ketik:

```bash
java -version
javac -version
```

Jika berhasil, akan muncul versi sesuai yang kamu instal.

---

## 5. Pasang Alice 3
- Unduh Alice 3 versi terbaru di: [https://www.alice.org/get-alice/alice-3/](https://www.alice.org/get-alice/alice-3/)
- Pilih versi **3.9.0.2 (Juni 2025)** sesuai OS kamu.
- Install seperti biasa.
- Setelah JDK terpasang, Alice 3 akan otomatis menggunakan JDK tersebut untuk menjalankan:
  - **Animasi 3D**
  - **Fitur pemrograman Java**

---

✅ **Selesai!**  
Sekarang kamu siap membuat animasi 3D dan belajar pemrograman Java di Alice 3.
