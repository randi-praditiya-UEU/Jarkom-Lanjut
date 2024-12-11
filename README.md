# Jarkom-Lanjut
# Rangkuman Jarkom lanjut
## Nama : Randi Praditiya
## Nim : 20210801265
## Prodi : Teknik Informatika
Pengertian Jaringan
Jaringan (dalam konteks komputer) adalah sistem yang menghubungkan dua atau lebih perangkat, seperti komputer, server, printer, atau perangkat lain, untuk saling berkomunikasi dan berbagi sumber daya. Jaringan memungkinkan transfer data, berbagi file, akses internet, dan penggunaan perangkat bersama, seperti printer.
Pengertian LAN, WAN,  Dan MAN
1. LAN (Local Area Network)
LAN adalah jaringan komputer yang mencakup area kecil, seperti dalam satu gedung, rumah, sekolah, atau kantor. Ciri-cirinya:
•	Cakupan kecil: Terbatas pada lokasi tertentu.
•	Kecepatan tinggi: Biasanya memiliki kecepatan lebih tinggi karena jaraknya pendek.
•	Contoh perangkat: Komputer, printer, router, switch.
•	Contoh penggunaan: Jaringan kantor untuk berbagi file dan printer.
Contoh: Jaringan komputer di dalam satu ruang kelas atau gedung kantor.
2. WAN (Wide Area Network)
WAN adalah jaringan komputer yang mencakup area geografis yang luas, seperti kota, negara, bahkan antar benua. WAN menghubungkan beberapa LAN melalui media komunikasi seperti kabel bawah laut, satelit, atau internet. Ciri-cirinya:
•	Cakupan luas: Melibatkan lokasi yang berjauhan.
•	Kecepatan lebih rendah: Dibanding LAN karena jarak jauh dan jumlah perangkat besar.
•	Contoh perangkat: Router, modem, switch, perangkat telekomunikasi.
•	Contoh penggunaan: Internet adalah WAN terbesar.
Contoh: Jaringan yang menghubungkan kantor pusat perusahaan di Jakarta dengan cabang di Surabaya.
3. MAN (Metropolitan Area Network) 
MAN adalah jaringan komputer yang mencakup area geografis lebih besar daripada LAN tetapi lebih kecil daripada WAN, biasanya dalam lingkup satu kota atau wilayah metropolitan. MAN digunakan untuk menghubungkan beberapa jaringan lokal (LAN) di dalam area tersebut, seperti jaringan universitas, kantor pemerintahan, atau perusahaan besar yang memiliki beberapa cabang di satu kota.
Contoh Penggunaan MAN:
•	Menghubungkan cabang-cabang bank di satu kota.
•	Mengintegrasikan jaringan universitas di beberapa kampus dalam satu wilayah.
•	Jaringan transportasi kota seperti sistem tiket elektronik.
MAN biasanya dioperasikan oleh penyedia layanan telekomunikasi, dan sering digunakan sebagai jaringan penghubung antara LAN lokal menuju WAN yang lebih luas seperti internet.
Pengertian IP
IP (Internet Protocol) pada jaringan adalah protokol atau aturan yang digunakan untuk mengidentifikasi dan mengatur komunikasi antara perangkat dalam sebuah jaringan komputer. IP memungkinkan perangkat seperti komputer, router, printer, dan perangkat lain untuk saling berkomunikasi, baik dalam jaringan lokal (LAN) maupun melalui internet.
Fungsi Utama IP:
1.	Identifikasi Perangkat
Setiap perangkat dalam jaringan diberikan IP address (alamat IP) yang unik untuk mengidentifikasinya, mirip seperti alamat rumah untuk mengirim surat.
2.	Routing Data
IP menentukan bagaimana data (dalam bentuk paket) dikirim dari pengirim ke penerima melalui jaringan.
Subnet (singkatan dari subnetwork) adalah bagian kecil dari jaringan yang lebih besar, yang dibentuk dengan membagi suatu jaringan menjadi segmen-segmen yang lebih kecil. Subnet digunakan untuk mengorganisasi jaringan, mengelola lalu lintas data, dan meningkatkan efisiensi komunikasi dalam jaringan.
IP Class :
P Class merujuk pada pengelompokan alamat IP yang digunakan dalam jaringan komputer berdasarkan rentang alamat dan tujuan penggunaannya. Alamat IP dikelompokkan ke dalam lima kelas utama: A, B, C, D, dan E. Berikut adalah penjelasan masing-masing kelas IP beserta contohnya:
1. Kelas A (Class A)
•	Rentang Alamat: 1.0.0.0 hingga 127.255.255.255
•	Prefix Subnet: /8
•	Penggunaan: Diperuntukkan untuk jaringan yang sangat besar, seperti jaringan internasional atau perusahaan besar.
•	Jumlah Jaringan: 128 jaringan (0 dan 127 digunakan untuk alamat khusus).
•	Jumlah Host per Jaringan: 16,777,214 host.
Contoh Alamat IP Kelas A:
•	10.0.0.0
•	64.100.50.0
•	120.200.255.0
2. Kelas B (Class B)
•	Rentang Alamat: 128.0.0.0 hingga 191.255.255.255
•	Prefix Subnet: /16
•	Penggunaan: Untuk jaringan yang lebih besar dari kelas C, misalnya kampus atau organisasi besar.
•	Jumlah Jaringan: 16,384 jaringan.
•	Jumlah Host per Jaringan: 65,534 host.
Contoh Alamat IP Kelas B:
•	172.16.0.0
•	150.100.50.0
•	190.200.100.0
3. Kelas C (Class C)
•	Rentang Alamat: 192.0.0.0 hingga 223.255.255.255
•	Prefix Subnet: /24
•	Penggunaan: Digunakan untuk jaringan kecil, seperti jaringan rumah atau kantor kecil.
•	Jumlah Jaringan: 2,097,152 jaringan.
•	Jumlah Host per Jaringan: 254 host.
Contoh Alamat IP Kelas C:
•	192.168.1.0
•	203.0.113.0
•	200.100.50.0
4. Kelas D (Class D)
•	Rentang Alamat: 224.0.0.0 hingga 239.255.255.255
•	Penggunaan: Kelas ini digunakan untuk multicast, yaitu mengirimkan data ke banyak perangkat sekaligus (seperti siaran video atau audio).
•	Jumlah Jaringan: Tidak dibatasi jumlahnya karena digunakan untuk tujuan multicast.
Contoh Alamat IP Kelas D:
•	224.0.0.1 (alamat multicast)
•	233.0.0.0
5. Kelas E (Class E)
•	Rentang Alamat: 240.0.0.0 hingga 255.255.255.255
•	Penggunaan: Diperuntukkan untuk tujuan eksperimen dan biasanya tidak digunakan dalam jaringan publik.
•	Jumlah Jaringan: Tidak ada alokasi umum.
Contoh Alamat IP Kelas E:
•	240.0.0.1
•	255.255.255.255 (alamat broadcast)

