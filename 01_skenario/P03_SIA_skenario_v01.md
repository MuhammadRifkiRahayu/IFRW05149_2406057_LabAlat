<!-- Skenaario Tugas -->
Mahasiswa mengajukan KRS dengan memilih mata kuliah. Setiap
pengajuan menjalankan validasi KRS yang memeriksa kelengkapan,
prasyarat mata kuliah, dan benturan jadwal. Jika validasi berhasil,
sistem menyimpan pengajuan berstatus menunggu persetujuan dosen
wali. Pada konfirmasi penyimpanan, mahasiswa dapat memilih
mengunduh bukti pengajuan. Dosen wali menyetujui atau menolak KRS
dan memberikan catatan keputusan.

<!-- Tabel kebutuhan -->
|  ID   |Kebutuhan|                             tugas                              |
|-------|---------|----------------------------------------------------------------|
|SIA-R01|Mahasiswa|                  dapat melihat jadwal kuliah                   |
|SIA-R02|  Admin  |             akademik dapat mengelola jadwal kuliah             |
|SIA-R03|Mahasiswa|                      dapat mengajukan KRS                      |
|SIA-R04| Sistem  |            memvalidasi KRS sebagai bagian pengajuan            |
|SIA-R05|Mahasiswa|dapat mengunduh bukti jika memilihnya pada konfirmasi pengajuan |
|SIA-R06|  Dosen  |      wali dapat memproses persetujuan atau penolakan KRS       |

<!-- tabel katalog -->
|   ID   |       Nama_use_case        |        Peran_dalam_model        |
|--------|----------------------------|---------------------------------|
|LAB-UC01|Lihat_ketersediaan_peralatan|     Fungsi utama mahasiswa      |
|LAB-UC02|   Kelola_data_peralatan    |      Fungsi utama petugas       |
|LAB-UC03|     Ajukan_peminjaman      |     Fungsi utama mahasiswa      |
|LAB-UC04|    Periksa_ketersediaan    |  Perilaku yang disertakan UC03  |
|LAB-UC05|   Cetak_bukti_pengajuan    |  Tambahan bersyarat pada UC03   |
|LAB-UC06|Proses_keputusan_peminjaman |      Fungsi utama petugas       |
|LAB-UC07|  Lihat_laporan_peminjaman  |Fungsi utama kepala laboratorium |
