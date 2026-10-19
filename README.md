1. Apa itu Bootsrap dan dan kegunaanya?:
Jawab:
Bootstrap adalah framework CSS yang digunakan untuk mempermudah pembuatan tampilan website. Bootstrap menyediakan berbagai class dan komponen siap pakai, seperti tombol, navbar, form, card, dan tabel.

Kegunaan Bootstrap:
- Mempermudah dan mempercepat pembuatan tampilan website.
- Membuat tampilan website lebih rapi dan konsisten.
- Membantu membuat website responsif agar dapat menyesuaikan ukuran layar HP, tablet, dan komputer.
- Mengurangi kebutuhan menulis kode CSS dari awal.

2. Ada beberapa cara untuk mengimpor atau menggunakan Bootstrap pada project. Sebutkan cara-caranya!
jawab:
Ada beberapa cara untuk menggunakan Bootstrap pada project, yaitu:
- Menggunakan CDN (Content Delivery Network), yaitu menghubungkan Bootstrap melalui URL pada file HTML. Cara ini praktis karena tidak perlu mengunduh file Bootstrap secara manual.
- Mengunduh file Bootstrap, yaitu mengunduh file CSS dan JavaScript Bootstrap, kemudian menyimpannya di dalam folder project dan menghubungkannya melalui HTML.
- Menggunakan package manager, seperti npm, untuk memasang Bootstrap pada project melalui perintah terminal.
- Menggunakan framework atau build tools, seperti Vite, untuk mengintegrasikan Bootstrap ke dalam project dan mengelola file CSS serta JavaScript.

3. Jelaskan mengenai class grid dan kegunaan breakpoint!
jawab:
Grid adalah sistem tata letak Bootstrap yang membagi halaman menjadi 12 kolom. Grid digunakan untuk mengatur posisi dan lebar elemen agar tampilan website lebih terstruktur dan responsif.
Class grid yang umum digunakan adalah:
- container: membungkus dan mengatur lebar konten.
- row: membuat baris untuk menampung kolom.
- col: membuat kolom dengan lebar yang menyesuaikan ruang tersedia.
- col-md-6: membuat elemen menggunakan 6 dari 12 kolom mulai breakpoint medium.

Sedangkan Breakpoint adalah batas ukuran layar yang digunakan Bootstrap untuk menyesuaikan tampilan website pada perangkat berbeda.

4. Sebutkan minimal lima class yang disediakan oleh Bootstrap beserta kegunaannya!
jawab:
Berikut adalah beberapa class yang disediakan Bootstrap beserta kegunaannya:
- container: Mengatur lebar dan posisi konten halaman.
- text-center: Membuat teks rata tengah.
- bg-success: Memberikan warna latar belakang hijau.
- btn btn-primary: Membuat tombol berwarna biru.
- shadow: Memberikan efek bayangan pada elemen.
- mt-3: Memberikan jarak margin pada bagian atas elemen.
- img-fluid: Membuat gambar responsif agar menyesuaikan lebar layar.
- d-flex: Mengatur tata letak elemen menggunakan Flexbox.

5. Bagaimana cara agar foto atau gambar pada website responsif menyesuaikan ukuran layar 
perangkat?
jawab:
Agar gambar pada website responsif dan menyesuaikan ukuran layar perangkat, kita dapat menggunakan class img-fluid dari Bootstrap.

Contoh kode HTML: <img src="gambar.jpg" class="img-fluid" alt="Gambar">

dimana Class img-fluid membuat lebar gambar maksimal 100% dari elemen induknya dan tinggi gambar menyesuaikan secara otomatis. Dengan demikian, gambar tidak melebihi lebar wadahnya dan tetap mempertahankan proporsi aslinya
