# AirBNB-Listings-Bangkok

**Latar Belakang**

Airbnb merupakan salah satu marketplace yang digunakan untuk menawarkan penginapan terutama homestay, atau pengalaman wisata. Airbnb 
digunakan para wisatawan untuk bepergian dengan cara yang lebih unik dan personal. Airbnb menyediakan properti seperti apartemen, 
kamar pribadi, hotel, dan sebagainya.

**Rumusan Masalah**

Dalam konteks ini, rumusan masalahnya adalah :

1. Perusahaan ingin mengetahui wilayah mana saja yang akan menjadi prioritas utama dalam penentuan listing perusahaan.
2. Perusahaan juga ingin mengetahui karakteristik yang diminati untuk guest dalam memilih listing di Bangkok, Thailand?

**Tujuan Masalah**

Sebagai data analyst, saya akan mencari tahu untuk jawabannya

1. Untuk mengetahui wilayah mana saja yang akan menjadi prioritas utama dalam penentuan listing perusahaan.
2. Untuk mengetahui karakteristik yang diminati untuk guest dalam memilih listing di Bangkok, Thailand.

Info dataset Airbnb Listings Bangkok:

- ***Setiap `baris` mewakili sebuah `transaksi` dalam sekali reservasi.***

| No. | Fitur | Deskripsi | Detail |
|-|-|-|-|
| 1. | **Unnamed:0** | Index dari dataset. | |
| 2. | **ID** | Identifikasi unik AirBNB untuk setiap listing. | |
| 3. | **Name** | Nama Daftar. |
| 4. | **host_id** | ID Unik airBNB untuk setiap host/user. |
| 5. | **host_name** | nama Host/Nama depan. |
| 6. | **Neighborhood** | kode geografis lingkungan menggunakan garis lintang dan garis bujur terhadap lingkungan. |
| 7. | **Latitude** | Menggunakan proyeksi Sistem Geodesi Dunia (WGS84) untuk garis lintang.|
| 8. | **Longitude** |  Menggunakan proyeksi Sistem Geodesi Dunia (WGS84) untuk garis bujur. |
| 9. | **Room Type** | Tipe ruangan yang dimiliki oleh AirBNB Bangkok. | Entire Home/Apt(Apartemen) adalah pilihan terbaik jika Anda mencari tempat seperti rumah di tempat yang jauh dari rumah. Dengan seluruh tempat, Anda akan memiliki seluruh ruangan untuk diri Anda sendiri. Biasanya, ini mencakup kamar tidur, kamar mandi, dapur, dan pintu masuk terpisah yang dedikasi. Host sebaiknya mencantumkan di deskripsi apakah mereka akan berada di properti atau tidak (contoh: "Host mendiami lantai pertama rumah") dan memberikan rincian lebih lanjut pada daftar. |
| | | | Private Room sangat baik jika Anda menginginkan sedikit privasi dan masih menghargai koneksi lokal. Ketika Anda memesan Private Room, Anda akan memiliki kamar tidur pribadi untuk tidur dan mungkin harus berbagi beberapa ruang dengan orang lain. Anda mungkin perlu melewati ruang dalam yang mungkin dihuni oleh host atau tamu lain untuk mencapai kamar Anda.|
| | | | Hotel Room Baik yang bersifat pribadi atau bersama, Hotel Room menyediakan tingkat layanan dan keramahan yang terkait dengan hotel tradisional. Kamar-kamar ini tersedia di hotel butik atau gaya hidup, hostel, penginapan sarapan pagi, atau properti serupa. Biasanya, mereka mencakup area umum yang ramai dan kamar-kamar dengan sentuhan unik. |
| | | | Shared Room cocok bagi Anda yang tidak keberatan berbagi ruang dengan orang lain. Ketika Anda memesan kamar bersama, Anda akan tidur di ruang yang dibagikan dengan orang lain dan berbagi seluruh ruangan dengan orang lain. Shared Room populer di kalangan pelancong yang fleksibel yang mencari teman baru dan akomodasi yang ramah di kantong. |

**Kesimpulan**

Berdasarkan analisis yang telah dilakukan, berikut adalah kesimpulan yang dapat diambil untuk mengidentifikasi karakteristik listing 
berdasarkan wilayah dan yang diminati oleh guest di Airbnb Listing Bangkok:

