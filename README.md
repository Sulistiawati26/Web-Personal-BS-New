<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Website</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.2/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <style>
        .hero-section {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('/api/placeholder/1920/1080');
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            align-items: center;
            color: white;
        }
        .about-section {
            padding: 100px 0;
            background-color: #f8f9fa;
        }
        .gallery-section {
            padding: 100px 0;
        }
        .gallery-item {
            margin-bottom: 30px;
            transition: transform 0.3s;
        }
        .gallery-item:hover {
            transform: scale(1.05);
        }
        .contact-section {
            padding: 100px 0;
            background-color: #343a40;
            color: white;
        }
        .social-icons a {
            color: white;
            font-size: 24px;
            margin: 0 10px;
            transition: color 0.3s;
        }
        .social-icons a:hover {
            color: #007bff;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">Sulistiawati</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#home">Beranda</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">Tentang Saya</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#gallery">Galeri</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Kontak</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-section">
        <div class="container text-center">
            <h1 class="display-1 mb-4">Sulistiawati</h1>
            <h3 class="mb-4">Web Developer & Designer</h3>
            <a href="#contact" class="btn btn-primary btn-lg">Kontak Saya</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about-section">
        <div class="container">
            <div class="row">
                <div class="col-lg-6">
                    <img src="Foto2.jpg" alt="About Me" class="img-fluid rounded">
                </div>
                <div class="col-lg-6">
                    <h2 class="mb-4">Tentang Saya</h2>
                    <p class="lead">Halo! Saya Sulistiawati, pengembang dan desainer web yang bersemangat dengan pengalaman lebih dari 5 tahun dalam menciptakan situs web yang indah dan fungsional.</p>
                    <p>Saya ahli dalam pengembangan front-end, desain responsif, dan pengalaman pengguna. Tujuan saya adalah membangun situs web yang tidak hanya tampak hebat tetapi juga memberikan pengalaman pengguna yang luar biasa.</p>
                    <div class="mt-4">
                        <h4>Kemampuan:</h4>
                        <div class="progress mb-3">
                            <div class="progress-bar" style="width: 90%">HTML/CSS</div>
                        </div>
                        <div class="progress mb-3">
                            <div class="progress-bar" style="width: 85%">JavaScript</div>
                        </div>
                        <div class="progress mb-3">
                            <div class="progress-bar" style="width: 80%">React</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="gallery-section">
        <div class="container">
            <h2 class="text-center mb-5">Galeri Saya</h2>
            <div class="row">
                <div class="col-lg-4 col-md-6 gallery-item">
                    <img src="Foto1.jpg" alt="Project 1" class="img-fluid rounded">
                </div>
                <div class="col-lg-4 col-md-6 gallery-item">
                    <img src="Foto3.jpg" alt="Project 2" class="img-fluid rounded">
                </div>
                <div class="col-lg-4 col-md-6 gallery-item">
                    <img src="Foto4.webp" alt="Project 3" class="img-fluid rounded">
                </div>
                <div class="col-lg-4 col-md-6 gallery-item">
                    <img src="Foto5.jpg" alt="Project 4" class="img-fluid rounded">
                </div>
                <div class="col-lg-4 col-md-6 gallery-item">
                    <img src="Foto6.jpg" alt="Project 5" class="img-fluid rounded">
                </div>
                <div class="col-lg-4 col-md-6 gallery-item">
                    <img src="Foto7.jpg" alt="Project 6" class="img-fluid rounded">
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact-section">
        <div class="container">
            <h2 class="text-center mb-5">Kontak Saya</h2>
            <div class="row justify-content-center">
                <div class="col-lg-6">
                    <form>
                        <div class="mb-3">
                            <input type="text" class="form-control" placeholder="Nama Anda">
                        </div>
                        <div class="mb-3">
                            <input type="email" class="form-control" placeholder="Email Anda">
                        </div>
                        <div class="mb-3">
                            <textarea class="form-control" rows="5" placeholder="Pesan Anda"></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary w-100">Kirim Pesan</button>
                    </form>
                    <div class="social-icons text-center mt-5">
                        <a href="#"><i class="fab fa-facebook"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-linkedin"></i></a>
                        <a href="#"><i class="fab fa-github"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-4">
        <p class="mb-0">© 2024 Sulistiawati. Semua hak dilindungi undang-undang.</p>
    </footer>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.2/js/bootstrap.bundle.min.js"></script>
</body>
</html>
