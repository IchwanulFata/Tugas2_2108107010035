1. Cara Menjalankan Kode Program
Untuk menjalankan kode program tersebut dapat menggunakan platform Google Colaboratory. Adapun langkah-langkah dalam menjalankan kode program tersebut yaitu :
>> Download file .ipynb yang ada pada repository
>> Ekspor file yang telah didownload ke dalam Google Drive
>> Klik kanan pada file yang telah diupload, klik open with dan pilih Google Colaboratory
>> Klik button run cell yang berada di sebelah kiri cell untuk tiap-tiap cell yang ada pada file tersebut
>> Output dari kode program akan ditampilkan dibagian bawah tiap-tiap cell
   
2. Penjelasan Dataset
# KLASIFIKASI (SVM)
Untuk melakukan klasifikasi menggunakan SVM, saya menggunakan dataset rice (Cammeo and Osmancik). Pada dataset ini memiliki 8 kolom yaitu :
1. Area : Jumlah piksel dalam batas butir beras
2. Perimeter : Menghitung keliling dengan menghitung jarak antar piksel di sekitar batas butiran beras
3. Major_Axis_Length : Garis terpanjang yang dapat ditarik pada butiran beras, yaitu jarak sumbu utama
4. Minor_Axis_Length : Garis terpendek yang dapat digambar pada butiran beras, yaitu jarak sumbu yang kecil, 
5. Eccentricity : Mengukur seberapa bulat elips, yang memiliki momen yang sama dengan butiran beras
6. Convex_Area : Jumlah piksel cangkang cembung terkecil di wilayah yang dibentuk oleh butiran beras
7. Extent : Rasio wilayah yang dibentuk oleh butiran beras terhadap kotak pembatas
8. Class : Label yaitu Cammeo dan Osmancik
Dari keseluruhan kolom saya menggunakan kolom Area dan Perimeter sebagai atribut/fitur. Dataset tersebut memiliki label yaitu pada kolom Class. Dataset memiliki jumlah field sebanyak 3810.
Link sumber dataset : https://archive.ics.uci.edu/dataset/545/rice+cammeo+and+osmancik
 
# REGRESI (SVR)
Untuk melakukan pemodelan regresi menggunakan SVR, saya menggunakan dataset Stroke Prediction. Pada dataset ini memiliki 12 kolom yaitu :
1. id : Identifier yang unik
2. gender : Jenis Kelamin
3. age : Umur
4. hypertension : Menderita hipertensi atau tidak
5. heart_disease : Mengidap penyakit jantung atau tidak
6. ever_married : Status Pernikahan ( Ya atau Tidak)
7. work_type : Tipe Pekerjaan
8. residence_type : TIpe Tempat Tinggal
9. avg_glucose_level : Rata-rata kadar glukosa dalam darah
10. bmi : Body mass index / indeks massa tubuh
11. smooking_status : Status merokok
12. stroke : Terkena Stroke atau tidak
Dari keseluruhan kolom yang ada pada dataset tersebut saya hanya menggunakan dua kolom yakni kolom BMI dan avg_glucose_level. Dataset tersebut memiliki jumlah field sebanyak 5110.
Link Sumber Dataset : https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset
