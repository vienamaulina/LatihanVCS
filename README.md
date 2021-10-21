# TUTORIAL PENGGUNAAN GIT
## BAHASA PEMROGRAMAN
### Viena Dwi Putri Maulina 312110469

1. Buka web Github kemudian masuk ke akun
2. Cara membuat Repository
    klik New
    ![gambar 1](ss/ss1.png)
    kemudian isi repository name > publik > ceklis add a README file
    ![gambar 2](ss/ss2.png)
    maka tampilannya seperti ini
    ![gambar 3](ss/ss3.png)
3. Cara membuat html
    copy link
    ![gambar 4](ss/ss4.png)
    buat folder di local disk d  (vcs).
	Buka aplikasi Gitbash yang sudah diinstall.
	untuk masuk  ke user ketik sebagai berikut.
	$ pwd
	$ cd /d/vcs/  (tempat folder yang tadi dibuat)
	$ git clone (link yang tadi dicopy, maka akan muncul repository yang tadi dibuat diGithub)
    ![gambar 5](ss/ss5.png)
	kemudian buka file readme.
	buat file baru dengan klik file > new file > kemudian save.
    ![gambar 6](ss/ss6.png)
	ketik html :5, maka akan muncul seperti ini
    ![gambar 7](ss/ss7.png)
	kemudian tambahkan sesuai keinginan contohnya seperti berikut.
    ![gambar 8](ss/ss8.png)
	kemudian save.
	lalu buka file html tadi
    ![gambar 9](ss/ss9.png)
    dan muncul seperti berikut.
    ![gambar 10](ss/ss10.png)
3. cara membuat perubahan file html lokal menuju server repository
	buka gitbush
	masuk ke cd repository dengan mengetik :
	$ cd LatihanVCS/
	$ git add latihan.html (nama file html)
	$ git status
	$ git config --global user.email "vienamaulina@gmail.com"
	$ git config --global user.name "Viena Maulina"
	$ git commit -m "menambahkan file html"
	$ git push -u origin main
    ![gambar 12](ss/revisi.png)
	buka github, dan akan muncul tampilan seperti itu
    ![gambar 13](ss/ss13.png)
4. Cara Memasukan gambar ke server repository
	screenshot gambar/pindahkan gambar yang ingin dimunculkan ke repository
	buka file README.md yang tadi.
	ubah sesuai keinginan, misal seperti berikut.
    ![gambar 14](ss/ss16.png)
	buka aplikasi gitbush untuk melakukan perubahan lokal le server repository
	ketik :
    $ git add ss/contoh.png
    $ git add README.md
    $ git commit -m "menambahkan gambar"
    $ git push -u origin main
    ![gambar 15](ss/ss14.png)
    maka tampilannya akan seprti berikut
    ![gambar 16](ss/ss15.png)
    -seleseai-
    semoga bermanfaat

