<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lorbelle Ganzan Portfolio</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Custom CSS -->
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

    <!-- Header Section -->
    <header class="header text-center text-white">
        <nav class="navbar navbar-expand-lg navbar-dark">
            <div class="container">
                <a class="navbar-brand" href="#">Lorbelle Ganzan</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                        <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
                        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                    </ul>
                </div>
            </div>
        </nav>
        <div class="profile-img mt-3">
            <img src="images/profile.jpg" alt="Lorbelle Ganzan" class="rounded-circle shadow-lg">
        </div>
        <h1 class="mt-3">Hello, I'm Lorbelle Ganzan</h1>
        <p>Student / Aspiring Web Developer</p>
        <a href="#skills" class="btn btn-light btn-lg mt-2">View My Skills</a>
    </header>

    <!-- About Section -->
    <section id="about" class="py-5 text-center">
        <div class="container">
            <h2>About Me</h2>
            <p>Hello! I'm <strong>Lorbelle Ganzan</strong>, a dedicated student learning web development and programming. I am passionate about coding and building creative solutions using HTML, CSS, JavaScript, and Java.</p>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-5 bg-light text-center">
        <div class="container">
            <h2>My Skills</h2>
            <div class="row justify-content-center mt-4">
                <div class="col-md-2 mb-3 skill-card">HTML</div>
                <div class="col-md-2 mb-3 skill-card">CSS</div>
                <div class="col-md-2 mb-3 skill-card">JavaScript</div>
                <div class="col-md-2 mb-3 skill-card">Java</div>
                <div class="col-md-2 mb-3 skill-card">Bootstrap</div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-5 text-center">
        <div class="container">
            <h2>Contact Me</h2>
            <p>Email: <strong>lorbelle@example.com</strong></p>
            <p>Phone: <strong>+63 912 345 6789</strong></p>
            <p>Connect with me on: 
                <a href="#" class="text-decoration-none">LinkedIn</a> | 
                <a href="#" class="text-decoration-none">GitHub</a>
            </p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="text-center text-white py-3 bg-dark">
        &copy; 2026 Lorbelle Ganzan
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <!-- Custom JS -->
    <script src="js/script.js"></script>
</body>
</html>
