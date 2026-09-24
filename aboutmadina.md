<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Created by: Kairullina Madina, Ashirbayeva Ayaulym -->
    <title>TilUP | About Us</title>
    <link rel="stylesheet" href="css/style.css">
</head>

<body>

    <header>
        <nav class="navbar">
            <a href="index.html" class="logo">
                <img src="images/logo.PNG" alt="TilUP logo">
                <span>Til<span class="logo-up">UP</span></span>
            </a>

            <div class="nav-menu">
                <a href="index.html">Home</a>
                <a href="why-learn.html">Why Learn</a>
                <a href="courses.html">Courses</a>
                <a href="tutors.html">Find a Tutor</a>
                <a href="become_tutor.html">Become a Tutor</a>
                <a href="about.html" class="active">About Us</a>
            </div>

            <a href="#" class="login-button">Login</a>
        </nav>
    </header>

    <main>

        <section class="page-hero">
            <div class="page-hero-content">
                <p class="section-label">WHO WE ARE</p>
                <h1>About TilUP</h1>
                <p>Empowering learners and tutors to connect, learn, and grow across cultures.</p>
            </div>
        </section>

        <!-- Development Team Section: Flexbox Cards -->
        <section class="team-section">
            <p class="section-label">DEVELOPMENT TEAM</p>
            <h2>Meet the Developers</h2>
            <p class="about-description">
                Meet the students behind the TilUP web project, responsible for designing 
                the user experience, HTML structure, and responsive stylesheet styling.
            </p>

            <div class="team-grid">

                <!-- Member 1: Kairullina Madina -->
                <article class="team-card">
                    <img src="images/madina.jpg" alt="Kairullina Madina" class="round-image profile-photo">
                    <div class="team-info">
                        <h3>Kairullina Madina</h3>
                        <span class="subject-tag">Frontend Developer</span>
                        <p class="bio-text">
                            Passionate about UI structuring, responsive design, and CSS layout architecture.
                        </p>
                        <div class="member-details">
                            <h4>Project Roles:</h4>
                            <ul>
                                <li>Home & About Us layout structuring</li>
                                <li>Semantic HTML5 boilerplate & accessibility</li>
                                <li>Box model & CSS Grid areas design</li>
                            </ul>
                        </div>
                    </div>
                </article>

                <!-- Member 2: Ashirbayeva Ayaulym -->
                <article class="team-card">
                    <img src="images/ayaulym.jpg" alt="Ashirbayeva Ayaulym" class="round-image profile-photo">
                    <div class="team-info">
                        <h3>Ashirbayeva Ayaulym</h3>
                        <span class="subject-tag">Frontend Developer</span>
                        <p class="bio-text">
                            Enthusiastic about interactive web technologies, responsive Flexbox styling, and forms.
                        </p>
                        <div class="member-details">
                            <h4>Project Roles:</h4>
                            <ul>
                                <li>Find a Tutor & Application Form implementation</li>
                                <li>Interactive tables and form components</li>
                                <li>Flexbox positioning & state pseudo-classes</li>
                            </ul>
                        </div>
                    </div>
                </article>

            </div>
        </section>

    </main>

    <footer>
        <p>&copy; 2026 TilUP</p>
        <p>Team Members: Kairullina Madina, Ashirbayeva Ayaulym</p>
    </footer>

</body>
</html>