# Rangkuman Pertemuan 03

Layanan Compute pada OCI
Oracle Cloud Infrastructure Compute memungkinkan menyediakan dan mengelola host komputasi, yang dikenal sebagai instances. 
Setelah membuat instances, kita dapat mengaksesnya dengan aman dari komputer, memulai ulang, melampirkan dan melepaskan volume, dan menghapusnya (terminate) setelah selesai. Setiap perubahan yang dibuat pada drive lokal instances akan hilang saat kita menghapusnya. Setiap perubahan yang disimpan pada volume yang dilampirkan ke instances akan dipertahankan.

Oracle Cloud Infrastructure menawarkan 2 jenis instances yaitu bare metal dan virtual machine (VM):
-Bare Metal: merupakan instances komputasi bare metal yang memberi Anda akses ke server fisik khusus untuk kinerja tertinggi dan isolasi yang kuat.
-Virtual Machine: Virtual Machine (VM) adalah lingkungan komputasi independen secara virtual yang berjalan di atas perangkat keras fisik bare metal.Virtualisasi memungkinkan untuk menjalankan

Jenis Instance
-Shapes adalah sebuah templat yang menentukan kebutuhan jumlah CPU, volume memori, dan sumber daya lainnya yang dialokasikan untuk sebuah compute instance.jenis shapes: standard shapes, DenseIO shapes, GPU shapes, HPC shapes, Optimized shapes.
-Flexible Shapes adalah sebuah templat yang dapat melakukan kustom sejumlah OCPU dan memori ketika melakukan launching atau mengubah VM.
