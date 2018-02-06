##Identifikasi Stakeholder
1. Penjual
2. Staff E-Commerce
3. Pelanggan

##Identifikasi Tujuan Proyek
1. Mempermudah kegiatan jual & beli
2. Membuat toko offline menjadi online

##Function Requirement
1. Menerima orderan pelanggan, menyimpan riwayat transaksi pembayaran, dan verifikasi ke pelanggan.
2. Memberikan pilihan pembayaran yang banyak.
3. Fitur tanya jawab di aplikasi, antara penjual dan pembeli.

setiap riwayat transaksi wajib menyertakan waktu, jumlah biaya, nama pelanggan, nama toko, dan detail product.

##Flow Proses Bisnis
1. Pelanggan melakukan pembelian di toko online.
2. Penjual menerima verifikasi pembayaran dan kemudian penjual mengirimkan barang.
3. Pelanggan menerima barang dan kemudian memverifikasi penerimaan.
4. Seluruh riwayat transaksi disimpan oleh sistem.

##Non- Functional Requirements
Aplikasi dapat dipakai dimana saja, dikapan saja, baik di mobile app, ataupun desktop.

##Design Solusi
###Needs

* Sistem login/logout penjual dan pembeli
* Tipe pembayaran variatif.
* Verifikasi penjual, staff dan pelanggan
* Sistem perantara transaksi.

###Features
* User management, berfungsi :
	* Register sebagai penjual atau pembeli
	* Fitur log in/out untuk melakukan transaksi ( ketika ingin membeli/menjual barang diharuskan log in ke dalam server )
 
* Pembayaran bisa dipilih melalui transfer atau COD via transfer ( pilihan yg tersedia tergantung kepada penjual )

* Sistem selalu memberikan verifikasi kepada penjual dan pembeli dibawah pengawasan staff
* Pihak E-commerce menjadi perantara antara penjual dan pembeli, dimana dana pembayaran dari pembeli disimpan terlebih dahulu oleh pihak e-commerce, dan akan dikirimkan kepenjual setelah pembeli menyatakan barang telah diterima.