Konsep Dasar Subnet
Subnet memungkinkan pembagian satu jaringan besar menjadi beberapa jaringan kecil. Setiap subnet memiliki:
1.	Alamat Jaringan (Network Address): Mengidentifikasi subnet tertentu dalam jaringan.
2.	Alamat Host: Mengidentifikasi perangkat individu di dalam subnet.
3.	Subnet Mask: Menentukan bagian dari alamat IP yang digunakan untuk mengidentifikasi jaringan dan bagian yang digunakan untuk host.
4.	Cara Menghitung Subnet Mask: Subnet mask ditulis dalam format desimal bertitik, seperti 255.255.255.0, atau dalam notasi CIDR seperti /24. Fungsi utama subnet mask adalah menentukan jumlah IP yang tersedia dalam sebuah subnet dan memisahkan jaringan menjadi segmen-segmen lebih kecil untuk meningkatkan efisiensi dan keamanan. Contohnya, subnet mask /24 menyediakan 256 alamat IP, dengan 254 alamat yang dapat digunakan untuk perangkat (karena satu alamat untuk jaringan dan satu untuk broadcast). Menghitung subnet mask dilakukan berdasarkan kebutuhan jumlah host atau jumlah subnet dalam jaringan.
Cara Config IP untuk pertama kali di mikrotik
1.	Reset mikrotik (softreset) - system > reset config > no default > download backup > reset
2.	after reset ip berubah menjadi 0.0.0.0 identity (mikrotik)
3.	cara conect kembali habis direset>login admin, pw (kosong)
4.	memberi nama mikrotik > system > identity > beri nama
5.	user baru > system > users > klik logo tambah > beri nama dan password untuk login > full group.
6.	disable admin untuk keamanan mikrotik
Config static
1.	new ip untuk port > addreses > tambah >contoh ip  (196.168.10.1/24) > ether 2.
2.	Ke menu ip > DHCP > DHCP SERVER > DHCP SETUP > Pilih Port > ether 2 > next sampai selesai
Config dynamic
1.	Control panel > network > change adapter > propertise > ipv4 > desable > enable > klik OK
2.	ke terminal > ipconfig > untuk medapatkan ip
3.	static ip dari laptop > control panel > change adapter > property > use ip > address 192.168.10.13 > subnet otomatis > gateway pakai yang di mikrotik.
Pengertian Bridge Pada Jaringan
Bridge pada jaringan adalah perangkat atau fungsi yang digunakan untuk menghubungkan dua atau lebih segmen jaringan lokal (LAN) sehingga berfungsi sebagai satu jaringan yang terintegrasi. Bridge bekerja pada lapisan data link (Layer 2) dalam model OSI, dan tugas utamanya adalah meneruskan data berdasarkan alamat MAC (Media Access Control). Dengan bridge, lalu lintas data antar segmen dapat diatur sehingga lebih efisien, mengurangi kemacetan, dan memisahkan domain collision tanpa memerlukan perangkat tambahan seperti router. Contohnya, dalam MikroTik, fitur bridge sering digunakan untuk menggabungkan beberapa antarmuka (interface) menjadi satu jaringan logis.
Cara Setting Bridge Pada Mikrotik :
1.	Pilih menu Brige > tambah > berikan username >  apply > ok 
2.	Cara menggabungkan > port > tambah > ether 2 > apply > tambah > ether 3 > aplly ok.
Cara setting ip bridge :
1.	Ip brige >addres> tambah> contoh (192.168.20.1/24) > interface > eth2eth3
Cara Setting DHCP Untuk Bridge :
1.	Masuk kedalam mikrotik > DHCP > silang DHCP LAMA > DHCP setup > pilih eth2eth3 > next sampe selesai
Pengertian Routing 
Routing adalah proses menentukan jalur terbaik untuk mengirimkan data dari sumber ke tujuan dalam sebuah jaringan. Routing dilakukan oleh perangkat jaringan seperti router, yang bertugas membaca alamat IP tujuan dalam paket data dan meneruskannya ke jaringan atau perangkat yang sesuai.


