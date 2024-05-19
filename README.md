# Assignment-Part-1-2-Analyzing-wildfire-activities-in-Australia-Data-Visualization-With-Python
Tugas ini dibagi menjadi dua bagian. Bagian 1 akan memberi kamu kesempatan untuk menunjukkan keterampilan plot dan visualisasi kamu dan Bagian 2 tentang membuat dan menyesuaikan dashboard.

**Bagian 1: Menganalisis aktivitas kebakaran hutan di Australia**

**Bagian 2: Dashboard untuk menampilkan grafik berdasarkan Wilayah dan Tahun yang dipilih**

**Deskripsi Data**

Dataset kebakaran hutan ini berisi data tentang aktivitas kebakaran di Australia mulai dari tahun 2005. Informasi tambahan dapat ditemukan di sini.
Dataset ini mencakup variabel-variabel berikut:

**Region: 7 wilayah**

~~~Date: dalam UTC dan menyediakan data untuk 24 jam ke depan

~~~Estimated_fire_area: jumlah harian dari perkiraan area kebakaran untuk kebakaran vegetasi yang diperkirakan dengan tingkat kepercayaan > 75% untuk setiap wilayah dalam km²

~~~Mean_estimated_fire_brightness: rata-rata harian (berdasarkan piksel kebakaran yang ditandai (=jumlah)) dari kecerahan kebakaran yang diperkirakan untuk kebakaran vegetasi yang diperkirakan dengan tingkat 

~~~kepercayaan > 75% dalam Kelvin

~~~Mean_estimated_fire_radiative_power: rata-rata harian dari kekuatan radiasi yang diperkirakan untuk kebakaran vegetasi yang diperkirakan dengan tingkat kepercayaan > 75% untuk wilayah tertentu dalam megawatt

~~~Mean_confidence: rata-rata harian dari tingkat kepercayaan untuk kebakaran vegetasi yang diperkirakan dengan tingkat kepercayaan > 75%

~~~Std_confidence: deviasi standar dari kekuatan radiasi kebakaran yang diperkirakan dalam megawatt

~~~Var_confidence: Varians dari kekuatan radiasi kebakaran yang diperkirakan dalam megawatt

~~~Count: jumlah harian dari piksel untuk kebakaran vegetasi yang diperkirakan dengan tingkat kepercayaan lebih dari 75% untuk wilayah tertentu

~~~Replaced: Menunjukkan dengan "Y" apakah data telah diganti dengan data berkualitas standar ketika tersedia (biasanya dengan penundaan 2-3 bulan). Data yang diganti memiliki kualitas lokasi yang sedikit lebih tinggi.

**Bagian 1: Menganalisis aktivitas kebakaran hutan di Australia**

Tujuan:
Tujuan dari bagian Tugas Praktik ini adalah untuk menganalisis dan memvisualisasikan aktivitas kebakaran hutan di Australia menggunakan dataset yang disediakan. Kamu akan mengeksplorasi pola dan tren, dan membuat visualisasi untuk mendapatkan wawasan tentang perilaku kebakaran hutan di berbagai wilayah di Australia.

Dalam lab ini, kamu akan membuat visualisasi menggunakan Matplotlib, Seaborn, Pandas, dan Folium.

Tugas yang harus dilakukan:

~~~TASK 1.1: Memahami perubahan rata-rata perkiraan area kebakaran dari waktu ke waktu menggunakan pandas untuk membuat grafik garis.

~~~TASK 1.2: Membuat plot area kebakaran yang diperkirakan berdasarkan bulan.

~~~TASK 1.3: Menggunakan fungsi dari seaborn untuk mengembangkan barplot, untuk menemukan wawasan tentang distribusi rata-rata kecerahan kebakaran yang diperkirakan di seluruh wilayah.

~~~TASK 1.4: Mengembangkan pie chart dan menemukan bagian jumlah piksel untuk kebakaran vegetasi yang diperkirakan bervariasi di seluruh wilayah.

~~~TASK 1.5: Menyesuaikan plot pie sebelumnya untuk representasi visual yang lebih baik.

~~~TASK 1.6: Menggunakan Matplotlib untuk mengembangkan histogram dari rata-rata kecerahan kebakaran yang diperkirakan.

~~~TASK 1.7: Menggunakan fungsi dari seaborn dan menyertakan wilayah sebagai hue, untuk memahami distribusi kecerahan kebakaran yang diperkirakan di seluruh wilayah.

~~~TASK 1.8: Mengembangkan scatter plot untuk menemukan korelasi antara rata-rata kekuatan radiasi kebakaran yang diperkirakan dan tingkat kepercayaan rata-rata.

~~~TASK 1.9: Menandai semua tujuh wilayah yang terkena dampak kebakaran hutan, di Peta Australia menggunakan Folium.

**Bagian 2: Dashboard untuk menampilkan grafik berdasarkan Wilayah dan Tahun yang dipilih**

Tujuan:

Tujuan dari bagian tugas praktik ini adalah untuk membuat dashboard yang berisi plot dan grafik kamu.
Dalam lab ini, kamu akan membuat dashboard menggunakan Dash dan Plotly dan kemudian menambahkan interaksi pengguna ke dashboard kamu.
Kamu diharuskan membuat dashboard di mana pengguna dapat memilih Wilayah dan Tahun. Berdasarkan pilihan tersebut, dashboard akan menampilkan dua grafik berikut:


Pie Chart tentang Rata-rata Bulanan Perkiraan Area Kebakaran

Bar Chart tentang Rata-rata Bulanan Jumlah Piksel untuk Kebakaran Vegetasi yang Diperkirakan

Tugas yang harus dilakukan:


~~~TASK 2.1: Menambahkan judul ke dashboard.

~~~TASK 2.2: Menambahkan item radio dan dropdown tepat di bawah divisi dalam pertama.

~~~TASK 2.3: Menambahkan dua divisi kosong untuk output di dalam divisi dalam berikutnya.

~~~TASK 2.4: Menambahkan komponen Output dan input di dalam dekorator app.callback.

~~~TASK 2.5: Menambahkan fungsi callback.
