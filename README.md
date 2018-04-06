# MDC
Kasih nama database : makassardentalcare
Username database : root
Password database : 


Semua tabel dalam database :
<table>
- Barangs
	id : int
	kode : vc 191
	nama : vc 191
	lokasi : vc 191
	stok : int
	timestamp
	category_id : int
- Categories
	id : int
	nama : vc 191
- Dokters
	id : int
	nama : vc 191
- Expires
	id : int
	tanggal : timestamp
	jumlah : int
	penyimpanan_id : int
	barang_id : int
- Pemakaians
	id : int
	tanggal : timestamp
	jumlah : int
	dokter_id : int
	barang_id : int
- Pembelians
	id : int
	tanggal : timestamp
	supplier_id : int
- Penyimpanans
	id : int
	nama : vc 191
- Suppliers
	id : int
	nama : vc 191
- Users
	id : int
	name : vc 191
	email : vc 191
	password : vc 191


M2M Relations :
- Barang_Pembelian
	barang_id : int
	pembelian_id : int
	jumlah : int
	sisa : int
	expire : timestamp
</table>