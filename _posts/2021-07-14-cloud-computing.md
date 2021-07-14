Cloud Computing

# Cloud Computing

## THERE IS NO CLOUD, It's Just Someone Else's Computer

*or is it?*  
Untuk mengetahuinya, kita harus memahami dulu tentang cloud computing. Apa itu cloud computing? Kenapa namanya cloud? Apakah komputernya memang ada di awan?

* * *

<img src="./_resources/cloud-computing_Ilust.jpg" alt="cloud-computing_Ilust.jpg" width=640>

## Apa Itu Cloud Computing?

Menurut [newyorker.com](https://www.newyorker.com/books/page-turner/how-the-metaphor-of-the-cloud-changed-our-attitude-toward-the-internet), istilah cloud (awan) adalah simbol, sebagai metafora bahwa data kita ada di suatu tempat di luar sana, melayang, mengambang, berpindah-pindah, dan selalu ada kapan saja dan dimana saja saat kita membutuhkannya. Istilah awan juga menarik dan menggugah benak orang karena merupakan antonim dari dunia nyata dengan material yang nyata colokan, kabel, hard disk drive, dan sebagainya.

Lalu apa itu cloud computing? Menurut [Ahmadreza](https://ieeexplore.ieee.org/document/9044834), cloud computing adalah kemampuan untuk menyediakan sumber daya sistem komputer sesuai permintaan, terutama data storage dan computing power, tanpa campur tangan langsung dari pengguna. Secara sederhana, cloud computing adalah sebuah layanan dimana pengguna dapat memiliki sumber daya IT seperti komputer, storage, IP Address, dan lain-lain secara mudah, sangat scalable, dan dengan dengan skema harga yang dapat dipilih sesuai keinginan.

Biasanya, jika kita ingin membuat suatu data center atau server untuk suatu layanan, kita harus membangunnya sendiri mulai dari rancangan spesifikasi komputer, prediksi penggunaan di masa depan, alokasi anggaran, penyediaan tempat, kelistrikan, pendinginan dan lain-lain. Model seperti ini biasanya disebut On-Premise, dimana perangkat keras data center berada di tempat yang sama dengan pengguna dan memiliki kontrol fisik terhadap server. Karena mengurus server model On-Premise sangat merepotkan dan membutuhkan banyak uang, munculnya inovasi cloud computing menjadi angin segar yang sangat menarik. Dengan cloud, masalah-masalah tersebut akan dibebankan kepada cloud provider. Kita cukup mengalokasikan anggaran dana dan rancangan penggunaan yang kita inginkan. Cloud computing juga sangat scalable, penggunaan sumber daya yang kita gunakan dapat dengan mudah diatur menyesuaikan kebutuhan. Penyesuaian skala seperti ini membuat biaya pengeluaran dapat ditekan serendah mungkin tanpa perlu khawatir kekurangan sumber daya untuk server.

* * *

## Jenis-Jenis Cloud Computing

Model penerapan (deployment) Cloud Computing secara umum terbagi menjadi 3 jenis: Public Cloud, Private Cloud, dan Hybrid Cloud.

### Public Cloud

Pada model penerapan Public Cloud, sumber daya IT (server, database, jaringan, dll) sepenuhnya berbasis di cloud dan dikelola oleh cloud provider. Sumber daya IT (biasanya hardware) dari model ini akan digunakan bersama-sama dengan user lain sehingga tidak ada yang menganggur, sehingga perbandingan biaya dan penggunaan cloud dapat ditekan serendah mungkin membuat harganya lebih murah. Tetapi dengan catatan memungkinkan munculnya masalah keamanan (hacking, bencana, privasi, dll).

### Private Cloud (On-Premise)

Model Private Cloud lebih mirip seperti On-Premise. Ketika menggunakan model Private Cloud, sumber daya IT yang disediakan cloud provider akan digunakan sepenuhnya untuk 1 client saja tanpa dibagi-bagi sehingga keamanannya lebih kuat dibanding model Public Cloud. Kekurangannya ada pada harganya yang lebih mahal.

### Hybrid Cloud

Hybrid Cloud adalah gabungan dari Public Cloud dan Private Cloud. Pendekatan seperti ini dapat digunakan untuk banyak situasi seperti aturan yang mengharuskan adanya data yang disimpan di data center lokal, penggunaan fungsi backup, atau untuk meningkatkan keamanan dengan menyimpan data penting dan rahasia di data center on-premise sementara aplikasinya diletakkan di public cloud untuk menjangkau pengguna secara cepat.

<img src="./_resources/cloud-computing_Deployment-Model.png" alt="cloud-computing_Deployment-Model.png" width=640>

Selain dari model penerapannya, cloud computing juga dapat dibagi dari model arsitektur atau layanannya, yaitu Iaas, Paas, dan SaaS.

### Infrastructure-as-a-Service (IaaS)

IaaS adalah layanan cloud computing dimana kita mendapat akses penuh terhadap VM yang kita pesan, sementara cloud provider akan mengelola sumber daya dasar seperti CPU, memory, storage, jaringan, dan server fisik. Pengguna akan mendapat akses ke VM melalui SSH, dashboard GUI, atau metode lain untuk mengelola server virtual tersebut. IaaS memberikan kontrol yang banyak kepada pengguna terhadap infrastuktur yang akan dibangun. Pengguna bebas melakukan hampir apa saja terhadap infrastruktur tersebut. Kelemahannya, karena diserahkan sepenuhnya kepada pengguna, cloud provider tidak memberi layanan keamanan yang mumpuni karena harus pengguna sendiri yang mengaturnya. Selain itu  juga dapat menguras waktu karena pengguna harus menyiapkan environment untuk aplikasi terlebih dahulu sebelum dapat digunakan. Contoh layanan IaaS antara lain Elastic Compute Cloud dari Amazon Web Service, Google Compute Engine, DigitalOcean, Microsoft Azure dan banyak penyedia VPS (Virtual Private Server) lainnya.

### Platform-as-a-Service (PaaS)

PaaS berada satu tingkat di atas IaaS dimana cloud provider selain mengelola resource dasar, mereka juga membantu mengelola software dasar seperti sistem operasi dan service-service yang dibutuhkan untuk meluncurkan aplikasi pengguna. Ini membuat kita tidak perlu membuang waktu untuk menyiapkan environment aplikasi dan bisa fokus untuk membuat dan meluncurkan aplikasi saja. Kelemahannya, keamanan yang disiapkan cenderung berfokus untuk mengamankan platform saja, bukan aplikasi. Selain itu juga dapat muncul masalah inkompatibilitas jika ternyata platform yang disediakan tidak cocok dengan aplikasi kita. Contoh layanan PaaS adalah Heroku, AWS Beanstalk, AWS RDS, dan Google App Engine.

### Software-as-a-Service (SaaS)

Pada SaaS, kita benar-benar dimanjakan oleh cloud. Semua urusan cloud akan dikelola oleh cloud provider sementara kita cukup menikmati layanan aplikasi yang sudah disediakan. Kita tidak perlu repot-repot mengurusi masalah pembuatan dan pengelolaan aplikasi atau server. Kelemahannya dari SaaS biasanya fitur yang tersedia sangat tergantung dari penyedia layanan dan kita tidak bisa melakukan kustomisasi secara bebas. Contoh layanan SaaS adalah Google Workspace, Office 365, Dropbox, Adobe Creative Cloud, dan sebagainya.

Selain 3 di atas ada pula model arsitektur lain seperti **Database as a Service** (**DBaaS**), **Bare Metal as a Service** (**BMaaS**), dan **Function as a Service** (**FaaS**).

Di bawah ini adalah visualisasi perbandingan antara On-Premise, IaaS, PaaS, dan SaaS dari segi manajemennya:

![cloud-computing_Architectures.png](./_resources/cloud-computing_Architectures.png)

* * *
## Plus-Minus dari Cloud Computing

Ada banyak sekali manfaat dan kelebihan dari pemanfaatan cloud computing, beberapa di antaranya adalah :

1. Waktu deployment yang sangat cepat
	Sumber daya IT pada Cloud Computing dapat digunakan dengan cepat, bahkan kurang dari satu jam. Kita tidak perlu menunggu perangkat datang, merakit server, dan melakukan instalasi macam-macam. Cukup beberapa kali klik dan cloud provider akan langsung menyiapkan semua resource yang diperlukan.
2. Harga yang murah
	Jika kita memilih model On-Premise maka kita akan dihadapkan oleh beban biaya yang sangat banyak, mulai dari biaya pembelian perangkat, kelistrikan, pendinginan, pembangunan ruang khusus, biaya instalasi, dll. Berbeda dengan model cloud dimana kita cukup membayar biaya penggunaan sumber daya saja karena beban-beban tersebut sudah ditanggung oleh cloud provider.
3. Mampu mendunia secara instant
	Karena ditempatkan di cloud alias internet, kebanyakan cloud provider juga sudah menyiapkan IP Address public yang dapat diakses langsung melalui internet. Beberapa cloud provider juga memiliki layanan DNS dan IP public statis, hal ini membuat kita tidak perlu memusingkan urusan langganan IP Address dan domain. Dengan begitu, aplikasi kita dapat langsung berada di internet dan diakses oleh siapa saja, di mana saja, kapan saja.
4. Skalabilitas yang luar biasa
	Karena kebanyakan layanan cloud berbasiskan virtualisasi, resource pada cloud computing dapat di-scale up/scale down dengan leluasa mengikuti kebutuhan sehingga bisa menghemat biaya pengeluaran dan mengurangi adanya sumber daya yang tidak terpakai/mubazir.
5. Dapat diandalkan
	Layanan cloud menerapkan pengelompokan dan redundansi pada infrastruktur data center-nya sehingga meningkatkan nilai ketersediaan (High Availabity) dan keandalan (Reliability) dari aplikasi kita. Adanya fitur backup and restore juga membuat kita tidak perlu khawatir merugi karena kehilangan data.

Namun dengan segala kelebihannya tersebut, cloud computing tetap memiliki beberapa kelemahan, seperti :

1. Harus selalu terhubung dengan internet
	Karena berada di internet, mau tidak mau perangkat cloud dan client kita harus selalu terhubung ke internet untuk mengelola semua layanan cloud yang digunakan. Jika terjadi internet outage di data center cloud provider, semua aplikasi kita akan berada dalam masalah besar. Masalah bandwidth juga menjadi concern utama dalam penggunaan cloud. Karena server kita diletakkan di satu tempat bersama dengan milik orang lain, dapat terjadi isu rebutan bandwidth karena jalur internet yang jauh lebih sedikit dibanding jumlah server dan masalah latency yang tinggi karena tempat data center-nya terlalu jauh dari pengguna.
2. Isu keamanan
	Masalah keamanan dapat datang dari berbagai sisi, mulai dari kelalaian dalam mengatur firewall, bug/vulnerability pada aplikasi, kelalaian dalam mengatur izin user, dll. Tetapi dengan penggunaan cloud dapat muncul satu sisi masalah kemanan lagi, yaitu kemungkinan hardware tempat virtual server kita berada diretas, atau bahkan worst case scenario-nya adalah kemungkinan layanan cloud provider diretas dan hacker mendapat akses penuh ke semua layanan.
3. Isu privasi
	Terutama untuk penerapan public cloud, masalah privasi dapat muncul karena server virtual kita berada di tangan cloud provider dan kita tidak tahu apa yang mereka lakukan terhadap perangkat kita. Mungkin saja ada Man-in-the-middle, sniffer, spyware, dll.
4. Inkompabilitas
	Terkadang ada server virtual yang mengharuskan firmware atau software-nya menggunakan versi khusus milik cloud provider sehingga dapat menyebabkan inkompatibilitas dengan aplikasi kita. Ada pula layanan-layanan yang mengharuskan pengguna meng-install modul khusus yang terkadang tidak disediakan cloud provider.
5. Locked vendor
	Meskipun cloud provider memiliki layanan migrasi atau integrasi dengan cloud provider lain, kebanyakan cukup merepotkan dan cenderung disulitkan karena cloud provider pun tidak ingin kehilangan pengguna potensialnya. Selain itu perbedaan cloud provider dapat menyebabkan munculnya masalah inkompatibilitas, perbedaan hardware/software, masalah support, dan lain-lain.

Dengan semua kekurangan dan kelebihannya tersebut, tidak dapat dipungkiri bahwa cloud computing masih menjadi topik yang hangat dibicarakan dan tetap menjadi primadona untuk meluncurkan aplikasi-aplikasi ke dunia. Banyak sekali aplikasi raksasa di dunia yang memilih untuk memanfaatkan cloud computing ketimbang membuat data center-nya sendiri.