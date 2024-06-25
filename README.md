# UAS-Pemrograman-Berorientasi-Objek
<!DOCTYPE html>
<html>
<head>
    <title>Form Percaharian Barang</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>
    <h1>Form Percaharian Barang</h1>
    <form>
        <!-- 1. Informasi Umum -->
        <div>
            <label for="nama_barang">Nama Barang:</label>
            <input type="text" id="nama_barang" name="nama_barang"><br><br>
            <label for="kode_barang">Kode Barang:</label>
            <input type="text" id="kode_barang" name="kode_barang"><br><br>
            <label for="jenis_barang">Jenis Barang:</label>
            <input type="text" id="jenis_barang" name="jenis_barang"><br><br>
            <label for="kategori_barang">Kategori Barang:</label>
            <input type="text" id="kategori_barang" name="kategori_barang"><br><br>
        </div>

        <!-- 2. Informasi Spesifikasi -->
        <div>
            <label for="jumlah">Jumlah:</label>
            <input type="number" id="jumlah" name="jumlah"><br><br>
            <label for="satuan">Satuan:</label>
            <input type="text" id="satuan" name="satuan"><br><br>
            <label for="harga_satuan">Harga Satuan:</label>
            <input type="number" id="harga_satuan" name="harga_satuan"><br><br>
            <label for="total_harga">Total Harga:</label>
            <input type="number" id="total_harga" name="total_harga" readonly><br><br>
        </div>

        <!-- 3. Informasi Pengiriman -->
        <div>
            <label for="tanggal_pengiriman">Tanggal Pengiriman:</label>
            <input type="date" id="tanggal_pengiriman" name="tanggal_pengiriman"><br><br>
            <label for="nama_pengirim">Nama Pengirim:</label>
            <input type="text" id="nama_pengirim" name="nama_pengirim"><br><br>
            <label for="alamat_pengirim">Alamat Pengirim:</label>
            <textarea id="alamat_pengirim" name="alamat_pengirim"></textarea><br><br>
            <label for="nama_penerima">Nama Penerima:</label>
            <input type="text" id="nama_penerima" name="nama_penerima"><br><br>
            <label for="alamat_penerima">Alamat Penerima:</label>
            <textarea id="alamat_penerima" name="alamat_penerima"></textarea><br><br>
        </div>

        <!-- 4. Informasi Pembayaran -->
        <div>
            <label for="metode_pembayaran">Metode Pembayaran:</label>
            <select id="metode_pembayaran" name="metode_pembayaran">
                <option value="Tunai">Tunai</option>
                <option value="Transfer">Transfer</option>
                <option value="Kartu Kredit">Kartu Kredit</option>
            </select><br><br>
            <label for="tanggal_pembayaran">Tanggal Pembayaran:</label>
            <input type="date" id="tanggal_pembayaran" name="tanggal_pembayaran"><br><br>
            <label for="jumlah_pembayaran">Jumlah Pembayaran:</label>
            <input type="number" id="jumlah_pembayaran" name="jumlah_pembayaran"><br><br>
        </div>

        <!-- 5. Informasi Catatan -->
        <div>
            <label for="catatan">Catatan Tambahan:</label>
            <textarea id="catatan" name="catatan"></textarea><br><br>
        </div>

        <!-- 6. Tanggal dan Waktu -->
        <div>
            <label for="tanggal">Tanggal:</label>
            <input type="date" id="tanggal" name="tanggal"><br><br>
            <label for="waktu">Waktu:</label>
            <input type="time" id="waktu" name="waktu"><br><br>
        </div>

        <!-- 7. Tanda Tangan -->
        <div>
            <label for="pengirim">Pengirim:</label>
            <input type="text" id="pengirim" name="pengirim"><br><br>
            <label for="penerima">Penerima:</label>
            <input type="text" id="penerima" name="penerima"><br><br>
        </div>

        <!-- 8. Keterangan -->
        <div>
            <label for="keterangan">Keterangan Tambahan:</label>
            <textarea id="keterangan" name="keterangan"></textarea><br><br>
        </div>

        <!-- 9. Tanggal dan Waktu -->
        <div>
            <label for="tanggal2">Tanggal:</label>
            <input type="date" id="tanggal2" name="tanggal2"><br><br>
            <label for="waktu2">Waktu:</label>
            <input type="time" id="waktu2" name="waktu2"><br><br>
        </div>

        <!-- 10. Tanda Tangan -->
        <div>
            <label for="pengirim2">Pengirim:</label>
            <input type="text" id="pengirim2" name="pengirim2"><br><br>
            <label for="penerima2">Penerima:</label>
            <input type="text" id="penerima2" name="penerima2"><br><br>
        </div>

        <button type="submit">Submit</button>
    </form>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <title>Form Pencarian Barang</title>
</head>
<body>
    <form action="proses.php" method="GET">
        <label for="search">Cari Nama Barang:</label>
        <input type="text" id="search" name="search" placeholder="Masukkan nama barang..." />
        <input type="submit" value="Cari" />
    </form>
</body>
</html>
