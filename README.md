# Movie-Recommendation-System-with-Collaborative-Filtering
Movie Recommendation System with Collaborative Filtering

## Collaborative Filtering
Pemfilteran kolaboratif berbasis item adalah algoritma pemfilteran kolaboratif (CF) yang melihat ke dalam set item yang telah dinilai oleh pengguna target dan menghitung seberapa mirip mereka dengan target dan kemudian memilih k item yang paling mirip untuk di rekomendasi kan.

Prediksi dihitung dengan mengambil rata-rata tertimbang pada peringkat pengguna target pada item yang paling mirip. Kesamaan antara item i dan j dihitung dengan mengisolasi pengguna yang telah menilai mereka dan kemudian menerapkan teknik perhitungan kesamaan. Persamaan di bawah ini menunjukkan kesamaan berbasis korelasi menggunakan korelasi pearson-r.


## Himpunan data
Dataset yang digunakan di sini adalah dari https://movielens.org. Dataset ini memiliki lebih dari 100k peringkat pengguna untuk lebih dari 1600 film. Dataset ini berisi dua file u.data yang berisi user_id, movie_id dan peringkat, file u.item berisi judul film untuk id film yang sesuai. Paket Pandas dapat digunakan untuk membaca dan data dari kedua file dan menggabungkan jika perlu.
