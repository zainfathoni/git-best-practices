# Teori Dasar Git

## Apa itu VCS?

*VCS (Version Control System)* bisa dibilang semacam suatu *"database"* yang memungkinkan kita menyimpan cuplikan utuh proyek kita di setiap titik waktu tertentu. Selanjutnya di artikel ini kita sebut setiap cuplikan tersebut sebagai **"versi"**. Dengan Git, kita bisa mengetahui detil perbedaan antara suatu versi dengan versi lainnya.

Sebagai contoh, pada gambar berikut ini terdapat 3 versi cuplikan:
1. Versi pada tanggal 7 Oktober 2013
2. Versi pada tanggal 9 Oktober 2013
3. Versi pada tanggal 12 Oktober 2013

Di bagian bawah, kita dapat melihat detil perubahan yang terjadi di setiap versinya.

![Apa itu VCS](https://www.git-tower.com/learn/content/01-git/01-ebook/en/02-desktop-gui/02-basics/01-what-is-version-control/what-is-vcs.png)
*Gambar: [Git Tower | What is Version Control?](https://www.git-tower.com/learn/git/ebook/en/desktop-gui/basics/what-is-version-control#start)*

Berikut beberapa keuntungan dari pemanfaatan VCS:

1. Kemampuan mengembalikan kondisi **file** pada versi tertentu.
2. Kemampuan mengembalikan kondisi **proyek secara utuh** pada versi tertentu.
3. Kemampuan membandingkan **perubahan** di setiap versinya untuk melihat adanya perubahan yang mengakibatkan suatu masalah terhadap proyek.
4. Kemampuan mengembalikan file yang **hilang/terhapus**. 

## Repository

Satuan entitas terbesar di dalam Git adalah ***Repository***.
*Repository* dapat dianggap seperti sebuah *database* tempat VCS menyimpan semua versi dan akumulasi *metadata* dalam suatu proyek. Pada Git, *repository* ini diwakili oleh sebuah folder tersembunyi bernama **`.git`** di akar folder proyek tersebut.
Dengan demikian, kita dapat dengan mudah mengetahui apakah suatu folder/proyek dikelola dengan Git atau tidak hanya dengan memastikan keberadaan folder **`.git`** tersebut.
Kita tidak perlu (bahkan jangan sampai) mengotak-atik isi "folder ajaib" ini.

## Commit

***Commit*** adalah suatu "pembungkus" sekumpulan perubahan yang terjadi pada beberapa file. Pembuat *commit* ini harus memberikan komentar mengenai perubahan yang dilakukan tersebut dalam bentuk ***Commit Message***. Hal ini memudahkan orang lain (dan si pembuat *commit* itu sendiri) untuk memahami apa maksud dia ketika melakukan perubahan tersebut.

### Struktur Dasar *Commit*

1. Data
2. Commit Message
3. Commit Hash

### *Commit Pointer*

## Working Copy, Staging Area, & Local Repository
### Working Copy
### Staging Area
### Local Repository
## Branching
## References
## Checkout
