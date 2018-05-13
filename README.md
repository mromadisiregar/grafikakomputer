## Grafika Komputer

**Belajar Unity 3D - Grafika Komputer - Pak Pius - AKAKOM**

Repository ini menampung beberapa gambar dan mungkin output dari unity dalam
bentuk video.

**SCENE :** JJS (Jalan Jalan Santai) Di Dalam Terrain

 - Screenshot setiap update diletakkan pada satu folder dengan nama screenshot-[versi].
 - Video screenrecord diletakkan pada folder video dengan nama file video[versi]-[resolusi].ext

Komponen yang digunakan untuk sementara :

- Asset : Standard Assets

  - Terrain
  - Tree _(palm dan broadleaf)_
  - Ethan _(karakter player)_
  - AircraftFuselage _(pesawat nyasar di tebing)_
  - SkyCar _(mobil jatuh dari langit)_
  - RollerBall _(ini seperti kapsul dalam film dragonball)_
  - WaterPlane _(genangan air)_
  - BlockPrototype _(kontainer)_
  - FloorPrototype _(tempat berdiri di pinggir genangan air)_
  - StepsPrototype _(tangga menuju genangan air)_
  - Texture _(GrassHillAlbedo, GrassRockyAlbedo)_
  - Steam
  - Smoke
  - Flames
  - Fire
  - FireComplex
  - WindZone
  - Point Light

  _(pembagian objek dihilangkan)_


**Konfigurasi**

- Terrain :

  - Diperkecil dengan ukuran Height 100 dan Length 100
  - Penambahan detail grass pada area genangan air

- Pencahayaan/Light :

  - Pergeseran posisi dan pemutaran sudut, menjadi waktu senja
  - Light dimasukkan ke beberapa objek 3D _(RollerBall, SkyCar, AircraftFuselage, Tree)_
  - Light juga dibuat untuk menerangi jalan
  - Tidak ada pertimbangan objek yang memberi sinar _(tiba-tiba ada cahaya)_

- Penambahan komponen pada objek 3d :

    - mesh collider _(StepsPrototype, RollerBall)_
    - riggidbody _(SkyCar)_
    - box collider _(BlockPrototype)_

Tujuan penambahan collider adalah untuk memebuat objek tidak bisa
ditembus oleh player. Collider untuk aircraft masih belum berfungsi dan player masih bisa menembus objek aircraft.

- Penambahan efek terbakar pada aircraft

  - Steam
  - Smoke
  - Flames
  - Fire
  - FireComplex


**Pengembangan**

- Collider
- Objek bergerak lain
