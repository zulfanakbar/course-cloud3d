# Pertemuan 3

Pada pertemuan ini membahas tentang layanan _Oracle Cloud Infrastructure Compute_ dan pembuatan Virtual Machine (VM) di layanan _compute Oracle Cloud_.

## Layanan Compute

_Oracle Cloud Infrastructure_ (OCI) _compute_ merupakan layanan yang menyediakan dan mengelola host komputasi, yang dikenal sebagai _instance_.

_Oracle Cloud Infrastructure_ menawarkan 2 jenis _instance_ yaitu _bare metal_ dan _virtual machine_ (VM);

1. Bare Metal

   Memiliki akses ke server fisik khusus untuk kinerja tertinggi dan isolasi yang kuat. Pada umumnya digunakan pada perusahaan besar.

2. Virtual Machine

   Merupakan lingkungan komputasi independen secara virtual yang berjalan di atas perangkat keras fisik _bare metal_. VM ideal untuk menjalankan aplikasi yang tidak memerlukan kinerja dan sumber daya yang besar.

## Jenis-jenis Instance

Ketika membuat compute instance, kebutuhan sumber daya dapat disesuaikan sesuai dengan kebutuhan seperti CPU, volume memori, dan sumber daya lainnya.

1.  Jenis-jenis _Shape_

    Merupakan template yang digunakan untuk alokasi sumber daya. Berikut jenis-jenis _shape_ antara lain :

        • Standard shapes

        • DenseIO shapes

        • GPU shapes

        • High performance computing (HPC) shapes

        • Optimized shapes

2.  Flexible _Shape_
    Merupakan template yang dapat dapat melakukan custom sejumlah 0CPU dan memori ketika menjalankan atau mengubah VM. Berikut jenis-jenis _shapes_ yang tersedia antara lain :

        • VM.Standard.E3.Flex (AMD)

        • VM.Standard.E4.Flex (AMD)

        • VM.Optimized3.Flex (Intel)

        • VM.Standard.A1.Flex (Arm processor dari Ampere)
