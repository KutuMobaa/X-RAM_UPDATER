# X-RAM_UPDATER
Module Magisk X-RAM

```
mengunci aplikasi langsung ke RAM fisik
meningkatkan kecepatan baca tulis ram
penjadwalan input dan output yang lebih baik
kontrol cache pada aplikasi
```

#### Flash Dan Reboot System lalu
1. su -c xram
2. masukan jalur game yang ingin di kunci ke ram fisik
3. tunggu beberapa detik karena proses sedang berjalan ( boleh keluar dari terminal/termux )
4. jika file ram.txt ada di dalam folder /storage/emulated/0/Android, berarti pemasangan sukses

Pastikan jalur game sesuai .
Contoh memasukan jalur game : /storage/emulated/0/Android/data/com.mobile.legends

#### 📌 PENTING

* Bukan bug atau terjadi kesalahan, setelah sampai di point nomor 3; system akan crees karena pengaruh ram dan aplikasi saat pemasangan aplikasi ke ram fisik. Tunggu 10-30 detik lalu reboot paksa system dengan menahan tombol power.

* Setelah booting, lihat file xram.txt di dalam /storage/emulated/0/Android . Jika tidak ada maka ulangi langkah 1-4 hingga muncul file xram.txt

* memunculkan file xram.txt sangatlah susah & merepotkan, beruntung jika kalian sukses dalam satu kali proses

Jika kalian tipe orang yang panik hanya karena module magisk, sebaiknya skip dan buang jauh jauh niat kalian pasang module ini. 
Module ini benar benar bikin panik tapi jika file xram.txt sukses terpasang, hasilnya cukup icikiwir 😁

DWYOR
