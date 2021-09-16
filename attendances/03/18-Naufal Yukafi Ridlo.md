# Pertemuan 03

## Jenis-jenis komputasi
Pada oracle cloud Infrastructure menawarkan 2 jenis instances:
1. *Bare Metal*: Instance komputasi bare metal yang memberi akses ke server fisik khusus untuk kinerja tertinggi dan isolasi yang kuat.
2. *Virtual Machine*: Lingkungan komputasi independen secara virtual yang berjalan di atas perangkat keras fisik *bare metal*

### Jenis-jenis instance
Ketika compute instance, kita bisa memilih sesuai kebutuhan, berikut jenis-jenis instance

1. Jenis Shapes: shapes adalah sebuah templat yang menentukan kebutuhan jumlah CPU, volume memori, dan sumber daya lainnya yang dialokasikan untuk sebuah compute instance.
    <ul>
    <li>Standard Shapes: dirancang untuk kebutuhan umum yang digunakan pada aplikasi-aplikasi dan use case.</li>
    <li>DenseIO Shapes: digunakan untuk basis data yang besar seperti big data dan yang lain sekiranya membutuhkan perform storage tinggi</li>
    <li>GPU Shapes: dirancang untuk akselerasi pada hardware terutama kebutuhan GPU termasuk Inter, AMD CPU dan prosesor grafis NVIDIA.</li>
    <li>High performance computing (HPC) shapes: dirancang untuk komputasi performa tinggi yang membutuhkan frekuensi prosesor core yang tinggi dan HPC dalam klaster jaringan yang diakses secara paralel.</li>
    <li>Optimized shapes: dirancang untuk komputasi tingkat tinggi pada frekuensi core prosesor. Shape ini juga cocok untuk kebutuhan HPC dengan low latency. Shape ini juga mendukung cluster networking.</li>
    </ul>
    <br />
2. Flexible Shapes: sebuah tempat yang dapat melakukan custom sejumlah OCPU dan memori ketika melakukan launching atau mengubah VM. Jenis Flexible shape yang tersedia seperti VM.Standard.E3.Flex (AMD), VM.Standard.E4.Flex (AMD), VM.Optimized3.Flex (Intel), VM.Standard.A1.Flex (Arm processor dari Ampere)

### Komponent ketika membuat VM
Secara default jenis host yang digunakan VM adalah jenis on-demand. Berikut untuk penjelasan jenis host:
<ul>
    <li>on-demand capacity: cukup bayar sesuai dengan kapasitas compute yang digunakan saja.</li>
    <li> Preemptible capacity: berguna saat membutuhkan sumber daya ketika beban kerja meningkat (autoscaling) pada periode waktu tertentu, sehingga lebih hemat biaya </li>
    <li>Reserved capacity: kapasitas cadangan yang berguna untuk masa yang akan datang sesuai dengan kebutuhan. Kapasitas cadangan yang tidak digunakan perhitungan biayanya berbeda dengan sumber daya yang sedang digunakan.</li>
    <li>Dedicated capacity: menjalankan instance VM pada dedicated server, sehingga sumber daya tidak dibagi dengan client/customer lain.</li>
</ul>