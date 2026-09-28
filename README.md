# PBO Latihan 1 - Object Oriented Programming

Repositori ini dibuat untuk memenuhi tugas Mata Kuliah **Object Oriented Programming**.

## Identitas Mahasiswa
* **Nama:** Iftitania Arifatuz Zahra
* **NIM:** STI202504354
* **Kelas:** #24
* **Dosen:** Ardian Webi Kirda, S.Kom., M.Eng

---

## Deskripsi Tugas
Membuat 3 buah skrip Python terpisah untuk membaca file `"data/raw_products.json"`. Tugas ini menggunakan 3 metode transformasi data yang berbeda:

1. **Standard For Loop** (`products_loop.py`)
2. **List & Dict Comprehension** (`products_lc.py`)
3. **Functional Programming / Lambda** (`products_fp.py`)

### Aturan Transformasi Data:
* Filter produk yang memiliki nilai `is_available == True`.
* Format ulang *dictionary* produk dengan key:
  1. `item_code` : Teks kode produk.
  2. `product_name` : Teks nama produk dalam **HURUF KAPITAL**.
  3. `price` : Float harga produk.
  4. `stock_category` : "High Stock" jika stock >= 20, sebaliknya "Low Stock".

### Output Hasil Transformasi
Simpan hasil transformasi ke dalam folder `"data/"` dengan nama:
* `data/products_loop.csv`
* `data/products_lc.csv`
* `data/products_fp.csv`
