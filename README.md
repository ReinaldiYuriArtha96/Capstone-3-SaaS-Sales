# Analisis Penjualan SaaS – Capstone 3

## Tentang Bisnis
Proyek ini menganalisis kinerja penjualan dari sebuah perusahaan SaaS (Software as a Service) B2B yang menawarkan berbagai produk perangkat lunak kepada beragam segmen pelanggan. 
---

## Deskripsi Proyek  
Proyek ini bertujuan untuk melakukan analisa mendalam terhadap data penjualan SaaS untuk mengeksplorasi perilaku pelanggan, profitabilitas produk, serta efektivitas diskon. Tujuannya adalah memberikan strategi berbasis data untuk meningkatkan revenue, retensi, dan efisiensi operasional.

---
## Tujuan Analisis
Analisis ini bertujuan untuk menghasilkan wawasan yang mendalam untuk mendukung keputusan bisnis berbasis data, dengan fokus pada:
-	Mengidentifikasi segmen pelanggan bernilai tinggi melalui RFM dan Customer Lifetime Value (CLV)
-	Mengevaluasi efisiensi dan margin keuntungan dari masing-masing produk
-	Mengkaji dampak dari strategi diskon terhadap penjualan dan profitabilitas
-	Menganalisis tren musiman dan harian untuk optimasi waktu promosi
-	Menemukan outlier yang mempengaruhi distribusi penjualan dan profit
-	Mengukur tingkat churn untuk masing-masing segmen pelanggan

---
## Urgensi Proyek

### Margin Tipis Meskipun Revenue Tinggi
- Banyak produk dengan volume penjualan tinggi namun margin keuntungan sangat rendah atau bahkan negatif. Ini mengindikasikan perlunya analisis strategis terhadap struktur harga dan diskon.
### Ketergantungan pada Diskon
- Diskon besar sering kali digunakan untuk mendorong penjualan, namun berdampak langsung pada profitabilitas. 
### Segmen Pelanggan Belum Dimaksimalkan
- Segmentasi pelanggan seperti SMB memiliki potensi revenue jangka panjang besar, namun belum dioptimalkan dari sisi efisiensi dan loyalitas.
### Produk Potensial Terabaikan
- Beberapa produk dengan margin tinggi justru memiliki volume penjualan rendah.
### Pentingnya Data dalam Pengambilan Keputusan
- Perusahaan SaaS perlu pendekatan yang berbasis data untuk merancang strategi promosi, retensi pelanggan, dan pengembangan produk

---

## Stakeholder yang Terlibat

| Tim / Fungsi           | Manfaat Insight                                                                                |
|------------------------|-----------------------------------------------------------------------------------------------|
| Sales                  | Strategy segmentasi pelanggan dan peluang upsell berdasarkan data revenue dan margin               |
| Marketing              | Persona pelanggan dan data churn untuk kampanye yang lebih efektif per segmen                 |
| Finance                | Pemahaman margin dan profit driver untuk mendukung penetapan harga yang sesuai dengan nilai pelanggan|
| Product                | Guideline pengembangan fitur dan tier produk dari perilaku pengguna                            |
| Customer Success       | Strategi onboarding dan re-engagement untuk menurunkan churn di segmen bernilai tinggi         |

---

## Ringkasan Dataset  

- **Ukuran:** 9.994 baris data dengan lebih dari 40 fitur  
- **Sumber Data:** Transaksi penjualan, profil pelanggan, dan detil produk  
- **Cakupan Analisis:** Segmentasi pelanggan, CLV, diskon dan margin produk, tren musiman, dan outlier  
- **Catatan Khusus:** Terdapat data outlier baik pendapatan tinggi maupun transaksi rugi yang akan dibahas secara mendetail

---

## Temuan Utama dan Analisis  

