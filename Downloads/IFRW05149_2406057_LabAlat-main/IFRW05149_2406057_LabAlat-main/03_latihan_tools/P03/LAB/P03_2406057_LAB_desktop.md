|       Elemen       |                   LAB-UC03-Ajukanpeminjaman                   |
|--------------------|---------------------------------------------------------------|
|       Tujuan       |         Menghasilkanpengajuanpeminjamanyangtersimpan          |
|     Aktorutama     |                           Mahasiswa                           |
|  Sumberkebutuhan   |                       LAB-R03danLAB-R04                       |
|       Pemicu       |           Mahasiswamemilihfungsipengajuanpeminjaman           |
|     Prasyarat      |     Mahasiswatelahterautentikasi; data peralatan tersedia     |
|Pascakondisiberhasil|Pengajuan tersimpan dengan nomor dan status Menunggu keputusan |
| Pascakondisigagal  |        Tidakada pengajuan baru yang berhasil tersimpan        |
|      Include       |                LAB-UC04 — Periksa ketersediaan                |
|   Extensionpoint   |           Bukti pengajuan tersedia, pada langkah 6            |
|       Extend       |            LAB-UC05 jika [mahasiswa memilih cetak]            |