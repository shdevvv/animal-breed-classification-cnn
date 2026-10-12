# Animal Breed Classification using CNN

Repositori ini berisi implementasi Convolutional Neural Network (CNN) dan Transfer Learning untuk klasifikasi ras hewan. Proyek ini berfokus pada evaluasi performa model melalui penyesuaian _Data Augmentation_, strategi _Fine-Tuning_, dan analisis arsitektur jaringan saraf tiruan (ResNet).

Proyek ini disusun sebagai bagian dari pemenuhan Tugas 05.

## 📌 Deskripsi Proyek

Proyek ini mengeksplorasi berbagai konsep fundamental dan lanjutan dalam Deep Learning untuk _Computer Vision_, meliputi:

- **Batch Normalization & Dropout**: Analisis efek stochastic noise dan mitigasi instabilitas pada _batch size_ kecil.
- **Residual Connections (ResNet)**: Mengatasi _vanishing gradient_ pada jaringan yang dalam menggunakan pemetaan identitas $H(x) = F(x) + x$.
- **Transfer Learning**: Perbandingan langsung antara pendekatan _Feature Extraction_ (membekukan _backbone_) dan _Fine-Tuning_.
- **Data Augmentation**: Penerapan augmentasi yang mempertahankan _semantic invariance_ pada data latih.
- **Mitigasi Catastrophic Forgetting**: Penggunaan _Differential Learning Rate_ dan _Linear Warmup_ saat melakukan pembaruan bobot.

## 📂 Struktur Repositori

- `Tugas05_NIM_StephanieHalim.ipynb`: Jupyter Notebook yang berisi seluruh kode implementasi (pelatihan, evaluasi, dan visualisasi).
- `Laporan_Analisis.pdf`: Laporan komprehensif yang berisi tabel konsolidasi, kurva pelatihan, dan analisis kegagalan (_failure analysis_).
- `metrics_log.json`: Log hasil mentah dari metrik pelatihan dan evaluasi model.
- `requirements.txt`: Daftar dependensi Python yang dibutuhkan untuk menjalankan proyek ini.

## ⚙️ Persyaratan Sistem

Pastikan Python 3.8+ telah terinstal di sistem Anda. Instal seluruh dependensi yang diperlukan dengan menjalankan perintah berikut:

```bash
pip install -r requirements.txt
```
