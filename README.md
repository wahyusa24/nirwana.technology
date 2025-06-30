<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nirwana Technology - Service Komputer & HP Profesional</title>
    <link rel="stylesheet" href="style.css">
    <link rel="icon" href="https://placehold.co/32x32/007bff/ffffff?text=NT" type="image/png">
</head>
<body>

    <header>
        <div class="container">
            <h1 class="logo">Nirwana Technology</h1>
            <nav>
                <ul>
                    <li><a href="#layanan">Layanan</a></li>
                    <li><a href="#antar-jemput">Antar Jemput</a></li>
                    <li><a href="#kontak">Hubungi Kami</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="hero">
            <div class="container">
                <h2>Solusi Cepat, Tepat, dan Terpercaya untuk Gadget Anda</h2>
                <p>Spesialis perbaikan Komputer, Laptop, Handphone (Android), dan iPhone.</p>
                <a href="#antar-jemput" class="cta-button">Minta Layanan Antar Jemput Sekarang</a>
            </div>
        </section>

        <section id="layanan">
            <div class="container">
                <h2>Layanan Profesional Kami</h2>
                <div class="layanan-grid">
                    <div class="layanan-item">
                        <img src="https://placehold.co/100/e8e8e8/000?text=💻" alt="Ikon Service Komputer">
                        <h3>Service Komputer & Laptop</h3>
                        <p>Instal Ulang OS (Windows, MacOS), perbaikan hardware (motherboard, RAM, HDD), basmi virus, dan upgrade performa.</p>
                    </div>
                    <div class="layanan-item">
                        <img src="https://placehold.co/100/e8e8e8/000?text=📱" alt="Ikon Service Handphone">
                        <h3>Service Handphone (Android)</h3>
                        <p>Ganti Baterai, Ganti LCD, perbaikan sinyal, flashing ROM, lupa pola/password, dan perbaikan mati total.</p>
                    </div>
                    <div class="layanan-item">
                        <img src="https://placehold.co/100/e8e8e8/000?text=" alt="Ikon Service iPhone">
                        <h3>Service iPhone</h3>
                        <p>Layanan khusus semua model iPhone: ganti baterai, ganti LCD original, perbaikan baseband, bypass, dan water damage.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="antar-jemput">
            <div class="container">
                <h2>Form Layanan Antar Jemput</h2>
                <p>Tidak perlu repot keluar rumah, kami yang akan jemput perangkat Anda. Gratis untuk wilayah tertentu!</p>
                <form id="service-form" class="service-form">
                    <div class="form-group">
                        <label for="nama">Nama Lengkap:</label>
                        <input type="text" id="nama" name="nama" placeholder="Contoh: Budi Santoso" required>
                    </div>
                    <div class="form-group">
                        <label for="telepon">Nomor WhatsApp Aktif:</label>
                        <input type="tel" id="telepon" name="telepon" placeholder="Contoh: 081234567890" required>
                    </div>
                    <div class="form-group">
                        <label for="alamat">Alamat Lengkap Penjemputan:</label>
                        <textarea id="alamat" name="alamat" rows="3" placeholder="Contoh: Jl. Merdeka No. 10, Jakarta Selatan" required></textarea>
                    </div>
                    <div class="form-group">
                        <label for="perangkat">Jenis Perangkat:</label>
                        <select id="perangkat" name="perangkat" required>
                            <option value="">-- Pilih Jenis Perangkat --</option>
                            <option value="Komputer/Laptop">Komputer / Laptop</option>
                            <option value="Handphone Android">Handphone Android</option>
                            <option value="iPhone">iPhone</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label for="keluhan">Jelaskan Keluhan/Kerusakan:</label>
                        <textarea id="keluhan" name="keluhan" rows="4" placeholder="Contoh: Laptop mati total, layar HP retak, dll." required></textarea>
                    </div>
                    <button type="submit" class="cta-button">Kirim Permintaan Jemput via WhatsApp</button>
                </form>
            </div>
        </section>

        <section id="kontak">
            <div class="container">
                <h2>Punya Pertanyaan?</h2>
                <p>Jangan ragu untuk berkonsultasi langsung dengan teknisi kami. Klik tombol di bawah untuk terhubung via WhatsApp.</p>
                <a href="https://wa.me/6283819474817?text=Halo%20Nirwana%20Technology,%20saya%20ingin%20bertanya%20tentang%20layanan%20service." class="whatsapp-button" target="_blank">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/WhatsApp_icon.png" alt="Logo WhatsApp">
                    Chat Langsung di WhatsApp
                </a>
                <p class="whatsapp-info">Nomor Kami: <strong>0838-1947-4817</strong></p>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2025 Nirwana Technology. Semua Hak Cipta Dilindungi.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
