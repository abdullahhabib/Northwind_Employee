# Northwind_Employee
Project Module 2 DS-JCVL

Pada project ini, akan dilakukan analisa pada sebuah database dengan tujuan sebagai untuk dapat menjawab pertanyaan berikut:
1. Faktor apa dari employee yang berpengaruh terhadap total profit perusahaan?
2. Apa yang harus dilakukan ke employee agar profit perusahaan meningkat?


RINGKASAN ISI DATABASE DAN HARAPAN OUTPUT DARI ANALISIS

NORTHWIND_DATABASE merupakan database dari sebuah perusahaan yang bergerak dalam bidang F&B (food and beverage). Database ini berisi hampir semua data operasional perusahaan, meliputi informasi mengenai detail pekerja, penjualan, pelanggan, supplier, sampai dengan partner jasa ekspedisi.

Untuk mengoptimalkan kinerja pekerja dalam penjualan produk, perusahaan ingin mengambil insight dari database yang mereka miliki.


INFORMASI DATABASE
sumber database: https://drive.google.com/drive/folders/1fTHrwh_gcLsOFKXHnUzUGEu_APxLoD9i

Database memiliki total 13 tabel yang terhubung baik secara langsung ataupun tidak langsung. Berikut adalah ulasan singkat mengenai isi tabel-tabel tersebut:
1. Employees            : Berisi data mengenai detail pekerja.
2. EmployeeTerritories  : Berisi data mengenai cakupan wilayah kerja setiap pekerja.
3. Territories          : Berisi data mengenai deskripsi wilayah kerja.
4. Region               : Berisi data mengenai deksripsi region dari setiap wilayah kerja.
5. Orders               : Berisi data mengenai informasi umum order, seperti ID order, ID customer, ID employee, tanggal order, tanggal penggiriman, jasa ekspedisi, alamat pengiriman, dsb.
6. Shippers             : Berisi data mengenai detail dari jasa ekspedisi yang dipilih di tabel Orders.
7. OrderDetails         : Berisi data dari orderan customer mengenai ID produk, harga satuan, qty, serta diskon jika ada.
8. Products             : Berisi data mengenai produk yang di order, seperti nama produk, kategori, supplier, stok, harga satuan, dsb.
9. Categories           : Berisi data mengenai deskripsi dari kategori produk.
10. Supplier            : Berisi data mengenai detail supplier.
11. Customers           : Berisi data mengenai detail pelanggan.
12. CustomerCustomerDemo: - (tidak ada data tersedia)
13. CustomerDemographic : - (tidak ada data tersedia)

