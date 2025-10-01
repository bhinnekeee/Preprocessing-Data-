**KONTEKS** 

Proyek ini dibuat untuk membantu merapikan data mahasiswa sebelum digunakan dalam analisis dan _machine learning_. Data mentah biasanya masih berantakan, ada yang kosong, _doubel_, atau formatnya beda-beda, sehingga kalau langsung dipakai bisa bikin hasil analisis jadi gak akurat. Karena itu, _preprocessing_ jadi langkah awal yang penting supaya data lebih rapi dan siap diolah.

**PROBLEM STATEMENT**

Masalah utama yang dihadapi adalah kualitas data yang kurang baik. Kalau ada nilai kosong, hasil analisis bisa bias. Kalau ada data ganda, perhitungan bisa melenceng. Sementara format yang tidak seragam bikin algoritma sulit membaca data dengan benar. Hal-hal kecil ini bisa berdampak besar pada performa model.

**TUJUAN**

Tujuan dari proyek diantaranya: membersihkan dan menyiapkan _dataset_ supaya konsisten dan siap dipakai. Caranya dengan ngecek kondisi data, ngapus duplikat, isi atau tangani data yang hilang, normalisasi teks biar seragam, _encoding_ variabel kategorik, sampai _scaling_ angka biar proporsional. Hasilnya diharapkan jadi data yang lebih “sehat” buat dianalisis.

**DATASET**

_Dataset_ yang dipakai berisi informasi akademik mahasiswa dengan beberapa variabel penting. Semua proses dikerjakan pakai _Python_ dengan bantuan pustaka favorit: _Pandas_ buat olah data, _NumPy_ buat operasi numerik, _Scikit-learn_ buat _encoding_ & _scaling_, _plus Matplotlib_ dan _Seaborn_ buat visualisasi.

**HASIL** 

Setelah melalui _preprocessing_, dataset berhasil dibersihkan dari duplikasi dan nilai kosong, format teks diseragamkan, variabel kategorik di _encoding_, dan skala numerik dinormalisasi. Hasil akhirnya adalah data yang lebih bersih, terstruktur, serta siap digunakan dalam berbagai algoritma _machine learning_. Data ini dapat diaplikasikan pada metode klasifikasi seperti _Decision Tree_ dan _AdaBoost_, maupun _clustering_ seperti K-_Means_ dan _Fuzzy C-Means_, untuk menghasilkan analisis yang lebih akurat.

**KESIMPULAN**

Tahap _preprocessing_ terbukti menjadi bagian krusial dalam siklus analisis data. Dengan data yang lebih bersih dan konsisten, model _machine learning_ yang dibangun akan memiliki performa yang lebih baik, serta hasil analisis yang lebih valid. Hal ini menunjukkan bahwa kualitas data merupakan pondasi utama dalam penelitian berbasis data.

**REKOMENDASI**

Agar hasil analisis tetap relevan dan _up-to-date_, disarankan untuk memperbarui _dataset_ secara berkala, terutama ketika ada data mahasiswa baru yang masuk. Selain itu, menambahkan variabel tambahan yang lebih kaya, seperti data sosial atau perilaku digital, juga dapat meningkatkan kedalaman analisis. Integrasi _preprocessing_ otomatis dengan _pipeline machine learning_ juga direkomendasikan untuk efisiensi dan replikasi penelitian di masa mendatang.
