
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio | The Gujarati Coder</title>
    <meta name="description" content="Personal portfolio of a student, programmer and technology enthusiast.">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.3.1/css/all.min.css" integrity="sha512-QeR2VH+lsBE5LSAe1Q5EnTBbe7XTBubt8dG93Y7gidSgdMCr8nVqKcfKAMyN96SV8KDbZVTDXChatu5G2KQGzg==" crossorigin="anonymous" referrerpolicy="no-referrer">
</head>
<body>

    <!-- Navbar -->
    <header>
        <nav class="navbar container">
            <a href="#home" class="logo">THE <span>GUJARATI CODER</span></a>

            <button class="menu-btn" id="menuBtn" aria-label="Toggle navigation"
                aria-expanded="false">☰</button>

            <ul class="nav-links" id="navLinks">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home -->
    <section class="hero container" id="home">
        <div class="hero-content">
            <p class="tag">WELCOME TO MY PORTFOLIO</p>
            <h1>Hello, I'm <span>Dharmendrasinh</span></h1>
            <h2>Student | programmer | Content Creator</h2>
            <p>
                I love coding, technology and creating new digital projects.
                I am learning new skills and building my future in technology.
            </p>

            <div class="hero-buttons">
                <a href="#projects" class="btn">View My Projects</a>
                <a href="#contact" class="btn btn-outline">Contact Me</a>
            </div>
        </div>

        <div class="hero-image">
            <div class="profile-circle">
                <img src="c:\Users\Shiv Shakti\Pictures\me\IMG_20261116_200204.jpg.jpeg"
                        alt="Profile pictuer"
                        class="profile-circle">
            </div>            
        </div>
    </section>

    <!-- About -->
    <section class="section container" id="about">
        <p class="tag">GET TO KNOW ME</p>
        <h2 class="section-title">About Me</h2>

        <div class="about-box">
            <h3>Who Am I?</h3>
            <p>
                Hello! I am a student, beginner programmer and technology
                enthusiast. I enjoy learning programming languages,
                developing websites and creating interesting projects.
                My goal is to become a skilled developer and entrepreneur.
            </p>
            <p>
                I also create technology and coding content through
                my YouTube channel, THE GUJARATI CODER.
            </p>
        </div>
    </section>

    <!-- Skills -->
    <section class="section light-section" id="skills">
        <div class="container">
            <p class="tag">WHAT I KNOW</p>
            <h2 class="section-title">My Skills</h2>

            <div class="card-grid">
                <div class="card"><span>🐍</span><h3>Python</h3><p>Programming basics</p></div>
                <div class="card"><span>⚙️</span><h3>C / C++</h3><p>Programming fundamentals</p></div>
                <div class="card"><span>🌐</span><h3>HTML</h3><p>Website structure</p></div>
                <div class="card"><span>🎨</span><h3>CSS</h3><p>Website design</p></div>
                <div class="card"><span>⚡</span><h3>JavaScript</h3><p>Website interactivity</p></div>
                <div class="card"><span>💡</span><h3>Problem Solving</h3><p>Creative thinking</p></div>
            </div>
        </div>
    </section>

    <!-- Projects -->
    <section class="section container" id="projects">
        <p class="tag">MY WORK</p>
        <h2 class="section-title">My Projects</h2>

        <div class="card-grid">
            <div class="card project-card">
                <span>🧮</span>
                <h3>Python Calculator</h3>
                <p>A beginner-friendly calculator built using Python.</p>
                <a href="#" class="project-link">Project Link →</a>
            </div>

            <div class="card project-card">
                <span>🎯</span>
                <h3>Number Guessing Game</h3>
                <p>A fun number guessing game developed using Python.</p>
                <a href="#" class="project-link">Project Link →</a>
            </div>

            <div class="card project-card">
                <span>📝</span>
                <h3>To-Do List</h3>
                <p>A task management project created with Python.</p>
                <a href="#" class="project-link">Project Link →</a>
            </div>

            <div class="card project-card">
                <span>🎈</span>
                <h3>Balloon Decoration Website</h3>
                <p>A business website with a booking feature.</p>
                <a href="#" class="project-link">Project Link →</a>
            </div>
        </div>
    </section>

    <!-- Education -->
    <section class="section light-section" id="education">
        <div class="container">
            <p class="tag">MY LEARNING JOURNEY</p>
            <h2 class="section-title">Education</h2>

            <div class="about-box">
                <h3>My Education</h3>
                <p>
                    I am currently continuing my studies and learning
                    programming, web development and technology.
                </p>
                <p><strong>Current focus:</strong> Learning and building projects.</p>
            </div>
        </div>
    </section>

    <!-- YouTube -->
    <section class="section container" id="youtube">
        <p class="tag">MY CREATIVE WORLD</p>
        <h2 class="section-title">YouTube Channel</h2>

        <div class="youtube-box">
            <h3>▶ THE GUJARATI CODER</h3>
            <p>
                Coding, technology, computer tips, education,
                DIY projects and vlogging.
            </p>
            <a href="https://www.youtube.com/@GujaratiCoding" target="_blank"
               rel="noopener noreferrer" class="btn">
                Visit My Channel
            </a>
        </div>
        <h2 class="section-title">WhatsApp</h2>

        <div class="youtube-box">
            <h3>THE GUJARATI CODER</h3>
            <p>
                You can easily find all the important links and updates on my WhatsApp Channel.
            </p>
            <a href="https://whatsapp.com/channel/0029VbDJeKIFsn0XtlOFhk0M" target="_blank"
               rel="noopener noreferrer" class="btn">
                Join My Channel
            </a>
        </div>
    </section>

    <!-- Contact -->
    <section class="section light-section" id="contact">
        <div class="container">
            <p class="tag">LET'S CONNECT</p>
            <h2 class="section-title">Contact Me</h2>

            <form class="contact-form" id="contactForm">
                <input type="text" id="name" placeholder="Your Name" required>
                <input type="email" id="email" placeholder="Your Email" required>
                <textarea id="message" rows="5"
                    placeholder="Your Message" required></textarea>
                <button type="submit" class="btn">Send Message</button>
                <p id="formStatus" role="status"></p>
            </form>

            <div class="social-links">
                
                <a href="https://www.instagram.com/dharmendrasinh0768?igsh=Z2drd3RidWdpaDVu" target="_blank"
                   rel="noopener noreferrer"><i class="fab fa-instagram"></i></a>
                <a href="https://youtube.com/@gujaraticoding?si=fMe3r6DqY3M0GoBb" target="_blank"
                   rel="noopener noreferrer"><i class="fab fa-youtube"></i></a>
                <a href="https://github.com/dharmendrasinh0768" target="_blank"
                   rel="noopener noreferrer"><i class="fab fa-github"></i></a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>© <span id="year"></span> THE GUJARATI CODER. All Rights Reserved.</p>
        <a href="#home">Back to Top ↑</a>
    </footer>

    <script src="script.js"></script>
</body>
</html>
