<br>Nama : Muhammad Fadhil Fakhrusyakirin<br/>
<br>NPM  : 20081010216<br/>
<br>kelas: Riset Informatika D

# <h2>Topik : Pengelolan Citra Digital (Face Recognition) Dengan Deep Learning <h2/>

# <h3>Riset : Face Recognition untuk absensi Pegawai menggunakan metode CNN (CONVOLUTIONAL NEURAL NETWORK) (.<h3/>

# Research Question
<li>Apa saja manfaat jika menggunakan Face Recognition untuk absensi?<li/>
<li>Bagaimana cara Convolutional Neural Network (CNN) mengklasifikasi wajah secara realtime dengan akurat?<li/>
<li>Apakah Sistem absensi Face Recognition lebih effisien dari pada absensi sidik jari ?<li/>
<li>Apa saja Faktor - Faktor yang mempengaruhi pegawai telat melakukan absensi?<li/>
<li>Apakah Performa Face Recognition lebih baik dibandingkan absensi sidik jari??<li/>

# Teori 
# **CNN ( CONVOLUTIONAL NEURAL NETWORK)**
Referensi : https://pdfs.semanticscholar.org/79b0/7e4da505b5089f7d8b211d565f10ea32d283.pdf 
<p>Face Recognition adalah metode sebuah teknologi dengan proses mengenali wajah yang diterapkan pada teknologi yang ada. Teknologi tersebut seperti kamera, komputer, telepon pintar, dan lain sebagainya. Teknologi ini banyak hal yang dapat digunakan untuk membantu berbagai macam pekerjaan manusia. Setiap harinya manusia melakukan segala kegiatan dengan cara konvensional, seperti kunci pintu yang masih menggunakan kunci konvensional, dan absensi masih menggunakan fingerprint bahkan tabel excel. Teknologi Face Recognition dapat integrasikan teknologi otomatis dengan konvensional seperti absen menggunakan pemindai wajah dan akses untuk membuka pintu menggunakan pemindai wajah. CNN adalah metode machine learning yang digunakan untuk data dua dimensi dan sering digunakan dalam pemrosesan citra. CNN termasuk dalam jenis Deep Neural Network dan menggunakan klasifikasi feedforward serta pembelajaran menggunakan backpropagation. CNN mempresentasikan setiap neuron dalam dua dimensi, berbeda dengan MLP yang menggunakan satu dimensi. CNN menggunakan operasi konvolusi dengan bobot empat dimensi, yaitu neuron input x neuron output x tinggi x lebar.Hasil akurasi metode ini tidak lebih baik dari metode bilinear CNN yang tidak melakukan part attention pada citra. Arsitektur yang digunakan pada metode part-stacked CNN adalah arsitektur cafeNet. Akurasi yang didapatkan dengan metode ini sebesar 76,63% ".
<p/>
# **Algoritma Viola Jones**
Referensi : https://ejournal.unama.ac.id/index.php/processor/article/view/316 
<p>Algoritma Viola-Jones digunakan untuk mendeteksi wajah seseorang dalam gambar yang diambil oleh sebuah kamera. Setelah wajah terdeteksi, algoritma ini membandingkan ciri-ciri wajah tersebut dengan kumpulan wajah yang ada dalam database menggunakan program Matlab. Hasilnya adalah gambar orang yang memiliki kemiripan tertinggi dengan ciri-ciri wajah yang terdeteksi, dalam format JPEG. Dengan cara ini, wajah seseorang dapat diidentifikasi sesuai dengan gambar yang ada dalam database. Proses ini bergantung pada metode pengambilan gambar dan analisis ciri-ciri wajah untuk menghasilkan hasil yang akurat dalam pengenalan wajah.
<p/>
# **Haar Cascade**
Referensi : http://www.jsisfotek.org/index.php/JSisfotek/article/view/154/110
<p>Metode Haar Cascade, yang menggunakan fitur Haar-like. Metode   ini   banyak   digunakan   untuk deteksi   objek   karena   strukturnya   yang   sederhana, tingkat deteksi yang tinggi, dan kecepatan deteksi yang cepat.  Hal  ini  menunjukkan  kinerja  yang  sangat  baik dalam    deteksi    wajah    manusia.    Fitur Haar-likemenghitung  nilai  fitur  area  melalui  perbedaan  nilai kecerahan. Fitur Haar-likemengklasifikasikan berbagai  fitur  yang  ada  pada  objek  dengan  posisi, ukuran,  dan  bentuk  yang  berbeda.  Saat  menggunakan fitur Haar-likedimungkinkan  untuk  mendeteksi  objek tertentu    dalam    sebuah    gambar.    Wajah    manusia memiliki  fitur  yang  dapat  digunakan  untuk  klasifikasi (misalnya,  mata,  hidung,  dan  mulut).  Oleh  karena  itu, wajah manusia dapat dideteksi dengan membandingkan  nilai  fitur  yang  dihitung  dan  dilatih sebagai nilai referensi.<p/>
