# Kebijakan Privasi — doo.id

_Terakhir diperbarui: 6 November 2026._

doo.id ("aplikasi") adalah aplikasi pencatat keuangan pribadi yang dikembangkan oleh ADHIIM
("kami"). Aplikasi bekerja sepenuhnya di perangkatmu: kami tidak punya server, akun pengguna, atau layanan
cloud untuk menyimpan datamu.

## Ringkasan
- Kami **tidak mengumpulkan** data pribadi apa pun dari aplikasi ini.
- Aplikasi **tidak punya izin internet** dan tidak mengirim data ke kami atau pihak lain.
- Tidak ada iklan, analitik, pelacak, atau pelaporan crash dari pihak ketiga.
- Datamu tersimpan terenkripsi di perangkatmu dan hanya keluar bila kamu sendiri yang membagikannya.

## Data yang disimpan di perangkatmu
Semua yang kamu catat: gaji, pemasukan, pengeluaran, akun, pocket, goal, produk investasi (diisi manual),
reminder, dan pengaturan aplikasi. Data ini:
- disimpan di database terenkripsi (SQLCipher) pada penyimpanan privat aplikasi;
- dikunci dengan kunci enkripsi yang disimpan di Android Keystore;
- dilindungi PIN yang disimpan hanya sebagai hash dengan salt, bukan PIN aslinya;
- dapat dibuka dengan sidik jari. Data sidik jarimu tidak pernah diakses aplikasi; pencocokan dilakukan oleh
  sistem Android.

Pencadangan otomatis Android ke akun Google dinonaktifkan untuk aplikasi ini, jadi datamu tidak ikut
tersalin ke cloud tanpa kamu minta.

## Izin yang diminta
| Izin | Untuk apa |
|---|---|
| Notifikasi | Pengingat pengeluaran dan gajian |
| Alarm tepat (SCHEDULE_EXACT_ALARM) | Pengingat muncul tepat waktu |
| Jalankan saat perangkat menyala (RECEIVE_BOOT_COMPLETED) | Memasang ulang pengingat setelah perangkat dinyalakan ulang |
| Biometrik | Membuka aplikasi dengan sidik jari (PIN tetap sebagai cadangan) |
| Getar | Getar saat notifikasi |

Aplikasi tidak meminta izin Aksesibilitas, tidak membaca notifikasi aplikasi lain, tidak membaca daftar
aplikasi terpasang, dan tidak mengakses kontak, lokasi, kamera, atau mikrofon.

## Berkas yang kamu pilih atau bagikan sendiri
- **Cadangan.** Fitur cadangan membuat berkas `.mtbackup` yang dienkripsi dengan frasa sandi pilihanmu. Berkas
  itu baru meninggalkan perangkat bila kamu sendiri menyimpannya ke folder atau membagikannya (mis. ke Google
  Drive atau email). Kami tidak dapat membuka cadangan tanpa frasa sandimu dan tidak menyimpan frasa sandi itu.
  Bila frasa sandi hilang, cadangan tidak bisa dipulihkan.
- **Impor CSV.** Aplikasi hanya membaca berkas yang kamu pilih, dan hanya di perangkat.
- **Ekspor CSV.** Fitur Cadangan juga bisa mengekspor satu jenis data (gaji, pengeluaran, terima dari luar,
  setoran goal, atau produk investasi) ke berkas CSV. **Berkas CSV tidak dienkripsi**: siapa pun yang memegang
  berkasnya bisa membacanya. Berkas dibuat di perangkat dan baru keluar bila kamu sendiri menyimpannya ke folder
  atau membagikannya. Gunakan cadangan `.mtbackup` bila kamu membutuhkan berkas terenkripsi.
- **Laporan PDF.** Laporan dibuat di perangkat. Isinya baru dibagikan bila kamu memilih membagikannya lewat
  aplikasi lain.

Setelah berkas keluar dari aplikasi, penyimpanannya menjadi tanggung jawab layanan atau aplikasi tujuan yang
kamu pilih, dengan kebijakan privasi masing-masing.

## Penghapusan data
- Menu Pengaturan › Reset semua data menghapus seluruh data di aplikasi (memerlukan PIN).
- Menghapus aplikasi atau data aplikasi dari pengaturan Android juga menghapus seluruh data di perangkat.
- Cadangan, laporan, atau berkas lain yang sudah kamu bagikan harus kamu hapus sendiri.

Karena kami tidak memegang salinan datamu, kami tidak dapat mengakses, memulihkan, atau menghapus data itu
atas namamu.

## Anak-anak
Aplikasi tidak ditujukan untuk anak di bawah 13 tahun.

## Perubahan kebijakan
Bila perilaku aplikasi berubah (misalnya menambah sinkronisasi atau layanan yang memakai internet), kebijakan
ini akan diperbarui sebelum perubahan itu dirilis, beserta tanggal pembaruannya di bagian atas halaman ini.

## Kontak
Pertanyaan tentang kebijakan ini: dalamadhiim@gmail.com
