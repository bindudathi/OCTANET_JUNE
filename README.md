<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LearnOnline - Your Gateway to Knowledge</title>
    <meta name="description" content="LearnOnline offers a diverse range of expert-led courses to help you gain new skills and advance your career.">
    <meta name="keywords" content="online learning, courses, web development, data science, skill development">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            color: #333;
        }

        .container {
            width: 80%;
            margin: 0 auto;
            max-width: 1200px;
        }

        .hero {
            background: url('hero-image.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 150px 0;
            position: relative;
        }

        .hero::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
        }

        .hero .container {
            position: relative;
            z-index: 1;
        }

        .hero h1 {
            font-size: 4em;
            margin-bottom: 0.5em;
        }

        .hero p {
            font-size: 1.5em;
            margin-bottom: 1.5em;
        }

        .btn {
            background-color: #ff6f61;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 50px;
            font-size: 1em;
            transition: background-color 0.3s;
        }

        .btn:hover {
            background-color: #e65c50;
        }

        section {
            padding: 70px 0;
        }

        .about, .courses, .signup, .testimonials, .contact {
            text-align: center;
            background-color: #f9f9f9;
        }

        .about h2, .courses h2, .signup h2, .testimonials h2, .contact h2 {
            font-size: 2.5em;
            margin-bottom: 0.5em;
            color: #ff6f61;
        }

        .about p, .signup p {
            font-size: 1.2em;
            line-height: 1.6;
            color: #666;
        }

        .course-grid {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .course {
            background: white;
            margin: 20px;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
            text-align: left;
            width: 300px;
        }

        .course img {
            border-radius: 10px;
            width: 100%;
            height: 200px;
            object-fit: cover;
            margin-bottom: 15px;
        }

        .course h3 {
            font-size: 1.5em;
            margin-bottom: 10px;
        }

        .course p {
            font-size: 1em;
            color: #666;
        }

        .testimonials {
            background-color: white;
        }

        .testimonial-grid {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .testimonial {
            background: #f9f9f9;
            margin: 20px;
            padding: 20px;
            border-radius: 10px;
            width: 300px;
            text-align: left;
        }

        .testimonial p {
            font-size: 1em;
            line-height: 1.6;
            color: #666;
        }

        .testimonial h4 {
            font-size: 1.2em;
            margin-top: 10px;
            color: #333;
        }

        .contact form {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 15px;
            max-width: 500px;
            margin: 0 auto;
        }

        .contact label {
            font-size: 1.2em;
            margin-bottom: 5px;
        }

        .contact input, .contact textarea {
            width: 100%;
            padding: 10px;
            font-size: 1em;
            border-radius: 5px;
            border: 1px solid #ddd;
        }

        .contact button {
            background-color: #ff6f61;
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 50px;
            font-size: 1em;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .contact button:hover {
            background-color: #e65c50;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
    </style>
</head>
<body>
    <header class="hero" role="banner">
        <div class="container">
            <h1>Welcome to LearnOnline</h1>
            <p>Unlock the power of online learning with our expert-led courses.</p>
            <a href="#courses" class="btn">Browse Courses</a>
        </div>
    </header>

    <main>
        <section class="about" id="about">
            <div class="container">
                <h2>About Us</h2>
                <p>LearnOnline offers a diverse range of courses to help you gain new skills and advance your career. Join thousands of learners from around the world and start your learning journey today.</p>
            </div>
        </section>

        <section class="courses" id="courses">
            <div class="container">
                <h2>Our Courses</h2>
                <div class="course-grid">
                    <div class="course">
                        <img src="course1.jpg" alt="Web Development Course">
                        <h3>Web Development</h3>
                        <p>Learn the fundamentals of web development with HTML, CSS, and JavaScript. Build responsive and interactive websites from scratch.</p>
                    </div>
                    <div class="course">
                        <img src="course2.jpg" alt="Data Science Course">
                        <h3>Data Science</h3>
                        <p>Dive into data analysis, machine learning, and statistical modeling. Gain the skills needed to become a data scientist.</p>
                    </div>
                    <div class="course">
                        <img src="course3.jpg" alt="Digital Marketing Course">
                        <h3>Digital Marketing</h3>
                        <p>Master the art of digital marketing. Learn about SEO, social media marketing, email marketing, and more.</p>
                    </div>
                </div>
            </div>
        </section>


        <section class="signup" id="signup">
            <div class="container">
                <h2>Sign Up</h2>
                <p>Join now and start your learning journey today!</p>
                <form>
                    <label for="name">Name</label>
                    <input type="text" id="name" name="name" required minlength="2">
                    <label for="email">Email</label>
                    <input type="email" id="email" name="email" required>
                    <button type="submit" class="btn">Join Now</button>
                </form>
            </div>
        </section>

        <section class="contact" id="contact">
            <div class="container">
                <h2>Contact Us</h2>
                <form>
                    <label for="contact-name">Name</label>
                    <input type="text" id="contact-name" name="contact-name" required minlength="2">
                    <label for="contact-email">Email</label>
                    <input type="email" id="contact-email" name="contact-email" required>
                    <label for="contact-message">Message</label>
                    <textarea id="contact-message" name="contact-message" rows="4" required></textarea>
                    <button type="submit" class="btn">Send Message</button>
                </form>
            </div>
        </section>
    </main>

    <footer role="contentinfo">
        <div class="container">
            <p>&copy; 2024 LearnOnline. All Rights Reserved.</p>
        </div>
    </footer>
</body>
</html># OCTANET_JUNE
