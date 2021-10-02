# 01-git-github

Langkah- Langkah Praktik Github :
1. Membuat account github

    o	Membuat account github dengan memasukan username, email dan pasword.
    
    o	Lalu melakukan konfirmasi melalui email.
    
    o	Login dengan account yang sudah dibuat.
2. Menginstal Git

    o	Download git pada https://git-scm.com/downloads (sesuaikan dengan sistem operasi laptop).
   
    o	Lakukan instalasi.
    
    o	Untuk cek instalasi dapat menggunakan command prompt dengan eksekusi "git --version".
    
3. Melakukan konfigurasi 
    o	Konfigurasi git dapat menggunakan command prompt dengan eksekusi :
		  git config --global user.name "Nama Anda di GitHub"
		  git config --global user.email email@domain.tld

    o	Lalu untuk melihat konfigurasi yang sudah ada dapat eksekusi "git config --list"
4. Membuat personal account token di  https://docs.github.com/en/authentication/keeping-your-  account-and-data-secure/creating-a-personal-access-token.
5. Membuat dan mengelola repository
    o	Membuat repo dapat dengan klik tombol + pada bagian kanan atas sebelah account.
    o	Setelah itu isi nama, keterangan, pilih publik, dan initialize this repository with a README.
    o	Lalu klik create repository.
    o	Clone repo dengan eksekusi "git clone https://github.com/oldstager/awesome-project" di cmd.
    o	Untuk edit dapat dilakukan dengan membuka repo di github lalu pada kotak README.md sebelah pojok kanan ada gambar pena untuk mengedit. 
    o	Setiap selesai mengedit dapat menggunakan commit untuk menandai pengeditan. Penamaan commit dapat disesuaikan dengan apa isi yang diedit.
    o	Setelah itu klik commit change.
6. Untuk sinkronisasi dari github ke local dapat menggunakan pull.
