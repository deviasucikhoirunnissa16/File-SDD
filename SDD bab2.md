<h1 align="center" id="software-requirements-specification">DOCUMENTASI PROYEK RPL
<p align="center"><font size="5"><b>SOFTWARE DESIGN DOCUMENT</b></font><br>
"Aplikasi Ujian Online Di Sman 1 Jatibarang Berbasis Website (Uline)"</p></h1>

<p align="center"><img src="Gambar/POLINDRA.png" width="250" height="250"></p>

<br>

<p align="center">
    <b><font size="4">Kelompok 4:</font></b><br>
    1. Devia Suci Khoirun Nissa (1703076) <br>
    2. Kastuti (1703062)<br>
    3. Reza Pahlevi Yahya (1703069)
</p>
<center><font size="3"><p align="center">Kelas D3TI2C</p></font></center>

<br>

<br>

<p align="center"><b><font size="5">D3 TEKNIK INFORMATIKA</font></b><br>
<b><font size="3">POLITEKNIK NEGERI INDRAMAYU</font></b><br>
<b><font size="3">2019</font></b></p>


<b>
<h1>
<i>SOFTWARE DESIGN DOCUMENT(SDD)</i>
</h1>
</b>

<ol>
	<li>Pendahuluan</li>
	<ol>
		1.1 Tujuan<br>
		1.2 Ruang Lingkup<br> 
		1.3 Gambaran Umum Dokumen<br>
	</ol>
	<li>Deskripsi Umum</li>
	<ol>
		2.1 Perspektif Produk<br>
		2.2 Manfaat Produk<br>
		2.3 Karakteristik User dan Stakeholder User<br>
		<ol>
			2.3.1 User yang terlibat dalam aplikasi ini adalah sebagai berikut: <br>
			<ol>
				<li>Admin</li>
				<li>Guru</li>
				<li>Siswa</li>
			</ol>
			2.3.2 Stakeholder yang terkait dengan aplikasi ini adalah sebagai berikut : <br>
			<ol>
				<li>Guru</li>
				<li>Siswa</li>
			</ol>
		</ol>
		2.4 Batasan-Batasan<br>
		2.5	Asumsi<br>
	</ol>
	<li>Software Design</li>
	<ol>
		3.1	Kebutuhan Fungsional<br>
		<ol>
			3.1.1 Spesifikasi yang diharapkan pada Pencatatan data guru, siswa dan mata pelajaran<br>
			3.1.2 Spesifikasi yang diharapkan pada Pencatatan data soal ujian<br>
			3.1.3 Spesifikasi yang diharapkan pada Pencatatan data nilai hasil ujian<br>
		</ol>
		3.2	Kebutuhan Non Fungsional<br>
		3.3	Kebutuhan Antarmuka (Interface)<br>
		3.4	Lingkungan Operasi<br>
		3.5	Batasan Perancangan<br>
		3.6	Model Proses<br>
		<ol>
			3.6.1 DFD Level 0 (Context Diagram)<br>
			3.6.2 DFD Level 1<br>
			3.6.3 DFD Level 2<br>
		</ol>
		3.7	Model Data<br>
		3.8	Data Structures<br>
		3.9	Program Spesification<br>
		3.10 Interface Design<br>
		<ol>
			3.10.1 Input Page Design<br>
			3.10.2 View Page Design<br>
			3.10.3 Front Page Design<br>
		</ol>
	</ol>
</ol>

<ol>
	<li>Deskripsi Umum</li>
	<ol>
		2.1 Perspektif Produk<br>
		<ol>
			Produk dari SDD ini adalah sebuah aplikasi yang berbasis website, yang akan dijalankan dan berfungsi sebagai media pembelajaran ujian secara online guna menghadapi Ujian Nasional Berbasis Komputer (UNBK) di SMAN 1 Jatibarang, seperti yang telah dijelaskan pada Pendahuluan. Produk ini  akan dapat diakses dari browser yang berjalan pada sistem operasi Windows maupun Linux.
		</ol>
		2.2 Manfaat Produk<br>
		<ol>
			Manfaat yang didapat dalam menggunakan sistem atau aplikasi ULine ini adalah:<br>
			<ol>
				<li>Memudahkan proses  pendataan guru dan siswa.</li>
				<li>Memudahkan proses pengelolaan soal ujian.</li>
				<li>Memudahkan proses pengoreksian ujian.</li>
				<li>Menyediakan informasi nilai hasil ujian.</li>
				<li>Memudahkan siswa dalam hal latihan soal dan latihan ujian secara komputerisasi.</li>
			</ol>
		</ol>
		2.3 Karakteristik User dan Stakeholder User<br>
		<ol>
			2.3.1 User yang terlibat dalam aplikasi ini adalah sebagai berikut: <br>
			<ol>
				<li>Admin</li>
				<li>Guru</li>
				<li>Siswa</li>
			</ol>
			2.3.2 Stakeholder yang terkait dengan aplikasi ini adalah sebagai berikut : <br>
			<ol>
				<li>Guru</li>
				<li>Siswa</li>
			</ol>
		</ol>
		2.4 Batasan-Batasan<br>
		<ol>
			<li>Aplikasi yang berjalan hanya untuk sistem ujian online di SMAN 1 Jatibarang-Indramayu.</li>
			<li>Aplikasi ini hanya diterapkan di kelas XII dengan harapan mampu memberikan pengalaman dan pembelajaran sistem ujian berbasis komputer sehingga sudah terbiasa ketika mengikuti Ujian Nasional Berbasis Komputer (UNBK).</li>
			<li>Aplikasi ini hanya memberikan ujian seputar mata pelajaran yang diujikan pada Ujian Nasional Berbasis Komputer (UNBK).</li>
		</ol>
		2.5	Asumsi<br>
		<ol>
			<li>Guru dan siswa mempunyai username dan password yang diberikan oleh admin untuk login.</li>
			<li>Sistem dapat random soal secara otomatis, sehingga setiap siswa mengerjakan ujian dengan nomor urut soal yang berbeda.</li>
			<li>Laptop/PC tidak dapat membuka program lain ketika ujian sedang berlangsung.</li>
			<li>Tersedia sarana koneksi ke internet, sarana jaringan komputer, dan sarana penunjang lainnya.</li>
		</ol>
	</ol>

