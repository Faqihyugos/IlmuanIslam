# IlmuanIslam
App sejarah ilmuan islam sederhana

## Cara Build :
1. Buat Project baru di Android Studio dengan cara klik File -> Project Baru.
ketika diminta untuk memilih Default Activity, Pilih Empaty Activity dan klik next.
Untuk minSDK, disini menggunakan set API 21.

2. Kemudian import beberapa library ke gradel source : [build.gradle](https://github.com/Faqihyugos/IlmuanIslam/blob/master/app/build.gradle)

3. Kamu ubah juga isi  **Android Manifest.xml** menjadi seperti source berikut : [Android Manifest.xml](https://github.com/Faqihyugos/IlmuanIslam/blob/master/app/src/main/AndroidManifest.xml)

4. kemudian kamu ubah file **activity_main.xml** dan **MainActivity.java** untuk menu utama menampilkan daftar ilmuan. source : [activity_main.xml](https://github.com/Faqihyugos/IlmuanIslam/blob/master/app/src/main/res/layout/activity_main.xml) dan [MainActivity.java](https://github.com/Faqihyugos/IlmuanIslam/blob/master/app/src/main/java/com/faqih/ilmuanislam/activities/MainActivity.java)

5. kemudian kamu buat menu detial file **activity_detail.xml** dan **DetailActivity.java** untuk menu utama menampilkan detail para ilmuan. source : [activity_detail.xml](https://github.com/Faqihyugos/IlmuanIslam/blob/master/app/src/main/res/layout/activity_detail.xml) dan [DetailActivity.java](https://github.com/Faqihyugos/IlmuanIslam/blob/master/app/src/main/java/com/faqih/ilmuanislam/activities/DetailActivity.java)

6. Buat menu intro untuk SplashScreen. Buat file **activity_intro.xml** dan **IntroActivity.java** untuk menu utama menampilkan detail para ilmuan. source : [activity_intro.xml](https://github.com/Faqihyugos/IlmuanIslam/blob/master/app/src/main/res/layout/activity_intro.xml) dan [IntroActivity.java](https://github.com/Faqihyugos/IlmuanIslam/blob/master/app/src/main/java/com/faqih/ilmuanislam/activities/IntroActivity.java)

7. Berikutnya buat Class Adapter untuk menampilkan daftar nama para ilmuan ke menu utama. Buat file **item_row_main.xml** dan **MainAdapter.java**. source : [item_row_main.xml](https://github.com/Faqihyugos/IlmuanIslam/blob/master/app/src/main/res/layout/item_row_main.xml) dan [MainAdapter.java](https://github.com/Faqihyugos/IlmuanIslam/blob/master/app/src/main/java/com/faqih/ilmuanislam/adapter/MainAdapter.java)

8. Buat Class Data **MainData.java**. Class ini berisi semua detail dari para ilmuan, seperti sejarah, foto dll.source : [MainData.Java](https://github.com/Faqihyugos/IlmuanIslam/blob/master/app/src/main/java/com/faqih/ilmuanislam/data/MainData.java) 

9. Buat Class Model **MainModel.java**. Model ini berguna untuk support atau decoration dari Class Adapter. Source : [MainModel.java](https://github.com/Faqihyugos/IlmuanIslam/blob/master/app/src/main/java/com/faqih/ilmuanislam/model/MainModel.java)

10. Buat Class Support ItemClickSupport.java. Class ini berguna untuk support atau decoration dari class adapter. source : [ItemClickSupport.java](https://github.com/Faqihyugos/IlmuanIslam/blob/master/app/src/main/java/com/faqih/ilmuanislam/support/ItemClickSupport.java)

Sisa nya liat dan download source code ini selamat ber-explorasi

* Bisa langsung dicoba apk hasilnya : [apk](https://github.com/Faqihyugos/IlmuanIslam/tree/master/outputs/apk/debug)

### Selesai terimakasih.
### Anggota kelompok tugas android studio : 
1. Faqih Yugo Susilo (10417082)
2. Steven Sebastian S (10417154)
3. Rizky Pratama (10417093)
4. Dessy Santi Megawati (10417047)
5. Siti Raisyah I.B (10417055)
