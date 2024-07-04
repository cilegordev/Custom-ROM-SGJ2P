# Ikuti langkah - langkah di bawah ini:
Unduh terlebih dahulu file - file yang di perlukan untuk melakukan Custom ROM
1. [Samsung USB Driver](https://samsungusbdriver.com/category/download)
2. [Odin](https://odindownloader.com/category/download)
3. [Custom Recovery](https://github.com/cilegordev/Custom-ROM-SGJ2P/releases/tag/v1.0.0)
4. [Custom ROM](https://github.com/cilegordev/Custom-ROM-SGJ2P/releases/tag/v1.0.0)

Penginstallan driver dan alat flash
1. Install Samsung USB Driver pada Laptop/PC
2. Ekstrak .zip file Odin kemudian buka Odin saat muncul peringatan klik OK (Peringatan tersebut mengingatkan untuk meghapus akun google terlebih dahulu agar saat ROM telah di pasang tidak merepotkan kita saat lupa akun sehingga harus melakukan Bypass FRP)
3. Pindahkan Custom ROM dari Laptop/PC ke Micro SD atau Flash Drive (Jika kalian menggunakan Flash Drive artinya kalian membutuhkan alat tambahan yaitu OTG converter USB ke Micro USB)

UBL untuk memflash Custom Recovery
1. Buka **Pengaturan** > **Tentang Perangkat** > **Info Perangkat Lunak** > Ketuk **Nomer Versi** hingga 7x sampai muncul bacaan **Mode Pengembang Telah Diaktifkan.**
2. Balik ke **Pengaturan** > **Pilihan Pengembang** > Aktifkan **OEM Terbuka Kunci** > Aktifkan **Mendebug USB**
3. Matikan perangkat
4. Tekan **Tombol Power + Tombol Home + Tombol Volume Bawah** secara bersamaan
5. Setelah masuk Mode Download tekan **Volume Atas**
6. Setelah masuk Mode Odin pasang kabel USB perangkat ke Laptop/Pc

Pemasangan Custom ROM
1. Di Odin pilih **AP** > Cari di mana letak unduh **Custom Recovery.tar** > **Open** > **Start**
2. Jika sudah selesai cabut kabel USB kemudian cabut Batrai dan pasangkan kembali Batrai sekaligus pasang MicroSD/Flash Drive
3. Tekan **Tombol Power + Tombol Home + Tombol Volume Atas** secara bersamaan
4. Setelah masuk Mode Recovery geser ke kanan > **Wipe** > **Format Data** > ketikan: **yes**
5. Balik ke Mode Recovery kemudian pilih **Mount** > Ceklis **MicroSD/USB OTG**
6. Balik ke Mode Recovery selanjutnya pilih **Install** > Cari di mana letak unduh **Custom ROM.zip** > Geser **Swip to confirm Flash** > **Reboot System**
