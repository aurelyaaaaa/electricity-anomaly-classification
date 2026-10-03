# Electricity Anomaly Classification

## PBL - Electricity Anomaly Classification using EfficientNet

Project ini merupakan implementasi Deep Learning untuk melakukan klasifikasi kondisi listrik menjadi dua kelas, yaitu **Anomaly** dan **Normal**.

## Dataset

Dataset yang digunakan terdiri dari:

- Total data: 1000 gambar
- Training: 800 gambar
- Validation: 200 gambar
- Kelas: Anomaly dan Normal

## Model

Model menggunakan **EfficientNet** sebagai feature extractor dengan classification layer.

Input image:
- 224 × 224 × 3

Optimizer:
- Adam

Loss:
- Binary Crossentropy

Epoch:
- 5

## Hasil Evaluasi

Hasil evaluasi pada validation set:

| Metric | Hasil |
|---|---:|
| Accuracy | 100% |
| Precision | 100% |
| Recall | 100% |
| F1-Score | 100% |

Confusion Matrix:

```text
[[101   0]
 [  0  99]]
