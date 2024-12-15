# DAY3

1. Menurut saya git adalah sistem control versi yang dapat membantu tim dengan mengerjakan projek sebuah atau lebih projek
2. flow cara kerja git <br>
![image](https://github.com/user-attachments/assets/145e593d-9baf-4136-97a5-4e9e9214e039) <br>
3. Command Git pada Virtual Machine <br>
3.1 Konfigurasi awal : menghubungkan git dengan virtual machine <br>
   - git init : untuk menginisialisasi repositori Git baru di direktori kerja. <br>
   ![image](https://github.com/user-attachments/assets/770b9701-7193-477b-a416-236bfff00d71) <br>
   - git add nama file : berfungsi untuk menyimpan perubahan yang dilakukan pada file terentu saja <br>
     ![image](https://github.com/user-attachments/assets/35ee9100-2736-4bf1-9382-0010e47d71b5) <br>
     git add . : berfungsi untuk menyimpan seluruh perubahan yang dilakukan pada VM <br>
   SEBELUM DI GIT ADD . file 4 blm terdeteksi perubahan <br>
![image](https://github.com/user-attachments/assets/96cb8583-bf1b-4309-a025-b4b4256cf748) <br>
SESUDAH DI GIT ADD . file 4 sudah terdeteksi perubahan <br>
![image](https://github.com/user-attachments/assets/108c621a-1412-4b57-9431-89a5c0bfbe9d) <br>
   - git commit -m "name" : berfungsi untuk menghubungkan git dengan vm <br>
   ![image](https://github.com/user-attachments/assets/112b31d6-70ff-4532-a72e-0fb17bd96e67) <br>
   - apabila menambahkan gi commit yang baru maka git commit yang lama akan tinggal status yang dapat dilihat pada git log --oneline <br>
   - git config --list : berfungsi untuk menampilkan konfigurasi Git yang saat ini aktif pada sistem
![image](https://github.com/user-attachments/assets/a4d4e107-fa7b-4318-b8b0-1b4ce8237b9d) <br>
   - git remote origin "url" : menghubungkan Git VM dengan Git <br> 
3.2 Cara Kerja Git menggunakan Command Git
- ssh -T git@github.com berfungsi untuk mengecek apakah ssh key yang telah di setting berhasil dilakukan pada VM dan git
- .nama : berfungsi untuk mengasingkan file, dll. yang dimana perubahan yang dilakukan tidak akan terlihat pada saat melakukan git status
- git log --oneline : menampilkan aktivitas dari vm yang telah melakukan penghapusan serta menampilkan ID <br>
-ssh-keygen : berfungsi untuk proses pengembalian data yang dihapus  <br>
- git checkout ID : untuk mengembalikan yang di hapus sebelumnya <br>
- ![image](https://github.com/user-attachments/assets/5444d5ed-6252-4f89-86c0-1423271ed0da) <br>

- git push : berfungsi untuk mengupload yang telah dikerjakan pada VM ke git
- git pull : berfungsi untuk mengambil (fetch) dan menggabungkan (merge) perubahan terbaru dari repositori remote ke dalam repositori lokal Anda

  



