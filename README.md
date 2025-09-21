# Posttest-PBO-3
### Rizky Yunia 
### 2409116089

### Penjelasan Package
<img width="466" height="329" alt="image" src="https://github.com/user-attachments/assets/02b1a037-37e3-4786-8a7a-e476e62d479e" />
Dalam program ini terdapat beberapa class dengan fungsi masing-masing. class BusanaService berperan sebagai superclass yang menyimpan atribut dasar berupa id, nama, dan harga sewa, lengkap dengan constructor, getter, dan setter untuk menerapkan konsep encapsulation. class ini juga memiliki method toString yang nantinya dioverride oleh subclass. selanjutnya, terdapat class BusanaTradisional dan BusanaModern yang menjadi subclass dari BusanaService. keduanya menambahkan atribut khusus yaitu kategori dan melakukan overriding pada method tostring agar menampilkan informasi tambahan sesuai jenis Busana. kemudian, class BusanaTradional berfungsi sebagai pengelola data busana dengan menerapkan operasi CRUD, yaitu menambah, menampilkan, memperbarui, menghapus, dan mencari jenis busana. semua data sewa busana disimpan dalam sebuah arrayList sehingga bisa menampung berbagai objek dari jenis busana, baik induk maupun turunannya. terakhir, class mainApp bertugas sebagai titik masuk (entry point) program yang menampilkan menu interaktif untuk customer. Dari menu ini, customer bisa menambah jenis baju di Tradisional dan modern, melihat daftar busana, menghapus, memperbarui, maupun mencari berdasarkan id.

# Encapsulation
<img width="1072" height="656" alt="image" src="https://github.com/user-attachments/assets/15c55b6a-dc80-4b2b-8ad5-5b3247897c97" />

# Inheritance
inheritance digunakan pada class BusanaTradisional dan BusanaModern yang mewarisi atribut serta method dari class BusanaService dengan menggunakan keyword extends. hal ini memudahkan kode agar tidak perlu menulis ulang atribut dasar.
<img width="1145" height="595" alt="image" src="https://github.com/user-attachments/assets/a8df585d-99dc-4968-89cd-24349c4e321c" />
<img width="1063" height="628" alt="image" src="https://github.com/user-attachments/assets/dc40459e-25d3-4a13-9762-c832d9fbe4df" />

# CRUD
class Service mengelola daftar jadwal dengan ArrayList. operasi CRUD yang tersedia meliputi tambah, lihat, update, hapus, dan cari berdasarkan id.
<img width="1044" height="681" alt="image" src="https://github.com/user-attachments/assets/3dc0b418-45f5-4f48-a2e5-e3633f7e7dc2" />
<img width="1078" height="414" alt="image" src="https://github.com/user-attachments/assets/660936e5-140e-4c5a-82c8-6b1b751d2071" />

# MainApp
<img width="1047" height="682" alt="image" src="https://github.com/user-attachments/assets/239799d3-1b2f-4494-acc5-e2cdcf8f2654" />
<img width="1148" height="351" alt="image" src="https://github.com/user-attachments/assets/1bbeb350-ee34-478d-bc40-9078fe62445a" />

# Output
saat dijalankan, program menampilkan menu dan memungkinkan customer untuk menambahkan kategori baju tradisional atau modern. data dapat dilihat, dihapus, diperbarui, serta dicari sesuai input id.
<img width="717" height="448" alt="image" src="https://github.com/user-attachments/assets/b1db279d-cabe-4339-b5cb-7fc29e04f47d" />
<img width="668" height="452" alt="image" src="https://github.com/user-attachments/assets/7ab8951f-5347-4375-8624-937feb4cfb62" />

