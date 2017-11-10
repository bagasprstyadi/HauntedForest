## Haunted Forest Survival Alpha 2.0

__Deskripsi__
Haunted Forest - Survival, Abimana terjebak di tengah hutan belantara yang dipenuhi
arwah jahat. Jelajahi hutan dan manfaatkan resources yang tersedia untuk bertahan
hidup dan keluar dari hutan. Mampukah Abimana keluar dari hutan dan mengalahkan
arwah arwah itu?

__Genre__
2D, Survival, Horror

__Platform__
Desktop Windows

__Mechanics__
Player bermain game ini sebagai karakter Waharyo Abimana (Abi) yang hilang ingatan
di tengah hutan. Pada awal permainan player dapat memilih action yang akan
dilakukan pertama kali, contohnya di antaranya player dapat memilih untuk
“Berteriak meminta tolong”, “Menjelajahi hutan di tengah malam” dan “Menunggu
terang di tempat itu”, kemudian player akan menemukan barang-barang awal untuk
melakukan survival. Player akan mendapatkan barang pertama berupa sebuah kapak,
air, makanan dan peta yang rusak. Selanjutnya setelah melewati prolog dan
mendapatkan barang-barang tersebut, Player dapat melihat beberapa status Abi di
kiri bawah layar, yaitu “Hunger”, “Condition”dan “Dehidration”. Semakin berjalannya
waktu, apabila status ini tidak dipenuhi dalam jangka waktu tertentu Abi bisa mati.
Selama permainan, Abi akan menemkan petunjuk-petunjuk tentang mengapa dia bisa
di hutan tersebut serta arwah Watuseke dalam bentuk barang yang ditemukan ketika
melakukan suatu action tertentu, serta kejadian yang terjadi setelah dia melakukan
action itu juga.

__Daftar​ ​Anggota​ ​Kelompok__
Kami Bersama​ ​:
- Ariz Buditiono 1506722802
- William Adjandra 1506725003
- Satria Bagus W 1506689156
- Faqrul A 1506728453
- Jonathan Prasetya W 1506725041
- Bagas Prasetya Adi 1506757402

## Repository Guidance

Untuk repository ini sementara terdapat struktur folder sebagai berikut :

- Haunted Forest
    - Assets
        - Sprite
        - Texture
        - Materials
        - Sound
    - Blueprints
    - Maps
    - UI

__Assets__ 
Berisi semua hal yang terkait kedalam aesthetic games

Perhatikan!

Taruh semua barang terkait asset disini dengan rapih sehingga tidak menimbulkan kerusuhan
Untuk suatu asset seperti pohon, bikin folder sendiri bernama Pohon yang nantinya berisi sebuah
file jpg, beserta sprite yang dipakainya.

__Blueprints__
Semua blueprints yang dibuat wajib ditaruh ke sini

__Maps__
Berisi level-level dari game

__UI__
Berisi seluruh UI / UMG / Widget dalam game. Ini juga tolong dibuat rapih per widget jadi untuk suatu 
widget health buat folder sendiri tetapi blueprintnya tetapi ditaruh di folder blueprint

#### Aturan pull - push

Apabila belum memiliki folder maka clone folder terlebih dahulu dengan

```
git clone https://github.com/bagasprstyadi/HauntedForest.git
```

Buat branch baru setiap ingin menambahkan task dengan format :
Nama_[Nama-Task]

```
git branch -b bagas_event-dispacher
```

Untuk push selalu menggunakan source control tetapi jangan lupa pull terlebih dahulu sebelum push 

```
git pull origin <your branch>
git push origin <your branch>
```

Kemudian setelah push pergi ke page pull request dalam github, lalu lakukan pull request dari branch hasil
editan ke branch master. Lalu tunggu merge dari pemilik github.

## Footnote

Semangat guys, H-30 hari kita mesti kelarkan ini game yang keren!! WKKWWKWKKW