1.Tempatkan Gambar di Direktori yang Tepat:
    Pastikan gambar yang ingin Anda tambahkan sudah ada di direktori yang benar dalam struktur proyek Jekyll. Umumnya, Anda dapat meletakkan gambar-gambar tersebut di dalam direktori assets atau images.
2.Panggil Gambar di File Markdown atau HTML: 
    Buka file Markdown atau HTML tempat Anda ingin menampilkan gambar tersebut.
    Jika Anda menggunakan Markdown (biasanya berakhir dengan ekstensi .md), gunakan sintaks Markdown untuk gambar. Contohnya:

  markdown
  ![Deskripsi Gambar](/path/to/image.jpg)
   Gantilah /path/to/image.jpg dengan jalur relatif atau absolut ke gambar Anda.
  Jika Anda menggunakan HTML, gunakan tag <img>:

  html
   <img src="/path/to/image.jpg" alt="Deskripsi Gambar">
 3.Jalankan Jekyll Lokal (Opsional):
     Jika Anda ingin melihat situs Jekyll Anda secara lokal sebelum mengunggahnya, jalankan server lokal Jekyll dengan perintah berikut di terminal (pastikan Anda berada di direktori proyek Jekyll):
      bash
     bundle exec jekyll serve
     Kemudian, buka browser dan kunjungi http://localhost:4000 untuk melihat perubahan yang Anda buat.
  4.Commit dan Push Perubahan:
     Setelah Anda puas dengan tampilan gambar di situs lokal Anda, commit perubahan tersebut dan dorong (push) ke repositori GitHub atau platform hosting lainnya yang Anda gunakan.
  5.Periksa Situs Online:
     Setelah perubahan diunggah, periksa situs web Jekyll Anda secara online untuk memastikan gambar ditampilkan dengan benar.
