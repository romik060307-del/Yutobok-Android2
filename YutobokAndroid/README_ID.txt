YUTOBOK ANDROID — PROYEK SUMBER + BUILD APK OTOMATIS DI CLOUD

Isi:
- Aplikasi Android WebView untuk index.html Yutobok V12.
- Ikon launcher memakai logo merah-putih yang disediakan.
- Tidak menambahkan SDK iklan.
- JavaScript, DOM storage, cookies pihak ketiga, dan pemutaran media diaktifkan.
- Workflow GitHub Actions untuk membangun APK debug secara otomatis tanpa Android Studio.

CARA MENDAPATKAN APK TANPA ANDROID STUDIO:
1. Buat repository baru di GitHub (akun GitHub gratis bisa digunakan).
2. Unggah SEMUA isi folder YutobokAndroid ini ke repository tersebut; pastikan folder .github/workflows ikut terunggah.
3. Setelah unggahan selesai, buka tab Actions di repository.
4. Pilih workflow "Build Yutobok APK". Jika belum berjalan otomatis, tekan Run workflow.
5. Tunggu sampai workflow berstatus sukses.
6. Buka hasil run tersebut dan unduh artifact bernama "Yutobok-Android-APK".
7. Ekstrak ZIP artifact untuk mendapatkan app-debug.apk, lalu pindahkan ke HP Android dan buka untuk memasang. Android mungkin meminta izin "Instal aplikasi tidak dikenal" untuk aplikasi pengelola file yang digunakan.

CATATAN:
- File ZIP sumber ini BELUM berisi APK yang telah dikompilasi. APK akan dibuat oleh GitHub Actions setelah source diunggah dan workflow berjalan sukses.
- APK debug cocok untuk uji/pemasangan pribadi; bukan APK release bertanda tangan khusus untuk distribusi resmi.
- Halaman memakai sebagian aset web dari CDN sehingga memerlukan internet untuk tampilan lengkap.
- Video pihak ketiga tetap tergantung koneksi, sumber video, format, serta dukungan Android WebView. Tidak ada jaminan bebas bug sebelum pengujian di perangkat nyata.
- Aplikasi tidak menambahkan SDK iklan, tetapi tidak bisa menghapus iklan yang ada pada situs atau sumber video eksternal.
