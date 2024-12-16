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
   - untuk mengubah url ssh menjadi git : set-url ".." <br>
   ![image](https://github.com/user-attachments/assets/f07daf64-31cc-4b2f-88dd-305683f3df5e) <br>
3.2 Cara Kerja Git menggunakan Command Git
- ssh -T git@github.com berfungsi untuk mengecek apakah ssh key yang telah di setting berhasil dilakukan pada VM dan git <br>
- .nama : berfungsi untuk mengasingkan file, dll. yang dimana perubahan yang dilakukan tidak akan terlihat pada saat melakukan git status
  ![image](https://github.com/user-attachments/assets/fa858274-74e6-4a47-acd2-a512046a4de9) <br>
- git log --oneline : menampilkan aktivitas dari vm yang telah melakukan penghapusan serta menampilkan ID <br>
- ssh-keygen : berfungsi untuk proses pengembalian data yang dihapus  <br>
- git checkout ID : untuk mengembalikan yang di hapus sebelumnya <br>
 ![image](https://github.com/user-attachments/assets/5444d5ed-6252-4f89-86c0-1423271ed0da) <br>
- git branch -a : berfungsi untuk melihat nama brach yg aktif <br>
![image](https://github.com/user-attachments/assets/066aed7e-39da-4aac-b013-0ba41122ca25) <br>
- git push : berfungsi untuk mengupload yang telah dikerjakan pada VM ke git dengan memanggil master dan nama branch <br>
  ![image](https://github.com/user-attachments/assets/b25ea2a3-4d64-47ab-8fec-0a5558ca84fe) <br>
- git pull : berfungsi untuk mengambil (fetch) dan menggabungkan (merge) perubahan terbaru dari repositori remote ke dalam repositori lokal <br>
![image](https://github.com/user-attachments/assets/ffb082c7-6b58-4b2b-b110-8121f6a66006) <br>

4. Study Case <br>
GIT INIT <br>
![image](https://github.com/user-attachments/assets/d49c2949-b75d-4bac-aed3-68419e8be8b9) <br>
MENGUBAH URL PROJECT DARI HTTP KE GIT <br>
![image](https://github.com/user-attachments/assets/647ab339-61b3-450c-b3d5-017280ef4ffa) <br>
MENAMBAHKAN FILE BERNAMA INDEX.HTML Di PUSH <br>
![image](https://github.com/user-attachments/assets/8a3a97c2-43ba-4af3-9f5a-a470c6cbcf07) <br>
![image](https://github.com/user-attachments/assets/431b3778-e772-4588-8c2b-2d33d1c4aa78) <br>
![image](https://github.com/user-attachments/assets/0b949f24-9316-4885-ae2a-aaa1d1ee60c7) <br>
![image](https://github.com/user-attachments/assets/3d0b194a-8e21-4205-a00c-6985b3bfb928) <br>

SETELAH DI PULL <br>
![image](https://github.com/user-attachments/assets/f826cb45-3d56-411e-bc45-c2b2b1691efb)







  



