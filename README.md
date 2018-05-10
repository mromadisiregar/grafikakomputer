## Grafika Komputer

**Belajar Unity 3D - Grafika Komputer - Pak Pius - AKAKOM**

Repository ini menampung beberapa gambar dan mungkin output dari unity dalam
bentuk video.

**SCENE :** JJS (Jalan Jalan Santai) Di Dalam Terrain

Komponen yang digunakan untuk sementara :

- Asset : Standard Assets

**- Object 3D :**

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

**- Object 2D :**

  - Texture _(GrassHillAlbedo, GrassRockyAlbedo)_


**Konfigurasi**

- Terrain diperkecil dengan ukuran Height 100 dan Length 100

- Pencahayaan : dilakukan sedikit pergeseran posisi

- Penambahan komponen pada Object 3d :

    - mesh collider _(StepsPrototype, RollerBall)_
    - riggidbody _(SkyCar)_
    - box collider _(BlockPrototype)_

Tujuan penambahan collider adalah untuk memebuat Object tidak bisa
ditembus oleh player. _(masih meragukan)_


**Pengembangan**

- Belum ada Grass
- Belum menggunakan angin
- dll
