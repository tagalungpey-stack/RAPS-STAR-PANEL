# Panel Developer RAPS STAR

Panel web untuk mengelola aplikasi RAPS STAR: user, room, gift, game, dompet, dan pengaturan.
Panel ini statis (HTML + JS + Firebase) dan bukan bagian dari APK.

Alamat: https://tagalungpey-stack.github.io/RAPS-STAR-PANEL/

Proyek Firebase: raps-star (paket com.rapsstar.app).
Hanya akun yang terdaftar sebagai admin yang bisa masuk.

Syarat sekali pasang:
1. Firebase Console > Authentication > Sign-in method: aktifkan Email/Password dan Google.
2. Firebase Console > Authentication > Settings > Authorized domains: tagalungpey-stack.github.io
3. Firebase Console > Firestore Database: buat database (mode production, region asia-southeast1), lalu Publish isi firestore.rules.
4. Login pertama memakai akun owner, lalu daftarkan admin lain di menu Pengaturan.
