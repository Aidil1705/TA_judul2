Tugas Akhir Judul 2

Pertama kita akan membuat folder project lalu membuat repositori.
Lalu saya akan menginisiasi folder dengan git

Dengan Perintah
git init


Perintah ini berfungsi untuk menginisialisasi folder agar bisa menggunakan Git.

</br>
Menghubungkan Folder dengan GitHub
git remote add origin https://github.com/Aidil1705/TA_judul2.git


Perintah ini digunakan untuk menghubungkan folder project lokal dengan repositori di GitHub.

</br>

Setelah itu saya melakukan perintah git pull untuk menarik data dari repositori GitHub agar sinkron dengan folder lokal.

</br>

Lalu saya membuat file index.html dan style.css.

Melakukan Add Pertama
git add .


Perintah ini digunakan untuk menambahkan semua file yang ada di folder ke staging area agar siap di-commit.

</br>
Melakukan Commit Pertama
git commit -m "komit pertama"


Perintah ini digunakan untuk menyimpan perubahan yang sudah ditambahkan ke staging area ke dalam riwayat Git.

</br>
Melakukan Push Pertama
git push origin master


Perintah ini digunakan untuk mengirim (upload) commit dari branch master ke repositori GitHub bernama origin.

</br>
Menambahkan File Baru

Saya kemudian membuat file index.html yang sebelumnya belum di-add, jadi saya menambahkan file itu secara manual.

git add index.html


Perintah ini hanya menambahkan satu file tertentu, yaitu index.html, ke staging area.

</br>
Melihat Status
git status


Digunakan untuk melihat file apa saja yang sudah ditambahkan ke staging area dan apakah ada perubahan yang belum di-commit.

</br>
Melakukan Commit Kedua
git commit -m "komit index"


Untuk menyimpan perubahan file index.html ke dalam repositori.

</br>
Melakukan Push Lagi
git push origin master


Untuk mengunggah perubahan commit index.html ke GitHub.

</br>
Membuat Branch Baru
git branch section


Perintah ini digunakan untuk membuat branch baru bernama section.

</br>
Pindah ke Branch Section
git checkout section


Untuk berpindah dari branch master ke branch section agar bisa mengerjakan bagian lain tanpa mengubah branch utama.

</br>
Menambahkan File Lagi
git add .


Saya menambahkan semua file yang telah diperbarui di branch section ke staging area.

</br>
Commit di Branch Section
git commit -m "section dan css"


Untuk menyimpan perubahan pada file index.html dan style.css di branch section.

</br>
Push ke GitHub
git push origin section


Untuk mengirim commit dari branch section ke GitHub agar bisa dibuat pull request nantinya.

</br>
Melakukan Perubahan Tambahan

Saya terus menambahkan bagian lain di index.html dan memperbarui style.css, lalu melakukan commit beberapa kali seperti:

git commit -m "section article"
git commit -m "section kontaj"
git commit -m "css"


Setiap commit ini menyimpan perubahan kecil sesuai bagian yang saya tambahkan.

</br>
Menggabungkan Branch Section ke Master

Setelah semua perubahan di branch section sudah selesai, saya kembali ke branch master dengan perintah:

git checkout master


Lalu saya menggabungkan hasil kerja dari branch section ke master dengan perintah:

git merge section


Perintah ini menggabungkan semua perubahan dari branch section ke branch utama (master).

</br>
Menghapus Branch Section
git branch -d section


Setelah branch section selesai digabung, saya menghapusnya agar repositori tetap rapi.

</br>
Mengecek Status Akhir
git status


Menampilkan bahwa tidak ada perubahan yang perlu di-commit dan semua sudah bersih.

</br>

Dengan langkah-langkah di atas, saya berhasil membuat project, menambahkan file, melakukan commit dan push beberapa kali, membuat branch baru, melakukan merge ke master, dan menjaga repositori tetap bersih dan sinkron dengan GitHub.
