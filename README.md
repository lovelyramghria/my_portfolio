<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Lovely | Python Django Developer</title>

    <!-- Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" />
    <!-- Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
    <!-- Custom CSS -->
    <!-- <link rel="stylesheet" href="style.css" /> -->
    <style>
        /* --------------------
 Global Theme Styling
--------------------- */
body {
    margin: 0;
    font-family: "Poppins", sans-serif;
    background: #0e0e0e;
    color: white;
}

section {
    padding: 100px 0;
}

/* --------------------
 Navbar (Glass Effect)
--------------------- */
.glass-nav {
    background: rgba(15, 15, 15, 0.5);
    backdrop-filter: blur(10px);
    padding: 15px 0;
}

/* --------------------
 Hero Section
--------------------- */
#hero {
    background: url("bg.jpg") no-repeat center/cover;
    height: 100vh;
    position: relative;
}

#hero::after {
    content: "";
    position: absolute;
    left: 0;
    top: 0;
    height: 100%;
    width: 100%;
    background: rgba(5, 5, 5, 0.65);
}

#hero .container {
    position: relative;
    z-index: 10;
}

.hero-title {
    font-size: 55px;
}

.highlight {
    color: #a45bff;
}

.hero-subtitle {
    font-size: 20px;
    opacity: 0.8;
}

/* --------------------
 Section Headings
--------------------- */
.section-title {
    font-size: 40px;
    font-weight: bold;
    color: #a45bff;
    margin-bottom: 30px;
}

/* --------------------
 About Section
--------------------- */
.about-text {
    font-size: 20px;
    max-width: 800px;
    margin: 15px auto;
    line-height: 1.7;
}

/* --------------------
 Skill Badges
--------------------- */
.skills-badges {
    margin-top: 20px;
}

.badge-skill {
    display: inline-block;
    background: linear-gradient(45deg, #7f49ff, #c27cff);
    padding: 12px 25px;
    border-radius: 30px;
    font-size: 18px;
    margin: 10px;
    font-weight: 600;
    color: #fff;
    box-shadow: 0 0 15px rgba(164, 91, 255, 0.5);
    transition: 0.3s;
}

.badge-skill:hover {
    transform: scale(1.1);
}

/* --------------------
 Projects Section
--------------------- */
.project-card {
    background: #1a1a1a;
    padding: 25px;
    border-radius: 18px;
    transition: 0.3s;
    border: 1px solid #3b3b3b;
}

.project-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 0 20px rgba(164, 91, 255, 0.5);
}

.project-card h4 {
    color: #d3b5ff;
    font-size: 22px;
    font-weight: bold;
}

.tech {
    font-size: 14px;
    opacity: 0.7;
}

/* --------------------
 Contact Section
--------------------- */
.social {
    font-size: 25px;
    margin: 10px;
    color: #a45bff;
    transition: 0.3s;
}

.social:hover {
    color: white;
    transform: scale(1.2);
}

/* --------------------
 Footer
--------------------- */
footer {
    text-align: center;
    padding: 20px;
    background: #111;
    margin-top: 50px;
    color: #8d8d8d;
}
/* Modal Background Black */
.modal-content {
    background-color: #322f2f !important;   /* Black background */
    color: white !important;             /* White text so it is readable */
    border-radius: 10px;
}

/* Make heading colors visible */
.modal-content .text-primary {
    color: #4da3ff !important;
}

.modal-content .text-success {
    color: #4dff88 !important;
}

.modal-content ul li {
    color: white !important;
}

.modal-header h5 {
    color: white !important;
}

.modal-header .btn-close {
    filter: invert(1); /* Make close button white */
}

    </style>
</head>

