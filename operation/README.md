# Departemen Litbang Bidang Operations

## Task

1. Buatkan sebuah file docker-compose untuk Web Environment (1 Load Balancer, 2 Web Server, 1 Database Server, phpmyadmin)  
Ketentuan : semua service bisa berjalan dan diakses dari luar container, file docker-compose harus bisa digunakan user tanpa harus melakukan konfigurasi apapun lagi

2. Buatkan sebuah Dockerfile untuk Docker Image yang berisi minimal 2 service apapun selain  pada no 1  
Ketentuan : Hasil image di-push ke Docker Hub, image dan service bisa digunakan user tanpa harus melakukan konfigurasi apapun lagi

3. Buatkan sebuah Vagrantfile dengan provider VirtualBox dan provision menggunakan shell berisi minimal 2 service lain apapun  
Ketentuan : OS yang digunakan wajib GNU/Linux non-GUI, VM dan semua service harus bisa berjalan & diakses dari luar VM

4. Buatkan sebuah Packer template dengan builder VirtualBox dan provision menggunakan Ansible berisi minimal 2 service apapun selain pada no 3  
Ketentuan : OS yang digunakan wajib GNU/Linux non-GUI, VM dan semua service harus bisa berjalan & diakses dari luar VM

* Untuk mendapatkan Freepass, challenger harus bisa menyelesaikan minimal 3/4 task yang diberikan
* Buatlah dokumentasi lengkap (baik yang selesai maupun yang tidak selesai) menggunakan Markdown yang berisi :
    1. Nama challenger
    2. Penjelasan singkat tentang task yang dikerjakan
    3. Penjelasan singkat tentang source code yang dibuat
    4. Foto/Screenshot WIP (Work in Progress)
* Manfaatkan fitur Firewall/SELinux sebaik-baiknya
* Untuk service berupa web, landing page tidak boleh digunakan. Buatlah halaman website sederhana
* Untuk service berupa database, minimal ada 1 user (non root) dengan 1 database berisi 1 tabel berisi >= 3 query
* Halaman website & database SQL dibuat di luar container/virtual machine (manfaatkan fitur dump, backup, restore, move, copy, volumes, dsb)
* Challenger tidak boleh mengubah apapun di dalam container/virtual machine setelah container/virtual machine berjalan (Output apa adanya tanpa sentuhan apapun lagi). Semua perubahan harus dilakukan pada source code sebelum dijalankan
* Upload source code dan write up ke repositori [GitHub](https://github.com/) atau alternatif lainnya

**[Kumpulkan link repositori disini](https://forms.gle/N4afM7ZCcakhUhKh7) maksimal pada tanggal 10 Maret 2021 pukul 23:59**

> NO CHEATING! Dilarang mengerjakan soal bersama dengan peserta lain  
> NO PLAGIARISM! Dilarang melakukan plagiasi karya orang lain. Kerjakan semaksimal mungkin dengan jujur  
> Challenger diperbolehkan untuk mencari di internet untuk referensi solving ataupun bertanya pada [discord POROS](https://discord.gg/QvHqMBtPv5)  
> Sebaiknya beri nama ```README.md``` pada write up agar bisa langsung terlihat di repositori  
> Buatlah dokumentasi serapi dan semenarik mungkin untuk dibaca :)

![](https://tenor.com/view/umaru-umaru-chan-smile-fighting-ganbante-gif-15089120.gif)
