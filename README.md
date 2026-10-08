# Praktikum 3: CSS Dasar - Pemrograman Web
Repository ini dibuat untuk menyelesaikan tugas Praktikum 3 Pemrograman Web.

## Identitas Mahasiswa

| Keterangan      | Data                  |
| --------------- | ---------------       |
| **Nama**        | Ilyan Arbiyani Sukhfi |
| **Kelas**       | I251D                 |
| **NIM**         | 312510436		|
| **Mata Kuliah** | Pemrograman Web       |

### Tujuan Praktikum

Mahasiswa mampu memahami konsep dasar CSS.

Mahasiswa mampu memahami aturan penulisan pada CSS (Internal, Eksternal, dan Inline).

Mahasiswa mampu memahami selector sebagai pengontrol CSS (Elemen, ID, dan Class).

Mahasiswa mampu membuat pengaturan CSS pada HTML.

---

## Struktur Folder Proyek

```
Lab3Web/
├── Lab3_css_dasar.html
├── style_eksternal.css
└── README.md

```
## 1. Struktur File

Struktur file pada praktikum ini adalah sebagai berikut:

<img width="247" height="152" alt="Image" src="https://github.com/user-attachments/assets/20dd606c-5a4c-45e2-a841-be0d75e72aae" />

## Langkah-langkah Praktikum

### 1. Membuat Dokumen HTML Dasar

Langkah pertama adalah membuat dokumen HTML dasar dengan nama lab2_css_dasar.html. Dokumen ini menggunakan struktur HTML5 yang berisi elemen-elemen seperti header, <nav>, dan <div> untuk menyusun kerangka halaman web.

<img width="1197" height="766" alt="Image" src="https://github.com/user-attachments/assets/88bc965d-a3fb-467d-8986-5cd2292c1be4" />

Selanjutnya buka pada brwoser untuk melihat hasilnya.

<img width="1210" height="252" alt="Image" src="https://github.com/user-attachments/assets/7d00b4aa-3922-4f6b-b221-7641390bc23d" />

### 2. Mendeklarasikan CSS Internal

CSS Internal ditulis di dalam tag <style> yang diletakkan pada bagian <head> dokumen HTML. Pada langkah ini, gaya ditambahkan untuk memodifikasi elemen body, header, dan teks h1.

<img width="861" height="445" alt="Image" src="https://github.com/user-attachments/assets/5b54465f-5d1b-4c94-954d-7bd17dd54181" />

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

<img width="1050" height="355" alt="Image" src="https://github.com/user-attachments/assets/4b73118c-d601-4539-b224-22d54f3ae6bd" />

### 3. Menambahkan Inline CSS

Inline CSS ditulis langsung di dalam baris tag HTML sebagai atribut style. Pada praktikum ini, inline CSS diterapkan pada tag <p> untuk mengubah perataan teks menjadi ke tengah (center) dan mengubah warna tulisan. Gaya ini hanya berdampak pada satu baris elemen tersebut.

<img width="1168" height="121" alt="Image" src="https://github.com/user-attachments/assets/d70230b7-31f8-4832-8704-b378dee889ba" />

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

<img width="952" height="237" alt="Image" src="https://github.com/user-attachments/assets/c4b94f86-110a-4058-9829-3e2922ae4ffd" />

### 4. Membuat CSS Eksternal

CSS Eksternal dipisahkan ke dalam file khusus bernama style_eksternal.css. File ini kemudian dihubungkan ke dokumen HTML menggunakan tag <link rel="stylesheet" href="style_eksternal.css">. Metode ini sangat efisien untuk mengatur gaya di banyak halaman sekaligus.

<img width="696" height="352" alt="Image" src="https://github.com/user-attachments/assets/54e1bf29-bc13-48d6-9d76-4bf71a00fc1c" />

Kemudian tambahkan tag <link> untuk merujuk file css yang sudah dibuat pada bagian
<head>

<img width="592" height="102" alt="Image" src="https://github.com/user-attachments/assets/48d28155-c63a-4ef2-a4bb-b79836864fbd" />

Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

<img width="1207" height="302" alt="Image" src="https://github.com/user-attachments/assets/2ea6ca4a-0176-4282-a4e4-3a0e2f78309c" />

### 5. Menambahkan CSS Selector (ID dan Class)

Selector digunakan untuk memilih secara spesifik elemen mana yang akan diubah gayanya:

ID Selector (#): Diterapkan pada elemen spesifik (contoh: #intro). ID bersifat unik dan hanya boleh digunakan satu kali pada satu halaman.

Class Selector (.): Digunakan untuk mengelompokkan beberapa elemen (contoh: .button). Class bisa digunakan berulang kali pada elemen-elemen yang berbeda.

<img width="755" height="587" alt="Image" src="https://github.com/user-attachments/assets/18970cd6-bf89-40c2-b668-2f78de9f8bb1" />


Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya.

<img width="1907" height="722" alt="Image" src="https://github.com/user-attachments/assets/934bc4a4-637d-4541-9919-f8111442e2f9" />

dan kita telah menyelesainkan tugas yang telah di berikan pada modul
