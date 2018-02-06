##Use Case Diagram

![](https://i.imgur.com/NKOhoxD.png)

###Keterangan :

1.	Registrasi
	
	**Description**
	
	User sebagai penjual atau pembeli mengisi data yang diperlukan sehingga bisa di masukkan kedalam sistem untuk proses transaksi jual beli 

	**Normal Flow**

	1.	User membuka halaman depan web mobile atau dekstop
	2.	User mengisi data-data yang diperlukan untuk registrasi
	3.	User akan diminta verifikasi melalui email dan nomor telepon
	4.	Setelah selesai Akun user sudah tersimpan dalam server.
	


2.	Login/Logout
	
	**Description**

	User masuk ke dalam server sebagai penjual/pebeli sebagaimana yang telah anda pilih pada bagian registrasi

	**Normal Flow**

	1.	User membuka halaman depan web mobile atau dekstop
	2.	User memilih untuk login sebagai penjual atau pembeli
	3.	User memasukkan username dan password
	4.	Sistem akan memeriksa ketersediaan akun, apabila ada server akan memasukkan user ke halaman utama  (penjual) dan halaman utama toko anda (pembeli)
	
	**Alternative Flow**
	
	1.	User memasukkan username dan password yang salah
	2.	Muncul error message
	3.	User mengulang langkah normal flow ke 2

3.	Tambah/Edit/Hapus Produk

	**Description**

	User sebagai penjual mengisi produk di dalam toko online sesuai dengan keinginan user dan akan di catat dalam server

	**Pre Contidion**
	
	User login sebagai penjual

	**Normal Flow**
	
	1.	User memilih untuk membuat produk baru di tokonya
	2.	User mengisi detail dan foto produk
	3.	User mem - post produk yang ingin dijual
	4.	server membaca dan akan ditampilkan pada toko online user
	
	**Alternative Flow 1**
	1. User memilih untuk mengedit produk yang sudah di post
	2. User mengubah detail atau foto produk
	3. Kemudian lanjut ke Normal Flow bagian 3

	**Alternative Flow 2**
	1. User memilih untuk menghapus produk yang telah di post
	2. server akan menghapus produk di toko online user

4.	Transaksi
	
	**Description**

	Suatu aktivitas dimana penjual dan pembeli melakukan proses jual & beli, dimana penjual memgirim produk dan pembeli melakukan pembayaran.
	

	**Pre Contidion**

	User 1 sebagai penjual, dan user lainnya sebagai penjual.
	
	
	**Normal Flow**

	1. Pelanggan memilih produk
	2. Pelanggan melakukan pebayaran
	3. Penjual menerima notifikasi pemesanan
	4. Penjual mengirim barang sesuai dengan pesanan pembeli
	5. Sistem menyimpan riwayat transaksi dengan pengawasan staf



5. Evaluasi Produk
	
	**Description**

	Suatu aktivitas dimana staff dari e-commerce mengevaluasi kembali sebuah produk yang dikirim oleh penjual.
	

	**Pre Contidion**

	Staff yang bekerja di perusahaan tersebut.
	
	
	**Normal Flow**

	1. Penjual mengirim produk yang telah dibeli.
	2. Produk diterima oleh Staff dan di evaluasi kembali sebelum dikirimkan ke pembeli.
	3. Staff melakukan pengirim produk ke tujuan.
	4. Sistem menyimpan semua riwayat transaksi.
	


 