<body>
    <!-- Navbar -->
    <nav class="navbar navbar-dark navbar-expand-lg fixed-top glass-nav">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#">Lovely</a>
            <button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#navMenu">
                <span class="fa fa-bars text-white"></span>
            </button>

            <div class="collapse navbar-collapse" id="navMenu">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a href="#hero" class="nav-link">Home</a></li>
                    <li class="nav-item"><a href="#about" class="nav-link">About</a></li>
                    <li class="nav-item"><a href="#skills" class="nav-link">Skills</a></li>
                    <li class="nav-item"><a href="#projects" class="nav-link">Projects</a></li>
                    <li class="nav-item"><a href="#contact" class="nav-link">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="hero" class="d-flex align-items-center">
        <div class="container text-center">
            <h1 class="fw-bold hero-title">Hi, I'm <span class="highlight">Lovely</span></h1>
            <h2 class="typing mt-3"></h2>

            <p class="mt-3 hero-subtitle">
                Python Django Developer | Full Stack Developer | Backend Developer
            </p>

            <a href="#projects" class="btn btn-primary mt-3">View Projects</a>
            <a href="" class="btn btn-outline-light mt-3">Download Resume</a>
        </div>
    </section>

    <!-- About -->
    <section id="about">
        <div class="container text-center">
            <h2 class="section-title">About Me</h2>

            <p class="about-text">
                My name is Lovely. I completed 6 months Full-Stack Development training 
                from ThinkNext Technologies Pvt Ltd and a 45-day internship 
                in Python Django at PAL InfoCom Technologies Pvt Ltd.
            </p>

            <p class="about-text">
                I completed BCA from Modern Group of Colleges under PTU University.
                I have completed 3 full-stack projects:
                <b>Hospital Management System, FoodZoon Website, Employee Management System.</b>
            </p>
        </div>
    </section>

    <!-- Skills -->
    <section id="skills">
        <div class="container text-center">
            <h2 class="section-title">Skills</h2>

            <div class="skills-badges">
                <span class="badge-skill">HTML</span>
                <span class="badge-skill">CSS</span>
                <span class="badge-skill">Bootstrap</span>
                <span class="badge-skill">Python</span>
                <span class="badge-skill">Django</span>
                <span class="badge-skill">SQL</span>
            </div>
        </div>
    </section>

    <!-- Projects -->
    <section id="projects">
        <div class="container text-center">
            <h2 class="section-title">Projects</h2>

            <div class="row g-4 justify-content-center">

                <div class="col-md-4">
                    <div class="project-card">
                        <h4>Hospital Management System</h4>
                        <p>Patient records, doctor scheduling & admin panel.</p>
                        <span class="tech">Python | Django | SQL</span><br>

                        <a href="https://github.com/lovelyramghria/HospitalManageMent_System"
                           target="_blank" class="btn btn-sm btn-outline-info mt-2">GitHub Link</a>

                        <!-- View Details Button -->
                        <button class="btn btn-sm btn-primary mt-2" data-bs-toggle="modal" data-bs-target="#hospitalModal">
                            View Details
                        </button>
                    </div>
                </div>

                <div class="col-md-4">
                    <div class="project-card">
                        <h4>FoodZoon Website</h4>
                        <p>Online food ordering website with cart & dynamic menu.</p>
                        <span class="tech">HTML | CSS | JS | Django</span><br>
                        <a href="https://github.com/lovelyramghria/FOODZONE" class="btn btn-sm btn-outline-info mt-2">GitHub Link</a>
                        <!-- View Details Button -->
                        <button class="btn btn-sm btn-primary mt-2" data-bs-toggle="modal" data-bs-target="#FoodModal">
                            View Details
                        </button>
                    </div>
                </div>

                <div class="col-md-4">
                    <div class="project-card">
                        <h4>Employee Management System</h4>
                        <p>CRUD system to manage employee data & reports.</p>
                        <span class="tech">Python | Django | SQL</span><br>
                        <a href="https://github.com/lovelyramghria/employemanagement" class="btn btn-sm btn-outline-info mt-2">GitHub Link</a>
                        <!-- View Details Button -->
                        <button class="btn btn-sm btn-primary mt-2" data-bs-toggle="modal" data-bs-target="#empModal">
                            View Details
                        </button>
                    </div>
                </div>

            </div>

            <!-- Resume Button -->
            <a href="Lovely_Resume.pdf" class="btn btn-primary mt-4">Download Resume</a>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact">
        <div class="container text-center">
            <h2 class="section-title">Contact Me</h2>

            <p>Email: <b>lovelyramghria39@gamil.com</b></p>
            <p>Phone: <b>+91 7743020641</b></p>
            <p>Current Location: <b>Mohali,Punjab</b></p>

            <div class="mt-4">
                <a class="social" href="https://www.linkedin.com/in/lovely-ramgarhia-746049396/?trk=opento_sprofile_details"><i class="fab fa-linkedin"></i></a>
                <a class="social" href="https://github.com/lovelyramghria?tab=repositories"><i class="fab fa-github"></i></a>
                <a class="social" href="#"><i class="fab fa-instagram"></i></a>
            </div>
        </div>
    </section>

    <footer>
        © 2025 Lovely | Python Django Developer
    </footer>

    <div class="modal fade" id="hospitalModal" tabindex="-1">
        <div class="modal-dialog modal-lg modal-dialog-centered">
            <div class="modal-content">

                <div class="modal-header">
                    <h5 class="modal-title">Hospital Management System - Full Details On GitHub</h5>
                    <button class="btn-close" data-bs-dismiss="modal"></button>
                </div>

                <div class="modal-body">

                    <h4 class="text-primary">Step 1: Project Overview</h4>
                    <p>
                        A full-stack hospital management system built with <b>Django + SQL</b>.
                        It manages patients, doctors, appointments, billing, staff & admin workflow.
                    </p>

                    <ul>
                        <li>Patient registration & medical record storage</li>
                        <li>Doctor scheduling & department management</li>
                        <li>Role-based login (Admin, Doctor, Staff)</li>
                        <li>Secure authentication</li>
                        <li>Admin dashboard with analytics</li>
                    </ul>

                    <hr>

                    <h4 class="text-success">Step 2: Features / How It Works</h4>
                    <ul>
                        <li>👉 Add / Update / Delete patient records</li>
                        <li>👉 Appointment booking & doctor assignment</li>
                        <li>👉 SQL database stores patient history</li>
                        <li>👉 Fully dynamic Django admin panel</li>
                        <li>👉 Medical department filtering system</li>
                    </ul>

                    <a href="https://github.com/lovelyramghria/HospitalManageMent_System"
                       class="btn btn-dark mt-3" target="_blank">
                       Visit GitHub
                    </a>

                </div>

            </div>
        </div>
    </div>
    
    <div class="modal fade" id="FoodModal" tabindex="-1">
        <div class="modal-dialog modal-lg modal-dialog-centered">
            <div class="modal-content">

                <div class="modal-header">
                    <h5 class="modal-title">Foodzone - Food Ordering System - Full Details On GitHub</h5>
                    <button class="btn-close" data-bs-dismiss="modal"></button>
                </div>

                <div class="modal-body">

                    <h4 class="text-primary">Step 1: Project Overview</h4>
                    <p>
                        A full-stack hospital management system built with <b>Django + SQL</b>.
                        It manages patients, doctors, appointments, billing, staff & admin workflow.
                    </p>

                    <ul>
                        <li>Patient registration & medical record storage</li>
                        <li>Doctor scheduling & department management</li>
                        <li>Role-based login (Admin, Doctor, Staff)</li>
                        <li>Secure authentication</li>
                        <li>Admin dashboard with analytics</li>
                    </ul>

                    <hr>

                    <h4 class="text-success">Step 2: Features / How It Works</h4>
                    <ul>
                        <li>👉 Add / Update / Delete patient records</li>
                        <li>👉 Appointment booking & doctor assignment</li>
                        <li>👉 SQL database stores patient history</li>
                        <li>👉 Fully dynamic Django admin panel</li>
                        <li>👉 Medical department filtering system</li>
                    </ul>

                    <a href="https://github.com/lovelyramghria/HospitalManageMent_System"
                       class="btn btn-dark mt-3" target="_blank">
                       Visit GitHub
                    </a>

                </div>

            </div>
        </div>
    </div>
    
    <div class="modal fade" id="empModal" tabindex="-1">
        <div class="modal-dialog modal-lg modal-dialog-centered">
            <div class="modal-content">

                <div class="modal-header">
                    <h5 class="modal-title">Employe Management System - Full Details On GitHub</h5>
                    <button class="btn-close" data-bs-dismiss="modal"></button>
                </div>

                <div class="modal-body">

                    <h4 class="text-primary">Step 1: Project Overview</h4>
                    <p>
                        A full-stack hospital management system built with <b>Django + SQL</b>.
                        It manages patients, doctors, appointments, billing, staff & admin workflow.
                    </p>

                    <ul>
                        <li>Patient registration & medical record storage</li>
                        <li>Doctor scheduling & department management</li>
                        <li>Role-based login (Admin, Doctor, Staff)</li>
                        <li>Secure authentication</li>
                        <li>Admin dashboard with analytics</li>
                    </ul>

                    <hr>

                    <h4 class="text-success">Step 2: Features / How It Works</h4>
                    <ul>
                        <li>👉 Add / Update / Delete patient records</li>
                        <li>👉 Appointment booking & doctor assignment</li>
                        <li>👉 SQL database stores patient history</li>
                        <li>👉 Fully dynamic Django admin panel</li>
                        <li>👉 Medical department filtering system</li>
                    </ul>

                    <a href="https://github.com/lovelyramghria/HospitalManageMent_System"
                       class="btn btn-dark mt-3" target="_blank">
                       Visit GitHub
                    </a>

                </div>

            </div>
        </div>
    </div>







    <!-- Scripts -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

    <script>
        const textArray = [
            "Python Django Developer",
            "Full Stack Developer",
            "Backend Developer"
        ];
        let typingIndex = 0;
        function typeEffect() {
            $(".typing").fadeOut(function () {
                $(this).html(textArray[typingIndex]).fadeIn();
            });
            typingIndex = (typingIndex + 1) % textArray.length;
        }
        setInterval(typeEffect, 2000);
        typeEffect();
    </script>

</body>

</html>
