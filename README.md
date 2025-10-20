# geojsonstreet
Proyek Pemetaan Jalan (LineString) dengan GeoJSON
Ini adalah proyek tugas untuk memetakan beberapa ruas jalan di sebuah area menggunakan format GeoJSON. Tujuan dari proyek ini adalah untuk mempraktikkan pembuatan data geografis berbasis vektor, khususnya untuk objek linear (garis) seperti jalan, dan memastikan data tersebut valid secara sintaks dan semantik.

🗺️ Tentang File map.geojson
File map.geojson yang ada di dalam repositori ini berisi data geografis dari 10 ruas jalan. Struktur data utamanya adalah FeatureCollection yang terdiri dari beberapa fitur (features). Setiap fitur merepresentasikan satu ruas jalan dengan tipe geometri LineString.

📍 Daftar Jalan yang Dipetakan
Berikut adalah nama-nama jalan yang telah dipetakan di dalam file GeoJSON ini:

Jl. Warung Pulus

Jl. Sukawargi

Gg. Masjid Bani Husen

Jl. Galanggang Batujajar

Jl. Haji Umar

Jl. Rancatiis

Jl. Raya Batujajar

Stasiun

Pintu

Ginangsih

📄 Contoh Struktur Data
Setiap objek jalan dalam file GeoJSON ini memiliki struktur dasar sebagai berikut. Properti name digunakan untuk menyimpan nama jalan.

JSON

{
  "type": "Feature",
  "properties": {
    "name": "Jl. Warung Pulus"
  },
  "geometry": {
    "coordinates": [
      [107.49133122105485, -6.917262210669989],
      [107.4902472431329, -6.917675882884595],
      [107.4889855351422, -6.918180649073761],
      [107.4879804539433, -6.918299451398497],
      [107.48722637257288, -6.918359073773587],
      [107.48581170986381, -6.918436293091773],
      [107.48506870456669, -6.918468528968248],
      [107.48475161701629, -6.918323431331743]
    ],
    "type": "LineString"
  }
}
🛠️ Validasi
Data GeoJSON ini telah divalidasi menggunakan geojson.io untuk memastikan tidak ada error pada sintaks maupun struktur datanya.

⏭️ Langkah Selanjutnya
Sesuai dengan instruksi tugas, langkah berikutnya adalah mengimpor setiap fitur jalan dari file ini ke dalam database MongoDB, di mana setiap jalan akan disimpan sebagai satu record (dokumen) terpisah.
