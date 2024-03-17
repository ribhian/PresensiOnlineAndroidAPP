# Presensi Online
# Our Team
- Muhammad Ribhiansyah
- Muhammad Widianto
- Muhammad Zahidy Syawal
- Nada Lutfiyah

<p><a href="http://if.uinsgd.ac.id/" rel="nofollow">Teknik Informatika</a></p>
<a href="https://uinsgd.ac.id/" rel="nofollow">UIN Sunan Gunung Djati Bandung</a>

<h2>Latar Belakang Masalah</h2>

Infomasi (information) adalah data yang telah dikelola dan diproses mutuk memberikan arti dari memperbaiki proses pengambilan keputusan. Sebagaima perannya, pengguna membuat keputusan yang lebih baik sebagai kuantitas dan kualitas dari peningkatan informasi. Sistem informasi adalah cara-cara yang diorganisasi untuk mengunpulkan, memasukan dan mengolah serta menyimpan data, dan cara-car yang diorganisasi untuk menympan, mengelola, mengendalikan, dan melaporkan informasi sedemikian rupa sehingga sebuah organisasi dapat mencapai tujuan yang telah ditetapkan. Presensi karyawan merupakan sebuah data yang menunjukkan tentang kehadiran karyawan setiap harinya dalam sebuah perusahaan.

Data yang dapat dihasilkan dari sebuah presensi karyawan adalah waktu kedatangan dan kepulangan karyawan sebagai bukti kehadiran bekerja di kantor. Kemudian, karyawan yang tidak masuk kerja juga dapat diketahui statusnya apakah yang bersangkutan izin atau sakit. Human Resource (HR) adalah tingkat manajer yang berfungsi untuk memanajemen karyawan. Salah satu tugas dari HR adalah memanajemen presensi. Dengan adanya data yang diolah dalam sebuah sistem informasi absensi maka seorang HR dapat melakukan manajemen presensi karyawan dengan baik.

Sebagian besar perusahaan/instansi negara menggunakan mesin <i>fingerprint</i> untuk presensi karyawannya. Setiap mesin <i>fingerprint</i> ditempatkan di lokasi tertentu seperti ruang lobi, ruangan staff, ruangan departemen, dan lorong utama. Setiap mesin <i>fingerprint</i> tersebut memiliki aplikasi atau software absensi karyawan yang dapat digunakan oleh pengelola presensi untuk merekap laporan absensi. Karyawan yang tidak hadir akan terdata sebagai tidak masuk kantor. Dan selanjutnya akan dimasukan oleh petugas pengelola presensi yang telah ditunjuk oleh HR untuk mnegedit data jika terdapat karyawan yang izin, sakit, atau sedang tugas keluar/dinas. Pada masa Work From Home (WFH) di perusahaan/instansi negara yang menggunakan mesin fingerprint tidak dapat digunakan karena mengharuskan setiap karyawan untuk ke kantor dan melakukan presensi. Di masa ini HR tidak dapat memanajemen kehadiran karyawan dengan baik.

Oleh karena itu, kami mengembangkan sistem presensi online berbasis mobile apps menggunakan flutter sehingga memmungkinkan karyawan untuk dapat melakukan presensi dimana saja dan kapan saja. Sistem mencatat lokasi longitude dan latitude disaat seorang karyawan melakukan presensi. Sehingga dapat menghasilkan data spasial berupa peta lokasi karyawan disaat absensi. Dengan ini maka dimasa WFH, manajemen kehadiran karyawan tetap dapat dilakukan.

<h2>Identifikasi Masalah</h2>

1. Tidak efektifnya penggunaan presensi menggunakan fingerprint dimasa WFH
2. Mencari cara agar para karyawan bisa melakukan presensi dimana saja
3. Data presensi yang sulit diubah-ubah ketika menggunakan fingerprint
4. Penetapan WFH membuat perusahaan terpaksa mencari cara untuk melakukan presensi karyawan secara jarak jauh

# Tujuan Teknis 
Adapun tujuan oenelitian inin yaitu :
1. Mengirimkan lokasi koordinat tiap pengguna ke web server dengan sistem LBS(Location Based Service) yang mampu mendeteksi lokasi setiap user
2. Menghasilkan suatu aplikasi monitoring kehadiran karyawan menggunakan GPS berbasis android untuk mempermudah memonitor kehadiran karyawan.
3. Mengembangkan sistem yang dapat menentukan klasifikasi area user yang terbaca dengan batas-batas area yang telah ditentukan untuk mengetahui status keberadaan lokasi user.

# Timeline Mini Riset
Timeline mini riset tentang Presensi Kehadiran mengikuti tahapan dari pencarian topik projek sampai menjadi sebuah aplikasi
1. Pencarian topik projek
2. Penetapan pemilihan projek sesuai kesepakatan kelompok
3. Data Understanding
4. Modeling
5. Pembagian tugas perkelompok
6. Pengerjaan Projek
7. Evaluasi

# Data Understanding
<h2>Kebutuhan Data</h2>
Data yang dibutuhkan dalam projek ini adalah pendapat para karyawan mengenai presensi disebuah perusahaan selama para karyawan Work From Home (WFH)

# Pengambilan Data
Pengambilan data dilakukan melalui dari berbagai platform untuk membantu kinerja dari projek kami, dintaranya:
1. Google Maps Services
2. Firebase
3. GPS (Global Positioning Service)

# Daftar Fitur
Berikut ini merupakan daftar fitur dari aplikasi presensi online :
1. Authentication menggunakan firebase Authentication.
2. Data presensi tersimpan secara online menggunakan Cloud Firestore
3. Melakukan presen WFO/WFH sesuai jam masuk /  jam keluar.
4. Melakukan Presensi WFO sesuai dengan radius kurang lebih 200 m dari kantor
5. Melakukan Presensi WFH sesuai dengan kabupaten user
6. Menampilkan lokasi user secara realtime dan lokasi kantor tempat user bekerja
7. Menampilkan log/riwayat presensi user sesuai tanggal yang diinputkan user
8. Menampilkan Status diterima/ditolaknya presensi user
9. Login
10.Logout

