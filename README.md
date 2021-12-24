# praktikum8
## Tugas pertemuan ke 12
```sh
Nama    : A. Reza Baehaqa Jamroni
Nim     : 312110494
Matkul  : Bahasa Perograman
```
### PROGRAM INPUT MAHASISWA MENGUNAKAN OOP (CLASS)
Tugas Praktikum<p>

Buat program sederhana dengan mengaplikasikan penggunaan class. Buatlah class untuk menampilkan daftar nilai mahasiswa, dengan ketentuan:<p>
• Method tambah() untuk menambah data<p>
• Method tampilkan() untuk menampilkan data<p>
• Method hapus(nama) untuk menghapus data berdasarkan nama<p>
• Method ubah(nama) untuk mengubah data berdasarkan nama<p>
• Buat diagram class, flowchart dan penjelasan programnya pada README.md.<p>
• Commit dan push repository ke github<p>

### DIAGRAM CLASS
![Gambar 1](screenshot/class.png)<p>

### FLOWCHART
![Gambar 1](screenshot/flowchart.png)<p>

### penjelasan 
Pemrograman berorientasi objek atau dalam bahasa inggris disebut Object Oriented Programming (OOP) adalah paradigma atau teknik pemrograman di mana semua hal dalam program dimodelkan seperti objek dalam dunia nyata.<p>

Berikut langkah-langkah yang saya bikin dalam membuat program sederhana untuk menampilkan daftar nilai mahasiswa dengan mengaplikasikan penggunann class : <p>
1. pertama saya buat dekralarasi dt={} sebagai object untuk menerima inputan data.
2. deklarasi class di isi dengan method diantaranya sebagai berikut:
```sh
def tambah(self)
def ubah(self)
def hapus(self)
def lihat(self)
def keluar(self)
```
3. kemudian saya membuat looping dengan while true
```sh
while True:
    data=daftarNilai()
    print('\ntambah\t(1)\nubah\t(2)\nhapus\t(3)\nlihat\t(4)\nkeluar\t(5)')                                                                                     
    c = input("\nsilahkan masukan pilihan yang diatas : ")
```
4. membuat fungsi if, elif, else untuk menjalankan methodnya
```sh
    if (c=="1"):
        data.tambah()
    elif (c=="2"):
        data.ubah()
    elif (c=="3"):
        data.hapus()
    elif (c=="4"):
        data.lihat()
    else:
        data.keluar()
        break
```
5. selesai

### TAMPILAN VISUAL STUDIO CODE
![Gambar 1](screenshot/vscd.png)<p>

### HASIL OUTPUT
• Berikut ini adalah contoh hasil dari output programnya yang saya buat dengan pilihan tambah (1), ubah (2), hapus (3), lihat (4), keluar (5) : <p>
![Gambar 1](screenshot/output1.png)<p>
![Gambar 1](screenshot/output2.png)<p>
![Gambar 1](screenshot/output3.png)<p>