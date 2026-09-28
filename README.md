# PBO-latihan-1
Repositori ini dibuat untuk memenuhi tugas Mata Kuliah [Object Oriented Programming]

Nama: Iftitania Arifatuz Zahra
NIM: STI202504354
kelas: #24
Dosen: Ardian Webi Kirda, S.Kom., M.Eng

#Deskripsi Tugas
Membuat 3 buah skrip Python terpisah untuk membaca file "data/raw_products.json".
Menggunakan 3 metode transformasi data yang berbeda:
1. Standard For Loop (products_loop.py)
2. List & Dict Comprehension (products_lc.py)
3. Functional Programming / Lambda (products_fp.py)

Aturan Transformasi Data:
- Filter produk yang memiliki nilai is_available == True.
- Format ulang dictionary produk dengan key:
 * item_code       : Teks kode produk.
 * product_name    : Teks nama produk dalam HURUF KAPITAL.
 * price           : Float harga produk.
 * stock_category  : "High Stock" jika stock >= 20, sebaliknya "Low Stock".

simpan hasil transformasi ke dalam folder "data/" dengan nama:
 - "data/products_loop.csv"
 - "data/products_lc.csv"
 - "data/products_fp.csv"
