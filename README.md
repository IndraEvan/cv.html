cv-indra-evan/
├── index.html
└── style.css

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>CV - Indra Evan</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="cv">

    <!-- HEADER -->
    <div class="header">
        <div>
            <h1>INDRA<br>EVAN</h1>
            <p class="subtitle">ADMINISTRASI & AKUNTANSI</p>
        </div>
    </div>

    <hr>

    <!-- PROFIL -->
    <section>
        <h2>PROFIL</h2>
        <p>
            Lulusan MTs 7 yang memiliki keterampilan akuntansi dan organisasi yang baik.
            Berpengalaman dalam penjualan serta pengelolaan barang dengan rapi dan sistematis.
            Aktif mengikuti berbagai kursus untuk memperkuat kemampuan profesional.
        </p>
    </section>

    <hr>

    <!-- CONTENT -->
    <div class="content">

        <!-- LEFT -->
        <div class="left">

            <h2>KONTAK</h2>
            <ul class="contact">
                <li>📞 08xxxxxxxxxx</li>
                <li>📧 email@example.com</li>
                <li>🌐 github.com/username</li>
                <li>📍 Indonesia</li>
            </ul>

            <h2>PENDIDIKAN</h2>
            <p><strong>MTs Negeri 7</strong><br>
            Lulus</p>

            <h2>KEMAMPUAN</h2>
            <ul>
                <li>Dasar Akuntansi</li>
                <li>Administrasi dan Organisasi</li>
                <li>Penjualan</li>
                <li>Manajemen Stok Barang</li>
                <li>Komunikasi Dasar</li>
            </ul>

        </div>

        <!-- RIGHT -->
        <div class="right">

            <h2>PENGALAMAN</h2>
            <p><strong>Staf Penjualan</strong></p>
            <ul>
                <li>Melayani pelanggan dengan baik dan ramah</li>
                <li>Mengatur dan mencatat barang masuk dan keluar</li>
                <li>Menjaga kerapihan dan ketersediaan stok</li>
            </ul>

            <h2>KURSUS</h2>
            <ul>
                <li>Kursus Dasar Akuntansi</li>
                <li>Pelatihan Administrasi</li>
                <li>Pelatihan Manajemen Organisasi</li>
            </ul>

        </div>
    </div>

</div>

</body>
</html>

body {
    font-family: Arial, Helvetica, sans-serif;
    background: #f4f4f4;
    margin: 0;
    padding: 20px;
}

.cv {
    max-width: 900px;
    margin: auto;
    background: #fff;
    padding: 40px;
}

.header h1 {
    font-size: 40px;
    letter-spacing: 3px;
    margin: 0;
}

.subtitle {
    letter-spacing: 4px;
    color: #555;
}

hr {
    margin: 30px 0;
}

h2 {
    letter-spacing: 3px;
    font-size: 16px;
    border-bottom: 2px solid #000;
    display: inline-block;
    padding-bottom: 5px;
}

.content {
    display: flex;
    gap: 40px;
}

.left {
    width: 35%;
}

.right {
    width: 65%;
}

ul {
    padding-left: 18px;
}

.contact {
    list-style: none;
    padding: 0;
}

.contact li {
    margin-bottom: 8px;
}

p {
    line-height: 1.6;
}
