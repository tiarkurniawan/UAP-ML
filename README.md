# UAP-ML

# Aplikasi Klasifikasi Gambar dengan Flask


## Gambaran Umum
Repositori ini memuat contoh implementasi sederhana model klasifikasi gambar dengan menggunakan Flask. Model ini telah dilatih menggunakan MobileNetV2 untuk mengelompokkan gambar ke dalam tiga kelas. Aplikasi web yang disediakan memungkinkan pengguna untuk mengunggah gambar dan menerima prediksi secara cepat.


## Struktur Proyek
|- static
|- templates
|- app.py
|- file.ipynb
|- model.h5
|- requirements.txt
|- README.md


## Dependensi
Pastikan untuk menginstal library yang dibutuhkan sebelum menjalankan aplikasi:
```bash
pip install flask tensorflow
```


## Pelatihan Model
Model pengklasifikasi gambar dilatih dengan menggunakan MobileNetV2 dan disimpan sebagai model.h5. Sesuaikan jumlah unit output pada lapisan terakhir dan pilih fungsi aktivasi yang sesuai dengan jumlah kelas.

![image](https://github.com/tiarkurniawan/UAP-ML/assets/108686908/46c55a86-3cea-42f7-ac94-a31b27c2d5db)


## Aplikasi Flask
Aplikasi web Flask yang terdapat dalam file app.py berperan sebagai antarmuka untuk model klasifikasi gambar. Aplikasi ini menggunakan model yang telah disimpan untuk melakukan prediksi terhadap gambar yang diunggah oleh pengguna.


## Cara Menjalankan
```bash
Copy code
python app.py
Buka browser dan akses
http://127.0.0.1:5000/.
Anda dapat mengunggah gambar dan mendapatkan prediksi.
```
Buka browser dan akses http://127.0.0.1:5000/. Anda dapat mengunggah gambar dan mendapatkan prediksi.

![Screenshot 2023-12-30 122021](https://github.com/tiarkurniawan/UAP-ML/assets/108686908/9b7ddf3c-3b12-420b-8598-c7e0d8fde76b)

