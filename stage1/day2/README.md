## DAY 2

# Linux Command
1. sudo snap install multipass berfungsi untuk menginstal multipass menggunanakan snap 
2. multipass launch berfungsi untuk membuat instansi VM baru <br>
   ![image](https://github.com/user-attachments/assets/d83ee977-6110-416f-9d6c-dd1215249b7f)
3. multipass ls berfungsi untuk menampikan multipass yang ada
   ![image](https://github.com/user-attachments/assets/a545f4b9-ee5f-4e27-8e0f-638429d3457a)
4. multipas shell berfungsi untuk mengarahkan instansi VM yang telah dibuat dengan menuliskan nama multipass yang terdaftar <br>
   ![image](https://github.com/user-attachments/assets/a339e61b-b51a-4073-8c5d-072a21cca887)
5. sudo adalah super user utama di linux server
6. sudo apt update berfungsi memperbarui daftar paket <br>
    ![image](https://github.com/user-attachments/assets/740e8179-0ed5-4966-8d34-d877ec5fb086)   
7. sudo apt update berfungsi untuk memperbarui paket ke versi terbaru <br>
    ![image](https://github.com/user-attachments/assets/c7a9ef12-084c-4379-9d29-8760488d7484)
8. ![image](https://github.com/user-attachments/assets/c8cc9551-573c-4c44-8571-fa3f22ae6126) berfungsi untuk mengubah direktori kerja <br>
    ![image](https://github.com/user-attachments/assets/7a452e0a-ff3d-4f8e-909b-356f124abc46)
9. ls berfungsi untuk menampilkan directori, penulisan directori tidak boleh ada spasi 
10. mkdir berfungsi untuk membuat directori <br>
    ![image](https://github.com/user-attachments/assets/205e0b2b-5bd0-4b69-8cc4-466522fe8cca)
11. rmdir berfungsi untuk menghapus directori, dapat menghapus lebih dari satu directori <br>
    ![image](https://github.com/user-attachments/assets/c12ec946-9f28-4aa3-afe3-cdf9194176df)
12. fungsi titik sebelum nama directori bersifat hidden dan untuk melihat mkdir yang di hidden : la  <br>
    ![image](https://github.com/user-attachments/assets/e6623a15-3471-4344-9f2e-4e9a1bbc1b8d)
13. membuat file di dalam file mkdir arahkan nama direktori yang diinginkan kemudian ls <br>
    ![image](https://github.com/user-attachments/assets/8531f2ab-7176-4341-a753-48c911e3d2ff)
14. pwd berfungsi untuk menampilkan direktori kerja saat ini <br>
    ![image](https://github.com/user-attachments/assets/63296b16-ddf9-431b-97a0-415730c39829)
15. jika nama direktori diawali dengan (/) itu berada di root <br>
    ![image](https://github.com/user-attachments/assets/fc3dd65c-433a-47d3-b8f8-15ba350b4236)
    ![image](https://github.com/user-attachments/assets/772c6eb7-58f8-4407-b4d2-5b8b6d2e3045)
16. untuk kembali ke directori sebelumnya dengan cara cd .. yang dimana titik satu menandakan lokasi saat ini dan titik satu lagi memerintahkan untuk keluar dari directory saat ini <br>
    ![image](https://github.com/user-attachments/assets/83e73abf-36cd-4074-b9cf-a57c2a7f3f9d)
17. untuk keluar dari dua directori sekaligus : cd ../.. <br>
    ![image](https://github.com/user-attachments/assets/00b8e573-cf0a-49f6-80ed-bbb2b0b038f2)
18. warna putih adalah file warna biru adalah directory, jika ingin mengakses file menggunakan : vim atau nano <br> jika ingin mengakses directory cd <br>
    ![image](https://github.com/user-attachments/assets/40f7d79f-ebf2-4291-b2b9-855040460cab)
19. touch berfungsi untuk menambahkan file <br?
    ![image](https://github.com/user-attachments/assets/71bb95df-e722-4753-a5eb-ecfb4ab862ba)
20. touch berfungsi jika ingin memasukkan satu file hingga banyak file ke dalam directory dapat digunakan secara bersamaan misal ingin memasukkan file lol kedalam direktori testing01 : touch testingo1/lol <br>
    ![image](https://github.com/user-attachments/assets/991d7e1d-2f8d-49c9-9cf2-1a25f99b3b97)
21. rm berfungsi untuk menghapus satu file hingga banyak file <br>
    ![image](https://github.com/user-attachments/assets/abfa4161-3f59-495f-b212-c5df7f2e3f4a)
22. rm -rf r directori f force berfungsi untuk menghapus directori yang memiliki isi <br>
    ![image](https://github.com/user-attachments/assets/64fb0b21-f140-40ed-a6ce-723cb8e7646f)
23. nano berfungsi untuk menambahkan teks ke sebuah file
    ![image](https://github.com/user-attachments/assets/42b29c1d-d59b-4711-82d5-8a36a4355bff)
    ![image](https://github.com/user-attachments/assets/0e9f64e0-f045-4006-9a55-8666b9849e4f)
24. cat berfungsi untuk menampilkan teks yang ada dalam file <br>
    ![image](https://github.com/user-attachments/assets/cb3b2109-23f2-4f71-bed9-91174261e072)
25. cp berfungsi untuk mengcopy isi dari suatu file ke file lainnya, kalau dari file ke direktori dapat di copy langsung apabila dari directori ke directori maka harus menambahkan -r <br>
    ![image](https://github.com/user-attachments/assets/7063f282-0796-4bc8-adc0-a2a4ea31d424) <br>
    ![image](https://github.com/user-attachments/assets/cd4048f7-5a00-45cb-8463-b3e110b3cee7) <br>
    ![image](https://github.com/user-attachments/assets/aa64a562-668b-4c8a-a22b-8f0db3f1995c)
26. mv berfungsi untuk Memindahkan atau mengganti nama file/folder, apabila ingin memindahkan direktori ke file atau file ke directory harus satu directory atau dapat mundur dengan ../nama directory yang dituju <br>
    ![image](https://github.com/user-attachments/assets/2d575625-c4c5-4412-8fa1-59afb607255d) <br>
    ![image](https://github.com/user-attachments/assets/3bb53637-9a5c-4e36-a8c4-2bc1b19c165f) <br>
    me rename file satu directory <br>
    ![image](https://github.com/user-attachments/assets/4fe6828d-ea8e-41f9-a0c8-e80ac2d0617b) <br>
    mengubah nama direktori <br> ![image](https://github.com/user-attachments/assets/cbb034a4-21c6-4f2c-a280-fc64b04b63d1) <br>
    merename sekaligus mengubah nama pada direktori 1 ke direktori 2 <br> ![image](https://github.com/user-attachments/assets/655cfa3b-11c4-4ca5-b83e-990b689024bd)

27. echo berfungsi untuk menampilkan teks atau output <br>
    ![image](https://github.com/user-attachments/assets/93470678-eb27-46b7-893e-8a9109714fd3)
28. > berfungsi untuk menyalin teks kedalam file baru <br>
    ![image](https://github.com/user-attachments/assets/4ee83106-e744-4b13-be1c-49082199ec13)
29. >> berfungsi untuk menambahkan teks ke suatu file <br>
    ![image](https://github.com/user-attachments/assets/b7daf304-d373-40f0-844e-09116fdb35b2)
30. find berfungsi untuk mencari file atau direktori berdasarkan kriteria tertentu di dalam sistem file dengan script : find -type f -name ... -> nama file yang ingin dicari jika directori huruf f berubah menjadi huruf d <br>
    ![image](https://github.com/user-attachments/assets/a9f9d305-c40f-407d-b3e8-1addd93a386f)
31. grep berfungsi untuk encari teks atau pola tertentu dalam file atau output dari perintah lain <br>
    ![image](https://github.com/user-attachments/assets/e8ce4ada-adac-4e4d-8845-e3629ed20221) <br>
    ![image](https://github.com/user-attachments/assets/ceb1de72-f199-4034-b352-71278df254c9)
32. history berfungsi untuk melihat perintah yang telah dijalankan <br>
    ![image](https://github.com/user-attachments/assets/4a8b53e0-c9d0-4764-8d7d-1dfeb46fe91b) <br>
33. history | grep untuk mencari perintah tertentu dalam riwayat perintah shell Anda dengan spesifik <br>
    ![image](https://github.com/user-attachments/assets/c6be6d3a-9e52-4648-94d6-9d33721b5d4e)
34. chmod berfungsi untuk mengubah hak akses (permissions) file atau direktori <br>
    d : directory <br>
    r : read 4 <br>
    w : write 2 <br>
    x : execuse 1 <br>
    -r untuk menghilangkan akses read  <br> ![image](https://github.com/user-attachments/assets/62b4fdcb-81bb-4597-9c28-377e9708370e) <br>
    +r untuk mengembalikan akses read <br>  ![image](https://github.com/user-attachments/assets/cd100f44-da36-4a19-9f17-f8cae81ce75b)
    -w untuk menghilangkan akses write <br> ![image](https://github.com/user-attachments/assets/677613cc-784a-48b7-8a73-3c896507f363) <br>
       ![image](https://github.com/user-attachments/assets/39cc4a3f-93c0-46d6-b641-f741342bcbcf) <br>
    +w untuk mengembalikan akses write <br>  ![image](https://github.com/user-attachments/assets/4204d162-b5d4-4ab8-8b81-ab0463154d9e)
       <br> ![image](https://github.com/user-attachments/assets/ecb70cdf-6a52-42c5-8331-e7036edc5ae1) <br>
      +x berfungsi untuk menambahkan execuse pada directori tanda direktori yang dapat di eksekusi adalah file warna hijau memiliki execuse <br> ![image](https://github.com/user-attachments/assets/28415468-9e37-4b8f-87e8-24ca404b3bd1) <br>
      -x berfungsi untuk menghilangkan execuse directori <br> ![image](https://github.com/user-attachments/assets/760f3676-2804-46c1-8efc-8dea4e955bd1) <br>
35. chmod dengan angka <br>
![image](https://github.com/user-attachments/assets/53dbfa34-7eeb-46a1-9a1d-973f48448682) <br>
36. rwxrwxrwx sepasang rwx memiliki permission fungsi <br>
rwx 1 sebagai user <br>
rwx 2 sebagai group <br>
rwx 3 sebagai others <br>
jika ingin memberikan complete permission dengan angka dapat menjumlahkan angka write, read, execuse = 7 <br>
![image](https://github.com/user-attachments/assets/d9efbb67-1a92-4341-888a-4f7366407984) <br>
37. chow berfungsi mengubah kepemilikan directory <br> ![image](https://github.com/user-attachments/assets/6379f3d0-8a1b-4df2-9ef8-d5a46ef78611) <br> 






      
    



36. 




    







