# HALLO NAMA SAYA SALMAN AL HARITS
Hari Ini Kita Akan Belajar Tentang Version Control System (VCS) Dengan menggunakan Git

# A.Penginstalan Git
Langkah pertama adalah penginstalan Git terlebih dahulu sebagai berikut:
	. Pertama pergi ke website www.git-scm.com
    ![git](https://user-images.githubusercontent.com/115677440/196120895-26d57a1a-343a-4aa5-b389-f475ab10e250.png)
    
	. Pilih menu Download > lalu pilih device anda
![downloadgit](https://user-images.githubusercontent.com/115677440/196155328-7a016988-5049-4b96-83f2-31d70bc6832d.png)

	. Silakan download, tergantung dengan device anda apakah 32 bit atau 64 bit, disini saya memakai 64 bit
	
	. Jika sudah maka pergi ke file manager > download > file git yang sudah di download
	
	. Klik kanan > lalu run as administrator
	
	. Klik next sampai tahap penginstalan
![instalgit](https://user-images.githubusercontent.com/115677440/196155340-5231e126-b160-4722-b765-213b6cb57a05.png)

  . setelah itu buka Git bash,ini adalah tampilan awalnya
    ![awal gitbash](https://user-images.githubusercontent.com/115677440/196123006-de0d5f71-9d79-4b45-a7e6-7cade84a0259.png)

# B.Membuat repository local
  Setelah membuka gitbash kita akan membuat repository local,caranya adalah sebagai berikut:
  . Sebelumnya pastikan file sudah berada di home atau dokumen lain,lalu buka direktory aktif di windows explorer
    disini saya menggunakan direktory c/user/..
    kita bisa berpindah directory dengan cara $ cd .. lalu cd d/nama_folder
    
  . Kita akan membuat repository dengan perintah $ mkdir nama_directory
          contoh : $ mkdir lab_komputer, $ mkdir tugas1
	  
  . Selanjutnya kita akan masuk kedalam directory menggunakan perintah $ cd nama_directory
  
  . Setelah itu kita akan membuat repository local dengan perintah $  git init
    ![mkdir](https://user-images.githubusercontent.com/115677440/196123766-7b479ee2-7ac1-4b08-bca0-cfb0345a8e5b.png)
    
  . Sekarang kita akan membuat sebuah file (teks) dengan menggunakan perintah $ echo "# membuat teks" >> README.md
    ![echo](https://user-images.githubusercontent.com/115677440/196123072-e45b6e02-4f6d-4ac2-b57c-89aaf6f99b06.png)
    
  . Sebelum kita menambahkan file kedalam repository,sebaiknya masukan perintah git config agar saat proses git commit tidak eror
  ($ git config --global user.name "nama.user"), 
  ($ git config --global user.email "email.user")
    ![configuser](https://user-images.githubusercontent.com/115677440/196123031-624d70d1-7c71-4c0d-bbb1-651c0a39a7fb.png)
    
  . Setelah menambahkan git config untuk memasukan file kedalam repository kita gunakan perintah $ git add README.md
    ![add git (2)](https://user-images.githubusercontent.com/115677440/196122977-3a8ef9ce-31a4-4d37-b78c-29be74091787.png)
    
  . Untuk menyimpan perubahan kedalam database repository maka menggunakan perintah $ git commit -m "komentar"
    ![commit m](https://user-images.githubusercontent.com/115677440/196123014-2299fff2-973e-4c2b-a367-6c911336f067.png)

# C.Membuat repository server
  Sekarang kita akan membuat repository server,langkahnya sebagai berikut
  . Masuk ke website git (www.github.com)
  . Lalu lakukan login / membuat akun terlebih dahulu
    ![login](https://user-images.githubusercontent.com/115677440/196121002-3a906879-343c-429c-83c8-7f5824e16aee.png)
    
  . masukan email, password dan nama pengguna
    ![daftra](https://user-images.githubusercontent.com/115677440/196123721-32164231-76e1-4354-99db-9e63b86bc32b.png)
    
  . setelah itu,ikuti perintah yang diarahkan oleh github.com
  
  . inilah tampilan awalnya,untuk membuat repository server klik icon "+" pojok kanan atas
    ![tampilan awal (2)](https://user-images.githubusercontent.com/115677440/196123780-ad18008b-32f4-4599-8352-139575c93168.png)
    
  . masukan nama repository, klik create repository
![repository git (2)](https://user-images.githubusercontent.com/115677440/196155353-05ba4d55-2ddf-4659-a583-48de2b44fb71.png)
    
# D.Mengirim perubahan
  Setelah kita membuat repository local dan repository server,kita akan mengirim file ke repository server caranya adalah sebagai berikut: 
  . kita akan menambahkan remote repository,fungsinya adalah menyimpan setiap perubahan pada repository local
    pada repository server ada link yang akan kita gunakan untuk menjalankan perintah $ git remote add origin [url]
    $ git remote add origin https://github.com/haritssalman/LatihanVCS.git
    ![remote](https://user-images.githubusercontent.com/115677440/196123772-37de047a-1e5d-4b00-8208-69efc3df32e8.png)
    
  . selanjutnya kita akan mengirim file ke repository server dengan perintah $ git push -u master
  
  . masukan nama user dan password
    ![pushu](https://user-images.githubusercontent.com/115677440/196123769-1adf0ede-9344-4c0e-8edf-6521b04c54b9.png)
    
  . untuk memeriksa hasil,buka kembali website github > user > repository > klik repository
    maka ini hasilnya
    ![hasil](https://user-images.githubusercontent.com/115677440/196123758-cc24823c-33ea-4556-a172-1279eb286dae.png)
    
# CLONE REPOSITORY
  .Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya (working directory).
Perintahnya adalah $ git clone [URL]
![Screenshot (76)](https://user-images.githubusercontent.com/115677440/196157053-a49b35a3-e1c2-428b-ace5-084e9f16fa8e.png)

# TERIMA KASIH
