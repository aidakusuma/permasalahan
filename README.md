# Proyek Akhir: Menyelesaikan Permasalahan

## Business Understanding

Latar Belakang Bisnis: Jaya Jaya Maju adalah perusahaan multinasional yang telah berdiri sejak tahun 2000 dan memiliki lebih dari 1000 karyawan yang tersebar di seluruh negeri. Meskipun telah berkembang pesat, perusahaan menghadapi masalah signifikan terkait dengan manajemen sumber daya manusia, khususnya tingkat attrition (tingkat pergantian karyawan) yang tinggi, mencapai lebih dari 10%. Hal ini berdampak pada produktivitas, biaya rekrutmen yang tinggi, dan retensi talenta yang baik. Oleh karena itu, perusahaan ingin mengidentifikasi faktor-faktor yang mempengaruhi attrition rate ini dan mencari solusi untuk mengurangi tingkat attrition.


### Permasalahan Bisnis

- Tingginya Attrition Rate: Perusahaan menghadapi tingginya tingkat keluar masuk karyawan, yang dapat memengaruhi kelangsungan dan produktivitas jangka panjang.
Kesulitan dalam Mengidentifikasi Faktor Penyebab Attrition: Manajer HR kesulitan untuk mengidentifikasi faktor-faktor yang secara signifikan mempengaruhi keputusan karyawan untuk bertahan atau keluar dari perusahaan.
- Keputusan HR yang Berdasarkan Persepsi: Tanpa data yang jelas, keputusan terkait retensi dan kebijakan SDM cenderung didasarkan pada asumsi atau persepsi, bukannya analisis data yang mendalam.
- Kurangnya Alat Pemantauan Kinerja Sumber Daya Manusia: Perusahaan tidak memiliki sistem yang efektif untuk memantau dan menganalisis faktor-faktor karyawan yang berpotensi meningkatkan attrition rate.

### Cakupan Proyek

- Analisis Data Karyawan: Mengidentifikasi faktor-faktor yang berhubungan dengan attrition, seperti usia, jabatan, lama bekerja, pendidikan, gaji, kepuasan kerja, dan lokasi.
Pembuatan Model Prediksi Attrition: Mengembangkan model machine learning untuk memprediksi karyawan yang berisiko tinggi untuk keluar (churn), berdasarkan data historis.
- Business Dashboard: Membuat dashboard untuk memvisualisasikan metrik terkait karyawan, termasuk prediksi churn, tingkat kepuasan, durasi kerja, dan faktor-faktor yang mempengaruhi keputusan untuk bertahan atau keluar.
- Rekomendasi Kebijakan SDM: Berdasarkan analisis dan hasil model prediksi, memberikan rekomendasi strategis untuk mengurangi attrition rate dan meningkatkan retensi karyawan.


### Persiapan

Data karyawan yang mencakup informasi seperti usia, jenis kelamin, status perkawinan, lama bekerja, gaji, jabatan, tingkat pendidikan, lokasi kerja, dan faktor-faktor lain yang relevan. terdapat pada link berikut ini https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee

Setup environment:

1. Install pipenv
```
pip install pipenv
```

2. Create an environment 
```
pipenv install
```

3. Install dependencies
```
pipenv install -r requirements.txt
```

4. Running predict
```
Input the data of the examined employee in the data dictionary
```

```
python prediction.py
```

Tools yang Digunakan:
- Python: Untuk analisis data dan pengembangan model.
- Pandas, Numpy: Untuk manipulasi data dan analisis.
- Scikit-learn: Untuk membangun model machine learning (misalnya, Random Forest, Logistic Regression).
- Matplotlib, Seaborn: Untuk visualisasi data dan pemantauan.
- Tableau atau Power BI: Untuk membuat dashboard interaktif yang menyajikan metrik-metrik kunci terkait karyawan.

Data Pipeline:
- Mengimpor data karyawan, membersihkan dan mempersiapkan data untuk analisis lebih lanjut.
- Menyusun fitur-fitur yang relevan untuk model prediksi dan integrasi dengan dashboard.

## Business Dashboard
Dashboard bisa diakses pada link berikut: https://public.tableau.com/views/Dashboard_17334715041000/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Dashboard ini memantau faktor-faktor yang memengaruhi tingkat attrition di perusahaan Jaya Jaya Maju, dengan elemen berikut:
- Jumlah Karyawan: Total karyawan dan distribusi berdasarkan job role.
- Kepuasan Kerja: Rata-rata kepuasan terhadap lingkungan kerja, keseimbangan kerja, dan pekerjaan.
- Tingkat Attrition: Posisi dengan tingkat attrition tertinggi, seperti Laboratory Technician dan Sales Executive.
- Durasi Kerja: Rata-rata masa kerja berdasarkan job role untuk mengidentifikasi posisi dengan turnover cepat.

## Conclusion

Berdasarkan analisis data, didapat:
- Rata-rata Kepuasan Kerja dan Lingkungan:

Rata-rata kepuasan terhadap lingkungan kerja adalah 2.72, sedangkan rata-rata keseimbangan pekerjaan dan kehidupan (Work-Life Balance) sedikit lebih tinggi di angka 2.76, dan rata-rata kepuasan pekerjaan adalah 2.73.
Nilai ini menunjukkan tingkat kepuasan yang cenderung rendah. Kepuasan kerja yang rendah sering kali berkaitan dengan tinggi rendahnya motivasi dan keinginan untuk meninggalkan perusahaan.
- Rasio Attrition Berdasarkan Job Role:

Laboratory Technician menunjukkan tingkat attrition yang tertinggi, diikuti oleh Sales Executive dan Research Scientist. Peran-peran ini mungkin membutuhkan evaluasi lebih lanjut terkait tekanan kerja, insentif, atau faktor lingkungan yang menyebabkan karyawan di posisi ini lebih cenderung untuk keluar.
Posisi lain dengan attrition lebih rendah seperti Healthcare Representative dan Manager mungkin menunjukkan lebih banyak stabilitas dalam pekerjaan mereka.
- Rata-rata Lama Bekerja Berdasarkan Job Role:

Posisi Manager memiliki rata-rata lama bekerja yang cukup tinggi (14.43 tahun), yang mengindikasikan tingkat retensi yang lebih baik pada level manajerial.
Di sisi lain, posisi seperti Sales Representative dan Laboratory Technician memiliki rata-rata lama bekerja yang relatif rendah (2.92 dan 5.02 tahun), menunjukkan tingkat turnover yang lebih tinggi pada posisi-posisi ini.

### Rekomendasi Action Items (Optional)

Action Item 1:
Meningkatkan program retensi karyawan dengan memberikan lebih banyak perhatian pada faktor-faktor yang berkontribusi terhadap kepuasan kerja, seperti gaji, tunjangan, dan pengembangan karir.

Action Item 2:
Menerapkan kebijakan yang lebih fleksibel dan mendukung keseimbangan kehidupan kerja (work-life balance) untuk karyawan yang berisiko tinggi, terutama di departemen dengan tingkat attrition tertinggi.

Action Item 3:
Meningkatkan keterlibatan manajer dengan karyawan, mengadakan sesi one-on-one untuk memahami tantangan mereka, dan memberikan dukungan untuk kemajuan karir.

Dengan rekomendasi action items ini, diharapkan perusahaan dapat menurunkan tingkat attrition, meningkatkan kepuasan kerja, dan mempertahankan talenta terbaik untuk kesuksesan jangka panjang.
