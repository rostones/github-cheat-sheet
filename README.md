### Cheat-sheet 
<hr />

#### Upload project
1. new repository
2. git init
3. git remote add origin "link repo"
4. git remote -v
5. git add . //pengunaan titik untuk seluruh file
6. git commit -m 'commit pertama' // di isi bebas
7. git push -u origin master

#### Upload pembaharuan
1. masuk ke folder project
2. git status // menampilkan daftar file yg mengalami perubahan
3. git add namafile.js // update 1 file ke server
4. git commit // update semua file ke server
5. git push origin master // masukkan username dan password
6. git log // cek perubahan di log

#### Baca perubahan
1. masuk ke folder project
2. git log

#### Buat cabang aplikasi
1. git checkout -b cabangAplikasi
2. git branch // lihat daftar cabang repo
3. git push --set-upstream origin cabangAplikasi // usulkan pull request ke master
4. Buka web github/repo terima confirm pull request dan merge ke master
5. Delete branch yg sudah disetujui kalau tidak diperlukan lagi
6. git checkout master // kembali ke repo master
7. git pull // tarik semua pembaharuan dari server
8. git branch --delete cabangAplikasi

#### Kembali ke commit sebelumnya
1. git reset kode_angka_commit
2. git reset --hard
