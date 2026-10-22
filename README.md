# Pale-chrome

<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Person</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <section class="contact-section" id="contact">
        <div class="container">

            <h2>Contact Person</h2>
            <p class="subtitle">
                Hubungi kami jika Anda memiliki pertanyaan
                atau membutuhkan informasi lebih lanjut.
            </p>

            <div class="contact-container">

                <!-- Informasi Kontak -->
                <div class="contact-info">
                    <h3>Informasi Kontak</h3>
                    <p>Silakan hubungi kami melalui informasi berikut.</p>

                    <div class="contact-item">
                        <div class="icon">📍</div>
                        <div>
                            <h4>Alamat</h4>
                            <p>Jl. Contoh No. 123, Indonesia</p>
                        </div>
                    </div>

                    <div class="contact-item">
                        <div class="icon">📞</div>
                            <h4>Telepon</h4>
                            <p>0812-3456-7890</p>
                        </div>
                    </div>

                    <div class="contact-item">
                        <div class="icon">✉️</div>
                        <div>
                            <h4>Email</h4>
                            <p>info@website.com</p>
                        </div>
                    </div>

                    <div class="contact-item">
                        <div class="icon">🕒</div>
                        <div>
                            <h4>Jam Operasional</h4>
                            <p>Senin - Jumat, 08.00 - 16.00</p>
                        </div>
                    </div>
                </div>

                <!-- Formulir Kontak -->
                <div class="contact-form">
                    <h3>Kirim Pesan</h3>

                    <form action="#" method="post">
                        <label for="nama">Nama Lengkap</label>
                        <input
                            type="text"
                            id="nama"
                            name="nama"
                            placeholder="Masukkan nama Anda"
                            required
                        >

                        <label for="email">Email</label>
                        <input
                            type="email"
                            id="email"
                            name="email"
                            placeholder="Masukkan email Anda"
                            required
                        >

                        <label for="pesan">Pesan</label>
                        <textarea
                            id="pesan"
                            name="pesan"
                            rows="5"
                            placeholder="Tuliskan pesan Anda..."
                            required
                        ></textarea>

                        <button type="submit">Kirim Pesan</button>
                    </form>
                </div>

            </div>
        </div>
    </section>

</body>
</html>
