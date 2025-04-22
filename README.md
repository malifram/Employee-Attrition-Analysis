# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech

## Business Understanding

Jaya Jaya Maju merupakan salah satu perusahaan multinasional yang telah berdiri sejak tahun 2000. Ia memiliki lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri. 

Walaupun telah menjadi menjadi perusahaan yang cukup besar, Jaya Jaya Maju masih cukup kesulitan dalam mengelola karyawan. Hal ini berimbas tingginya attrition rate (rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan) hingga lebih dari 10%.

### Permasalahan Bisnis

Berdasarkan latar belakang diatas, Permasalahan Bisnis yang dapat disimpulkan antara lain:
1. Sulit mengidentifikasi dan mengelola kriteria setiap karyawan.
2. Tingginya rasio jumlah karyawan yang keluar mencapai lebih dari 10%.

### Cakupan Proyek

Beberapa cakupan proyek yang akan dikerjakan sebagai berikut:
1. Membuat dashboard yang dapat mengidentifikasi kriteria karyawan dari berbagai macam aspek.
2. Menganalisis penyebab karyawan memilih untuk mengundurkan diri (attrition).

### Persiapan

Sumber data: https://github.com/dicodingacademy/dicoding_dataset/blob/main/employee/employee_data.csv

Setup environment:

1. Membuat environment baru dengan nama hr-problem

```
conda create --name hr-problem python
```

2. Mengaktifkan environment yang telah dibuat

```
conda activate hr-problem
```

3. _Install_ semua library yang dibutuhkan

```
pip install -r requirements.txt
```

4. Jalankan jupyter notebook

```
jupyter-notebook .
```

5. Buat folder baru yang akan menampung proyek ini dan beri nama **human_resource_project**

6. Unggah dataset yang akan digunakan

7. Buat _notebook.ipynb_ baru dan mulai melaksanakan proyek pada _notebook_ tersebut.

## Business Dashboard

Dashboard yang dibuat menggunakan Aplikasi Tableau Public. Link untuk melihat dashboard: https://public.tableau.com/app/profile/muhamad.alif.ramadhan/viz/AttritionAnalysis_17449124618950/Dashboard

Dashboard tersebut dikembangkan dengan tujuan untuk memudahkan menyelesaikan Permasalahan departemen Human Resources (HR) dalam analisa kriteria karyawan yang melakukan pengunduran diri. Agar dapat memudahkan dalam membaca dashboard, terdapat 2 warna berbeda yakni Biru (NO) untuk karyawan yang mengundurkan diri dan Hijau (Yes) untuk karyawan yang tidak melakukan pengunduran diri.

## Conclusion
Hasil yang diperoleh setelah dilakukan analisis dapat disimpulkan sebagai berikut:
1. Dari jenis kelamin baik laki-laki maupun perempuan yang mengundurkan diri tidak jauh berdeda yaitu 5 - 8%. Begitu juga dari 3 status perkawinan yaitu 4 - 7 %, dan melakukan pengunduran diri terbanyak ada pada status Single/lajang (7%).
2. Karyawan berdasarkan 3 Department secara keseluruhan yang melakukan pengunduran diri terbanyak ada pada Department Research & Development sebesar 8.37%. Juga dapat dilihat pada Job Role yang mengundurkan diri teratas ada pada Laboratory Technician (57 Karyawan), kemudian disusul Research Scientist (46 Karyawan) dan Sales Executive (40 Karyawan).
3. Dari sisi Business Travel, semakin jarang karyawan yang melakukan perjalanan bisnis, semakin besar peluang karyawan untuk mengundurkan diri.
4. Dari segi kepuasan karyawan (Job Satisfaction & Relationship Satisfaction) yang melakukan pengunduran diri selalu dibawah rata-rata karyawan yang tidak melakukan pengunduran diri. Faktor karyawan yang mengundurkan diri memang sudah tidak puas dari segi pekerjaan, relasi maupun lingkungan.
5. Karyawan berdasarkan segmen yang melakukan pengunduran diri terbanyak ada pada kategori Entry-Level (5.9%) dan Mid-Level (4.7%). Kedua segmen ini memiliki kesamaan pada tahun peran pekerjaan saat ini dan lama tahun di perusahaan selama 0-5 tahun.
6. Dari segi Work Life Balance, karyawan yang mengundurkan diri ada pada kategori Excellent (7.2%) tetapi juga banyak karyawan yang menetap pada perusahaan (53.5%).
7. Karyawan yang melakukan lembur lebih banyak mengundurkan diri dari pada karyawan yang tidak lembur dengan presentase sebesar 7%.
8. Dari segi pendidikan, karyawan yang mengundurkan diri tertinggi ada pada tingkat lulusan Sarjana/Bachelor sebesar 6.2% dan dari segi bidang pendidikan adalah Life Sciences (5.1%), Medical (3.7%) dan Marketing (2%).
9. Dari sisi performa, tidak terdapat perbedaan yang signifikan antara karyawan yang mengundurkan diri dan yang tetap bekerja. Dengan kata lain, kedua kategori nilai performa karyawan tersebut relatif sama.
10. Dilihat dari segi rata-rata tahunan, karyawan yang tidak mengundurkan diri memiliki masa kerja yang lebih lama di semua aspek dibandingkan dengan karyawan yang mengundurkan diri. Menunjukkan bahwa lamanya masa kerja berkorelasi dengan keputusan karyawan untuk tetap bertahan di perusahaan.

### Rekomendasi Action Items (Optional)

Berikan beberapa rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka.

- action item 1
- action item 2
