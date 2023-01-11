## Project UAS Bahasa Pemrograman Semester 1

Nama: Siti Yasmin Nurcholifah

Nim: 312210057

Kelas: TI.22.C1

## Program Data Mahasiswa Menggunakan Python

## Deskripsi

File ini berfungsi untuk menginport modul-modul yang dibuat.

Contoh pengimportan modul:

# mengimport class view dari modul view_nilai di dalam folder view
from view.view_nilai import view
# mengimport class daftar dari modul daftar_nilai di dalam folder daftar
from model.daftar_nilai import daftar

## Mode/_data.py

Modul ini berfungsi sebagai penampung data dari modul - modul yang di buat.

## model/ _init.py & view/ _init.py

Modul ini di isi dengan method Init dan berfungsi sebagai method yang pertama kali di jalankan atau di proses sebelum method-method yang lainnya dan method _init() berguna untuk melakukan inisialisasi pembuatan object dari class.

contoh pembuatan method _init()

def init(self, nama, nim): self._nama = nama self._alamat = nim

## view/input_nilai.py

Modul ini di isi class inputdata dan di isi dengan method inputan - inputan untuk modul - modul lainnya dan di inisialisasi dari method __init.

contoh pembuatan input:

self._nama = input('Masukan Nama : ')
self._nim = input('Masukan Nim : ')

## view/input_nilai.py

Modul ini di berisi method cetak data mengimport dari modul model/_data.py

contoh import dan cetak data:

mengimport class data dari modul _data di dalam folder model

from model._data import data

## mencetak hasil inputan yang di tampung di class data

print("| {0:15} | {1:9} |".format(self.nama, self

## model/daftar_nilai.py

Modul ini di isi dengan class yang berisi method - method :

-tambah_data() yang mengimport modul inputan dari input_nilai dan di masukan ke modul data

-ubah_data() yang mengimport modul inputan dari input_nilai dan menggunakan pengkondisian jika inputan di dalam modul data lalu memasukan inputan baru dari modul input_nilai ke dalam modul data

-hapus_data() yang mengimport modul inputan dari input_nilai dan menggunakan pengkondisian jika inputan di dalam modul data lalu menghapus data di dalam modul data yang sesuai dengan modul inputan dari input_nilai.

-cari_data() yang mengimport modul inputan dari input_nilai dan mencetak data dari modul view_nilai yang sesuai dengan inputan dari modul input_nilai contoh program:

def tambah_data(self):

# modul input_nilai

# memasukan input_nilai ke modul data

def ubah_data(self):

# modul input_nilai

# pengkondisian jika modul input_nilai di dalam modul data

# memasukan modul input_nilai baru ke dalam modul data

def hapus_data(self):

# modul input_nilai

# pengkondisian jika modul input_nilai di dalam modul data

# hapus data yang sesuai modul input_nilai

def cari_data(self):

# modul input_nilai

# pengkondisian jika modul input_nilai di dalam modul data

# modul view

Hasil Running Program

![gambar1](https://user-images.githubusercontent.com/115986870/211769376-f86cf960-be58-477c-9b29-872a6027354e.png)
png)


![gambar2](https://user-images.githubusercontent.com/115986870/211769478-682e134e-d4c4-474a-8502-83400c919633.png)


![gambar3](https://user-images.githubusercontent.com/115986870/211769542-dd1ef1a3-50ad-4b19-b4df-297b0cee666f.png)
