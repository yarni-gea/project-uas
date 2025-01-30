# project-uas

# nama : yarni gea

# nim : 312410413

# kelas : TI.24.A3

# struktur program

# 1. class data

menyinpan informasi tentang data buku

Atribut:

title: Judul buku

author: Pengarang buku

year: Tahun terbi

Metode:

          __init__(self, title, author, year): Konstruktor untuk inisialisasi atribut
          
# 2. Class View
   
Mengelola input/output dari pengguna:

Metode:

           dispalay_ menu(): menampilkan menu utama 

           geet_book_input(): meminta data buku dengan validasi

           display_book(books)(): menampilkan data buku dalam bentuk tabel
           
3. Class BookManager
   
Mengelola daftar buku:

atribut:

        books: daftar buku yang disimpna 
        
metode:

        add_book(title, author, year):menambahkan buku ke daftar 

        get_all_books(): mengembalikan semua data buku yang di simpan 
        
# 4. Class Main

atribut:

          manager: Objek dari class BookManager.

          view: Objek dari class View.
          
metode:

        run(): Menjalankan program dalam loop hingga pengguna keluar.
        
Validasi Input:

Judul Buku: Tidak boleh kosong.

Pengarang Buku: Tidak boleh kosong.

Tahun Terbit: Harus berupa bilangan bulat positif.

# Cara Menjalankan

# 1.simpan file dangan nama book_maneger.py.

# 2.Jalankan program di terminal/command prompt

          python book_manager.py.
          
# Contoh Penggunaan

# menambahkan buku


![image](https://github.com/user-attachments/assets/2fd24222-1d86-4921-a15a-e05fd6ee9aa0)

# menampilkan data buku

![image](https://github.com/user-attachments/assets/1c8bed64-f685-4f07-a2fc-9b14bc936cb9)

# Mengakhiri Program

![image](https://github.com/user-attachments/assets/95dd7fab-ab0a-46a2-bb56-5730148e92f6)



