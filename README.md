Disclaimer: 
1. This program was created solely for personal learning purposes.

2. This program is written in the Python programming language and is created in Indonesian Language. The available ReadMe file is also written in Indonesian

3. This project was created for the purpose of gaining a better understanding of Southampton Football Club during the 2024/2025 season.

4. It is not intended to offend, criticize, or disparage any individual, organization, or related parties in any way.

5. All questions or discussions can be submitted via [x.com](https://x.com/ssatrioo), [Instagram](https://www.instagram.com/satriobp_/), or email: satriobagusp.8@gmail.com


# Southampton Defense Analysis 2024/25

## Deskripsi
Notebook ini berisi analisis performa **defensif Southampton** pada musim **Premier League 2024/25**. Analisis dilakukan menggunakan Python (pandas, matplotlib, seaborn) dengan fokus pada data **defensive metrics** seperti tackles, interceptions, blocks, dan errors.  

## Tujuan Analisis
- Mengevaluasi kekuatan dan kelemahan Southampton dalam aspek pertahanan.  
- Membandingkan performa pemain Southampton dengan tim-tim lain di Premier League.  
- Memberikan insight terkait pola permainan defensif (misalnya tackling success, shot-blocking, dan kesalahan yang berujung peluang lawan).  

## Struktur Notebook
1. **Import Library**  
   Digunakan untuk memanggil library utama (pandas, seaborn, matplotlib, numpy).  

2. **Load Dataset**  
   Membaca data mentah (CSV/Excel) yang berisi statistik pertahanan pemain. Dataset disediakan pada repository, dan syntax koding bisa diganti ke tempat anda menyimpan file dataset di lokal komputer anda.

3. **Data Cleaning**  
   - Handling missing values  
   - Konversi tipe data (misalnya date → datetime)  
   - Normalisasi kolom  

4. **Exploratory Data Analysis (EDA)**  
   - Distribusi tackles, blocks, interceptions  
   - Boxplot perbandingan antar tim  
   - Line chart pergerakan posisi klasemen  
   - Analisis distribusi (KDE, histogram)  

5. **Visualisasi**  
   - **Boxplot** perbandingan Tkl_Percentage antar tim  
   - **Grouped Bar Chart** untuk error count & defensive contribution  
   - **Line Chart** pergerakan klasemen per matchday  

6. **Insight & Kesimpulan**  
   Menyajikan interpretasi hasil analisis terkait kekuatan dan kelemahan Southampton di lini belakang.  

## Contoh Visualisasi
- Boxplot distribusi **Tkl_Percentage** antar tim  
- Distribusi kesalahan pemain Southampton (Errors)  
- Perbandingan **Blocks (Total, Shots, Passes)** antar tim  

## Cara Menjalankan
1. Clone repository / unduh notebook  
2. Install requirements:  
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Buka notebook di JupyterLab / VS Code / Google Colab  
4. Jalankan sel secara berurutan  

## Dataset
1. Data dari kaggle: [Football Matches 2024/25 — Dataset](https://www.kaggle.com/datasets/tarekmasryo/football-matches-20242025-top-5-leagues) Berisi data dari 6 Liga top Eropa yang nantinya akan bisa dipisahkan menjadi data Premier League Untuk melihat kiprah Southampton
2. Data hasil scrapping website: [Fbref.com](https://fbref.com/en/comps/9/2024-2025/2024-2025-Premier-League-Stats) difokuskan untuk statistik pemain di Premier League musim 2024/2025.

## Catatan
1. Analisis ini hanya fokus pada **Southampton** dan perbandingan dengan beberapa tim Premier League lain. Hasil insight dapat dijadikan bahan evaluasi performa tim di musim 2024/25.
2. Hasil insight juga sudah dibuat dalam bentuk artikel dan bisa dibaca di [medium.com](https://medium.com/@SatrioPrabowo/premier-league-24-25-musim-berat-untuk-southampton-yang-berujung-degradasi-ab3ac4a720cf)
