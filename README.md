# Capstonemodule2

## SaaS Sales Analysis Dashboard (Tableau)

Proyek ini bertujuan untuk menganalisis data penjualan sebuah perusahaan SaaS (Software as a Service) menggunakan Tableau. Visualisasi interaktif dibuat untuk membantu memahami tren penjualan, profitabilitas, efektivitas diskon, dan kontribusi pelanggan serta produk terhadap total profit.

---

## Dataset
Dataset yang digunakan adalah *Cleaned SaaS Sales Data* yang berisi informasi seperti:
- Order ID, Order Date
- Customer & Country
- Product & Segment
- Sales, Profit, Discount
- Industry & Region

---

## Dashboard & Analisis

### 1. **Trend Penjualan & Profit Tahunan**
- Menunjukkan tren pertumbuhan dari tahun ke tahun.
- Tahun dengan penjualan dan profit tertinggi di-highlight.

### 2. **Distribusi Profit per Region**
- Menggunakan peta geografis untuk menunjukkan performa tiap negara.
- Warna menunjukkan tingkat profit (positif/negatif).
- Insight: Beberapa negara seperti Jepang dan Rusia memiliki profit negatif.

### 3. **Pengaruh Discount terhadap Profit**
- Scatter plot antara diskon dan profit menunjukkan bahwa:
  - Diskon besar tidak selalu menjamin profit tinggi.
  - Ada titik di mana diskon terlalu besar → menyebabkan kerugian.

### 4. **Kontribusi Produk**
- Pie chart menampilkan proporsi produk terhadap total profit.
- Insight: Produk A dan B memiliki kontribusi terbesar.

### 5. **Top & Bottom Customers**
- Menampilkan pelanggan dengan profit tertinggi dan terendah.
- Membantu strategi retensi dan efisiensi marketing.

### 6. **Frekuensi Pembelian per Customer**
- Histogram pembelian berdasarkan jumlah order.
- Sebagian besar customer hanya melakukan pembelian 1-2 kali.

### 7. **Profit Margin per Segment**
- Melihat efisiensi tiap segmen.
- Segment "Enterprise" memiliki margin yang lebih baik dibandingkan "Small Business".

### 8. **Total Discount**
- Calculated field digunakan untuk mengakumulasi seluruh nilai diskon.
- Insight: Marketing Suite memberikan diskon besar namun tetap rugi → strategi harus dievaluasi.

---

## 🛠 Tools & Teknologi
- **Tableau Public**
- **GitHub** untuk dokumentasi & versioning

---

## Insight Utama
- Beberapa region dengan profit negatif sebaiknya jadi prioritas evaluasi.
- Diskon besar ≠ profit besar.
- Segmentasi pelanggan dan produk bisa jadi kunci peningkatan efisiensi.

---

## Author
Kelvin Setyadi  
Capstone Project Module 2 — Data Science Bootcamp  
