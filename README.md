# **Truth or Dare Filter**

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" alt="Python Logo" width="100" />
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" alt="Jupyter Lab Logo" width="100" />
  <img src="https://upload.wikimedia.org/wikipedia/commons/9/9a/Visual_Studio_Code_1.35_icon.svg" alt="VS Code Logo" width="100" />
</p>

---

## **Anggota Kelompok**
| **Nama**                 | **NIM**     |**ID GITHUB**                                     |
|--------------------------|-------------|--------------------------------------------------|
| Nasrul Alfin Prassetyo | 121140001 |<a href="https://github.com/JOKIPIN">@JOKIPIN</a> |
| Muhammad Faisal Safira | 121140139 |<a href="https://github.com/MFaisal00359">@MFaisal00359</a> |
| Muhamad Ivan Aulia     | 121140100 |<a href="https://github.com/ipanggeming">@ipanggeming</a> |

---

## **Deskripsi Proyek**
Proyek ini adalah filter multimedia berbasis gerakan kepala yang memungkinkan pengguna bermain "Truth or Dare." Filter ini mendeteksi gerakan kepala pengguna menggunakan kamera, lalu secara otomatis memilih "Truth" atau "Dare" berdasarkan arah kepala (kiri atau kanan). Fitur tambahan mencakup countdown timer, animasi, dan tampilan antarmuka yang menarik.

---

## **Teknologi yang Digunakan**
Berikut adalah teknologi dan alat yang digunakan dalam proyek ini:

| Logo                                                                                           | Nama Teknologi | Fungsi                                                                                                                                     |
|------------------------------------------------------------------------------------------------|----------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" alt="Python Logo" width="60"> | Python         | Bahasa pemrograman utama untuk pengembangan filter.                                                                                     |
| <img src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" alt="Jupyter Lab Logo" width="60">  | Jupyter Lab    | Lingkungan pengembangan untuk menjalankan dan menguji skrip Python.                                                                    |
| <img src="https://upload.wikimedia.org/wikipedia/commons/9/9a/Visual_Studio_Code_1.35_icon.svg" alt="VS Code Logo" width="60"> | VS Code        | Editor teks untuk mengedit skrip secara efisien dengan dukungan ekstensi Python.                                                       |

---

## **Library yang Digunakan**
Berikut adalah daftar library Python yang digunakan dalam proyek ini, beserta fungsinya:

| **Library**      | **Fungsi**                                                                                  |
|------------------|---------------------------------------------------------------------------------------------|
| `cv2`           | Digunakan untuk menangkap gambar dari kamera dan memproses gambar secara langsung.          |
| `mediapipe`      | Digunakan untuk mendeteksi landmark wajah, seperti posisi hidung, untuk mendeteksi gerakan kepala. |
| `random`         | Digunakan untuk memilih pertanyaan "Truth" atau tantangan "Dare" secara acak.              |
| `time`           | Digunakan untuk mengimplementasikan countdown timer untuk setiap sesi Truth atau Dare.      |
| `pygame`         | Digunakan menambahkan elemen audio, efek suara, atau meningkatkan antarmuka grafis, dan juga ada peran dalam logika filter |

---

## **Fitur**
### **1. Deteksi Gerakan Kepala**
- Filter ini mendeteksi arah gerakan kepala:  
  - **KIRI**: Memilih Truth.  
  - **KANAN**: Memilih Dare.  
  - **NETRAL**: Tidak ada teks yang ditampilkan.

### **2. Countdown Timer**
- Pengguna diberikan waktu untuk menjawab Truth atau menyelesaikan Dare sebelum filter kembali ke mode netral.

### **3. Antarmuka Filter**
- Tampilan mencakup:  
  - Informasi arah gerakan kepala untuk panduan pengguna.

### **4. Warna Gradient atau bakground Filter**
- Warna pada gradient dan antarmuka.  

---

## **Cara Menjalankan**
1. **Pastikan library berikut terinstal di Python Anda:**
   - OpenCV (`pip install opencv-python`)
   - Mediapipe (`pip install mediapipe`)
   - pygame (`pip install pygame`)
2. **Buka file proyek di Jupyter Lab atau VS Code.**
3. **Pastikan kamera eksternal atau internal sudah terhubung.**
4. **Jalankan program**
