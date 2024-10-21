# **Membuat Kode Program dari flowchart pertemuan ke 4**

Tugas Pertemuan Ke 5

Nama= Althaf Afif Faiz

Kelas= TI.24.A.3

NIM= 312410404

# **1. BilanganTerbesar.py**

Pada program pertama yang akan dibuat adalah Program untuk menampilkan bilangan terbesar dari 3 Bilangan yang di Inputkan

Berikut ini contoh flowchartnya

![Screenshot 2024-10-21 193144](https://github.com/user-attachments/assets/7800d266-0059-44bd-b19d-33aa39e9973c)

**Program akan meminta untuk menginput 3 angka untuk dibandingkan :**
![Screenshot 2024-10-21 201816](https://github.com/user-attachments/assets/84d7f7e1-8c7c-4e2f-9bf2-554471df369d)




**Penjelasan code**

```
def mencari_bilangan_terbesar(a, b, c):
    if a > b=
        if a > c=
            return a, "A adalah terbesar"
        else:
            return c, "C adalah terbesar"
    else:
        if b > a=
            if b > c=
            return b, "B adalah terbesar"
        else:
            return c, "C adalah terbesar"

# Input bilangan A, B, C
print("Masukkan tiga bilangan:")
number1 = float(input("A: "))
number2 = float(input("B: "))
number3 = float(input("C: "))

# Menentukan bilangan terbesar
largest, message = mencari_bilangan_terbesar(a, b, c)

# Menampilkan hasil
print(f"\n{message}")
print(f"Bilangan terbesar adalah: {largest}")
```
## **2. BilanganN.py**
Pada program kedua ini untuk membandingkan bilangan yang diinput dan input akan terus berjalan sampai user menemukan nilai 0

Berikut ini contoh Flowchartnya

![Screenshot 2024-10-21 211417](https://github.com/user-attachments/assets/58022a94-e40e-43fc-ac09-c35caa05dfdc)

**Program akan meminta menginput angka untuk dibandingkan dan input akan terus berjalan sampai user memasukan angka 0 :**

![Screenshot 2024-10-21 211720](https://github.com/user-attachments/assets/b7603491-7dec-4646-bb13-92a55935b592)

**Penjelasan code**
```
Definisi Fungsi cari_max():
Fungsi cari_max() digunakan untuk mencari nilai maksimum.
Fungsi ini tidak menerima parameter input.
```

```
Inisialisasi Nilai Maksimum:
max_number = -float('inf'): Inisialisasi max_number dengan nilai negatif tak terhingga.
Ini memastikan bahwa setiap input bilangan bulat akan lebih besar dari nilai ini pada awalnya.
```

```
Loop while True:
Loop ini terus berjalan sampai input adalah 0.
number = int(input(...)): Menerima input bilangan bulat dari pengguna.
if number == 0:: Jika input adalah 0, keluar dari loop.
```

```
Perbarui Nilai Maksimum:
if number > max_number:: Jika input lebih besar dari nilai maksimum saat ini (max_number), maka:
max_number = number: Perbarui nilai maksimum (max_number) dengan input terbaru (number).
````

```
Cetak Nilai Maksimum:
print("Nilai maksimum adalah:", max_number): Setelah loop selesai, cetak nilai maksimum yang ditemukan.
```

```
Panggil Fungsi cari_max():
cari_max(): Panggil fungsi cari_max() untuk menjalankan program.
```



