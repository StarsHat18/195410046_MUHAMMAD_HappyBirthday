#195410046 MUHAMMAD DZUHRI ALAMSYAH
PERTEMUAN 3 sebelumnya disini dikarenakan PERTEMUAN 4 saya tidak sengaja push kedalam repo ini maka saya buat Pertemuan 4 disini

195410046_MUHAMMAD_HappyBirthday

MEMBUAT PROJEK PERTAMA HAPPY BIRTH DAY.APP
1. Buka adndroid studio 
	 ![Screenshot (97)](https://user-images.githubusercontent.com/89612818/134303453-955ad517-38ea-4c94-9814-b09bfac654f7.png)
2. klik new pjocet seperti gambar diatas.
3. didalam android studio terdapat berbagai tamplate untuk phone n tablet, wear os, android tv, dan aoutomotive
4. Kemudian akan muncul gambar seperti diatas kita memilih tamplate untuk pjocet kita, klik android dan tablet tab.
5. pilih empty activity lalu next
6. jika sudah di next maka akan keluar tampilan configur your pjocet
   ![Screenshot (99)](https://user-images.githubusercontent.com/89612818/134305795-75069e3c-db1e-49ad-9992-07f7df7ebce5.png)
   ikuti  _configurasi_ diatas
7. nama berfungsi untuk menamakan pjocet yang dibuat, isi nama dengan project **Happy Brithday**
8. _Package name_ di android studio kita membedakan nama aplikasi dengan unik biasanya default huruf kecil contoh seperti  **"com.example.happybirthday"**
9. _Save location_ adalah perintah untuk menyimpan pjocet didalam folder komputer kita, supaya memudahkan kita untuk menemukan folder project tersebut.
10. _Language_ mendefinisikan bahasa pemrograman mana yang anda gunakan untuk project yang anda buat, pastikan menggunakan bahasa kotlin.
11. _minimum SDK_ menunjukan versi menimum android, yang digunakan dalam aplikasi yang anda buat, pilih API android 4.4 KitKat
12. pastikan **use legacy android.support libraries**  tidak dicentang.
13. clik **finish**

15. tunggu android studio memproses project yang baru di buat jika sudah maka akan muncul gambar seperti dibawah ini
  ![Screenshot (100)](https://user-images.githubusercontent.com/89612818/134347696-f2d0b50d-8454-4273-a4df-8885cd36c516.png)


CARA MENJALANKAN APP DI EMULATOR ANDROID STUDIO
MEMBUAT ANDROID VIRTUAL DEVICE UNTUK MENJALANKAN APP
1. cari di menu bar tools kemudian **klik tools > AVD Manager**
![Screenshot (102)](https://user-images.githubusercontent.com/89612818/134348436-e111390c-6705-4fd8-ad8d-140498da5542.png)
2. klik **Create Cirtual Device**
![Screenshot (103)](https://user-images.githubusercontent.com/89612818/134348949-a69ac522-90b6-4590-9584-36a556145152.png)
3. terdapat banyak kategori hardware di emulator androind studio pilih **phone**
4. pilih hardware phone diprojek kali ini menggunakan **Nexus 5**, kemudian klik next
![Screenshot (104)](https://user-images.githubusercontent.com/89612818/134349334-59827f2e-5fa2-4069-a56e-6e1c5f524f81.png)
5. untuk system android kita gunakan category recomended, kita pilih **pie**, kemudian klik next
![Screenshot (105)](https://user-images.githubusercontent.com/89612818/134349720-fc26c374-60d0-43fc-8f5b-e83c08b0f2e4.png)
6. dibagian ini kita periksa apakah sudah sesuai dengan yang kita pilih sebelumnya dan beri nama AVD yang akan kita buat contoh disini menggunakan nama **Nexus Api 28 P3**
![Screenshot (106)](https://user-images.githubusercontent.com/89612818/134349982-5c0c8349-4845-4f82-93b0-6fd6684b368e.png)
7. klik **finish** hasil dari pembuatan AVD
![Screenshot (107)](https://user-images.githubusercontent.com/89612818/134350507-11dbb069-7d03-4e95-a942-498af654fe43.png)
8. kemudian tutup **Your Virtual Device** window

MENJALANKAN APP DI VIRTUAL DEVICE
1. cari ditools bar  temukan **virtual device dropdown** contoh seperti gambar berikut, kemudian pilih AVD yang sudah dibuat
![Screenshot (108)](https://user-images.githubusercontent.com/89612818/134351277-f6e2b20e-3314-4198-bb0d-64b5d91a9287.png)
2. klik **RUN**
3. Hasil dari Pjocet Happy Brithday memunculkan hello world
![Screenshot (109)](https://user-images.githubusercontent.com/89612818/134351763-73c30b59-ada7-4446-8262-3535203c25f0.png)


MENEMUKAN FILE PROJEK YANG SUDAH DIBUAT
1. jika kamu membuat folder pjocet didalam androidstudio maka buka folder androidstudio, kemudian cari folder bernama Happy Brithday yang sudah kita buat
 ![Screenshot (110)](https://user-images.githubusercontent.com/89612818/134352136-aff1b18a-de90-4066-9e93-90a87ca96d4e.png)


++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
PERTEMUAN 4
Pertama kita buat project seperti pertemuan 3 sebelumnya kemudian :

https://developer.android.com/codelabs/basic-android-kotlin-training-birthday-card-app?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fandroid-basics-kotlin-three%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fbasic-android-kotlin-training-birthday-card-app#1

**Mengubah pesan Hello World (Halo Dunia)**
1. Di Android Studio, temukan jendela Project di sebelah kiri.
2. Perhatikan folder dan file berikut: Folder **app** berisi sebagian besar file untuk aplikasi yang akan Anda ubah. Folder res ditujukan untuk 	resource, seperti gambar atau tata letak layar. Folder **layout** ditujukan untuk tata letak layar. File _**activity_main.xml**_ berisi deskripsi tata letak layar Anda.
3. Luaskan folder **app**, lalu folder **res**, dan selanjutnya folder **layout**.
4. Klik dua kali pada _**activity_main.xml**_. Tindakan ini akan membuka _**activity_main.xml** _ di layout Editor dan menampilkan tata letak yang dideskripsikan dalam tampilan Design.

![Screenshot (143)](https://user-images.githubusercontent.com/89612818/136321859-aa5a124e-3837-4588-8308-911251a6b958.png)

Catatan: Dalam codelab ini, Anda akan sering diminta untuk membuka file seperti di langkah sebelumnya. Sederhananya, langkah-langkah tersebut dapat dipersingkat menjadi: Buka **activity_main.xml (res > layout > activity_main.xml)** alih-alih mencantumkan setiap langkah secara terpisah.

5. Lihat daftar tampilan di **Component Tree**. Perhatikan bahwa ada **ConstraintLayout** dan **TextView** di bawahnya. Keduanya mewakili UI aplikasi Anda. **TextView** diindentasi karena berada di dalam **ConstraintLayout**. Saat Anda menambahkan lebih banyak **Views** ke **ConstraintLayout**, **Views** akan ditambahkan ke daftar ini.
6. Perhatikan bahwa **TextView** berisi "Hello World!" (Halo Dunia!) di sebelahnya, yaitu teks yang Anda lihat saat menjalankan aplikasi.
![Screenshot (143)](https://user-images.githubusercontent.com/89612818/136322102-93437c4a-8fe0-4719-94e9-02f8b47e14e0.png)

7. Di **Component Tree**, klik **TextView**.
8. Cari **Attributes** di sebelah kanan.
9. Cari bagian **Declared Attributes**.
10. Perhatikan bahwa atribut **text** di bagian **Declared Attributes** berisi **Hello World!** (Halo Dunia!).
![Screenshot (168)](https://user-images.githubusercontent.com/89612818/136322290-1531427e-c28b-4933-9b4c-6c4019bed87f.png)

Atribut **text** menampilkan teks yang dicetak di dalam **TextView**.

11. Klik atribut **text** yang menampilkan teks **Hello World!** (Halo Dunia!).
12. Ubah menjadi **Happy Brithday!**, lalu tekan tombol **Enter**. Jika Anda kemudian melihat peringatan tentang string yang di-hardcode, jangan khawatir. Anda akan mempelajari cara menghapus peringatan tersebut di codelab berikutnya.
13. Perhatikan bahwa teks di Design View telah berubah.....(Bagus! Anda bisa langsung melihat perubahannya)
14. Jalankan aplikasi, dan sekarang Anda melihat teks **Happy Brithday!** 
![Screenshot (145)](https://user-images.githubusercontent.com/89612818/136322770-b9fa437e-6d2e-4149-9fde-b7260c6e8d60.png)
lupa ss hasil seperti berikut harusnya
![233655306db5a589](https://user-images.githubusercontent.com/89612818/136322839-5c62be2c-4431-45e7-8cf1-8997d80bf815.png)
Bagus! Anda membuat perubahan pertama pada aplikasi Android.

**Menambahkan TextView ke tata letak**
Kartu ulang tahun yang sedang Anda buat tampak berbeda dengan kartu yang ada di aplikasi. Sebagai ganti teks kecil di tengah, Anda memerlukan dua pesan yang berukuran lebih besar: satu di kiri atas dan satu di pojok kanan bawah. Dalam tugas ini, Anda akan menghapus TextView yang ada, dan menambahkan dua TextViews baru, serta mempelajari cara memosisikannya di dalam ConstraintLayout.
**Menghapus TextView saat ini**
1. Di Layout Editor, klik untuk memilih **TextView** di bagian tengah tata letak.
 ![delete](https://user-images.githubusercontent.com/89612818/136324488-49cb90ce-fd8d-447c-9535-8b07db6b83c0.png)
3. Tekan tombol **Delete**. Android Studio akan menghapus **TextView**, dan sekarang aplikasi Anda hanya menampilkan **ConstraintLayout** di **Layout Editor** dan **Component Tree**.

**Menambahkan TextView**
Pada langkah ini, Anda akan menambahkan **TextView** di kiri atas aplikasi untuk menampung ucapan selamat ulang tahun.
![Screenshot (169)](https://user-images.githubusercontent.com/89612818/136324662-a44a2bb7-874b-4f93-8e0c-e971fe5e76a7.png)

**Palette** di kiri atas **Layout Editor** berisi daftar berbagai jenis **Views**, yang disusun berdasarkan kategori, yang dapat Anda tambahkan ke aplikasi
1. Cari **TextView**. Kode ini muncul dalam kategori **Common** dan kategori **Text**.
![palette](https://user-images.githubusercontent.com/89612818/136325477-09bc2046-70d4-41cc-b08d-7ec1cc4541b4.png)

2. Tarik **TextView** dari **Palette** ke kiri atas permukaan desain di **Layout Editor** dan letakkan. Posisinya tidak harus sama persis, cukup letakkan di dekat sudut kiri atas.
![tariktextview](https://user-images.githubusercontent.com/89612818/136325730-df36954a-65f5-419e-acb9-91eb31e8ab33.png)

3. Perhatikan bahwa ada TextView yang ditambahkan, dan perhatikan tanda seru berwarna merah di Component Tree.
4. Arahkan kursor ke tanda seru, dan Anda akan melihat pesan yang berisi peringatan bahwa tampilan tidak dibatasi dan akan melompat ke posisi yang berbeda saat aplikasi dijalankan. Anda akan memperbaikinya di langkah berikutnya.

**Memosisikan TextView**
Untuk kartu ulang tahun, **TextView** harus berada di dekat sudut kiri atas dengan ruang di sekitarnya. Untuk memperbaiki peringatan, Anda perlu menambahkan beberapa batasan ke **TextView** sehingga aplikasi akan tahu cara memosisikannya. Batasan terdiri dari arah dan batas agar **View** dapat berada di dalam tata letak.

Batasan yang Anda tambahkan ke atas dan kiri akan memiliki margin. Margin menentukan seberapa jauh jarak **View** dari tepi penampungnya.
![hbd](https://user-images.githubusercontent.com/89612818/136326002-11a3cd47-51d8-4d1b-a8dd-af73ea324fb8.png)

1. Di Attributes di sebelah kanan, cari Constraint Widget di bagian Layout. Gambar persegi yang muncul mewakili tampilan Anda.
![layout](https://user-images.githubusercontent.com/89612818/136326215-f0058be5-9482-4ef9-9dba-2ac5677be529.png)
2. Klik tanda + di bagian atas kotak. Ini untuk batasan antara bagian atas tampilan teks dan tepi atas tata letak batasan.
3. Kolom berisi angka akan muncul untuk menyetel margin atas. Margin adalah jarak dari TextView ke tepi penampung, yaitu ConstraintLayout. Angka yang muncul akan berbeda mengikuti posisi Anda meletakkan TextView. Saat Anda menyetel margin atas, Android Studio secara otomatis juga menambahkan batasan dari bagian atas tampilan teks ke bagian atas ConstrainLayout.
![layout](https://user-images.githubusercontent.com/89612818/136326215-f0058be5-9482-4ef9-9dba-2ac5677be529.png)
4. Ubah margin atas menjadi 16.
5. Lakukan hal yang sama untuk margin kiri.
6. Atur text untuk mengucapkan selamat ulang tahun kepada teman, misalnya **"Happy Brithday, Alam!"** lalu tekan tombol Enter
![declared](https://user-images.githubusercontent.com/89612818/136326697-f1a739e5-e71c-48b9-b793-2a15f6e0aa22.png)
7. Perhatikan bahwa tampilan Design akan diperbarui untuk memperlihatkan tampilan terkini aplikasi Anda. 
![hbd](https://user-images.githubusercontent.com/89612818/136326002-11a3cd47-51d8-4d1b-a8dd-af73ea324fb8.png)

**Menambahkan dan memosisikan TextView lain**
Kartu ulang tahun Anda memerlukan baris teks kedua di dekat pojok kanan bawah, yang akan Anda tambahkan di langkah ini menggunakan cara yang sama seperti di tugas sebelumnya. Menurut Anda bagaimana margin TextView ini?

1. Tarik TextView baru dari Palette dan letakkan di dekat bagian kanan bawah tampilan aplikasi di Layout Editor.
![image](https://user-images.githubusercontent.com/89612818/136327588-2a3fc7c1-1825-4f51-82e5-743d3987d037.png)
2. Tetapkan margin kanan ke 16.
3. Tetapkan margin bawah ke 16. 
![layout1](https://user-images.githubusercontent.com/89612818/136327446-c6ffce5f-bf37-49b4-a5ee-fcedbc0a5a1a.png)
4. Di **Attributes**, tetapkan atribut text untuk menandatangani kartu, misalnya "**FROM Dzuhri**".
5. Jalankan aplikasi dan Anda akan melihat ucapan selamat ulang tahun di kiri atas dan tanda tangan di kanan bawah.
![output hbdalamfrom](https://user-images.githubusercontent.com/89612818/136327018-27cefc28-b8ed-4fc1-93d4-fafe8d4f1b99.png)
