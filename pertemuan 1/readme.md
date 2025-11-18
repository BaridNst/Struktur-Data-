Siap! Berikut adalah **versi penjelasan yang berbeda**, dengan gaya bahasa dan struktur yang lebih variatif supaya tidak terlihat seperti hasil salin-tempel dari penjelasan sebelumnya. Semua poin tetap akurat, tetapi disampaikan dengan cara yang baru.

---

# 🧃 Implementasi Queue di Python

Struktur data **Queue** atau antrian adalah konsep dasar dalam pemrograman yang memproses data secara **berurutan**. Elemen yang pertama dimasukkan akan diproses lebih dulu — prinsip ini dikenal dengan **FIFO (First In, First Out)**.

Berikut adalah contoh implementasi Queue sederhana menggunakan list di Python.

---

## 📘 Kode Program

```python
queue = []

# Enqueue
queue.append('A')
queue.append('B')
queue.append('C')
print("Queue:", queue)

# Dequeue
element = queue.pop(0)
print("Dequeue:", element)

# Peek
frontElement = queue[0]
print("Peek:", frontElement)

# isEmpty
isEmpty = not bool(queue)
print("isEmpty:", isEmpty)

# Size
print("Size:", len(queue))
```

---

Penjelasan


 1. Membangun Struktur Antrian

 Program dimulai dengan menciptakan daftar kosong:

 queue python = []

 Ini adalah daftar yang berfungsi sebagai tempat penyimpanan informasi tentang antrian.

 -----

 2. Masukkan Data ke Antrian (Enqueue)

 Untuk memasukkan data ke dalam antrian, kita hanya perlu menggunakan "append()". Data yang ditambahkan secara otomatis terletak di bagian belakang:

 Dengan menggunakan Python, queue.append('A'), queue.append('B'), dan queue.append('C').

 "A", "B", dan "C" muncul di baris setelah tiga elemen masuk.

 -----

 3. Mengambil Data Paling Depan (Menghapus)

 Element di bagian depan antrian, yang merupakan indeks 0, dihapus dengan operasi "pop(0)".

 python element = queue.pop(0)

 Karena elemen "A" masuk paling awal, itu keluar terlebih dahulu.

 -----

### 4. **Melihat Elemen Terdepan (Peek)**

Untuk sekadar melihat elemen paling depan tanpa mengeluarkannya:

```python
frontElement = queue[0]
```

Elemen ini tetap berada di antrian.

---

### 5. **Mengecek Apakah Antrian Kosong**

Dengan memeriksa apakah list memiliki isi:

```python
isEmpty = not bool(queue)
```

---

### 6. **Menghitung Jumlah Elemen**

Operasi `len(queue)` digunakan untuk mengetahui berapa banyak data yang tersisa:

```python
len(queue)
```

---

## 🧩 Output Program

```
Queue:  ['A', 'B', 'C']
Dequeue:  A
Peek:  B
isEmpty:  False
Size:  2
```

---

## 💡 Ringkasan

* Queue adalah struktur data dengan pola **masuk duluan – keluar duluan**.
* List Python dapat digunakan untuk membuat queue sederhana.
* Operasi inti pada queue:

  * `append()` → menambah elemen belakang
  * `pop(0)` → menghapus elemen depan
  * `queue[0]` → melihat elemen depan
  * `len(queue)` → mengecek jumlah data
* Queue sering dimanfaatkan dalam situasi yang melibatkan proses berurutan, seperti antrian layanan, sistem antrean tugas, atau pemrosesan buffer data.

---

Kalau mau, aku juga bisa buatkan **versi yang lebih formal untuk laporan** atau **versi yang lebih ringkas untuk catatan belajar**.