- **Segmentasi Pelanggan:** Segmen SMB menyumbang lebih dari 50% total revenue, namun mencatat margin profit terendah. Sebaliknya, segmen Enterprise menunjukkan efisiensi profitabilitas tertinggi per pelanggan
- **RFM dan CLV analysis:** Skor Recency dan Frequency pelanggan umumnya tinggi, sejalan dengan Customer Lifetime Value (CLV) yang mencapai hingga $36K. Mayoritas pelanggan termasuk dalam segmen Loyal dan Others, menandakan potensi retensi jangka panjang
- **Efisiensi Produk:** Produk seperti ContactMatcher dan FinanceHub memiliki volume penjualan tinggi namun margin negatif. Sebaliknya, produk Alchemy dan Data Smasher menunjukkan margin tinggi meski volume rendah, ini membuka peluang untuk strategi promosi yang lebih agresif.
- **Profit Margin & Diskon:** Diskon di atas 30% secara konsisten dikaitkan dengan margin negatif dan volatilitas profit yang tinggi. Diskon di bawah 10% merupakan zona aman, menjaga profitabilitas tanpa mengorbankan volume penjualan secara signifikan
- **Tren Waktu:** Penjualan memuncak pada bulan Oktober hingga Desember, serta hari Kamis, khususnya pada awal dan akhir tahun. Namun, profit cenderung stagnan sejak 2021, mengindikasikan potensi inefisiensi biaya atau penurunan margin
- **Outlier:** Terdapat lebih dari 100 transaksi bernilai di atas $10.000 yang menaikkan rata-rata revenue. Terdapat data diskon ekstrem (50–70%) menjadi kontributor utama kerugian. 
- **Churn per Segment:** Tingkat churn rata-rata hanya sekitar 3%, mencerminkan strategi retensi yang efektif. Namun, segmen Strategic mencatat churn tertinggi (3,5%), menimbulkan kekhawatiran mengingat nilai pelanggan yang tinggi. Segmen SMB memiliki churn terendah dan paling stabil.

---

## Rekomendasi Strategis  

1. Batasi Diskon Maksimal 20%. Untuk menjaga stabilitas margin, tetapkan batas diskon maksimum pada 20%. Pantau ketat diskon ekstrem di atas 30%, terutama pada produk yang menunjukkan profit negatif.
2. Tingkatkan Cross-Selling dan Bundling Produk Margin Tinggi. Fokus pada strategi cross-sell dan bundling untuk produk dengan margin tinggi seperti Alchemy dan Data Smasher, guna meningkatkan profitabilitas tanpa perlu volume tinggi.
3. Perkuat Retensi di Segmen Strategic. Implementasikan program onboarding yang proaktif dan value realization yang terukur untuk segmen Strategic, yang memiliki CLV tinggi namun churn relatif lebih besar.
4. Optimalkan Promosi Berdasarkan Pola Musiman. Sinkronkan kampanye promosi dengan periode penjualan tertinggi di bulan Oktober hingga Desember dan hari Kamis, namun hindari ketergantungan pada diskon besar untuk menjaga margin. 
5. Kelola Risiko dan Peluang Outlier. Identifikasi dan pantau transaksi outlier dengan nilai tinggi (> $10K) maupun kerugian besar, guna mengelola risiko dan mengungkap peluang targeted upselling.
6. Optimalkan Strategi untuk Pelanggan SMB. Kurangi ketergantungan pada diskon besar di segmen SMB, dan arahkan pelanggan ke produk premium serta layanan otomatisasi untuk mendorong peningkatan margin dan efisiensi. 

---

## Tools dan Teknologi
- **Python**: Untuk data wrangling, analisis, dan visualisasi
- **Jupyter Notebook**: Dokumentasi dan eksplorasi interaktif
- **Pandas, NumPy**: Manipulasi dan analisis data
- **Seaborn, Plotly, Matplotlib**: Visualisasi eksploratif dan interaktif
- **Scikit-Learn**: Segmentasi pelanggan dan analisis prediktif
- **Looker Studio**: Dashboard visual untuk stakeholder
- **Figma Slides**: Presentasi hasil temuan

---
## Cara Penggunaan `.ipynb`

1. **Siapkan Python**  
   Pastikan Python 3.10 atau lebih baru sudah terinstal.

2. **Install dependensi**  
   Jalankan perintah berikut di terminal:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly scikit-learn
3. **Buka notebook analisis**  
Gunakan Jupyter Notebook, Google Colab, atau VSCode untuk membuka:
- Capstone 3 Final 01082025.ipynb
4. **Ikuti alur analisis berikut**
- Praproses dan eksplorasi data
- Segmentasi pelanggan (RFM dan CLV)
- Evaluasi diskon, margin, dan profit
- Analisis churn dan outlier
- Insight dan rekomendasi


---

## Link Presentasi

[Capstone 3 –Enhancing SaaS Revenue through Data Driven Sales and Customer Analytics (Figma Slides)](https://www.figma.com/deck/YhycFILOuPeEm7JfbzrglG/Capstone-3?node-id=3-118&t=KGkFBTanc0tgrxAW-1)

---

## Link Looker

[Capstone 3 –Enhancing SaaS Revenue through Data Driven Sales and Customer Analytics (Google Looker Studio)](https://lookerstudio.google.com/reporting/c582073a-22dd-4d03-a820-edfcb5c507aa)

---

