<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Created by: Kairullina Madina, Ashirbayeva Ayaulym -->

    <title>TilUP | Find a Language Tutor</title>
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
            <a href="tutors.html" class="active">Find a Tutor</a>
            <a href="become_tutor.html">Become a Tutor</a>
            <a href="about.html">About Us</a>
        </div>

        <a href="#" class="login-button">Login</a>
    </nav>
</header>

<main>

    <section class="page-hero">
        <div class="page-hero-content">
            <p class="section-label">FIND YOUR LANGUAGE TUTOR</p>
            <h1>Meet Our Tutors</h1>
            <p>Choose a tutor based on the language you want to learn and your current level.</p>
        </div>
    </section>

    <!-- Filters Section -->
    <section class="filters-section">
        <p class="section-label">FILTER TUTORS</p>
        <form class="filters">
            <div class="filter-box">
                <label for="filter-language">
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"></circle><line x1="2" y1="12" x2="22" y2="12"></line><path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"></path></svg>
                    Language
                </label>
                <select id="filter-language" name="language">
                    <option value="">All Languages</option>
                    <option value="kazakh">Kazakh</option>
                    <option value="chinese">Chinese</option>
                    <option value="english">English</option>
                    <option value="korean">Korean</option>
                    <option value="french">French</option>
                    <option value="german">German</option>
                    <option value="spanish">Spanish</option>
                    <option value="japanese">Japanese</option>
                    <option value="arabic">Arabic</option>
                    <option value="russian">Russian</option>
                    <option value="italian">Italian</option>
                    <option value="turkish">Turkish</option>
                </select>
            </div>

            <div class="filter-box">
                <label for="filter-level">
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="18" y1="20" x2="18" y2="10"></line><line x1="12" y1="20" x2="12" y2="4"></line><line x1="6" y1="20" x2="6" y2="14"></line></svg>
                    Level
                </label>
                <select id="filter-level" name="level">
                    <option value="">All Levels</option>
                    <option value="a1-a2">A1–A2 (Beginner)</option>
                    <option value="b1-b2">B1–B2 (Intermediate)</option>
                    <option value="c1-c2">C1–C2 (Advanced)</option>
                </select>
            </div>

            <div class="filter-box">
                <label for="filter-type">
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 19.5A2.5 2.5 0 0 1 6.5 17H20"></path><path d="M6.5 2H20v20H6.5A2.5 2.5 0 0 1 4 19.5v-15A2.5 2.5 0 0 1 6.5 2z"></path></svg>
                    Lesson Type
                </label>
                <select id="filter-type" name="type">
                    <option value="">All Lessons</option>
                    <option value="speaking">Speaking Practice</option>
                    <option value="grammar">Grammar & Writing</option>
                    <option value="exam">Exam Preparation (HSK, IELTS, TORFL)</option>
                    <option value="business">Business Language</option>
                </select>
            </div>
        </form>
    </section>

    <!-- Tutors Grid Section (Grid Areas + Flexbox) -->
    <section class="tutors-section">
        <div class="tutors-grid">

            <!-- 1. Kazakh -->
            <article class="tutor-card">
                <img src="images/tutor7.jpg" alt="Aizhan Kassymova" class="tutor-photo">
                <span class="subject-tag">Kazakh</span>
                <h3 class="tutor-name">Aizhan Kassymova</h3>
                <p class="rating">
                    <svg class="star-icon" width="16" height="16" viewBox="0 0 24 24" fill="#F59E0B"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg>
                    5.0 • Native Speaker & Philologist
                </p>
                <p class="tutor-bio">Modern Kazakh for everyday life, conversational practice and business communication.</p>
                <ul class="tutor-details">
                    <li>Levels: A1–C1</li>
                    <li>Lesson: Conversational & QAZTEST</li>
                    <li>Hourly Rate: $16</li>
                </ul>
                <a href="#" class="button tutor-btn">Choose Tutor</a>
            </article>

            <!-- 2. Chinese -->
            <article class="tutor-card">
                <img src="images/chinese.jpg" alt="Li Wei" class="tutor-photo">
                <span class="subject-tag">Chinese</span>
                <h3 class="tutor-name">Li Wei</h3>
                <p class="rating">
                    <svg class="star-icon" width="16" height="16" viewBox="0 0 24 24" fill="#F59E0B"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg>
                    4.9 • Certified HSK Trainer
                </p>
                <p class="tutor-bio">Mandarin pronunciation, pinyin, Chinese characters and intensive HSK 1–6 preparation.</p>
                <ul class="tutor-details">
                    <li>Levels: Beginner – HSK 6</li>
                    <li>Lesson: HSK Exam & Speaking</li>
                    <li>Hourly Rate: $22</li>
                </ul>
                <a href="#" class="button tutor-btn">Choose Tutor</a>
            </article>

            <!-- 3. English -->
            <article class="tutor-card">
                <img src="images/tutor1.jpg" alt="Emily Brown" class="tutor-photo">
                <span class="subject-tag">English</span>
                <h3 class="tutor-name">Emily Brown</h3>
                <p class="rating">
                    <svg class="star-icon" width="16" height="16" viewBox="0 0 24 24" fill="#F59E0B"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg>
                    4.9 • Native English Speaker
                </p>
                <p class="tutor-bio">Specializes in IELTS, Business English and conversational fluency practice.</p>
                <ul class="tutor-details">
                    <li>Levels: A2–C2</li>
                    <li>Lesson: IELTS & Speaking</li>
                    <li>Hourly Rate: $18</li>
                </ul>
                <a href="#" class="button tutor-btn">Choose Tutor</a>
            </article>

            <!-- 4. Korean -->
            <article class="tutor-card">
                <img src="images/tutor2.jpg" alt="Kim Ji-eun" class="tutor-photo">
                <span class="subject-tag">Korean</span>
                <h3 class="tutor-name">Kim Ji-eun</h3>
                <p class="rating">
                    <svg class="star-icon" width="16" height="16" viewBox="0 0 24 24" fill="#F59E0B"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg>
                    5.0 • TOPIK Specialist
                </p>
                <p class="tutor-bio">Teaches Korean grammar, everyday expressions and TOPIK exam preparation.</p>
                <ul class="tutor-details">
                    <li>Levels: A1–B2</li>
                    <li>Lesson: TOPIK & Conversation</li>
                    <li>Hourly Rate: $20</li>
                </ul>
                <a href="#" class="button tutor-btn">Choose Tutor</a>
            </article>

            <!-- 5. French -->
            <article class="tutor-card">
                <img src="images/tutor3.jpg" alt="Sophie Martin" class="tutor-photo">
                <span class="subject-tag">French</span>
                <h3 class="tutor-name">Sophie Martin</h3>
                <p class="rating">
                    <svg class="star-icon" width="16" height="16" viewBox="0 0 24 24" fill="#F59E0B"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg>
                    4.8 • DELF Certified Tutor
                </p>
                <p class="tutor-bio">French conversation, accent reduction, grammar and DELF preparation.</p>
                <ul class="tutor-details">
                    <li>Levels: Beginner – Advanced</li>
                    <li>Lesson: Grammar & Speaking</li>
                    <li>Hourly Rate: $19</li>
                </ul>
                <a href="#" class="button tutor-btn">Choose Tutor</a>
            </article>

            <!-- 6. German -->
            <article class="tutor-card">
                <img src="images/tutor4.jpg" alt="Max Müller" class="tutor-photo">
                <span class="subject-tag">German</span>
                <h3 class="tutor-name">Max Müller</h3>
                <p class="rating">
                    <svg class="star-icon" width="16" height="16" viewBox="0 0 24 24" fill="#F59E0B"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg>
                    4.9 • Goethe Exam Tutor
                </p>
                <p class="tutor-bio">Structured German lessons focused on vocabulary, grammar and Goethe certificates.</p>
                <ul class="tutor-details">
                    <li>Levels: A1–C1</li>
                    <li>Lesson: Goethe Exam</li>
                    <li>Hourly Rate: $21</li>
                </ul>
                <a href="#" class="button tutor-btn">Choose Tutor</a>
            </article>

            <!-- 7. Spanish -->
            <article class="tutor-card">
                <img src="images/tutor5.jpg" alt="Carlos Ruiz" class="tutor-photo">
                <span class="subject-tag">Spanish</span>
                <h3 class="tutor-name">Carlos Ruiz</h3>
                <p class="rating">
                    <svg class="star-icon" width="16" height="16" viewBox="0 0 24 24" fill="#F59E0B"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg>
                    4.8 • Speaking Club Host
                </p>
                <p class="tutor-bio">Practice everyday Spanish through interactive speaking lessons and cultural discussions.</p>
                <ul class="tutor-details">
                    <li>Levels: A1–B2</li>
                    <li>Lesson: Speaking Practice</li>
                    <li>Hourly Rate: $17</li>
                </ul>
                <a href="#" class="button tutor-btn">Choose Tutor</a>
            </article>

            <!-- 8. Japanese -->
            <article class="tutor-card">
                <img src="images/tutor6.jpg" alt="Yuki Tanaka" class="tutor-photo">
                <span class="subject-tag">Japanese</span>
                <h3 class="tutor-name">Yuki Tanaka</h3>
                <p class="rating">
                    <svg class="star-icon" width="16" height="16" viewBox="0 0 24 24" fill="#F59E0B"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg>
                    5.0 • JLPT Specialist
                </p>
                <p class="tutor-bio">Japanese lessons for JLPT preparation, kanji mastery and natural conversational flow.</p>
                <ul class="tutor-details">
                    <li>Levels: A1–C1</li>
                    <li>Lesson: JLPT & Speaking</li>
                    <li>Hourly Rate: $22</li>
                </ul>
                <a href="#" class="button tutor-btn">Choose Tutor</a>
            </article>

            <!-- 9. Arabic -->
            <article class="tutor-card">
                <img src="images/tutor-arabic.jpg" alt="Omar Al-Mansoor" class="tutor-photo">
                <span class="subject-tag">Arabic</span>
                <h3 class="tutor-name">Omar Al-Mansoor</h3>
                <p class="rating">
                    <svg class="star-icon" width="16" height="16" viewBox="0 0 24 24" fill="#F59E0B"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg>
                    4.9 • Modern Standard Arabic
                </p>
                <p class="tutor-bio">Specializes in Modern Standard Arabic (MSA), pronunciation, calligraphy and Gulf dialogs.</p>
                <ul class="tutor-details">
                    <li>Levels: A1–C1</li>
                    <li>Lesson: MSA & Speaking</li>
                    <li>Hourly Rate: $21</li>
                </ul>
                <a href="#" class="button tutor-btn">Choose Tutor</a>
            </article>

            <!-- 10. Russian -->
            <article class="tutor-card">
                <img src="images/tutor-russian.jpg" alt="Daria Ivanova" class="tutor-photo">
                <span class="subject-tag">Russian</span>
                <h3 class="tutor-name">Daria Ivanova</h3>
                <p class="rating">
                    <svg class="star-icon" width="16" height="16" viewBox="0 0 24 24" fill="#F59E0B"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg>
                    5.0 • TORFL Instructor
                </p>
                <p class="tutor-bio">Russian for beginners, intensive cases & grammar breakdown, and TORFL exam preparation.</p>
                <ul class="tutor-details">
                    <li>Levels: A1–C2</li>
                    <li>Lesson: Grammar & TORFL</li>
                    <li>Hourly Rate: $17</li>
                </ul>
                <a href="#" class="button tutor-btn">Choose Tutor</a>
            </article>

            <!-- 11. Italian -->
            <article class="tutor-card">
                <img src="images/tutor-italian.jpg" alt="Matteo Rossi" class="tutor-photo">
                <span class="subject-tag">Italian</span>
                <h3 class="tutor-name">Matteo Rossi</h3>
                <p class="rating">
                    <svg class="star-icon" width="16" height="16" viewBox="0 0 24 24" fill="#F59E0B"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg>
                    4.8 • Native Italian
                </p>
                <p class="tutor-bio">Conversational Italian, travel vocabulary, cultural immersion, music and CILS certificate practice.</p>
                <ul class="tutor-details">
                    <li>Levels: A1–B2</li>
                    <li>Lesson: Speaking & Travel</li>
                    <li>Hourly Rate: $20</li>
                </ul>
                <a href="#" class="button tutor-btn">Choose Tutor</a>
            </article>

            <!-- 12. Turkish -->
            <article class="tutor-card">
                <img src="images/tutor-turkish.jpg" alt="Emre Demir" class="tutor-photo">
                <span class="subject-tag">Turkish</span>
                <h3 class="tutor-name">Emre Demir</h3>
                <p class="rating">
                    <svg class="star-icon" width="16" height="16" viewBox="0 0 24 24" fill="#F59E0B"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg>
                    4.9 • TÖMER Specialist
                </p>
                <p class="tutor-bio">Modern Turkish grammar, daily conversation, business vocabulary and preparation for TÖMER exams.</p>
                <ul class="tutor-details">
                    <li>Levels: A1–C1</li>
                    <li>Lesson: TÖMER & Conversation</li>
                    <li>Hourly Rate: $18</li>
                </ul>
                <a href="#" class="button tutor-btn">Choose Tutor</a>
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