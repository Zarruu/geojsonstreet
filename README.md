#geojsonstreet
🗺️✨ Proyek Jalan Digital: Mengubah Peta Menjadi Kode
Selamat datang di Proyek Jalan Digital! Ini bukan sekadar tugas biasa; ini adalah sebuah ekspedisi untuk mengubah jalanan fisik di sekitar kita menjadi data geografis yang hidup dalam format GeoJSON. Misi kami adalah memetakan arteri kehidupan sehari-hari—jalan dan gang—dan merangkainya menjadi sebuah peta digital yang presisi dan elegan.

🚀 Misi Proyek
Tujuan utama proyek ini adalah untuk menyelami dunia data geografis berbasis vektor. Dengan menggunakan objek LineString, kami menangkap esensi setiap jalan—lekukan, panjang, dan lokasinya—dan menyajikannya dalam format data yang universal dan dapat divalidasi. Setiap baris kode adalah langkah di jalan digital yang kita buat.

📍 Menjelajahi Peta Digital: map.geojson
File utama dalam ekspedisi ini adalah map.geojson. Anggap saja ini sebagai gulungan peta digital kami, yang berisi 10 jalur petualangan (ruas jalan). Di dalamnya, Anda akan menemukan sebuah FeatureCollection, yaitu kumpulan dari setiap jalan yang telah kami petakan.

Jalur-jalur yang berhasil ditaklukkan dan didokumentasikan meliputi:

Jl. Warung Pulus

Jl. Sukawargi

Gg. Masjid Bani Husen

Jl. Galanggang Batujajar

Jl. Haji Umar

Jl. Rancatiis

Jl. Raya Batujajar

Rute Stasiun

Jalur Pintu

Lintasan Ginangsih

🔬 Anatomi Sebuah Jalan Digital
Penasaran bagaimana sebuah jalan di dunia nyata bisa diubah menjadi data? Mari kita bedah struktur salah satu Feature kami. Setiap jalan memiliki identitas (properties) dan jejak digitalnya sendiri (geometry), yang terdiri dari serangkaian koordinat lintang dan bujur.

JSON

{
  "type": "Feature",
  "properties": {
    "name": "Jl. Warung Pulus"
  },
  "geometry": {
    "type": "LineString",
    "coordinates": [
      [107.491331, -6.917262],
      [107.490247, -6.917675],
      [107.488985, -6.918180],
      ...
    ]
  }
}
Validasi: Setiap koordinat dan struktur data telah diperiksa dan divalidasi melalui geojson.io untuk memastikan peta kami bebas dari kesalahan.

💡 Petualangan Selanjutnya: Menuju MongoDB!
Peta ini barulah permulaan. Langkah selanjutnya adalah membawa data ini ke level berikutnya dengan menyimpannya di MongoDB. Setiap jalan yang tadinya hanya bagian dari satu file kolektif akan diarsipkan sebagai "catatan" atau dokumen individual. Ini akan mengubah data mentah kita menjadi sebuah basis data yang terstruktur, kuat, dan siap untuk dianalisis lebih lanjut.
