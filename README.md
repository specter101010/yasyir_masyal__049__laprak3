  <table>
        <tr>
            <th>Nama</th>
            <td>: yasyir masy'al</td>
        </tr>
        <tr>
            <th>Kelas</th>
            <td>: Tk 4 B</td>
        </tr>
        <tr>
            <th>Nim</th>
            <td>: 09030282327049</td>
        </tr>
    </table>

<h1 style="font-weight: bold;">
ANALISIS JARINGAN MENGGUNAKAN WIRESHARK
</h1 >
<br>

<h2 style="font-weight: bold;">
 Pendahuluan
</h2 >

<p>
Wireshark adalah perangkat lunak open-source yang digunakan untuk menganalisis lalu lintas jaringan. Dengan menggunakan Wireshark, administrator jaringan dapat memantau, menganalisis, dan mengidentifikasi permasalahan jaringan, serta mendeteksi aktivitas mencurigakan.
</p>


<h2 style="font-weight: bold;">
Metodologi
</h2 >

<ul>
  <li>
Perangkat Lunak: Wireshark versi terbaru.
  </li>
  <li>
Lingkungan: Jaringan wifi Universitas Sriwijaya.
  </li>
  <li>
Merekam lalu lintas selama 10 menit.
  </li>
  <li>
Menyimpan hasil dalam format .pcap untuk analisis lebih lanjut.
  </li>
  <li>
Meyimpan hasil dengan format CSV, untuk menganalisis perhitunga QOS
  </li>
</ul>


<h2 style="font-weight: bold;">
Pengaplikasian
</h2 >

<ol>
    <li>
  Membuka wireshark dan menjalankan dengan jaringan yang sudah di pilih seperti gambar di bawah
  </li>
  <img src="open wireshark.png" width="320px">
    <li>
      Lakukan analsis dari data yang ada dengan melihat data dari tabel analisis yang ada wireshark
  </li>
  <img src="open wireshark.png" width="320px">
    <li>
      Buka tab statistik pada bar
    </li>
  <img src="open analisis view.png" width="320px">
    <li>
      Klik Capture file Properties, dapat dilihat beberapa component penting untuk perhitungan QOS seperti bites,packets dll
    </li>
  <img src="analsisi properties.png" width="320px">
    <li>
      Import file menjadi CSV untuk melakukan analisis yang lebih mendalam
    </li>
     <li>
      Klik Tab File pada Bar
     </li>
  <img src="open bar file.png" width="320px">
    </li>
     <li>
       Klik Export Packet Disection, export to CSV
     </li>
  <img src="save as file.png" width="320px">
     <li>
       Lakukan beberapa perhitungan dengan data yang  ada pada Analisis Propertis tadi
     </li>
  <img src="qos awal.png" width="320px">
     <li>
       Untuk mencari delay dan jitter di perlukan analisis tambahan di CSV
     </li>
     <li>
       Lakukan pengkategorian untuk mencari Delay dan Jitter seperti gambar di samping
     </li>
  <img src="open csv.png" width="320px">
     <li>
      Perhitungan untuk mencari Delay
     </li>
  <img src="delay.png" width="320px">
     <li>
      Perhitungan untuk mencari Jitter
     </li>
  <img src="jitter.png" width="320px">
     <li>
     Perhitungan Lengkap QOS ( Quality of Service )
     </li>
  <img src="qos akhir.png" width="320px">
   
</ol

<br>

<h2>Kesimpulan </h2>


<p>
  Berdasarkan analisis, lalu lintas jaringan menunjukkan aktivitas normal dengan beberapa anomali yang perlu diperhatikan. Dari segi QoS, jaringan menunjukkan kinerja yang cukup baik dengan beberapa area yang perlu ditingkatkan. Untuk meningkatkan keamanan dan kinerja jaringan, beberapa rekomendasi yang dapat diterapkan antara lain:
</p>

<ul>
  <li>
    Menerapkan firewall untuk memblokir lalu lintas mencurigakan.
  </li>
  <li>
    Memantau dan membatasi permintaan DNS yang berlebihan.
  </li>
  <li>
Menggunakan sistem deteksi intrusi (IDS) untuk mengidentifikasi potensi serangan lebih lanjut.
  </li>
  <li>
Mengoptimalkan QoS dengan pengaturan bandwidth dan prioritas lalu lintas jaringan.
  </li>
  <li>
Mengurangi jitter dengan mengimplementasikan traffic shaping dan QoS policies.
  </li>
 
</ul>













