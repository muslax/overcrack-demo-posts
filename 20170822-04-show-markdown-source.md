Show Your Markdown Source
====================
Image: 
Description: Showing Markdown source to users.
Published: 2017-08-22 11:21am
Publish-now


**Show-Markdown** adalah sebuah fitur Overcrack yang berfungsi mencetak kode sumber (_source code_) asal sebuah postingan yang tersimpan dalam format Markdown. Dengan fitur ini penulis atau pemilik blog dapat mengecek kode sumber, misalnya ketika ada keganjilan dalam tampilan, langsung melalui browser tanpa harus _ribet_ login ke server. Bagi pengguna, fitur ini antara lain dapat memberikan gambaran bagaimana sebuah artikel blog tersusun dalam bentuk aslinya.

Fitur **Show Markdown** berlaku dan hanya berlaku untuk halaman _permalink_, yaitu halaman blog yang menampilkan postingan tunggal, jadi bukan pada halaman beranda (_frontpage_) atau halaman arsip. Dalam Overcrack halaman _permalink_ dicirikan dengan format URL (yaitu alamat yang tertulis di baris alamat atau _address bar_) yang memuat secara berurutan tahun, bulan, tanggal dan judul postingan, misalnya seperti ini: `/2017/02/28/judul-artikel`.

Untuk memanggil fitur **Show Markdown** silakan tambahkan **`/markdown`** setelah alamat yang tercetak di _address bar_. Lebih mudah lagi, template _default_ Overcrack menyediakan _shortcut_ **`Ctrl-M`** untuk memanggil fitur ini. 

Nah, untuk artikel yang sedang Anda baca ini, bila yang tercetak di _address bar_ browser adalah `[nama.domain]/2017/08/22/show-markdown-source` berarti Anda sedang mengunjungi halaman _permalink_. Bila tidak, klik [link&nbsp;ini](/2017/08/22/show-markdown-source) untuk memastikan Anda sudah berada di halaman _permalink_, atau klik [link&nbsp;ini](/2017/08/22/show-markdown-source/markdown) untuk melihat langsung versi Markdownnya.


###How it works

Fitur **Show Markdown** terinspirasi oleh halaman [Proyek Markdown](https://daringfireball.net/projects/markdown/) di situs Daring Fireball yang bisa menampilkan kode sumber dengan menambahkan sufiks `/index.text`. Tetapi bila [John Gruber](https://twitter.com/gruber/) hanya mengijinkan melihat kode sumber Markdown hanya pada _satu_ halaman saja, **Show Markdown** di Overcrack diaplikasikan untuk _seluruh_ halaman _permalink_. Dan terus terang saya menganggap implementasi di Overcrack lebih elegan. :-) Lalu, _how it works_?

Berbeda dengan CMS rumit seperti Wordpress dan lain-lain yang menyimpan konten asli dalam sejumlah tabel database yang _tidak bisa_ begitu saja dibaca oleh mata manusia, Overcrack menyimpan konten aslinya dalam file teks sederhana – ya, tentu dengan format penulisan Markdown. 



Seluruh halaman HTML blog Overcrack 

Berbeda dengan hal yang pertama, Overcrack akan memanggil calon korban dengan sendirinya.


Selain bisa dibuka dan mudah dibaca dengan aplikasi paling sederhana seperti Notepad di Windows atau TextEdit di Mac (bahkan di konsol terminal), seluruh konten Overcrack bersifat portabel.