1. Pada daerah Inner, tipe ruangan Airbnb berdasarkan per area district di Bangkok. Dari sini,
   saya simpulkan bahwa bahwa tipe ruangan Entire home/apt memiliki proporsi terbesar yaitu 58%
   di wilayah Inner dan 33% di wilayah Intermediate. Hal ini menunjukkan bahwa banyak guest/penyewa
   yang menginginkan privasi dan kenyamanan seperti di rumah sendiri. Di sisi lain, tipe ruangan Hotel
   room dan Shared room memiliki proporsi kecil untuk di semua area district. Kemungkinan ini menunjukkan
   bahwa jenis akomodasi tersebut kurang populer di daerah-daerah tersebut.

3. Berdasarkan tipe ruangan dan wilayah (area_district) di Bangkok :

- Inner : Harga Hotel room dan Entire home/apt di Inner Bangkok cenderung lebih tinggi daripada di Intermediate dan Outer.
- Intermediate : Hotel room memiliki median harga tertinggi di wilayah Intermediate. Menandakan adanya pilihan akomodasi
  dengan harga yang lebih terjangkau dibandingkan dengan Inner.
- Outer : Semua tipe ruangan di Outer Bangkok memiliki median harga yang lebih rendah dibandingkan dengan wilayah lainnya.
- Daerah ini kemungkinan menarik bagi pengguna yang mencari akomodasi dengan harga lebih terjangkau.
3. Secara umum, wilayah Outer memiliki kecenderungan untuk menjadi tujuan utama bagi pengguna Airbnb yang melakukan kunjungan
   singkat atau menengah. Wilayah Inner lebih cenderung menarik bagi mereka yang mencari penginapan dalam jangka waktu yang
   lebih lama. Wilayah Intermediate memiliki campuran preferensi, dengan dominasi tipe Short-Term.

  **Recomendation**

  Berdasarkan analisis karakteristik listing Airbnb di Bangkok, terutama dalam hal tipe ruangan dan harga berdasarkan wilayah,
  berikut beberapa rekomendasi untuk pengembangan strategi dan peningkatan daya tarik listing:

1. Daerah Inner Bangkok :

Rekomendasi Tempat Wisata: Fokus pada promosi tempat-tempat wisata populer dan kegiatan kultural di sekitar wilayah Inner Bangkok.
Jelaskan keunikan dan kenyamanan penginapan berjenis Entire home/apt, yang banyak diminati oleh tamu di wilayah ini. Rekomendasi 
Tambahan: Pertimbangkan menawarkan paket khusus untuk tamu yang menginap dalam jangka waktu yang lebih lama, seperti diskon untuk
pemesanan mingguan atau bulanan.

2.Daerah Intermediate :

Rekomendasi Tempat Wisata: Highlight tempat-tempat unik di sekitar wilayah Intermediate, serta promosikan berbagai jenis akomodasi
dengan harga yang lebih terjangkau, khususnya Hotel room yang memiliki median harga tertinggi. Rekomendasi Tambahan: Pertimbangkan 
kolaborasi dengan tempat-tempat populer di wilayah ini untuk menawarkan paket akomodasi dan pengalaman lokal yang menarik.

3. Daerah Outer Bangkok:

Rekomendasi Tempat Wisata: Fokus pada promosi destinasi wisata di luar kota, seperti area pedesaan, kebun buah, atau tempat-tempat 
alam yang menarik. Tekankan kelebihan akomodasi dengan harga lebih terjangkau. Rekomendasi Tambahan: Perkuat promosi untuk tipe 
ruangan Entire home/apt yang mungkin lebih diminati oleh tamu yang ingin menjelajahi daerah lebih jauh.

4. Rekomendasi Umum :

Tawarkan diskon atau paket khusus untuk pemesanan jangka panjang di wilayah Inner. Tingkatkan visibilitas listing dengan menambahkan
informasi unik, foto berkualitas tinggi, dan deskripsi menarik. Perbarui harga secara berkala sesuai dengan tren pasar dan kebutuhan tamu.
Selalu perhatikan umpan balik tamu dan gunakan sebagai bahan evaluasi dan peningkatan. Dengan mengikuti rekomendasi ini, diharapkan listing
Airbnb di berbagai wilayah di Bangkok dapat menarik lebih banyak tamu dan memenuhi berbagai preferensi pengguna.


**Link To Tableu Public**
https://public.tableau.com/app/profile/muhammad.umar.fatwa.ilhami/viz/AirBnBBangkok_17140367459100/Dashboard1?publish=yes
