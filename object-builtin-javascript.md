## Mengakses Property

* `Object.keys()` — mendapatkan semua nama property
* `Object.values()` — mendapatkan semua nilai property
* `Object.entries()` — mendapatkan pasangan nama property dan nilai
* `Object.fromEntries()` — membuat object dari pasangan key dan value
* `Object.hasOwn()` — mengecek apakah object memiliki property tertentu

## Menggabungkan & Menyalin

* `Object.assign()` — menyalin property dari satu atau beberapa object ke object lain
* `Object.create()` — membuat object dengan prototype tertentu

## Mengatur Property

* `Object.defineProperty()` — menambahkan atau mengubah satu property dengan descriptor
* `Object.defineProperties()` — menambahkan atau mengubah beberapa property dengan descriptor
* `Object.getOwnPropertyDescriptor()` — mendapatkan descriptor sebuah property
* `Object.getOwnPropertyDescriptors()` — mendapatkan semua descriptor property

## Prototype

* `Object.getPrototypeOf()` — mendapatkan prototype sebuah object
* `Object.setPrototypeOf()` — mengubah prototype sebuah object
* `Object.hasOwn()` — mengecek apakah property dimiliki langsung oleh object

## Membatasi Object

* `Object.freeze()` — membekukan object agar property tidak dapat diubah
* `Object.isFrozen()` — mengecek apakah object sudah dibekukan
* `Object.seal()` — menyegel object agar property tidak dapat ditambah atau dihapus
* `Object.isSealed()` — mengecek apakah object sudah disegel
* `Object.preventExtensions()` — mencegah penambahan property baru
* `Object.isExtensible()` — mengecek apakah object masih dapat ditambahkan property

## Perbandingan

* `Object.is()` — membandingkan dua nilai dengan aturan equality yang lebih ketat

## Konversi & Representasi

* `Object.prototype.toString()` — mendapatkan representasi tipe object
* `Object.prototype.toLocaleString()` — mendapatkan representasi string berdasarkan locale
* `Object.prototype.valueOf()` — mendapatkan nilai primitif dari object

## Property & Prototype Object

* `Object.prototype.hasOwnProperty()` — mengecek apakah property dimiliki langsung oleh object
* `Object.prototype.isPrototypeOf()` — mengecek apakah object merupakan prototype dari object lain
* `Object.prototype.propertyIsEnumerable()` — mengecek apakah property bersifat enumerable

## Lainnya

* `Object.groupBy()` — mengelompokkan elemen iterable berdasarkan hasil callback
* `Object.getOwnPropertyNames()` — mendapatkan semua nama property sendiri, termasuk non-enumerable
* `Object.getOwnPropertySymbols()` — mendapatkan semua Symbol property sendiri
* `Object.getOwnPropertyDescriptors()` — mendapatkan descriptor semua property sendiri
