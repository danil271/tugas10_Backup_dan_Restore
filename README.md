Nama : Danil Bahri Tanjung
Nim : 311910391
Kelas : TI.19.B2

Backup dan Restore Menggunakan Perintah SQL
Masuk kedalam database
![image](https://user-images.githubusercontent.com/81598231/123588844-9540e080-d812-11eb-975f-242f03a4cf26.png)
![image](https://user-images.githubusercontent.com/81598231/123588932-b43f7280-d812-11eb-88a5-21721be633ee.png)
Lakukan proses penguncian table.
![image](https://user-images.githubusercontent.com/81598231/123589244-23b56200-d813-11eb-9154-9944f416f46b.png)
Lakukan proses backup table dengan perintah : SELECT * INTO OUTFILE
![image](https://user-images.githubusercontent.com/81598231/123589414-670fd080-d813-11eb-8519-77ee95080fe5.png)
Data yang telah di-backup dapat dikembalikan kapan saja bila diperlukan. Sintaks SQL yang digunakan
adalah LOAD DATA INFILE. Perintah yang dijalankan adalah
![image](https://user-images.githubusercontent.com/81598231/123589589-ab9b6c00-d813-11eb-89e8-a3fd04befbda.png)
![image](https://user-images.githubusercontent.com/81598231/123590106-6592d800-d814-11eb-98b1-892895051c37.png)
Data yang telah di-backup dapat dikembalikan kapan saja bila diperlukan. Sintaks SQL yang digunakan
adalah LOAD DATA INFILE. Perintah yang dijalankan adalah
![image](https://user-images.githubusercontent.com/81598231/123590990-a9d2a800-d815-11eb-8503-295d69c3034d.png)
Menuju ke folder aplikasi mysqldump di xamp/mysql/bin
Jalankan shell atau commad-prompt dan ketikkan perintah berikut untuk memulai dump database :
MySQLDUMP –u root –p –alldatabase
![image](https://user-images.githubusercontent.com/81598231/123591819-a8ee4600-d816-11eb-94ed-ff3819265493.png)
