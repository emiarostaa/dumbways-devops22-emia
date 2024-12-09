## Day1

# 1. Deffinisi DevOpas 
DevOps adalah perantara dari programer dan Sistem operasi dari sebuah aplikasi yang berguna untuk mempercepat atau melancarkan suatu peroses dalam aplikasi dimana DevOps memiliki beberapa bagian :
1. Plan : mengikuti planning yang dirancang oleh tim dev
2. code : menentukan bahasa programer yang digunakan, melakukan coding jika diperlukan minimal memahami arti dari sourcecode yang dibuat dari development 
3. build : membangun sebuah aplikasi
4. test : menguji sebuah aplikasi
5. release : alat yang siap uji dirilis ke publik
6. Deploy : aplikasi diimplementasikan di lingkungan produksi
7. monitor : untuk memantau masalah atau mendeteksi masalah yang perlu ditingkatkan <br>
kesimpulannya DevOps akan mengikuti dari Plan hingga test dengan Development team dan mengikuti Release hingga monitor yang dalam pembuatan sistem operasi yang bekerja secara otomatis untuk perbaharuan sistem dan lainnya. Dapat juga dikatakan Development team adalah Continous Intergration (CI)  dan Operation team adalah Continous Delivery (CD) <br>
![image](https://github.com/user-attachments/assets/12278286-afb8-4e36-9870-d6392fa422cb) <br>

DevOps dibutuhkan karena bisa membuat otomatis sebuah pekerjaan Seluruh proses devops dibuat secara otomatis ke dalam CICD agar
•	Mempercepat release ke public
•	Menurunkan tingkat kegagalan pada rilisan terbaru
•	Mempersingkat waktu perbaikan
Ngoding lebih ke script 

# Virtual Machine
Operating System
Virtual adalah teknologi yang dapat membagi resource besar menjadi lebih kecil. 
Kita bisa mempecah jadi kecil2 suatu resourc
Hypervisor adlh suatu program utk membuat dan menjalankan virtual macine
Virtual machine adalah sistem operasi command yang berjalan di ubuntu 
Lsb_release -a cek versi ubuntu
Dr -h
Struktur virtualization
![image](https://github.com/user-attachments/assets/d617ce80-c90b-4f52-b93e-59f84dabfd12) <br>

Ip Bersifat Statik Itu Terus 
DHCP Alamat IP Berubah-Ubah Nomornya
Statik Alamat Ip Tdk Berubah-Ubah Dari Multipas

Release 
DHCP Dinamik Digunakan Para Kantoran Dan Rumahan 

Static Lebih Cocok Utk Membuat Server Karena Di Dlm Server Melakukan Konfigurasi Yg Diarahkan Ke Server tersebut

langkah-langkah membuat vvirtual machine : 
1. sudo snap install multipass berfungsi untuk menginstal multipass
2. multipass version berfungsi untuk melihat versi dari multipass
3. multipass launch --name berfungsi untuk membuat multipass yang baru
4. multipass list berfungsi untuk melihat multipass yang telah ada pada vm
5. multipass shell myname vm berfungsi untuk masuk ke multipass
6. multipass start berfungsi untuk ketika multipass berhenti dapat dijalankan kembali dengan multipass start
7. multipass stop myname vm untuk menghentikan multipass
8. multipass delete myname vm untuk menghapus multipass yang sudah ada
9. multipass vurge myname vm untuk memberssihkan Vm yang sudah dihapus
10. multipass find untuk menjalankan mesin virtual Ubuntu secara cepat dan mudah di atas sistem host mereka <br>
   ![image](https://github.com/user-attachments/assets/1d96135f-f134-4e16-a6db-352d4e603e9f) <br>

11. multipass launch berfungsi untuk membuat instansi VM baru <br>
   ![image](https://github.com/user-attachments/assets/d83ee977-6110-416f-9d6c-dd1215249b7f) 
12. multipass ls berfungsi untuk menampikan multipass yang ada
   ![image](https://github.com/user-attachments/assets/a545f4b9-ee5f-4e27-8e0f-638429d3457a)
13. multipas shell berfungsi untuk mengarahkan instansi VM yang telah dibuat dengan menuliskan nama multipass yang terdaftar <br>
   ![image](https://github.com/user-attachments/assets/a339e61b-b51a-4073-8c5d-072a21cca887)
14. sudo adalah super user utama di linux server
15. sudo apt update berfungsi memperbarui daftar paket <br>
    ![image](https://github.com/user-attachments/assets/740e8179-0ed5-4966-8d34-d877ec5fb086)   
16. sudo apt update berfungsi untuk memperbarui paket ke versi terbaru <br>
    ![image](https://github.com/user-attachments/assets/c7a9ef12-084c-4379-9d29-8760488d7484)








