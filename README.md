CARA PENGGUNAAN GIT & CARA MEMBUAT REPOSITORY LOCAL SERTA CARA MEMBUAT FILE README.md
Untuk hal ini yang kalian butuhkan adalah :
  1. Akun GitHub
  2. Software atau Program Git

CARA MENDAFTAR AKUN GitHub
  1. Buat akun GitHub dengan cara membuka laman https://github.com
  2. Kemudian masukan username, Email dan Password yang ingin kalian gunakan pada akun Github kalian.
  ![Screenshot (3)](https://user-images.githubusercontent.com/57002773/67613055-20164000-f7d3-11e9-8ed6-754abf3e0760.png)
  3. Lakukan verifikasi pada email yang sudah kalian masukan untuk mendaftar.
  "Gambar"
  4. Setelah melakukan verifikasi pada email kalian, selanjutnya kalian akan dialihkan langsung ke laman GitHub untuk selanjutnya membuat new repository, kemudian masukan nama repository kalian dan klik "create repository".
  "Gambar"
  5. Maka seperti inilah tampilan New Repository.
  "Gambar"
 CARA MENGINSTALL SOFTWARE GIT
  1. Untuk menginstall Git, sebelumnya kalian harus mendownload software di laman https://git-scm.com
  "Gambar"
  2. Pilih download dan sesuaikan dengan Operating System pada Computer atau Laptop kalian.
  "Gambar"
  3. Kemudian install software yang telah kalian download.
  4. Ikuti langkah-langkahnya, dan kemudian klik install.
  "Gambar"
  5. Pastikan software telah terinstal secara penuh lalu pilih finish.
  "gambar"
  6. Pastikan program Git sudah dapat digunakan pada perangkat kalian dengan cara membuka command prompt lalu ketik "git --version"jika muncul berarti Git sudah dapat digunakan.
  "Gambar"
  
  CARA MEMBUAT REPOSITORY LOCAL DAN FILE README.md
   1. Buatlah "new folder",lalu klik kanan pada folder tersebut dan pilih "Git Bash Here"
   ![31](https://user-images.githubusercontent.com/57002773/67614222-3b894700-f7e3-11e9-9e8b-0116208bff64.png)
   ![31 (2)](https://user-images.githubusercontent.com/57002773/67614219-362bfc80-f7e3-11e9-95fb-a24c98b307a4.png)
   2. Lalu akan muncul tampilan sebagai berikut:
   "gambar"
   3. Lakukan konfigurasi user.name dan user.email seperti pada gambar.
   ![Screenshot (50)](https://user-images.githubusercontent.com/57002773/67614226-49d76300-f7e3-11e9-8d35-dd6bb3aa5a38.png)
   4. Buatlah directori baru dengan menggunakan perintah "mkdir latihan1"
   "gambar"
   5. Jalankan perintah "git init", untuk membuat file kosong berformat ".git"
   "gambar"
   6. Buatlah file README.md, dengan cara menjalankan perintah echo "#latihanpython1">>README.md"
   "gambar"
   7. Intuk membuat file gunakan perintah ls -l
   "gambar"
   8. Gunakan perintah "git add README.md", untuk memasukan file README.md ke repository local
   "gambar"
   9. Gunakan perintah "git commit -m" untuk menyimpan perubahn kedalam database repository
   "gambar"
   10. Masuk ke laman GitHub yang sudah kalian buat tadi, kemudian salin url, gunakan perintah "git remote add origin [url]
   "gambar"
   11.Kirim perubahan local repository ke Gihub dengan menggunakan perintah "git push -origin master"
   "gambar"
   
