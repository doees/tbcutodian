# tbcutodian
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TB Custodian</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #eef2f3;
            text-align: center;
            color: #333;
        }
        header {
            background: linear-gradient(to right, #4facfe, #00f2fe);
            color: white;
            padding: 20px 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 20px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
        }
        .section {
            padding: 50px;
            background: white;
            margin: 30px auto;
            width: 80%;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
            border-radius: 15px;
            transition: transform 0.3s;
        }
        .section:hover {
            transform: scale(1.02);
        }
        button {
            background: #4facfe;
            color: white;
            padding: 12px 25px;
            border: none;
            cursor: pointer;
            border-radius: 8px;
            font-size: 16px;
            font-weight: bold;
            transition: background 0.3s;
        }
        button:hover {
            background: #00c6ff;
        }
        footer {
            background: #2c3e50;
            color: white;
            padding: 15px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>TB Custodian</h1>
        <nav>
            <ul>
                <li><a href="#home">Beranda</a></li>
                <li><a href="#prediction">Prediksi TB</a></li>
                <li><a href="#monitoring">Pemantauan Gejala</a></li>
                <li><a href="#doctors">Rekomendasi Dokter</a></li>
                <li><a href="#reminders">Pengingat Obat</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="section">
        <h2>Selamat Datang di TB Custodian</h2>
        <p>Solusi berbasis AI untuk deteksi dini, pemantauan, dan manajemen pengobatan TB.</p>
    </section>

    <section id="prediction" class="section">
        <h2>Prediksi TB Berdasarkan Citra Rontgen</h2>
        <p>Unggah gambar X-ray Anda untuk mendapatkan hasil analisis otomatis.</p>
        <button>Unggah X-ray</button>
    </section>

    <section id="monitoring" class="section">
        <h2>Pemantauan Gejala Pasien</h2>
        <p>Catat perkembangan gejala TB Anda untuk pemantauan lebih baik.</p>
        <button>Mulai Pemantauan</button>
    </section>

    <section id="doctors" class="section">
        <h2>Rekomendasi Dokter Spesialis</h2>
        <p>Cari dokter spesialis paru-paru terdekat di Indonesia.</p>
        <button>Cari Dokter</button>
    </section>

    <section id="reminders" class="section">
        <h2>Notifikasi Pengingat Obat</h2>
        <p>Atur pengingat otomatis agar tidak melewatkan jadwal pengobatan Anda.</p>
        <button>Atur Pengingat</button>
    </section>

    <footer>
        <p>&copy; 2025 TB Custodian. Semua Hak Dilindungi.</p>
    </footer>
</body>
</html>
