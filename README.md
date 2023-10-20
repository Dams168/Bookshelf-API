# BookShelf API
Terdapat 7 kriteria utama yang harus Anda penuhi dalam membuat proyek Bookshelf API.
- Kriteria 1 : Aplikasi menggunakan port 9000
- Kriteria 2 : Aplikasi dijalankan dengan perintah npm run start.
- Kriteria 3 : API dapat menyimpan buku
- Kriteria 4 : API dapat menampilkan seluruh buku
- Kriteria 5 : API dapat menampilkan detail buku
- Kriteria 6 : API dapat mengubah data buku
- Kriteria 7 : API dapat menghapus buku

### Optional 
- Tambahkan fitur query parameters pada route GET /books (Mendapatkan seluruh buku).
    - `?name` : Tampilkan seluruh buku yang mengandung nama berdasarkan nilai yang diberikan pada query ini. Contoh /books?name=”dicoding”, maka akan menampilkan daftar buku yang mengandung nama “dicoding” secara non-case sensitive  (tidak peduli besar dan kecil huruf).
    - `?reading` : Bernilai 0 atau 1. Bila 0, maka tampilkan buku yang sedang tidak dibaca (reading: false). Bila 1, maka tampilkan buku yang sedang dibaca (reading: true). Selain itu, tampilkan buku baik sedang dibaca atau tidak.
    - `?finished` : Bernilai 0 atau 1. Bila 0, maka tampilkan buku yang sudah belum selesai dibaca (finished: false). Bila 1, maka tampilkan buku yang sudah selesai dibaca (finished: true). Selain itu, tampilkan buku baik yang sudah selesai atau belum dibaca.

- Menggunakan ESLint dan salah satu style guide agar gaya penulisan kode JavaScript lebih konsisten. Serta ketika dijalankan perintah npx eslint . tidak terdapat error yang muncul.

<h3>How To Install</h3>

```bash
npm install 
```

<h3>How To Run</h3>

```bash
npm run start 
```

<h3>How To Run with Nodemon</h3>

```bash
npm run start-dev 
```
<h3>How To Run Eslint</h3>

```bash
npx eslint / npm run lint 
```