Cara Kerja Routing:
•	Pengumpulan Informasi: Router mengumpulkan informasi tentang jaringan yang terhubung menggunakan protokol routing.
•	Penentuan Jalur: Berdasarkan informasi tersebut, router menentukan jalur terbaik untuk mengirimkan data.
•	Penerusan Paket: Router meneruskan paket data sesuai dengan tabel routing yang dimilikinya.
Jenis Routing:
Static Routing:
•	Jalur ditentukan secara manual oleh administrator jaringan.
•	Cocok untuk jaringan kecil dengan sedikit perubahan.
Dynamic Routing:
•	Jalur ditentukan secara otomatis menggunakan protokol routing seperti RIP, OSPF, atau BGP.
•	Cocok untuk jaringan besar dan kompleks.
Fungsi Routing:
•	Menghubungkan jaringan yang berbeda.
•	Mengarahkan data ke tujuan dengan efisien.
•	Menangani lalu lintas data yang kompleks pada jaringan besar.
Contoh:
Jika komputer di jaringan A ingin berkomunikasi dengan komputer di jaringan B, router menggunakan routing untuk mencari jalur terbaik sehingga data dapat mencapai jaringan B dengan benar.
Routing adalah fondasi dari komunikasi di jaringan besar seperti internet, di mana data harus melewati berbagai jalur dan perangkat sebelum mencapai tujuannya.
Langkah – Langkah Routing Static :
1.	Bikin ulang Ip > addres > tambah > 192.168.10.1/24 > ether 2 > apply > ok 
2.	Ke menu Ip > address > tambah > contoh (10.10.10.1/24) > ether 3 > ip penghubung 
3.	Ke menu ip > router > tambah > router 1 contoh ipnya (192.168.10.1/24) > router ip eth 3 10.10.10.1/24 > router 2 eth 2 contoh ipnya (192.168.20.1/24) > buat eth 3 di router 2 ipnya 10.10.10.2/24
Langkah – Langkah Routing Dynamic :
1.	Aktifkan Protokol Routing Dinamis (seperti RIP, OSPF, atau BGP).
2.	Tentukan Jaringan yang Ditransmisikan (konfigurasi jaringan yang akan dipelajari).
3.	Router Berbagi Informasi Routing antar perangkat di jaringan.
4.	Pemutakhiran Tabel Routing dengan jalur terbaik yang diterima dari router lain.
5.	Penyebaran Informasi ke Router Lain jika ada perubahan topologi jaringan.
6.	Pemilihan Jalur Terbaik berdasarkan metrik seperti biaya, jarak, atau kecepatan

