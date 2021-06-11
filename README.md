# grant-permission-apk
Intinya memberi semua izin applikasi secara cepat.

# pendahuluan.
baca aja ini.
Sy ambil dari : https://stackoverflow.com/questions/46658643/android-grant-permissions-through-adb

1. adb shell pm list packages (melihat name package apk)

2. adb shell pm list permissions -d -g

(Melihat tipe permission) (perizinan biasa)

3. aapt d permissions /path/keaplikasi/master.apk

4. (Ini hanyabisa dilinux/mac/yermux, bisa melihat spesifik perizinan aplikasi)

4. Contoh 

pm grant com.whatsapp android.permission.CAMERA

(Mengizikan kamera, ganti grant jadi revoke jika membatalkan)

• Cara paling mudah ada di sini https://stackoverflow.com/a/41904800

# tujuan repo ini.
file dalam repo ini, isinya kumpulan command untuk nge grant semua perizinan aplikasi, sesuai nama-aplikasi.
Daripada pm grant satu satu, kan kelamaan, makanya sy singkat disini,

tengok aja dah isi filenya biar paham
