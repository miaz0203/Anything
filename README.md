<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portal Berita Indonesia</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
  <style>
    body {
      padding-top: 56px; /* Adjusted for fixed navbar */
      font-family: 'Arial', sans-serif;
    }

    .navbar {
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
    }

    footer {
    background-color: #343a40;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
  }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand text-primary" href="#">NEWS.ID</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item active">
          <a class="nav-link" href="#" onclick="showNews('beranda')">Beranda</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#" onclick="showNews('politik')">Politik</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#" onclick="showNews('ekonomi')">Ekonomi</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#" onclick="showNews('teknologi')">Teknologi</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#" onclick="showNews('olahraga')">Olahraga</a>
        </li>
      </ul>
      <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </nav>

  <!-- Content -->
  <div class="container mt-4">
    <h2 id="newsCategory">Berita Terkini</h2>
    <div id="newsContent">
      <!-- Isi berita disini -->
      <div class="card mt-3 md-3" style="max-width: 540px;">
        <div class="row g-0">
          <div class="col-md-4 mt-3 mb-2 ">
            <img src="pan.jpeg" class="img-fluid rounded-start" alt="PAN">
          </div>
          <div class="col-md-8 mb-2">
            <div class="card-body">
              <h5 class="card-title">PAN Gelar Ijab Kabul dengan Rakyat, Janji Lanjutkan Program Jokowi</h5>
            </div>
          </div>
          <div class="col-md-4 mt-3 mb-2">
            <img src="vietnam_indonesia.jpeg" class="img-fluid rounded-start" alt="AFC">
          </div>
          <div class="col-md-8 mb-2">
            <div class="card-body">
              <h5 class="card-title">Kilau Marselino, Solo Run Impresif Bikin Pemain Vietnam Diusir Wasit</h5>
            </div>
          </div>
          <div class="col-md-4 mt-3 mb-2">
            <img src="tungku.jpeg" class="img-fluid rounded-start" alt="Kebakaran">
          </div>
          <div class="col-md-8 mb-2">
            <div class="card-body">
              <h5 class="card-title">Kronologi Tungku Smelter PT SMI di Morowali Terbakar</h5>
            </div>
          </div>
          <div class="col-md-4 mt-3 mb-2">
            <img src="pabrik.jpg" class="img-fluid rounded-start" alt="Bau Pabrik">
          </div>
          <div class="col-md-8 mb-2">
            <div class="card-body">
              <h5 class="card-title">Bau Menyengat dari Pabrik Kimia di Cilegon, Anak SD Muntah-muntah</h5>
            </div>
          </div>
          <div class="col-md-4 mt-3 mb-2">
            <img src="syl.jpeg" class="img-fluid rounded-start" alt="SYL">
          </div>
          <div class="col-md-8 mb-2">
            <div class="card-body">
              <h5 class="card-title">Firli Bahuri Rampung Jalani Pemeriksaan Kasus Dugaan Pemerasan SYL/</h5>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

   <!-- Content -->
   <div class="container mt-4">
    <h2 id="newsCategory">Politik</h2>
    <div id="newsContent">
      <!-- Isi berita disini -->
      <div class="card mb-3">
        <img src="pdip.jpeg" class="card-img-top" alt="partai">
        <div class="card-body">
          <h5 class="card-title text-dark">Survei Indikator: PDIP Perkasa, Tinggalkan Gerindra-Golkar Posisi 2-3</h5>
          <p class="card-text">Lembaga Survei Indikator Politik Indonesia merilis hasil sigi terbaru terkait keterpilihan partai pada Pemilihan Legislatif (Pileg) Pemilu 2024. PDIP diperkirakan akan tetap menjadi juara disusul Gerindra dan Golkar di posisi 2 dan 3.
            Direktur Eksekutif Indikator Politik Indonesia Burhanuddin Muhtadi mengatakan dari hasil simulasi surat suara, PDI Perjuangan diperkirakan akan mendapat 20,7 persen suara.
            Sementara partai yang menempati posisi selanjutnya yakni Gerindra dengan tingkat elektabilitas 16,5 persen dan disusul oleh Partai Golkar dengan 12,2 persen."Ini simulasi yang paling mendekati fakta pemilu legislatif. Oleh karena itu, simulasi surat suara seharusnya lebih merepresentasikan pilihan warga," ujarnya dalam konferensi pers, Sabtu (20/1).
          </p>
          <p class="card-text"><small class="text-body-secondary">Last updated 3 hours ago</small></p>
        </div>
      </div>
      <div class="card mb-3">
        <img src="undian.jpeg" class="card-img-top" alt="pemilu">
        <div class="card-body">
          <h5 class="card-title text-dark">Survei Indikator: Prabowo-Gibran 48,5 Persen, AMIN Menyusul Posisi Dua</h5>
          <p class="card-text">Hasil survei terbaru Indikator Politik Indonesia mencatat tingkat elektabilitas pasangan Prabowo Subianto-Gibran Rakabuming masih yang tertinggi ketimbang kedua rivalnya dalam Pilpres 2024.
            Direktur Eksekutif Indikator Politik Indonesia Burhanuddin Muhtadi mengatakan dalam survei yang dilakukan pada periode 10-16 Januari 2024, tingkat elektabilitas pasangan Prabowo-Gibran mencapai 48,55 persen.
            Sementara itu posisi kedua ditempati oleh pasangan Anies Baswedan-Muhaimin Iskandar dengan elektabilitas sebesar 24,17 persen. Capaian itu sekaligus mengalahkan pasangan Ganjar Pranowo-Mahfud MD yang hanya 21,60 persen.
            "Kita pakai simulasi surat suara, ada fotonya dan hasilnya konsisten dengan sebelumnya. Prabowo-Gibran berada di peringkat pertama kisaran 48,55 persen," ujarnya dalam konferensi pers, Sabtu (20/1)."Disusul Anies 24,17 persen, selisihnya tidak signifikan secara statistik dengan Ganjar-Mahfud. Tapi secara absolut Anies-Muhaimin ada di peringkat kedua," imbuhnya.
          </p>
          <p class="card-text"><small class="text-body-secondary">Last updated 4 hours ago</small></p>
        </div>
      </div>
      <div class="card mb-3">
        <img src="pidana.jpg" class="card-img-top" alt="pidana pemilu">
        <div class="card-body">
          <h5 class="card-title text-dark">Pidana Pemilu, Politik Uang Diklaim Turun Jauh Dibanding 2019</h5>
          <p class="card-text">Sebanyak 21 kasus dugaan pelanggaran tindak pidana Pemilu 2024 dilimpahkan ke Polri. Delapan kasus di antaranya merupakan politik uang, jauh dibanding 2019 yang mencapai 100 kasus.
            Kepala Satuan Tugas Penegakan Hukum Terpadu (Gakkumdu) Polri Brigjen Djuhandhani Rahardjo Puro mengatakan pelimpahan itu dilakukan oleh Badan Pengawas Pemilu (Bawaslu) usai menelaah 114 laporan dugaan pelanggaran pemilu yang diterima.
            "Dari 114 laporan ini ada 21 yang diduga sebagai tindak pidana Pemilu, selanjutnya diteruskan kepolisian," ujar Direktur Tindak Pidana Umum Bareskrim Polri itu kepada wartawan, Sabtu (19/1).
            "Tindak pidana Pemilu laporannya ke Bawaslu ataupun temuan dari Bawaslu. Manakala Polisi dan Jaksa bersama membahas dan menyatakan tindak pidana Pemilu, baru Bawaslu meneruskan menjadi laporan polisi untuk proses lebih lanjut," imbuhnya.
            Djuhandhani menjelaskan dari total 21 kasus tindak pidana pemilu yang diterima 13 diantaranya masih dalam tahap penyidikan. Sementara 2 kasus dihentikan dan 6 kasus lainnya sudah dijatuhi vonis.
            Berdasarkan jenisnya, Djuhandani menyebut tindak pidana pemilu paling banyak yakni kasus pemalsuan saat proses pendaftaran dengan total 8 perkara. Ia menyebut jumlah itu masih jauh lebih rendah ketimbang Pemilu 2019 yang mencapai 18 perkara.
            Urutan berikutnya adalah tindak pidana pemilu terkait politik uang 6 perkara. Jumlah kasus ini juga tercatat menurun dibanding sebelumnya yang mencapai 100 perkara.
            "Dua perkara tindak pidana pemilu berupa kampanye melibatkan pihak yang dilarang. Sedangkan, pada Pemilu 2019 jumlah tindak pidana pemilu tersebut mencapai 14 perkara," tuturnya.
            Selanjutnya Satgas Gakkumdu juga mengusut 1 kasus tindak pidana pemilu terkait kampanye di tempat ibadah. Serta 1 kasus tindak pidana pemilu dengan jenis perusakan alat peraga kampanye (APK).
            Terakhir, pihak yang dilarang sebagai pelaksana/tim kampanye sebanyak 2 perkara. Jumlah ini menurun dari Pemilu 2019 yang mencapai 15 perkara," pungkasnya.
            </p>
          <p class="card-text"><small class="text-body-secondary">Last updated 5 hours ago</small></p>
        </div>
      </div>
      <div class="card mb-3">
        <img src="pemilu.jpg" class="card-img-top" alt="pemilu">
        <div class="card-body">
          <h5 class="card-title text-dark">Sudah Ada 83 Lembaga Survei Pemilu 2024 Daftar ke KPU</h5>
          <p class="card-text">Komisi Pemilihan Umum (KPU) telah menerima pendaftaran 83 lembaga yang ingin melakukan survei selama Pemilu 2024. Jumlah itu tercatat di akhir masa pendaftaran pada 15 Januari lalu.
            Menurut KPU, pendaftaran lembaga ini merupakan salah satu upaya melibatkan masyarakat dalam penyelenggaraan Pemilu 2024.
            Akan tetapi, KPU belum merilis nama 83 lembaga survei yang telah mendaftarkan diri. KPU baru mengumumkan 63 nama lembaga survei.
            Lembaga yang mendaftar wajib memenuhi ketentuan sesuai Peraturan KPU (PKPU) Nomor 9 Tahun 2022 tentang Partisipasi Masyarakat dalam Pemilihan Umum dan Pemilu Gubernur dan Wakil Gubernur, Bupati dan Wakil Bupati, dan/atau Walikota dan Wakil Walikota.
          </p>
          <p class="card-text"><small class="text-body-secondary">Last updated 6 hours ago</small></p>
        </div>
        <h5 class="text-dark">Lembaga survei berstatus terdaftar di KPU:</h5>
        <p> 1. PT Kio Sembilan Lima (Lembaga Survei Kedai Kopi)
            2. PT Poltracking Indonesia
            3. PT Ipsos Market Research
            4. PT Kompas Media Nusantara
            5. Charta Politika/PT Indonesian Consultant Mandiri
            6. Voxpol Consulting Center Research and
            7. Pandawa Research
            8. PT Lingkar Strategi Indonesia
            9. PT Parameter Konsultindo (PARMET)
            10. Indikator Politik Indonesia
            11. Lembaga Survei Nasional
            12. Lembaga Klimatologi Politik
            13 Polstat Indonesia
            14. Political Weather Station (PWS)
            15. PT Jaringan Cyrus Nusantara (Cyrus Network)
            16. PT Publik Riset Cendekia (Politika Research and Consulting/PRC)
            17. Centre For Strategic International Studies (CSIS)
            18. Lembaga Survei Jakarta
            19. Indonesia Polling Stations (IPS)
            20. Surabaya Survey Center (SSC)
            21. Lembaga Survei Indonesia (LSI)
            22. Fixpoll Media Polling Indonesia
            23. Forum Rektor PTMA
            24. Yayasan Akselerasi Indodata (INDODATA)
            25. Surabaya Research Syndicate (SRS)
            26. Indopol Survei & Consulting
            27. Polsentrum Data Indonesia
            28. PT Lingkaran Survei Indonesia
            29. PT Citra Publik
            30. Saiful Mujani Research And Consulting
            31. Rakata Analytics and Advisory
            32. Strategi Lingkar Nusantara
            33. Trust Indonesia Research & Consulting
        </p>
        <h5 class="text-dark">Lembaga survei berstatus lengkap berkas pendaftarannya:</h5>
        <p> 34. PUSKAPI (Pusat Kajian Pemilu Indonesia)
            35. PT Losta Institute
            36. PT Citra Komunikasi LSI
            37. PT Lingkaran Survei Kebijakan Publik
            38. Populi Center
            39. PT SCL Taktika Konsultan
            40. PT Citra Publik Indonesia
            41. Indekstat Research And Data Science
            42. PT Sigi LSI Network
            43. PT Konsultan Citra Indonesia
            44. Jaringan Isu Publik
            45. Lembaga Riset Indonesia
            46. Jaringan Suara Indonesia
            47. Media Survei Nasional
            48. PT Alvara Strategi Indonesia
            49. Lingkar Survei Sulawesi (LSS)
            50. Ide Cipta Research and Consulting (ICRC)
            51. The Haluoleo Institute
            52. Media Survei Center Indonesia
            53. PT PARAMETER PUBLIK INDONESIA
            54. PT Paradigma Riset Nusantara
            55. Lembaga Survei Kuadran
            56. Nakama Research & Consulting
            57. PT Indopolling Riset dan Konsultan
            58. PT SINERGI DATA INDONESIA
            59. PT LSI NETWORK
        </p>
        <h5 class="text-dark">Lembaga survei berstatus perbaikan dokumen pendaftaran di KPU:</h5>
        <p>60. DEITRO (PT Delt Kabar Indonesia)
            61. Algoritma Research & Consulting
            62. PUSPOLL INDONESIA
            63. Parameter Politik Indonesia.
        </p>
      </div>
    </div>
   </div>
   
    <!-- Content -->
    <div class="container mt-4">
       <h2 id="newsCategory">Ekonomi</h2>
       <div id="newsContent">
    <!-- Isi berita disini -->
        <div class="card mb-3">
        <img src="pembangunan.jpg" class="card-img-top" alt="Airlangga">
        <div class="card-body">
        <h5 class="card-title text-dark">Airlangga: Pembangunan Giant Sea Wall Butuh Rp600 - Rp700 T</h5>
        <p class="card-text">Menteri Koordinator Bidang Perekonomian Airlangga Hartarto menyebut pembangunan tanggul laut raksasa atau giant sea wall di utara Pulau Jawa membutuhkan anggaran Rp700 triliun.
            Airlangga mengatakan kebijakan itu sudah berjalan dan masuk Proyek Strategis Nasional (PSN). Dia menyebut pemerintah akan menggandeng swasta untuk membangun tanggul itu.
            "Estimasi biaya mungkin bisa Rp600 sampai Rp700 tergantung berapa besar karena itu studinya kita sedang siapkan. Kita bicara triliun," kata Airlangga di Bandung, Jumat (19/1).
            Airlangga mengatakan pemerintah masih mengkaji semua aspek tentang pembangunan giant sea wall. Termasuk skema pembangunan melalui public private partnership.
            Dia menyebut banyak investor yang tertarik dengan proyek ini. Namun, ia belum mau membeberkan siapa investor-investor yang dimaksud."Dananya investor banyak yang mau masuk," ujarnya.
            Airlangga mengatakan kebijakan ini penting untuk melindungi masyarakat. Dia berkata masyarakat di utara Pulau Jawa terancam banjir rob seiring perubahan iklim.
            "Kita akan melihat di pesisir utara dampak ke masyarakat dan dampak kepada kawasan ekonomi yang ada di sana karena kawasan ekonomi kita sebagian besar di utara dan ini bisa terancam oleh rob," ucapnya.
            Sebelumnya, Presiden Jokowi mengatakan giant sea wall diperlukan untuk mencegah rob di Jakarta dan daerah-daerah di utara Pulau Jawa.
            Proyek itu kembali menjadi sorotan setelah calon presiden Prabowo Subianto membahasnya dalam seminar nasional 'Strategi perlindungan Kawasan Pulau Jawa, Melalui Pembangunan Tanggul Pantai dan Tanggul Laut', di Jakarta, Rabu (10/1).
            Dia menyindir komitmen politisi membangun tanggul raksasa di utara Jawa. Prabowo mengatakan proyek ini penting untuk melindungi masyarakat, tetapi tak diminati politisi karena butuh waktu 40 tahun.
            "Ini masalah bukan apakah bisa atau tidak bisa, ini harus kalau tidak pantai utara tenggelam," ucap Prabowo di seminar itu.
        </p>
          <p class="card-text"><small class="text-body-secondary">Last updated 3 hours ago</small></p>
        </div>
        <div class="card mb-3">
            <img src="debat.jpeg" class="card-img-top" alt="Cawapres">
            <div class="card-body">
              <h5 class="card-title">Tebak Senjata Tiga Cawapres soal Energi hingga Pangan di Debat Keempat</h5>
              <p class="card-text">Debat keempat calon presiden dan wakil presiden 2024 bakal digelar Minggu (21/1) besok. Ini menjadi debat kedua yang diikuti oleh ketiga calon wakil presiden, yakni Muhaimin Iskandar (Cak Imin), Gibran Rakabuming Raka, dan Mahfud MD.
                Para cawapres bakal kembali beradu gagasan dan visi misi terkait dengan isu-isu dengan tema pembangunan berkelanjutan, sumber daya alam (SDA), lingkungan hidup, energi, pangan, agraria, masyarakat adat dan desa. 
                Ketiga pasangan calon (paslon) capres cawapres pun sebelumnya sudah memaparkan masing-masing visi dan misinya terkait ekonomi Tanah Air.
                Misalnya terkait energi, paslon nomor urut 1 Anies-Cak Imin menekankan ketahanan energi pada misinya.
                "Memastikan ketersediaan kebutuhan pokok dan biaya hidup murah melalui kemandirian pangan, ketahanan energi, dan kedaulatan air," demikian bunyi misi nomor 1, dikutip dari buku Visi-Misi Anies-Cak Imin berjudul 'Indonesia Adil Makmur untuk Semua'.
                Paslon nomor urut 2 Prabowo-Gibran memiliki visi mendorong kemandirian bangsa melalui swasembada pangan, energi, air, ekonomi kreatif, ekonomi hijau, dan ekonomi biru.
                Untuk energi, kata mereka, Indonesia berpeluang bisa menjadi raja energi hijau dunia melalui pengembangan produk biodiesel dan bioavtur dari sawit, bioetanol dari tebu dan singkong, serta energi hijau lainnya dari angin, matahari, dan panas bumi.
                Kemudian, paslon nomor urut 3 Ganjar-Mahfud ingin mempercepat perwujudan lingkungan hidup yang berkelanjutan melalui ekonomi hijau dan biru.
                Dalam buku visi misi Ganjar-Mahfud, pasangan ini secara spesifik memasukkan isu energi dalam misi ekonomi hijau, yang dibagi dalam empat program kerja, di antaranya transisi energi, desa mandiri energi, limbah jadi berkah, dan ekonomi sirkuler.
                Adapun untuk program pangan, Anies-Cak Imin ingin mendorong sektor pangan untuk memastikan Indonesia sebagai negara agraris bekerja keras untuk memaksimalkan potensi sumber daya untuk memproduksi pangan.
                Keduanya menawarkan sejumlah program di antaranya memfasilitasi pasar dan harga jual melalui tata niaga yang transparan dan akuntabel demi tercapainya kesejahteraan petani melalui penyediaan dana murah, peningkatan stabilisasi harga jual hasil panen, serta pemberian kepastian pembelian hasil panen dengan harga yang menguntungkan petani.
                Kemudian Prabowo-Gibran ingin memantapkan sistem pertahanan keamanan negara dan mendorong kemandirian bangsa, termasuk swasembada pangan. Kubu ini menjanjikan pengembangan program food estate khususnya untuk komoditas padi, jagung, singkong, kedelai, dan tebu.
                Keduanya menargetkan minimal tambahan 4 juta hektare luas panen tanaman pangan tercapai pada 2029. Selain itu, mereka menjamin ketersediaan pupuk, benih, dan pestisida langsung ke petani guna menggenjot produksi dan produktivitas pangan, mendirikan lembaga pembiayaan untuk usaha tani rakyat, hingga memperkuat tata kelola impor pangan pokok dan utama agar lebih efektif dan optimal.
                Sementara Ganjar-Mahfud ingin mempercepat pembangunan ekonomi berdikari berbasis pengetahuan dan nilai tambah. Ini salah satunya, dapat dicapai melalui kedaulatan pangan.
                Keduanya menjabarkan lima janjinya untuk mencapai kedaulatan pangan, di antaranya menjamin ketersediaan pangan dari dalam negeri aman, mendukung petani, peternak, dan nelayan, membangun industri pangan berdaya saing, menyediakan lahan subur bagi petani, dan mensejahterakan petani, peternak dan nelayan.
                Lantas program manakah yang bakal menjadi andalan dan kekuatan para cawapres dalam debat keempat ini?
            </p>
              <p class="card-text"><small class="text-body-secondary">Last updated 4 hours ago</small></p>
            </div>
          </div>
          <div class="card mb-3">
            <img src="led tv.jpeg" class="card-img-top" alt="LED">
            <div class="card-body">
              <h5 class="card-title">LED TV hingga AC Diskon Besar-besaran di Transmart Besok</h5>
              <p class="card-text">Berbagai produk elektronik seperti LED TV, kulkas, hingga AC diskon besar-besaran di Transmart Full Day Sale.
                Ada LED TV 65" mulai Rp7 jutaan, ada juga AC 1/2 pk cuma Rp2 jutaan. Selain itu, ada kulkas SBS 472L mulai Rp8 jutaan. 
                Produk elektronik yang diskon ini hadir dengan berbagai merek ternama seperti LG, Polytron, Panasonic, Sharp, dan Samsung.
                Kalau penasaran sama produk elektronik yang diskon di Transmart Full Day Sale, intip daftarnya di bawah ini.
                LED TV 65" UHD Smart harga sale mulai Rp7.199.200 dari harga normal Rp11.209.000 per unit. Diskonnya sampai Rp4.009.800.
                LED TV 50" UHD Smart harga sale mulai Rp4.799.200 dari harga normal Rp6.969.000 per unit. Diskonnya Rp2.169.800.
                AC Split 1/2 PK harga sale Rp2.699.200 dari harga normal Rp4.199.000 per unit. Bonus pipa dan instalasi standar. Harga berlaku di Pulau Jawa, Bali, dan Lampung. Diskonnya Rp1.499.800.
                AC Split 1/2 PK harga sale Rp2.799.200 dari harga normal Rp3.899.000 per unit. Bonus pipa dan instalasi standar. Harga berlaku di luar Jawa, Bali, dan Lampung. Diskonnya sampai Rp2.099.800.
                Kulkas SBS 472L harga sale Rp8.799.200 dari harga normal Rp12.049.000 per unit. Harga berlaku di Pulau Jawa, Bali, dan Lampung. Diskonnya sampai Rp3.249.800.
                Kulkas SBS 472L harga sale Rp9.239.200 dari harga normal Rp12.649.000 per unit. Harga berlaku di luar Jawa, Bali, dan Lampung. Diskonnya sampai Rp3.409.800.
              <p class="card-text"><small class="text-body-secondary">Last updated 6 hours ago</small></p>
            </div>
          </div>
    <!-- Content -->
    <div class="container mt-4">
        <h2 id="newsCategory">Teknologi</h2>
        <div id="newsContent">
    <!-- Isi berita disini -->
          <div class="card mb-3">
            <img src="jet.jpg" class="card-img-top" alt="jet tempur">
            <div class="card-body">
              <h5 class="card-title">Sindiran Berjemaah Netizen usai Akun Kemhan Ungkap Jumlah Jet Tempur</h5>
              <p class="card-text">Warganet ramai-ramai menyindir Menteri Pertahanan Prabowo Subianto usai akun Twitter atau X milik Kementerian Pertahanan mengunggah angka total pesawat tempur RI.
                Sebelumnya, Prabowo, dalam debat calon presiden, tak bisa menjawab pertanyaan lawan-lawannya soal alat utama sistem senjata (alutsista) dengan dalih rahasia negara.
                "TNI AU saat ini memiliki 466 unit armada pesawat, dan di awal tahun 2026 secara bertahap akan diperkuat 42 jet tempur Rafale Dassault Aviation, bagian dari upaya modernisasi Menteri Pertahanan Prabowo Subianto," kicau akun @Kemhan_RI, Rabu (17/1).
            <h5 class="text-dark">Definisi rahasia</h5>
            <p>Menyusul polemik terkait sifat kerahasiaan alutsista, Pasal 17 UU Keterbukaan Informasi Publik (KIP) sebenarnya sudah mengungkap apa saja informasi publik yang jika dibuka "dapat membahayakan pertahanan dan keamanan negara.Berikut rinciannya:</p>    
            <p>1. Informasi tentang strategi, intelijen, operasi, taktik dan teknik yang berkaitan dengan penyelenggaraan sistem pertahanan dan keamanan negara, meliputi tahap perencanaan, pelaksanaan dan pengakhiran atau evaluasi dalam kaitan dengan ancaman dari dalam dan luar negeri;</p>
            <p>2. Dokumen yang memuat tentang strategi, intelijen, operasi, teknik dan taktik yang berkaitan dengan penyelenggaraan sistem pertahanan dan keamanan negara yang meliputi tahap perencanaan, pelaksanaan dan pengakhiran atau evaluasi;</p>
            <p>3. Jumlah, komposisi, disposisi, atau dislokasi kekuatan dan kemampuan dalam penyelenggaraan sistem pertahanan dan keamanan negara serta rencana pengembangannya;</p>
            <p>4. Gambar dan data tentang situasi dan keadaan pangkalan dan/atau instalasi militer;</p>
            <p>5. Data perkiraan kemampuan militer dan pertahanan negara lain terbatas pada segala tindakan dan/atau indikasi negara tersebut yang dapat membahayakan kedaulatan Negara Kesatuan Republik Indonesia dan/atau data terkait kerjasama militer dengan negara lain yang disepakati dalam perjanjian tersebut sebagai rahasia atau sangat rahasia;</p>
            <p>6. Sistem persandian negara;</p>
            <p>7. sistem intelijen negara.</p>
            </p>
              <p class="card-text"><small class="text-body-secondary">Last updated 2 hours ago</small></p>
            </div>
          </div>
          <div class="card mb-3">
            <img src="DPT.jpeg" class="card-img-top" alt="Cek DPT">
            <div class="card-body">
              <h5 class="card-title">Cara Cek DPT Pemilu 2024 Secara Online</h5>
              <p class="card-text">Pemilih harus memastikan namanya terdaftar pada DPT Pemilu 2024 agar hak pilihnya bisa digunakan pada Februari mendatang. Pengecekan DPT sendiri cukup mudah karena bisa dilakukan secara online dari gawai Anda.
                Daftar Pemilih Tetap (DPT) merupakan daftar pemilih yang dianggap telah memenuhi syarat untuk menggunakan hak pilihnya pada pemilihan umum (pemilu).
                DPT sendiri ditetapkan oleh Komisi Pemilihan Umum (KPU) berdasarkan data kependudukan dari Dinas Kependudukan dan Pencatatan Sipil (Dukcapil).
                <p>Berikut cara mengecek apakah kita terdaftar dalam DPT Pemilu 2024 secara online:</p>
                <P>1.Buka situs https://cekdptonline.kpu.go.id/ di perangkat ponsel, tablet, atau laptop</P>    
                <p>2.Masukkan Nomor Induk Kependudukan (NIK) berjumlah 16 digit atau Nomor Paspor bagi pemilih luar negeri di kolom yang tersedia</p>      
                <p>3.Kemudian klik "Pencarian"</p>
                <p>4.Status kepemilihan akan muncul di layar</p>
                <p>5.Apabila nama Anda telah terdaftar sebagai Pemilih Tetap, akan muncul nama lengkap dan lokasi Tempat Pemungutan Suara (TPS).</p>  
                <p>6. Jika nama Anda belum terdaftar sebagai Pemilih Tetap, akan muncul keterangan "Data Anda belum terdaftar! Ayo gunakan hak pilihmu. Hubungi kantor KPU terdekat untuk memastikan data diri kamu di DPT."</p>
                <p>7. Sesuai keterangan tersebut, sebaiknya Anda segera menghubungi kantor KPU untuk mendaftarkan diri sebagai Pemilih Tetap agar tidak kehilangan hak pilihmu pada 14 Februari.</p>    
            </p>
              <p class="card-text"><small class="text-body-secondary">Last updated 3 hours ago</small></p>
            </div>
          </div>
        <div class="card mb-3">
          <img src="penipuan.jpeg" class="card-img-top" alt="whatsapp">
          <div class="card-body">
          <h5 class="card-title">Daftar Modus Penipuan via WhatsApp Terbaru 2024</h5>
          <p class="card-text">Sempat ramai tahun lalu, sejumlah modus penipuan online yang berujung kuras rekening dengan memanfaatkan trik social engeneering via WhatsApp masih beredar hingga awal 2024 ini. Simak daftarnya.
            Pada 2023, penipuan sedot rekening semacam ini memanfaatkan file apk dengan modus mulai kurir paket, undangan nikah, surat tilang elektronik (eTLE), tagihan internet, lowongan pekerjaan, hingga Panitia Pemungutan Suara (PPS).
            apk (formatnya .apk), yang merupakan kependekan dari Application Package File, yang adalah format berkas yang digunakan untuk mendistribusikan dan memasang software dan middle-ware ke Hp Android.
            Biasanya, apk tidak ada di toko aplikasi resmi seperti Google Playstore.
            File jenis ini kerap dimanfaatkan untuk mengunggah malware atau program jahat yang bisa membuat pelaku mengakses SMS di Hp korban hingga bisa menguras rekeningnya.
            Pakar keamanan siber sekaligus pendiri Ethical Hacker Indonesia Teguh Aprianto menjelaskan penipuan dengan modus ini tekniknya tak jauh dari aplikasi ilegal yang bisa mengakses SMS untuk mendapatkan One Time Password (OTP).
            "Soal modus penipuan seperti ini, ketika korban lengah dan menginstall aplikasi tersebut, maka pelaku akan memiliki akses untuk membaca dan juga mengirimkan SMS. Dari sana bisa melebar kemana-mana," kicaunya di Twitter, 2022.
            Direktur Jenderal Aplikasi dan Informatika Kominfo Semuel Abrijani Pangerapan mengatakan pada dasarnya untuk mencegah jadi korban adalah tak memedulikan kiriman file apk.
          </p>
          <p class="card-text"><small class="text-body-secondary">Last updated 4 hours ago</small></p>
        </div>
      </div>
    <!-- Content -->
    <div class="container mt-4">
        <h2 id="newsCategory">Olahraga</h2>
        <div id="newsContent">
    <!-- Isi berita disini -->
    <div class="card mb-3">
        <img src="penalti.jpeg" class="card-img-top" alt="asnawi">
        <div class="card-body">
          <h5 class="card-title">Penalti Asnawi Akhiri Kutukan Shin Tae Yong vs Vietnam</h5>
          <p class="card-text">Kutukan Shin Tae Yong saat melawan Vietnam bersama Timnas Indonesia berakhir berkat kemenangan 1-0 pada laga Grup D Piala Asia 2023 di Stadion Abdullah bin Khalifa, Doha, Jumat (19/1) malam.
            Shin Tae Yong punya rekor yang buruk jika melawan Vietnam sejak menjadi pelatih Timnas Indonesia pada 2020. Sebelum pertemuan di Piala Asia 2023, STY tidak pernah menang melawn Vietnam di empat kali laga, termasuk menelan dua kekalahan.
             Bukan hanya tidak pernah menang, Timnas Indonesia asuhan Shin Tae Yong juga tidak bisa mencetak gol di empat pertemuan itu.
             Gol penalti Asnawi Mangkualam pada menit ke-42 memastikan kemenangan Indonesia atas Vietnam. Penalti didapat Tim Merah Putih setelah Rafael Struick dilanggar Nguyen Thanh Binh di dalam kotak.
            Jika ditarik lebih jauh, ini adalah kemenangan pertama Timnas Indonesia atas Vietnam di level senior sejak 2016. Sebelumnya, kemenangan terakhir Indonesia terjadi pada leg pertama semifinal Piala AFF 2016.
            </p>
          <p class="card-text"><small class="text-body-secondary">Last updated 2 hours ago</small></p>
        </div>
      </div>
      <div class="card mb-3">
        <img src="jordi.jpeg" class="card-img-top" alt="jordi amat">
        <div class="card-body">
          <h5 class="card-title">Update Kondisi Jordi Amat: Patah Tulang Hidung, Perlu Masker Pelindung</h5>
          <p class="card-text">Jordi Amat mengalami patah tulang hidung dan berniat menggunakan masker pelindung agar bisa bermain pada laga Jepang vs Indonesia di Piala Asia 2023.
            Jordi Amat tidak bisa menuntaskan duel sengit lawan Vietnam pada Derby Asia Tenggara di Piala Asia di Stadion Abdullah bin Khalifa, Doha, Jumat (19/1).
            Jordi mengalami pendarahan di hidung usai disikut Nguyen Van Tung di babak kedua. Akibatnya pemain 31 tahun itu pun harus ditandu keluar lapangan dan digantikan Rizky Ridho pada menit ke-70.
            </p>
          <p class="card-text"><small class="text-body-secondary">Last updated 4 hours ago</small></p>
        </div>
      </div>
      <div class="card mb-3">
        <img src="jepangvsindo.jpeg" class="card-img-top" alt="afc">
        <div class="card-body">
          <h5 class="card-title">Jadwal Jepang vs Indonesia di Piala Asia 2023</h5>
          <p class="card-text">Timnas Indonesia akan menjalani laga pemungkas babak Grup D Piala Asia 2023 (2024) melawan Jepang. Berikut jadwal pertandingan Jepang vs Indonesia.
            Duel Jepang kontra Indonesia akan tersaji di Stadion Al Thumama, Doha pada Rabu (24/1). Pertandingan akan disiarkan secara langsung RCTI pukul 18.30 WIB.
            Pertarungan lawan Jepang akan jadi penentuan apakah Indonesia bisa lolos ke babak 16 besar atau tidak.
            Saat ini Indonesia menempati peringkat ketiga klasemen sementara Grup D. Tim asuhan Shin Tae Yong ini mengoleksi poin tiga dari dua pertandingan, setelah menang atas Vietnam.
            Sejatinya poin Indonesia dan Jepang sama-sama tiga. Akan tetapi Jepang berhak berada di atas Indonesia karena unggul produktivitas gol. Saat ini Jepang surplus satu gol dan Indonesia minus satu gol.
            Dalam laga ini Jepang diyakini akan mengamuk, setelah dipermalukan Irak pada Jumat (19/1). Akan tetapi Jepang pun bisa saja gagal melaju ke babak 16 besar jika kalah dari Indonesia.
            Sama seperti Jepang, Indonesia butuh minimal hasil imbang agar bisa memperbesar peluang lolos ke 16 besar dengan status peringkat tiga terbaik.
            Bedanya Indonesia berharap bisa imbang, tetapi Jepang tidak. Bagi Indonesia imbang dari Jepang adalah pencapaian, tetapi bagi mereka adalah hasil negatif.
        </p>
          <p class="card-text"><small class="text-body-secondary">Last updated 6 hours ago</small></p>
        </div>
      </div>
      </div>
     </div>
    </div>
      











  <!-- Footer -->
  <div class="footer">
    <p class="text-dark bg-white">&copy; 2024 Portal Berita Indonesia</p>
  </div>

  <!-- Bootstrap JS, Popper.js, and jQuery -->
  <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>

  <!-- Custom JavaScript -->
  <script>
    function showNews(category) {
      var newsCategoryElement = document.getElementById('newsCategory');
      var newsContentElement = document.getElementById('newsContent');

      // Set judul berita berdasarkan kategori
      newsCategoryElement.innerText = 'Berita ' + category.charAt(0).toUpperCase() + category.slice(1);

      // Contoh isi berita, bisa diganti dengan data berita yang sesuai dengan kategori
      var newsContent = 'Ini adalah berita terkini dalam kategori ' + category + '.';
      newsContentElement.innerHTML = '<p>' + newsContent + '</p>';
    }
  </script>
</body>
</html>
