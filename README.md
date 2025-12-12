<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Profesional | JS</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <nav class="navbar">
    <div class="initials">Timz</div> 
    
    <button class="nav-toggle" id="navToggle">☰</button> 
    
    <ul class="nav-links" id="navLinks">
        <li><a href="#projects" class="cta-button">Projects</a></li>
        <li><a href="#about" class="cta-button">About Me</a></li>
        <li><a href="#contact" class="cta-button">Contact</a></li> 
    </ul>
</nav>

    
    <section id="about" class="main-section about-me">
        <header class="about-header">
            <div class="profile-container">
                <img src="Timz.jpg" alt="Foto Profesional Anda" class="profile-photo"> 
                </div>
            
            <h1 class="full-name">Timotius Vasco Pandu Dewanata Ardi</h1> <p class="expertise">Pelajar Jurusan PPLG | Mempelajari UI/UX </p> 
            <p class="bio-summary">
                Pelajar Jurusan PPLG yang bersemangat dalam menjembatani teknologi dan desain. Memiliki minat yang besar terhadap UI/UX dan Desain juga didukung oleh pemahamam logika dasar
            </p>
        </header>
    </section>

    <section id="skills" class="main-section skills">
        <h2>Keahlian Utama</h2>
        <div class="skills-grid">
            
            <div class="skill-card">
                <h3>HTML dasar</h3>
                <p>Menguasai HTML dasar dengan baik, juga ingin belajar lebih dalam mengenai HTML</p>
            </div>
            
            <div class="skill-card">
                <h3>CSS & Desain</h3>
                <p>Mampu membuat desain poster atau bahkan Website, untuk keperluan Komersial dan Profesional </p>
            </div>
            
            <div class="skill-card">
                <h3>Soft Skill Debate</h3>
                <p>Mampu melakukan debat dengan topik ringan didukung dengan pemahaman argumen lawan dan penggunaan logika yang koheren sesuai dengan topik debat.</p>
            </div>
            
        </div>
    </section>

    <section id="projects" class="main-section projects">
        <h2>Proyek Unggulan</h2>

        <table class="project-table">
            <thead>
                <tr>
                    <th>Foto/Mockup</th>
                    <th>Judul Proyek & Deskripsi Singkat</th>
                </tr>
            </thead>
            <tbody>
    <tr>
        <td class="project-img-cell" data-label="Foto/Mockup">
            <img src="Animasi login interaktif.jpg" alt="Project 1: Aplikasi XYZ">
        </td>
        <td data-label="Proyek & Deskripsi">
            <h3>Animasi login interaktif</h3>
            <p>Desain page login yang interaktif dan tidak monoton menggunakan HTML&CSS murni dengan integrasi animasi CSS minimal </p>
        </td>
    </tr>
    <tr>
        <td class="project-img-cell" data-label="Foto/Mockup">
            <img src="projek .jpg" alt="Project 2: Website Pribadi">
        </td>
        <td data-label="Proyek & Deskripsi">
            <h3>Desain Poster</h3>
            <p>Mendesain poster untuk peraturan Lab Komputer menggunakan Canva</p>
        </td>
    </tr>
    <tr>
        <td class="project-img-cell" data-label="Foto/Mockup">
            <img src="Project Gundam.jpg" alt="Project 3: Analisis Data">
        </td>
        <td data-label="Proyek & Deskripsi">
            <h3>Merakit Gundam</h3>
            <p>Merakit Gundam dari 0 dengan menggunakan tahapan dan logika dasar supaya Gundam bisa sempurna</p>
        </td>
    </tr>
</tbody>

        </table>
    </section>

    <footer id="contact">
        <p>&copy; 2025 Timz. | <a href="mailto:ljcom209@gmail.com">ljcom209@gmail.com</a></p>
        </footer>
    
    <script>
    document.getElementById('navToggle').addEventListener('click', function() {
        document.getElementById('navLinks').classList.toggle('active');
    });
</script>

</body>
</html>
