# BTWH

Installing the FFmpeg for Windows
Unduh salah satu versi FFmpeg yang tersedia dengan mengklik di sini.
Extract file ke C:\ path.
Ganti nama folder yang telah di-extract menjadi ffmpeg.
Run Command Prompt as Administrator.
Jalankan perintah berikut::
> setx /m PATH "C:\ffmpeg\bin;%PATH%"
Jika berhasil, akan memberikanmu pesan seperti: SUCCESS: specified value was saved.

Sekarang setelah Anda menginstal FFmpeg, verifikasi bahwa itu berhasil dengan menjalankan perintah ini untuk melihat versi:
> ffmpeg -version
Installing the libwebp for Windows
Unduh salah satu versi libwebp yang tersedia dengan mengklik di sini.
Extract file ke C:\ path.
Ganti nama folder yang telah di-extract menjadi libwebp.
Run Command Prompt as Administrator.
Jalankan perintah berikut::
setx /m PATH "C:\libwebp\bin;%PATH%"
Jika berhasil, akan memberikanmu pesan seperti: SUCCESS: specified value was saved.

Sekarang setelah Anda menginstal libwebp, verifikasi bahwa itu berhasil dengan menjalankan perintah ini untuk melihat versi:
webpmux -version
