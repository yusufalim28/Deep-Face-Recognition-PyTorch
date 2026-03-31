# Face Recognition System - Computer Vision Task

Repository ini berisi implementasi sistem pengenalan wajah (Face Recognition) menggunakan model FaceNet dengan arsitektur MTCNN untuk deteksi wajah dan InceptionResnetV1 untuk ekstraksi fitur (embeddings).

## 🚀 Fitur Utama
- **Face Detection:** Menggunakan MTCNN untuk mendeteksi lokasi wajah secara presisi.
- **Face Embedding:** Menggunakan InceptionResnetV1 (pretrained on VGGFace2).
- **Matching System:** Perhitungan kemiripan wajah menggunakan **Cosine Similarity**.
- **Integrated with Google Colab:** Script sudah dioptimasi untuk berjalan di lingkungan Colab.

## 🛠️ Teknologi yang Digunakan
- Python 3.x
- PyTorch
- Facenet-PyTorch
- OpenCV (cv2)
- NumPy & Matplotlib

## 📂 Struktur Dataset
Program membaca dataset dari Google Drive dengan struktur folder sebagai berikut:
dataset/ ├── person_1/ │ ├── img1.jpg │ └── img2.jpg ├── person_2/ │ ├── img1.jpg ...


## 📝 Cara Menjalankan
1. Clone repositori ini.
2. Buka file `.ipynb` di Google Colab.
3. Pastikan Anda memiliki folder dataset di Drive dengan struktur yang sesuai.
4. Jalankan sel secara berurutan.

## 👥 Anggota Kelompok
- yusuf alim romadon
- Najwa Rafa Fauziah
- Revi Injani
- Dicky Dermawan
- Syahril Nadzif Ramadhan
