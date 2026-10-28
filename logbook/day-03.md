# Day 3 - Linux Users & Permissions

## Learning Focus
Memahami user, group, permission file dan directory, serta dasar hak akses administratif di Linux.

## Commands Practiced
- `whoami` — melihat username aktif.
- `id` — melihat UID, GID, dan grup pengguna.
- `groups` — melihat grup pengguna.
- `ls -l` — memeriksa permission, owner, dan group.
- `chmod` — mengubah permission file.
- `chgrp` — mengubah group file.
- `umask` — melihat mask permission default.
- `touch` — membuat file untuk menguji permission default.
- `sudo -l` — memeriksa hak akses sudo.
- `su --help` — melihat panduan penggunaan `su`.

## Practice Results
- Memeriksa identitas user dan grup yang aktif.
- Memahami format output `ls -l`.
- Mengubah permission `day-03/permission-lab.txt` dari `644` menjadi `600`, lalu mengembalikannya ke `644`.
- Mengubah group `permission-lab.txt` menjadi `users` menggunakan `chgrp`.
- Memeriksa `umask` dan mendapatkan nilai `0022`.
- Membuat `umask-test.txt` dan memeriksa permission hasilnya, yaitu `644`.
- Memeriksa izin sudo menggunakan `sudo -l`.

## Key Learnings
- Permission `r`, `w`, dan `x` memiliki arti berbeda untuk file dan directory.
- Angka permission dihitung dari kombinasi `4` (read), `2` (write), dan `1` (execute).
- Owner dan group merupakan dua bagian berbeda dari kepemilikan file.
- `umask` memengaruhi permission default saat file atau directory dibuat.
- `sudo` dan `su` memiliki fungsi berbeda: `sudo` menjalankan perintah dengan hak tertentu, sedangkan `su` berpindah akun.

## Not Yet Practiced Successfully
- `chown`: sudah dipelajari, tetapi belum berhasil mengubah owner file.
- `su`: baru memeriksa bantuan penggunaan; belum mencoba berpindah akun.

## Next Step
Melanjutkan pembelajaran melalui mini project Linux Permission Lab agar konsep user, group, dan permission dapat diterapkan pada skenario yang lebih nyata.
