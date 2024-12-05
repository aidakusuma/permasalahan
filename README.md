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

Data karyawan yang mencakup informasi seperti usia, jenis kelamin, status perkawinan, lama bekerja, gaji, jabatan, tingkat pendidikan, lokasi kerja, dan faktor-faktor lain yang relevan.

Setup environment:

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

Dashboard ini akan memberikan pemantauan langsung terhadap faktor-faktor yang mempengaruhi tingkat attrition dan metrik terkait lainnya. Beberapa elemen yang akan ditampilkan di dashboard termasuk:

- Prediksi Attrition: Menampilkan proporsi karyawan yang berisiko tinggi keluar berdasarkan hasil model prediksi.
- Kepuasan Kerja: Grafik yang menunjukkan tingkat kepuasan kerja karyawan berdasarkan survei atau feedback yang dikumpulkan.
- Durasi Kerja: Rata-rata masa kerja karyawan di perusahaan, dengan kategori berdasarkan usia, jabatan, atau divisi.
- Gaji dan Tunjangan: Visualisasi mengenai distribusi gaji dan tunjangan yang mungkin mempengaruhi kepuasan dan keputusan untuk bertahan.
- Analisis Departemen: Menampilkan departemen dengan tingkat attrition tertinggi dan karyawan yang berisiko tinggi.

## Conclusion

Proyek ini berhasil mengidentifikasi faktor-faktor yang mempengaruhi tingkat attrition di Jaya Jaya Maju, serta membangun model prediksi yang dapat membantu perusahaan untuk mengantisipasi karyawan yang berisiko keluar. Dengan menggunakan dashboard yang telah dikembangkan, manajer HR dapat memantau faktor-faktor yang memengaruhi karyawan dan mengambil langkah preventif yang lebih cepat. Hasil dari model ini memberikan wawasan yang lebih jelas tentang apa yang perlu diperbaiki untuk mengurangi tingkat attrition dan meningkatkan kepuasan serta retensi karyawan.

### Rekomendasi Action Items (Optional)

Action Item 1:
Meningkatkan program retensi karyawan dengan memberikan lebih banyak perhatian pada faktor-faktor yang berkontribusi terhadap kepuasan kerja, seperti gaji, tunjangan, dan pengembangan karir.

Action Item 2:
Menerapkan kebijakan yang lebih fleksibel dan mendukung keseimbangan kehidupan kerja (work-life balance) untuk karyawan yang berisiko tinggi, terutama di departemen dengan tingkat attrition tertinggi.

Action Item 3:
Melakukan pelatihan dan pengembangan kepemimpinan untuk manajer SDM dan lini depan guna meningkatkan komunikasi dengan karyawan dan menciptakan lingkungan kerja yang lebih inklusif dan mendukung.

Dengan rekomendasi action items ini, diharapkan perusahaan dapat menurunkan tingkat attrition, meningkatkan kepuasan kerja, dan mempertahankan talenta terbaik untuk kesuksesan jangka panjang.
