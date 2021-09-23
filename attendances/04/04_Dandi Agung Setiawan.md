# PERTEMUAN 4
## Komponen-komponen Networking
1) VIRTUAL CLOUD NETWORK (VCN)
2) SUBNETS
3) VNIC (Virtual Network Interface Cards)
4) PRIVATE IP
5) PUBLIC IP
6) IPV6
7) DYNAMIC ROUTING GATEWAY (DRG)
8) INTERNET GATEWAY
9) NETWORK ADDRESS TRANSLATION (NAT) GATEWAY
10) SERVICE GATEWAY
11) LOCAL PEERING GATEWAY (LPG)
12) REMOTE PEERING CONNECTION (RPC)
13) ROUTE TABLES
14) SECURITY RULES
15) DHCP OPTIONS

## Virtual Cloud Network (VCN)
Jaringan pribadi virtual yang disiapkan di pusat data Oracle. Mirip dengan jaringan konvensional, 
dengan aturan firewall dan jenis gateway komunikasi tertentu yang dapat dipilih untuk digunakan. 
VCN berada di satu region Oracle Cloud Infrastructure dan mencakup satu atau beberapa blok CIDR 
(IPv4 dan IPv6, jika diaktifkan).

## Subnets
Subdivisi yang ditentukan dalam VCN (misalnya, 10.0.0.0/24, 10.0.1.0/24, atau 2001:DB8::/64). 
Subnet berisi Virtual Network Interface Cards (VNIC), yang ditautkan ke dalam instance. 
Setiap subnet terdiri dari rentang alamat IP yang berdekatan (untuk IPv4 dan IPv6, jika diaktifkan) 
yang tidak tumpang tindih dengan subnet lain dalam VCN.

## Virtual Network Interface Cards (VNIC)
VNIC melekat pada sebuah instance dan berada di subnet untuk mengaktifkan koneksi ke VCN subnet. 
Setiap instans memiliki VNIC utama yang dibuat bersamaan dengan instance dan tidak dapat dihapus.

## Private IP
Alamat IPv4 pribadi dan informasi terkait untuk menangani instance (misalnya, nama host untuk DNS). 
Setiap VNIC memiliki IP pribadi primer, dan dapat menambah dan menghapus IP pribadi sekunder. 

## Public IP
Alamat IPv4 publik dan informasi terkait. Anda dapat secara opsional menetapkan IP publik ke instances 
Anda atau sumber daya lain yang memiliki IP pribadi. 

## Dynamic Routing Gateway (DRG)
Router virtual (opsional) yang dapat ditambahkan ke VCN. Ini menyediakan jalur lalu lintas jaringan pribadi 
antara VCN Anda dan jaringan lokal.

## Service Gateway
Router virtual (opsional) yang dapat ditambahkan ke VCN. Ini menyediakan jalur untuk lalu lintas jaringan pribadi 
antara VCN Anda dan layanan yang didukung di Oracle Services Network (contoh: Oracle Cloud Infrastructure Object 
Storage dan Autonomous Database). 

## Local Peering Gateway (LPG)
Router virtual (opsional) yang dapat ditambahkan ke VCN. Ini memungkinkan mengaitkan satu VCN dengan VCN lain di 
wilayah yang sama.

## Remote Peering Connection (RPC)
Komponen yang dapat ditambahkan ke DRG. Ini memungkinkan mengaitkan satu VCN dengan VCN lain di wilayah yang berbeda.

## Route Tables
Virtual route tables untuk VCN Anda. Mereka memiliki aturan untuk merutekan lalu lintas dari subnet ke tujuan di luar 
VCN melalui gateway atau instance yang dikonfigurasi secara khusus. 

## Security Rules
Aturan firewall virtual untuk VCN Anda. Ini untuk aturan masuk dan keluar yang menentukan jenis lalu lintas (protokol dan port) 
yang diizinkan masuk dan keluar dari instance. Anda dapat memilih apakah aturan yang diberikan bersifat stateful atau stateless. 

## DHCP Options
Informasi konfigurasi yang secara otomatis diberikan ke instances saat dilakukan booting.
