# lab4web

```
nama : raja heppyanto
Ti22a2
```
### Daftar isi

```
1. Tugas dan pertanyaan
2. praktek praktikum 4
```

### 1. Tugas dan pertanyaan. 

0. halaman utama 

![ft8](foto/ft8.png)

1. Tambahkan Layout untuk menu About
=> buat single layout yang berisi deskripsi, portfolio, dll

![fd1](foto/fd1.png)

code
```
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title></title>
	<link rel="stylesheet" type="text/css" href="ex.css">	

</head>
<body>
	<div id="container">
		<header>
			<h1>My portofolio</h1>
		</header>
		<nav>
			<a href="ex.html" >Home</a>
			<a href="artikel.html">Artikel</a>
			<a href="about.html" class="bored">About</a>
			<a href="kontak.html">Kontak</a>
		</nav>
		<section>
			<section id="roro">
				<div class="happy">
					<h2>About Me</h2>
					<p>Nama		: Raja heppyanto</p>
					<p>Pekerjaan: pengangguran</p>
					<p>Umur		: 22 tahun</p>
					<p>Status	: Mahasiswa</p>
				</div>
				
			</section>
			<aside id="burik">

				<div class="foto">
					<img src="foto.jpg" width="250" height="300" alt="Raja heppyanto si tampan">
				</div>

			</aside>
		</section>
			
		<footer>
			<h1>Rajahappyanto portofolio</h1>
		</footer>
		<section id="seren">
			<h1>Description</h1>
			<p><b>Raja Heppyanto</b>, seorang pemuda berusia 22 tahun, adalah seorang individu yang bersemangat dan berbakat dalam dunia desain. Dengan tekad yang kuat, ia selalu berusaha untuk menghadirkan kreativitasnya dalam setiap karya desain yang dihasilkannya. Hobi desainnya telah mengantarkannya pada perjalanan yang penuh inspirasi, di mana ia terus mengembangkan kemampuannya dalam menciptakan konsep visual yang menarik dan inovatif. Keingintahuan dan dedikasinya dalam dunia desain membuat Raja Heppyanto menjadi seseorang yang selalu siap untuk menghadapi tantangan dan terus berkembang dalam bidang yang ia cintai.</p>
		</section>

		<h1 class="OLOR">Comming Soon</h1>
			
	</div>
	
</body>
</html>
```

2. Tambahkan layout untuk menu Contact
=> yang berisi form isian: nama, email, message, dll

![fd2](foto/fd2.png)

code 
```
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title></title>
	<link rel="stylesheet" type="text/css" href="ex.css">	

</head>
<body>
	<div id="container">
		<header>
			<h1>Kontak dan pendaftaran</h1>
		</header>
		<nav>
			<a href="ex.html" >Home</a>
			<a href="artikel.html">Artikel</a>
			<a href="about.html" >About</a>
			<a href="kontak.html" class="bored">Kontak</a>
		</nav>


		<form action="proses.php" method="post" style="padding: 20px;">
			<fieldset>
				<legend>Isi Data anda dan hubungi kontak di bawah ini</legend>
				<p>
					<label for="nama">Nama</label>
					<input type="text" id="nama" name="nama">
				</p>
				<p>
					<label for="eama">Email</label>
					<input type="text" id="nama" name="nama">
				</p>
				<p>
					<label for="alamat">Alamat</label>
					<textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
				</p>
				<p>
					<label>Jenis Kelamin</label>
					<input id="jk_l" type="radio" name="kelamin" value="L" /><label
		for="jk_l">Laki-laki</label>
					<input id="jk_p" type="radio" name="kelamin" value="P" /><label
		for="jk_p">Perempuan</label>
				</p>

				<p><b>Kontak Saya</b></p>

				<div id="oke">
				
					<a href="email.com" class="room">Email</a>
					<a href="email.com" class="toom">Whatsapp</a>
					<a href="email.com" class="doom">Instagram</a>

				</div>
				
				
			</fieldset>
		</form>

	</div>
	
</body>
</html>
```

### 2. latihan praktikum

1. Buat kerangka layout

![ft1](foto/ft1.png)

2. Buat navigasi

![ft2](foto/ft2.png)

3. Membuat hero panel

![ft3](foto/ft3.png)

4. Mengatur layout main sidebar

![ft4](foto/ft4.png)

5. Membuat sidebar widget

![ft5](foto/ft5.png)

6. Mengatur footer

![ft6](foto/ft6.png)

7. menambahkan elemen lainnya pada content

![ft7](foto/ft7.png)

8. Menambahkan konten artikel

![ft8](foto/ft8.png)

### terimakasih 

