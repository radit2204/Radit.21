# Radit.21
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Rangga Motor</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>Rangga Motor</h1>
    <p>Temukan Sperpart Yang Pengen Anda Cari</p>
  </header>

  <nav>
    <a href="#produk">Produk</a>
    <a href="#tentang">Tentang Kami</a>
    <a href="#kontak">Kontak</a>
  </nav>

  <section id="produk">
    <h2>Daftar Motor</h2>
    <div class="produk-container">
      <div class="produk">
        <img src="1cb893af-568f-4fd6-bfbd-319a86908c93" alt="Motor 1">
        <h3>Packing Vario 150</h3>
        <p>Harga: Rp80.000</p>
      </div>
      <div class="produk">
        <img src="https://via.placeholder.com/250x150" alt="Motor 2">
        <h3>Head vario 150</h3>
        <p>Harga: Rp900.000</p>
      </div>
      <div class="produk">
        <img src="https://via.placeholder.com/250x150" alt="Motor 3">
        <h3>Ecu Juken </h3>
        <p>Harga: Rp1.400.000</p>
      </div>
    </div>
  </section>

  <section id="tentang">
    <h2>Tentang Kami</h2>
    <p>Kami menjual berbagai sperpart motor berkualitas dari merek ternama seperti Honda, Yamaha, dan Vespa.</p>
  </section>

  <section id="kontak">
    <h2>Hubungi Kami</h2>
    <p>Email: ranggaaditya2114@gmail.com</p>
    <p>Instagram: <a href="#">@ranggaid.21</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Rangga Motor. All rights reserved.</p>
  </footer>

</body>
</html>

<section id="pesan">
  <h2>Form Pemesanan</h2>
  <form action="#" method="post" class="form-pesan">
    <label for="nama">Nama Lengkap:</label>
    <input type="text" id="nama" name="nama" required>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>

    <label for="motor">Pilih Motor:</label>
    <select id="motor" name="motor" required>
      <option value="">-- Pilih Motor --</option>
      <option value="Packing vario">Packing Vario 150</option>
      <option value="Head">Head vario 150</option>
      <option value="Ecu">EcuJ uken</option>
    </select>

    <label for="pesan">Catatan Tambahan:</label>
    <textarea id="pesan" name="pesan" rows="4"></textarea>

    <button type="submit">Kirim Pesanan</button>
  </form>
</section>