Langkah – Langkah Routing RIP :
1.	Bikin ip > address > tambah > 192.168.10.1/24  eth 2> apply ok.
2.	Bikin ip ke router lain > 10.10.10.1/24 eth 3 > aplly
3.	routing > RIP > interface > eth 3 buat penghubung misalkan > apply 
4.	networks > tambah > masukin ip  192.168.10.0/24 yang di mikrotiknya > tambah lagi 10.10.10.0/24 > apply semua
5.	neghboard > masukin punya ip punya orang 10.10.10.2 > aplly
Pengertian NAT :
NAT (Network Address Translation) adalah teknik untuk mengubah alamat IP dalam paket data saat melewati router, memungkinkan perangkat di jaringan lokal (LAN) menggunakan satu alamat IP publik untuk akses internet. Fungsi utamanya adalah menghemat alamat IP publik dan meningkatkan keamanan dengan menyembunyikan perangkat lokal dari internet. Ada beberapa jenis NAT, seperti:
•	Static NAT: Satu alamat IP privat ke satu alamat IP publik.
•	Dynamic NAT: Alamat IP privat ke alamat IP publik yang berubah-ubah.
•	PAT (Port Address Translation): Beberapa alamat IP privat berbagi satu alamat IP publik dengan membedakan koneksi berdasarkan nomor port.
NAT memungkinkan komunikasi antar jaringan dengan lebih efisien dan aman.
Langkah – Langkah Setting NAT :
UNTUK NAT [masukan internet ke mikrotik]
1.	masukan ip
2.	DHCP Server > eth2
3.	ip > DHCP Client > Tambah > eth1 > apply > ok
4.	ip > firewall > nat > tambah > out interface >eth 1 (karena ada internet) 
5.	action > mascruade > aplly ok.
6.	control panel > networks > desbale dan enable > nanti dapat ethernet
Pengertian OSPF :
OSPF adalah protokol routing berbasis link-state yang digunakan di jaringan internal (intra-domain). OSPF memetakan jaringan dengan membuat basis data topologi dan menggunakan algoritma Dijkstra untuk menentukan rute terbaik.
Langkah – Langkah Setting OSPF :
1.	Aktifkan OSPF: Mulai proses OSPF di router.
2.	Tentukan jaringan yang akan diaktifkan OSPF: Tentukan jaringan mana yang akan mengikuti protokol OSPF.
3.	Verifikasi OSPF: Periksa status tetangga OSPF dan lihat tabel routing untuk memastikan OSPF berjalan dengan benar.

Pengertian BGP :
BGP adalah protokol routing berbasis path vector yang digunakan untuk pertukaran informasi routing antar sistem otonom (AS) yang berbeda. BGP adalah protokol utama yang digunakan di internet.
Langkah – Langkah Setting BGP :
1.	Aktifkan BGP: Mulai proses BGP di router dengan menentukan Autonomous System (AS) yang digunakan.
2.	Tentukan tetangga BGP: Tentukan router tetangga yang akan berkomunikasi menggunakan BGP.
3.	Iklankan jaringan melalui BGP: Tentukan jaringan yang akan diumumkan ke tetangga BGP.
4.	Verifikasi BGP: Periksa status BGP dan tabel routing untuk memastikan BGP berjalan dengan baik.
