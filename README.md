# project-insurance

## Background Project 
Asuransi kesehatan adalah salah satu hal yang patut diperhatikan karena bersangkutan dengan
kebutuhan perencanaan masa depan. Pengguna asuransi kesehatan diwajibkan untuk
membayar besaran uang secara rutin (premi) kepada pihak perusahaan asuransi. Premi
tersebut diolah oleh perusahaan asuransi untuk membayarkan tagihan kesehatan pengguna
yang tertanggung. Penentuan nilai premi menjadi tantangan tersendiri bagi pihak asuransi
mengingat ada banyak faktor yang dapat mempengaruhi & meningkatkan profil resiko
pengguna.
Melalui project ini, Anda akan diminta untuk membantu menganalisa variable-variabel yang
memiliki hubungan dengan tagihan kesehatan yang diterima oleh setiap pengguna. Anda akan
diberikan data yang berisi data personal pengguna seperti umur, gender, tempat tinggal
pengguna, banyak anak tertanggung asuransi, nilai bmi, keadaan merokok atau tidaknya
pengguna.

## Petunjuk Analisa
Dengan menggunakan dasar ilmu probability, anda diharapkan dapat melakukan analisa secara scientifics untuk mencari variabel-variabel yang berhubungan dengan tagihan kesehatan.

## Langkah #1 - Analisa Descriptive Statistic
Kita awali proses analisa ini dengan hal yang paling dasar, yakni merangkum karakter-karakter
berdasarkan data seperti mencari rata-rata & persebaran data. Anda bisa memilih 5 pertanyaan
dibawah ini untuk melakukan eksplorasi data. Beberapa hal yang dapat Anda jawab adalah
1. Rata-rata umur pengguna
2. Rata-rata nilai BMI dari pengguna yang merokok
3. Berapa rata rata umur pada data tersebut?
4. Berapa rata rata nilai BMI dari yang merokok?
5. Apakah variansi dari data charges perokok dan non perokok sama?
6. Apakah rata rata umur perempuan dan laki-laki yang merokok sama?
7. Mana yang lebih tinggi, rata rata tagihan kesehatan perokok atau non merokok?
8. Mana yang lebih tinggi, rata rata tagihan kesehatan perokok yang BMI nya diatas 25
atau non perokok yang BMI nya diatas 25
9. BMI mana yang lebih tinggi, seseorang laki-laki atau perempuan?
10. BMI mana yang lebih tinggi, seseorang perokok atau non perokok?

## Langkah #2 - Analisa Variabel Kategorik (PMF)
Selanjutnya, untuk memperdalam analisa, Anda dapat mengidentifikasi peluang kondisi tertentu yang berpotensi memiliki besaran tagihan kesehatan tertentu. Anda bisa memilih 5 pertanyaan dibawah ini untuk pengecekan kondisi pada data. Beberapa hal yang dapat Anda jawab adalah
1. Gender mana yang memiliki tagihan paling tinggi?
2. Distribusi peluang tagihan di tiap-tiap region
3. Apakah setiap region memiliki proporsi data banyak orang yang sama?
4. Mana yang lebih tinggi proporsi perokok atau non perokok?
5. Berapa peluang seseorang tersebut adalah perempuan diketahui dia adalah perokok?
6. Berapa peluang seseorang tersebut adalah laki-laki diketahui dia adalah perokok?
7. Bagaimana bentuk distribusi tagihan dari tiap-tiap region?

## Langkah #3 - Analisa Variabel Kontinu (CDF)
Variabel dalam data yang kita punya tidak semuanya berbentuk kategorik, untuk memahami kemungkinan kondisi variabel bernilai kontinu terhadap tagihan kesehatan, kita bisa melakukan analisa CDF pada data. Beberapa hal yang dapat Anda jawab adalah
1. Mencari peluang besar tagihan berdasarkan BMI
2. Mencari kemungkin terjadi, seorang perokok dengan BMI diatas 25 akan mendapatkan tagihan kesehatan di atas 16.700.
3. Berapa peluang seseorang acak tagihan kesehatannya diatas 16.7k diketahui dia adalah perokok
4. Mana yang lebih mungkin terjadi
a. Seseorang dengan BMI diatas 25 mendapatkan tagihan kesehatan diatas 16.7k,
atau
b. Seseorang dengan BMI dibawah 25 mendapatkan tagihan kesehatan diatas
16.7k
5. Mana yang lebih mungkin terjadi
a. Seseorang perokok dengan BMI diatas 25 mendapatkan tagihan kesehatan diatas 16.7k, atau
b. Seseorang non perokok dengan BMI diatas 25 mendapatkan tagihan kesehatan diatas 16.7k

## Langkah #4 - Analisa Korelasi Variabel
Setelah menjawab kondisi-kondisi yang lebih mungkin memiliki tagihan kesehatan yang tinggi
dari langkah sebelumnya. Kita juga dapat mencari keterhubungan antara kondisi-kondisi
tersebut dengan tagihan kesehatan. Analisa korelasi akan diperlukan disini.

## Langkah #5 - Pengujian Hipotesis
Langkah terakhir, kita cari apakah ada bukti statistik yang cukup terhadap klaim atau hipotesis
tentang tagihan kesehatan. Anda wajib mengecek 3 hipotesis tentang karakter populasi dari
data. Hipotesis yang wajib uji adalah
1. Tagihan kesehatan perokok lebih tinggi daripada tagihan kesehatan non perokok
2. Tagihan kesehatan dengan BMI diatas 25 lebih tinggi daripada tagihan kesehatan
dengan BMI dibawah 25
Satu hipotesis lain, anda bisa pilih salah satu hipotesis dibawah ini, atau anda dapat membuat
hipotesis lainnya
1. BMI laki-laki dan perempuan sama
2. Tagihan kesehatan laki-laki lebih besar dari perempuan
3. Proporsi perokok berbeda di tiap region

# Outcome Project
Setelah Anda mengerjakan itu semua, kami ingin Anda dapat melakukan analisa & merangkum
hasilnya dalam sebuah short report & presentasi. Simpan short report beserta file pengerjaan
dalam tautan repository github dan rekam presentasi anda melalui youtube. Berikan link
repository project dan link youtube presentasi ke dalam form submission.

## Dataset & Tools

## Dataset
Dataset yang disediakan adalah tagihan kesehatan personal. Data ini memiliki 7 variabel dengan variabel charges menunjukkan besaran kesehatan. Deskripsi setiap kolom dari dataset adalah sebagai berikut:

* Age: age of the primary policyholder.
* Sex: insurance contractor gender, female, male.
* BMI: Body mass index, providing an understanding of the body, weights that are relatively high or low relative to height, objective index of body weight(kg/m^2) using the ratio of height to weight, ideally 18.5 to 24.9
* Smoker status: Whether the policyholder is a smoker or a non-smoker.
* Children: number of children covered by health insurance.
* Region of residence: the beneficiary's residential area in the U.S. - northeast, southeast, southwest, northwest.
* Charges: individual medical costs are billed by health insurance.

# Tools
Projek ini menggunakan tools apa saja untuk melakukan perhitungan, analisa, dan plotting data:
* Tableau
* Python
* Github
