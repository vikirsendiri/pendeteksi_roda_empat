# pendeteksi roda empat
# 🚗 QuadraVision Dataset

![YOLO](https://img.shields.io/badge/YOLO-v11-red)
![Dataset](https://img.shields.io/badge/Dataset-Vehicle%20Detection-green)
![Runtime](https://img.shields.io/badge/Runtime-Python%20%7C%20ONNX-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

**QuadraVision Dataset** adalah proyek dataset computer vision yang berfokus pada deteksi kendaraan roda empat menggunakan teknologi YOLO modern. Dataset ini dirancang untuk kebutuhan pelatihan model AI pada sistem transportasi cerdas, smart city, monitoring lalu lintas, hingga implementasi edge AI real-time.

💡 **Catatan:** Dataset ini dibuat untuk mendukung pengembangan model object detection berkinerja tinggi dengan akurasi optimal pada berbagai kondisi lingkungan dan kamera.

---

# ✨ Fitur Utama

### 🚘 Multi-Class Vehicle Dataset

Dataset mencakup berbagai kategori kendaraan roda empat seperti:

* Sedan
* SUV
* Hatchback
* Pickup
* Truck
* Bus
* Van

---

### 📷 Variasi Data yang Luas

Dataset dilatih menggunakan gambar dari berbagai kondisi:

* Siang & malam
* Hujan & berkabut
* Jalan raya & perkotaan
* CCTV & dashcam
* Sudut kamera berbeda

---

### ⚡ Optimized for Real-Time AI

Dataset dioptimalkan untuk model lightweight seperti:

* YOLO11n
* YOLOv8n
* YOLOv5n

cocok untuk:

* Edge Computing
* Smart Traffic System
* Vehicle Counting
* Smart Parking
* CCTV Analytics

---

### 🧠 Annotation Presisi Tinggi

Semua gambar telah melalui proses:

* Bounding Box Labeling
* Data Cleaning
* Data Validation
* Augmentasi Dataset

untuk memastikan kualitas pelatihan model tetap optimal.

---

# 🧠 Arsitektur Model

Proyek ini menggunakan arsitektur **YOLO11 Nano (YOLO11n)** karena memiliki:

* Inferensi cepat
* Konsumsi memori rendah
* Akurasi tinggi
* Cocok untuk perangkat edge

---

# 📊 Dataset

Dataset dikembangkan menggunakan kombinasi:

* Roboflow
* Open Images Dataset
* Custom Vehicle Images

🔗 **Lihat Dataset:**
[https://roboflow.com](https://roboflow.com)

---

# 🚀 Pipeline Training

Proses training dilakukan menggunakan:

* Google Colab
* Ultralytics YOLO
* Roboflow API

Pipeline meliputi:

1. Dataset Import
2. Data Augmentation
3. Training YOLO
4. Evaluasi
5. Export ONNX

---

# 📈 Metrik Evaluasi

| Metric    | Score  |
| --------- | ------ |
| Precision | 0.9001 |
| Recall    | 0.8267 |
| mAP50     | 0.8666 |
| F1-Score  | 0.8618 |

---

# 🛠️ Struktur Proyek

```bash
QuadraVision-Dataset/
│
├── dataset/
│   ├── train/
│   ├── valid/
│   └── test/
│
├── models/
│   └── best.onnx
│
├── notebooks/
│   └── training.ipynb
│
├── app/
│   ├── index.html
│   ├── app.js
│   └── style.css
│
├── README.md
└── requirements.txt
```

---

# ⚙️ Teknologi yang Digunakan

* YOLO11n
* Python
* OpenCV
* ONNX Runtime
* Roboflow
* Google Colab
* JavaScript
* HTML5 Canvas

---

# 🚀 Instalasi

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🚀 Training Model

```bash
yolo detect train data=data.yaml model=yolo11n.pt epochs=100 imgsz=640
```

---

# 🚀 Export Model ke ONNX

```bash
yolo export model=best.pt format=onnx
```

---

# 🌐 Deployment

Proyek dapat di-deploy menggunakan:

* GitHub Pages
* Netlify
* Vercel

Karena seluruh sistem berbasis aset statis dan ONNX Runtime.

---

# 📸 Use Case

✅ Smart Traffic Monitoring
✅ Vehicle Detection System
✅ AI CCTV Analytics
✅ Smart Parking System
✅ Vehicle Counting
✅ Smart City Infrastructure

---

# 👨‍💻 Penulis

## vira kania indri rifka
github : https://vikirsendiri.github.io/pendeteksi_roda_empat/

**AI Engineer | Computer Vision Enthusiast**

Dibangun dengan ☕, Python, dan GPU gratis dari Google Colab 🚀

---

# 📄 Lisensi

MIT License © 2026

---

# ⭐ Dukungan

Jika proyek ini membantu Anda:

⭐ Beri Star repository ini
🍴 Fork untuk pengembangan lebih lanjut
📢 Bagikan ke komunitas AI lainnya
