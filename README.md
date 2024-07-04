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
1. Buka <b>Pengaturan</b> > <b>Tentang Perangkat</b> > <b>Info Perangkat Lunak</b> > Ketuk <b>Nomer Versi</b> hingga 7x sampai muncul bacaan <b>Mode Pengembang Telah Diaktifkan.</b>
2. Balik ke <b>Pengaturan</b> > <b>Pilihan Pengembang</b> > Aktifkan <b>OEM Terbuka Kunci</b> > Aktifkan <b>Mendebug USB</b>
3. Matikan perangkat
4. Tekan <b>Tombol Power + Tombol Home + Tombol Volume Bawah</b> secara bersamaan
5. Setelah masuk Mode Download tekan <b>Volume Atas</b>
6. Setelah masuk Mode Odin pasang USB Perangkat ke Laptop/Pc

Pemasangan Custom ROM
1. Di Odin pilih <b>AP</b> > Cari di mana letak unduh <b>Custom Recovery.tar</b> > <b>Open</b> > <b>Start</b>
2. Jika sudah selesai cabut USB kemudian cabut Batrai kemudian pasang kembali Batrai
3. Tekan <b>Tombol Power + Tombol Home + Tombol Volume Atas</b> secara bersamaan
4. Setelah masuk Mode Recovery geser ke kanan > <b>Wipe</b> > <b>Format Data</b> ketikan <b>yes</b>
5. Kemudian pilih <b>Mount</b> > Ceklis <b>MicroSD/USB OTG</b>
6. Selanjutnya pilih <b>Install</b> > Cari di mana letak unduh <b>Custom ROM.zip</b> > Geser <b>Swip to confirm Flash</b> > <b>Reboot System</b>
