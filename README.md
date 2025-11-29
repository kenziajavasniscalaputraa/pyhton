🐍 Python — Introduction & Basic Usage






Repository ini berisi penjelasan dasar tentang Python, cara instalasi, contoh kode, dan struktur project. Cocok untuk pemula yang ingin memulai belajar Python maupun dokumentasi project kecil.

📌 Apa itu Python?

Python adalah bahasa pemrograman tingkat tinggi yang terkenal karena:

Sintaks yang sederhana dan mudah dipelajari

Memiliki banyak library powerful

Cocok untuk pembuatan aplikasi, web development, automasi, AI, data science, dan lainnya

Didukung oleh komunitas besar di seluruh dunia

📦 Instalasi Python
1. Unduh Python

Kunjungi:
https://www.python.org/downloads/

2. Centang opsi berikut saat instalasi:

✔ Add Python to PATH
✔ Install launcher

3. Cek instalasi
python --version

🚀 Menjalankan Program Python
Menjalankan file .py
python main.py

Masuk ke mode interaktif (REPL)
python

📁 Struktur Folder Project (Contoh)
python-project/
│── main.py
│── requirements.txt
└── README.md

✨ Contoh Kode Dasar Python
Hello World
print("Hello, World!")

Variabel & Tipe Data
nama = "Kenji"
umur = 17
is_student = True

print(nama, umur, is_student)

Fungsi
def tambah(a, b):
    return a + b

print(tambah(2, 5))

Looping
for i in range(5):
    print(i)

Class
class Siswa:
    def __init__(self, nama, kelas):
        self.nama = nama
        self.kelas = kelas

    def info(self):
        print(f"{self.nama} dari kelas {self.kelas}")

s = Siswa("Kenji", "X RPL 7")
s.info()

🧪 Virtual Environment (Disarankan)
Membuat environment
python -m venv venv

Aktifkan

Windows:

venv\Scripts\activate


Mac/Linux:

source venv/bin/activate

📦 Menginstall Library
pip install numpy


Simpan daftar library:

pip freeze > requirements.txt


Install ulang library:

pip install -r requirements.txt

🛠 Tools Umum di Python

pip — Package manager

venv — Virtual environment

pytest — Unit testing

Flask / Django — Web framework

Jupyter Notebook — Data science

📜 License

Repository ini menggunakan lisensi MIT — bebas digunakan dan dimodifikasi.

🤝 Kontribusi

Pull request diterima!
Silakan buat issue jika ada bug, saran, atau request fitur.

⭐ Jangan Lupa Star Repo Ini!

Kalau repo ini membantu, klik ⭐ untuk mendukung 🔥
