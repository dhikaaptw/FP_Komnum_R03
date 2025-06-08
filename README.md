# RO3_ProgramKomnum_20.py
## Kelompok R03 *Handhika Putra Widyartono (5053241039)*
•⁠  ⁠Nama Anggota:
  - Ledwino Galih Wandanu (5053241017)
  - Farrel Ahmad Lazuardi (5053241035)
  - Handhika Putra Widyartono (5053241039)
  - Ziyad Raziq Lahitidra Afey (5053241042)
  - M. Alfaraldi Raihan (5053241043)

## 🧮 Newton-Raphson Modifikasi (Python)

Program ini menyelesaikan akar persamaan nonlinear menggunakan Metode Newton-Raphson Modifikasi. Pendekatan ini digunakan untuk mencari akar dari fungsi:

	⁠f(x) = x³ + 6x² – 19x – 84

---

## 🧠 Metode Newton-Raphson Modifikasi

Metode ini merupakan pengembangan dari Newton-Raphson biasa, dengan mempertimbangkan turunan pertama dan kedua dari fungsi, agar iterasi lebih stabil dan cepat konvergen.

### Rumus yang digunakan:
xₙ₊₁ = xₙ - [f(xₙ) * f′(xₙ)] / [(f′(xₙ))² - f(xₙ) * f″(xₙ)]

---

## 📌 Informasi Input
•⁠  ⁠Fungsi: f(x) = x³ + 6x² – 19x – 84
•⁠  ⁠Turunan pertama: f'(x) = 3x² + 12x – 19
•⁠  ⁠Turunan kedua: f''(x) = 6x + 12
•⁠  ⁠Nilai awal (x₀): 1
•⁠  ⁠Nilai sebenarnya (x_true): 4
•⁠  ⁠Iterasi: Hingga ke-3

---

## ✅ Output yang Ditampilkan

| Iterasi |   xₙ    |  Et (%)  |  Ea (%)  |
|--------:|--------:|---------:|---------:|
|   1     |  2.5300 |  36.75   |   53.23  |
|   2     |  3.6701 |   8.25   |   30.91  |
|   3     |  4.0418 |   1.05   |    9.21  |

•⁠  ⁠Et (True Error): Selisih relatif terhadap nilai sebenarnya.
•⁠  ⁠Ea (Approximate Error): Galat relatif antar iterasi (akurasi lokal).

---

## 💡 Contoh Hasil Konsol

Iterasi | x_n | Et (%) | Ea (%)
1 | 2.5300 | 36.75 | 53.23
2 | 3.6701 | 8.25 | 30.91
3 | 4.0418 | 1.05 | 9.21
