## Readme: Sistem Pengenalan Wajah dengan Python

**Sistem ini menggunakan pengenalan wajah untuk keperluan login pengguna.**

**Teknologi yang digunakan:**

* OpenCV
* dlib
* Python

**Persyaratan:**

* Python 3.x terinstal
* Pustaka tambahan: `glob`, `tkinter`, `cv2`, `os`, `numpy`, `PIL`, `pandas`, `datetime`, `time`, `dlib`, dan `scipy.spatial.distance` (dapat diinstal menggunakan `pip install <nama_pustaka>`)
* File `haarcascade_frontalface_default.xml` (dapat diunduh dari [https://github.com/opencv/opencv/blob/4.x/data/haarcascades/haarcascade_frontalface_default.xml](https://github.com/opencv/opencv/blob/4.x/data/haarcascades/haarcascade_frontalface_default.xml))

**Penggunaan:**

1. Salin kode Python ke dalam file bernama `facial_recognition.py`.
2. Pastikan semua pustaka terinstal dan file `haarcascade_frontalface_default.xml` berada di direktori yang sama dengan file Python.
3. Jalankan kode menggunakan interpreter Python (misalnya: `python facial_recognition.py`).

**Fungsi Utama:**

* **Registrasi:** Pengguna dapat mendaftarkan wajah mereka dengan memasukkan ID dan nama, lalu klik tombol "Ambil Gambar". Sistem akan mengambil beberapa gambar wajah untuk melatih model pengenalan wajah.
* **Login:** Pengguna dapat login menggunakan pengenalan wajah. Masukkan password untuk memulai proses pengenalan. Sistem akan mendeteksi wajah pada kamera dan mencoba mengenalinya berdasarkan model yang telah dilatih. Jika wajah dikenali, pengguna akan berhasil login.

**Antarmuka Pengguna (GUI):**

Sistem menggunakan pustaka `tkinter` untuk membuat antarmuka pengguna yang terdiri dari:

* Kotak teks untuk memasukkan ID dan nama
* Tombol untuk mengambil gambar, registrasi, login, dan fungsi lainnya

**Catatan:**

* Kode ini merupakan contoh dasar dari sistem pengenalan wajah. 
* Untuk keamanan yang lebih baik, disarankan menggunakan mekanisme hashing password yang lebih aman.
* Pengembangan lebih lanjut dapat dilakukan untuk menambah fitur seperti manajemen pengguna dan penanganan error.
