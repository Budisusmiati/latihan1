CARA PENGGUNAAN GIT & CARA MEMBUAT REPOSITORY LOCAL SERTA CARA MEMBUAT FILE README.md
Untuk hal ini yang kalian butuhkan adalah :
  1. Akun GitHub
  2. Software atau Program Git

CARA MENDAFTAR AKUN GitHub
  1. Buat akun GitHub dengan cara membuka laman https://github.com
  2. Kemudian masukan username, Email dan Password yang ingin kalian gunakan pada akun Github kalian.
  ![Screenshot (3)](https://user-images.githubusercontent.com/57002773/67613055-20164000-f7d3-11e9-8ed6-754abf3e0760.png)
  3. Lakukan verifikasi pada email yang sudah kalian masukan untuk mendaftar.
  ![11](https://user-images.githubusercontent.com/57002773/67614204-067cf480-f7e3-11e9-8154-ea11bb1ebacb.png)
  4. Setelah melakukan verifikasi pada email kalian, selanjutnya kalian akan dialihkan langsung ke laman GitHub untuk selanjutnya membuat new repository, kemudian masukan nama repository kalian dan klik "create repository".
  ![13](https://user-images.githubusercontent.com/57002773/67614205-0bda3f00-f7e3-11e9-8733-3013afcbd1d7.png)
  5. Maka seperti inilah tampilan New Repository.
  ![15](https://user-images.githubusercontent.com/57002773/67614206-11378980-f7e3-11e9-9cd4-ee07a48ccd57.png)
 
 CARA MENGINSTALL SOFTWARE GIT
  1. Untuk menginstall Git, sebelumnya kalian harus mendownload software di laman https://git-scm.com
  ![17](https://user-images.githubusercontent.com/57002773/67614208-185e9780-f7e3-11e9-8f1e-46eb808de836.png)
  2. Pilih download dan sesuaikan dengan Operating System pada Computer atau Laptop kalian.
  ![20](https://user-images.githubusercontent.com/57002773/67614210-1eed0f00-f7e3-11e9-9f5f-bcbc225047c1.png)
  3. Kemudian install software yang telah kalian download.
  4. Ikuti langkah-langkahnya, dan kemudian klik install.
  ![23](https://user-images.githubusercontent.com/57002773/67614211-23b1c300-f7e3-11e9-9b0c-e89e31691916.png)
  5. Pastikan software telah terinstal secara penuh lalu pilih finish.
  ![25](https://user-images.githubusercontent.com/57002773/67614213-28767700-f7e3-11e9-9fee-da972e033ff4.png)
  6. Pastikan program Git sudah dapat digunakan pada perangkat kalian dengan cara membuka command prompt lalu ketik "git --version"jika muncul berarti Git sudah dapat digunakan.
  ![27](https://user-images.githubusercontent.com/57002773/67614215-2e6c5800-f7e3-11e9-8352-09dcf5371e03.png)
  
  CARA MEMBUAT REPOSITORY LOCAL DAN FILE README.md
   1. Buatlah "new folder",lalu klik kanan pada folder tersebut dan pilih "Git Bash Here"
   ![31](https://user-images.githubusercontent.com/57002773/67614222-3b894700-f7e3-11e9-9e8b-0116208bff64.png)
   ![31 (2)](https://user-images.githubusercontent.com/57002773/67614219-362bfc80-f7e3-11e9-95fb-a24c98b307a4.png)
   2. Lakukan konfigurasi user.name dan user.email seperti pada gambar.
   ![Screenshot (50)](https://user-images.githubusercontent.com/57002773/67614226-49d76300-f7e3-11e9-8d35-dd6bb3aa5a38.png)
   3. Buatlah directori baru dengan menggunakan perintah "mkdir latihan1"
   "gambar"
   4. Jalankan perintah "git init", untuk membuat file kosong berformat ".git"
   "gambar"
   5. Buatlah file README.md, dengan cara menjalankan perintah echo "#latihanpython1">>README.md"
   "gambar"
   6. Intuk membuat file gunakan perintah ls -l
   "gambar"
   7. Gunakan perintah "git add README.md", untuk memasukan file README.md ke repository local
   "gambar"
   8. Gunakan perintah "git commit -m" untuk menyimpan perubahn kedalam database repository
   "gambar"
   9. Masuk ke laman GitHub yang sudah kalian buat tadi, kemudian salin url, gunakan perintah "git remote add origin [url]
   "gambar"
   10.Kirim perubahan local repository ke Github dengan menggunakan perintah "git push -origin master",kemudian log on ke akun 
   GitHub yang sudah kalian buat tadi
   "gambar"
   
