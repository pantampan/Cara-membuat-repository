pertama kita masuk ke web git dulu lalu buat repository baru disana namanya bebas mau apa aja, untuk awal² jangan centang bagian initialize with README

lalu create, setelah muncul link, kalian salin karna itu bakal kepake banget 

lalu buat dulu file dengan membuat nya terlebih dahulu

mkdir "nama folder"

lalu masuk ke dalam folder dengan command cd

cd "nama folder"

setelah masuk, masukan git kedalam folder dengan cara

git init

setelah text kuning banyak keluar langsung edit isi file dengan cara command nano

nano "nama file".txt

setelah puas mengisi text dalam file kalian bisa simpan dengan cara menekan

ctrl -> x -> y -> enter

otomatis file kalian tersimpan@

kalau sudah kalian bisa push folder kalian ke git dengan cara

git add "nama folder"

lalu setelah di proses kalian ketik

git commit -m "pesan yang mau dikirim"

yang nanya apa fungsi m?, m itu singkatan dari massage yang artinya pesan jadi kita bisa mengirimkan pesan tanpa perlu ke editor lagi
kalo gak pake -m nanti akan muncul menu dari git buat masukin pesan, karna ribet jadi pake -m aja biar cepet

lanjut buat selanjut nya ada 

git remote add origin "link yang udah di salin"

lalu ketik

git branch -m main

lalu ketik lagi

git push -u origin main

buat yang nanya u itu buat apa? u itu singkatan dari upstream fungsinya untuk menghubungkan branch remote ke branch repository di web git

setelah itu git bakal minta user name sama password kamu masukin aja username kamu tapi kalo password kamu harus buat token nya dulu caranya

pergi ke web github lalu pencet profil lalu ke seting lalu gulir ke bawah hingga ketemu tulisan devloper seting setelah itu pencet dan masuk ke setingan, kamu pilih personal access token, lalu pilih yang classic lalu pilih repo dan dapatkan token

copy token itu

lalu kamu masukan ke command password sebelumnya 

saat memasukan password text akan tak terlihat jadi setelaj memasukan password kalian bisa langsung enter 

ITULAH CARA MEMBUAT REPOSITORY 
