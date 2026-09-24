<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Created by: Kairullina Madina, Ashirbayeva Ayaulym -->
    <title>TilUP | Become a Language Tutor</title>
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
        <a href="become_tutor.html" class="active">Become a Tutor</a>
        <a href="about.html">About Us</a>
    </div>

    <a href="#" class="login-button">Login</a>
</nav>
</header>

<main>

<section class="page-hero">
    <div class="page-hero-content">
        <p class="section-label">TEACH LANGUAGES WITH TILUP</p>
        <h1>Become a Language Tutor</h1>
        <p>Help students achieve their language goals while teaching online from anywhere in the world.</p>
    </div>
</section>

<!-- Why Teach With Us - Flexbox Cards -->
<section class="about-tilup">
    <p class="section-label">WHY TEACH WITH US?</p>
    <h2>Inspire learners around the world</h2>

    <div class="feature-cards flex-cards-container">
        <article class="feature-card flex-mini-card">
            <div class="feature-icon">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"></circle><line x1="2" y1="12" x2="22" y2="12"></line><path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"></path></svg>
            </div>
            <h3>International Students</h3>
            <p>Teach learners from different countries and diverse cultural backgrounds.</p>
        </article>

        <article class="feature-card flex-mini-card">
            <div class="feature-icon">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>
            </div>
            <h3>Flexible Schedule</h3>
            <p>Choose your own working hours and teach at your maximum convenience.</p>
        </article>

        <article class="feature-card flex-mini-card">
            <div class="feature-icon">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"></path></svg>
            </div>
            <h3>Speaking Practice</h3>
            <p>Lead conversational clubs, structured grammar lessons and exam classes.</p>
        </article>
    </div>
</section>

<!-- Requirements Section -->
<section class="requirements-section">
    <div class="requirements-content">
        <div class="requirements-text">
            <p class="section-label">REQUIREMENTS</p>
            <h2>Who can become a TilUP tutor?</h2>
            <ul class="requirements-list">
                <li>Be at least 18 years old.</li>
                <li>Have B2–C2 proficiency or be a native speaker.</li>
                <li>Be able to communicate clearly in English or target teaching language.</li>
                <li>Have a stable internet connection and webcam.</li>
                <li>Enjoy teaching and helping students learn languages.</li>
            </ul>
        </div>
        <img src="images/tutor-team.jpg" alt="Language tutors" class="round-image">
    </div>
</section>

<!-- Benefits Table Section (Step 4) -->
<section class="benefits-table-section">
    <p class="section-label">WHAT YOU GET</p>
    <h2>Tutor Benefits</h2>
    <table class="benefits-table">
        <tr>
            <th>Benefit</th>
            <th>Description</th>
            <th>Included</th>
        </tr>
        <tr>
            <td>Flexible Schedule</td>
            <td>Teach mornings, evenings or weekends.</td>
            <td>✓ Yes</td>
        </tr>
        <tr>
            <td>Online Lessons</td>
            <td>Teach from home using our integrated tools.</td>
            <td>✓ Yes</td>
        </tr>
        <tr>
            <td>Teaching Materials</td>
            <td>Use ready-made lesson plans and grammar tests.</td>
            <td>✓ Yes</td>
        </tr>
    </table>
</section>

<!-- Tutor Form Section (Step 5, ID Selector #tutor-form) -->
<section class="tutor-form-section">
    <p class="section-label">APPLICATION FORM</p>
    <h2>Apply to Become a Tutor</h2>

    <form class="tutor-form" id="tutor-form">
        <div class="form-grid">
            <div class="form-group">
                <label>Full Name</label>
                <input type="text" placeholder="Enter your full name" required>
            </div>
            <div class="form-group">
                <label>Email</label>
                <input type="email" placeholder="example@email.com" required>
            </div>
            <div class="form-group">
                <label>Phone Number</label>
                <input type="tel" placeholder="+7 700 000 0000">
            </div>
            <div class="form-group">
                <label>Language You Teach</label>
                <select>
                    <option>Kazakh</option>
                    <option>Chinese</option>
                    <option>English</option>
                    <option>Korean</option>
                    <option>French</option>
                </select>
            </div>
            <div class="form-group">
                <label>Teaching Level</label>
                <div class="radio-group">
                    <label><input type="radio" name="level" value="A1-A2" checked> A1–A2</label>
                    <label><input type="radio" name="level" value="B1-B2"> B1–B2</label>
                    <label><input type="radio" name="level" value="C1-C2"> C1–C2</label>
                </div>
            </div>
            <div class="form-group">
                <label>Profile Accent Color</label>
                <input type="color" value="#2563eb">
            </div>
        </div>

        <div class="form-group">
            <label>Tell us about yourself</label>
            <textarea rows="5" placeholder="Describe your experience, teaching style and motivation..."></textarea>
        </div>

        <button class="button" type="submit">Submit Application</button>
    </form>
</section>

<!-- Application Process - Flexbox Cards -->
<section class="about-tilup">
    <p class="section-label">APPLICATION PROCESS</p>
    <h2>Start teaching in 3 easy steps</h2>

    <div class="feature-cards flex-cards-container">
        <article class="feature-card flex-mini-card">
            <div class="feature-icon">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"></path><polyline points="14 2 14 8 20 8"></polyline><line x1="16" y1="13" x2="8" y2="13"></line><line x1="16" y1="17" x2="8" y2="17"></line><polyline points="10 9 9 9 8 9"></polyline></svg>
            </div>
            <h3>1. Complete the Form</h3>
            <p>Share your language qualifications and background information.</p>
        </article>

        <article class="feature-card flex-mini-card">
            <div class="feature-icon">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"></path><circle cx="9" cy="7" r="4"></circle><path d="M23 21v-2a4 4 0 0 0-3-3.87"></path><path d="M16 3.13a4 4 0 0 1 0 7.75"></path></svg>
            </div>
            <h3>2. Interview</h3>
            <p>Meet our team online and demonstrate your communication capabilities.</p>
        </article>

        <article class="feature-card flex-mini-card">
            <div class="feature-icon">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polygon points="13 2 3 14 12 14 11 22 21 10 12 10 13 2"></polygon></svg>
            </div>
            <h3>3. Start Teaching</h3>
            <p>Publish your tutor profile and welcome students worldwide.</p>
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