<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio | Dimas Satria</title>
    <!-- Font Google: Plus Jakarta Sans -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <!-- Ikon Boxicons -->
    <link href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css" rel="stylesheet">
    <!-- Hubungkan ke CSS -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navigasi -->
    <header class="navbar">
        <div class="container nav-container">
            <a href="#" class="logo">Portofolio<span>.</span></a>
            
            <nav class="nav-links" id="nav-links">
                <a href="#home" class="active">Beranda</a>
                <a href="#about">Tentang</a>
                <a href="#skills">Keahlian</a>
                <a href="#projects">Proyek</a>
                <a href="#contact">Kontak</a>
            </nav>

            <div class="nav-actions">
                <button id="theme-toggle" class="icon-btn" aria-label="Ganti Tema">
                    <i class='bx bx-moon'></i>
                </button>
                <button id="menu-toggle" class="icon-btn mobile-only" aria-label="Menu">
                    <i class='bx bx-menu'></i>
                </button>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container hero-container">
            <div class="hero-content fade-in">
                <span class="badge">👋 Halo, selamat datang!</span>
                <h1>Saya <span>Nama Anda</span>,<br>Creative Content & Web Enthusiast</h1>
                <p>Membangun pengalaman digital yang bersih, fungsional, dan berorientasi pada detail untuk membantu ide dan brand berkembang secara efektif.</p>
                <div class="hero-buttons">
                    <a href="#projects" class="btn btn-primary">Lihat Karya</a>
                    <a href="#contact" class="btn btn-outline">Hubungi Saya</a>
                </div>
            </div>
            <div class="hero-image fade-in">
                <div class="image-wrapper">
                    <!-- Ganti URL gambar di bawah dengan foto profil Anda -->
                    <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&w=600&q=80" alt="Foto Profil">
                </div>
            </div>
        </div>
    </section>

    <!-- Tentang Saya -->
    <section id="about" class="section bg-alt">
        <div class="container">
            <div class="section-header fade-in">
                <h2>Tentang Saya</h2>
                <p>Sekilas mengenai latar belakang dan dedikasi saya dalam berkarya</p>
            </div>
            <div class="about-grid fade-in">
                <div class="about-text">
                    <p>Saya adalah seorang profesional kreatif dengan ketertarikan mendalam pada pengembangan web, desain visual, dan penyusunan konten digital. Bagi saya, setiap proyek adalah perpaduan antara estetika dan penyampaian pesan yang tepat sasaran.</p>
                    <p>Dengan pengalaman mengerjakan berbagai proyek mulai dari antarmuka web modern, tata letak editorial, hingga identitas visual, saya selalu mengutamakan struktur yang rapi dan pengalaman pengguna yang nyaman.</p>
                </div>
                <div class="about-stats">
                    <div class="stat-card">
                        <h3>3+</h3>
                        <p>Tahun Pengalaman</p>
                    </div>
                    <div class="stat-card">
                        <h3>25+</h3>
                        <p>Proyek Selesai</p>
                    </div>
                    <div class="stat-card">
                        <h3>15+</h3>
                        <p>Klien Puas</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Keahlian -->
    <section id="skills" class="section">
        <div class="container">
            <div class="section-header fade-in">
                <h2>Keahlian & Tools</h2>
                <p>Teknologi dan perangkat lunak yang sering saya gunakan</p>
            </div>
            <div class="skills-grid fade-in">
                <div class="skill-card">
                    <i class='bx bxl-html5'></i>
                    <h3>HTML5 & CSS3</h3>
                    <p>Struktur semantik & tata letak responsif modern.</p>
                </div>
                <div class="skill-card">
                    <i class='bx bxl-javascript'></i>
                    <h3>JavaScript</h3>
                    <p>Interaktivitas dinamis dan manipulasi DOM.</p>
                </div>
                <div class="skill-card">
                    <i class='bx bxs-pen'></i>
                    <h3>Editorial & Copywriting</h3>
                    <p>Penulisan terstruktur, penyuntingan naskah, & SEO.</p>
                </div>
                <div class="skill-card">
                    <i class='bx bxs-palette'></i>
                    <h3>Desain Grafis & UI</h3>
                    <p>Adobe Illustrator, Figma, & layout publikasi.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Portofolio Proyek -->
    <section id="projects" class="section bg-alt">
        <div class="container">
            <div class="section-header fade-in">
                <h2>Proyek Pilihan</h2>
                <p>Beberapa karya terbaik yang pernah saya kerjakan</p>
            </div>

            <!-- Filter Kategori -->
            <div class="filter-buttons fade-in">
                <button class="filter-btn active" data-filter="all">Semua</button>
                <button class="filter-btn" data-filter="web">Web Dev</button>
                <button class="filter-btn" data-filter="design">Desain & Branding</button>
                <button class="filter-btn" data-filter="editorial">Editorial</button>
            </div>

            <!-- Grid Proyek -->
            <div class="projects-grid fade-in">
                <!-- Proyek 1 -->
                <article class="project-card" data-category="web">
                    <div class="project-img">
                        <img src="https://images.unsplash.com/photo-1460925895917-afdab827c52f?auto=format&fit=crop&w=600&q=80" alt="Proyek Web">
                    </div>
                    <div class="project-info">
                        <span class="project-tag">Web Development</span>
                        <h3>Portal Berita & Olahraga</h3>
                        <p>Website portal berita responsif dengan sistem navigasi cepat dan tampilan baca yang nyaman.</p>
                        <a href="#" class="project-link">Lihat Detail <i class='bx bx-right-arrow-alt'></i></a>
                    </div>
                </article>

                <!-- Proyek 2 -->
                <article class="project-card" data-category="design">
                    <div class="project-img">
                        <img src="https://images.unsplash.com/photo-1626785774573-4b799315345d?auto=format&fit=crop&w=600&q=80" alt="Proyek Desain">
                    </div>
                    <div class="project-info">
                        <span class="project-tag">Desain & Branding</span>
                        <h3>Identitas Visual UMKM Kuliner</h3>
                        <p>Perancangan logo vektor, tipografi khusus, dan kemasan untuk brand kuliner lokal.</p>
                        <a href="#" class="project-link">Lihat Detail <i class='bx bx-right-arrow-alt'></i></a>
                    </div>
                </article>

                <!-- Proyek 3 -->
                <article class="project-card" data-category="editorial">
                    <div class="project-img">
                        <img src="https://images.unsplash.com/photo-1586281380349-632531db7ed4?auto=format&fit=crop&w=600&q=80" alt="Proyek Editorial">
                    </div>
                    <div class="project-info">
                        <span class="project-tag">Editorial</span>
                        <h3>Tata Letak Majalah Digital</h3>
                        <p>Desain tata letak publikasi multi-halaman dengan hierarki tipografi yang kuat.</p>
                        <a href="#" class="project-link">Lihat Detail <i class='bx bx-right-arrow-alt'></i></a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- Kontak -->
    <section id="contact" class="section">
        <div class="container contact-container fade-in">
            <div class="section-header">
                <h2>Mari Berkolaborasi</h2>
                <p>Punya ide proyek atau tawaran kerja sama? Kirimkan pesan di bawah ini.</p>
            </div>

            <form id="contact-form" class="contact-form">
                <div class="form-group">
                    <input type="text" id="name" placeholder="Nama Lengkap" required>
                </div>
                <div class="form-group">
                    <input type="email" id="email" placeholder="Alamat Email" required>
                </div>
                <div class="form-group">
                    <textarea id="message" rows="5" placeholder="Tulis pesan Anda di sini..." required></textarea>
                </div>
                <button type="submit" class="btn btn-primary full-width">Kirim Pesan</button>
                <p id="form-status" class="form-status"></p>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container footer-container">
            <p>&copy; 2026 Nama Anda. Hak Cipta Dilindungi.</p>
            <div class="social-links">
                <a href="#" aria-label="LinkedIn"><i class='bx bxl-linkedin'></i></a>
                <a href="#" aria-label="GitHub"><i class='bx bxl-github'></i></a>
                <a href="#" aria-label="Instagram"><i class='bx bxl-instagram'></i></a>
            </div>
        </div>
    </footer>

    <!-- Hubungkan ke JavaScript -->
    <script src="script.js"></script>
</body>
</html>
