# Belajar-lua
Ini adalah dokumentasi untuk mengingat kembali apa saja yang saya sulit untuk memahami maksud dari sintaks atau kode program tersebut



# Maksud dari Operator AND & OR Pada Lua
- Untuk AND itu Isi Dari Variabel tidak boleh berisi selain angka di salah satu variabel.Jika Salah Satu Variable berisikan Selain Angka Maka Hasilnya Akan FALSE.jika Kedua Variable berisikan Angka Semua Maka akan TRUE.
- Untuk OR itu isi dari kedua variable boleh berbeda di salah satu variable nya selain angka, maka akan menghasilkan TRUE.Jika kedua variable nya berisi bukan angka maka akan menghasilkan FALSE.
- CONTOH :
- local a = 1
 local b = 2
 if ( a and b)
 then
 print("kondisinya adalah TRUE")
 else
 print("kondisinya adalah FALSE")
 end
