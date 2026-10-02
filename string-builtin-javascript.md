## Mencari

* `includes()` — mengecek apakah string mengandung teks tertentu

### contoh
  
* `startsWith()` — mengecek apakah string diawali teks tertentu
* `endsWith()` — mengecek apakah string diakhiri teks tertentu
* `indexOf()` — mencari posisi pertama teks tertentu
* `lastIndexOf()` — mencari posisi terakhir teks tertentu
* `search()` — mencari posisi teks berdasarkan regular expression
* `match()` — mencari kecocokan berdasarkan regular expression
* `matchAll()` — mencari semua kecocokan berdasarkan regular expression

## Mengambil Bagian String

* `at()` — mengambil karakter berdasarkan index
* `charAt()` — mengambil karakter berdasarkan index
* `charCodeAt()` — mengambil kode UTF-16 karakter berdasarkan index
* `codePointAt()` — mengambil Unicode code point berdasarkan index
* `slice()` — mengambil sebagian string
* `substring()` — mengambil sebagian string berdasarkan posisi
* `substr()` — mengambil sebagian string berdasarkan posisi dan panjang *(deprecated)*

## Mengubah String

* `toUpperCase()` — mengubah string menjadi huruf besar
* `toLowerCase()` — mengubah string menjadi huruf kecil
* `toLocaleUpperCase()` — mengubah string menjadi huruf besar berdasarkan locale
* `toLocaleLowerCase()` — mengubah string menjadi huruf kecil berdasarkan locale
* `trim()` — menghapus whitespace di awal dan akhir
* `trimStart()` — menghapus whitespace di awal
* `trimEnd()` — menghapus whitespace di akhir
* `replace()` — mengganti kecocokan pertama
* `replaceAll()` — mengganti semua kecocokan
* `normalize()` — menormalkan representasi Unicode

## Memisahkan & Menggabungkan

* `split()` — memecah string menjadi array
* `concat()` — menggabungkan string dengan string lain
* `repeat()` — mengulang string beberapa kali

## Padding

* `padStart()` — menambahkan karakter di awal hingga panjang tertentu
* `padEnd()` — menambahkan karakter di akhir hingga panjang tertentu

## Iterasi

* `String.prototype[Symbol.iterator]()` — membuat iterator untuk setiap karakter string

## Konversi

* `toString()` — mengubah nilai menjadi string
* `valueOf()` — mendapatkan nilai primitif dari String object

## Static String Methods

* `String.fromCharCode()` — membuat string dari kode UTF-16
* `String.fromCodePoint()` — membuat string dari Unicode code point
* `String.raw()` — membuat string raw dari template literal

## Property

* `length` — mendapatkan jumlah karakter dalam string
