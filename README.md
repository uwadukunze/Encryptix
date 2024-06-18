<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stellarserve Solutions</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f8f9fa;
            line-height: 1.6;
        }
        header {
            background-color: #343a40;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
            font-weight: 700;
        }
        header p {
            font-size: 1.2em;
            font-weight: 400;
        }
        section {
            padding: 50px 0;
        }
        .about, .services, .features, .testimonials, .team, .contact {
            text-align: center;
        }
        .service, .feature, .testimonial, .team-member, .contact-info, .form-container {
            margin-bottom: 40px;
            padding: 30px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 20px rgba(0,0,0,0.1);
            transition: all 0.3s ease;
        }
        .service:hover, .feature:hover, .testimonial:hover, .team-member:hover, .contact-info:hover, .form-container:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 20px rgba(0,0,0,0.2);
        }
        footer {
            background-color: #343a40;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
        .cta a {
            display: inline-block;
            background-color: #2cc3a6;
            color: #fff;
            padding: 15px 30px;
            text-decoration: none;
            font-weight: 700;
            border-radius: 30px;
            transition: background-color 0.3s ease;
        }
        .cta a:hover {
            background-color: #239f86;
        }
        form input, form textarea {
            width: 100%;
            margin-bottom: 20px;
            padding: 15px;
            border: 1px solid #ced4da;
            border-radius: 5px;
            transition: border-color 0.3s ease;
        }
        form input:focus, form textarea:focus {
            border-color: #2cc3a6;
        }
        form button {
            width: 100%;
            padding: 15px;
            background-color: #2cc3a6;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        form button:hover {
            background-color: #239f86;
        }
        .social-links a {
            color: #333;
            text-decoration: none;
            margin: 0 10px;
            font-size: 1.5em;
            transition: color 0.3s ease;
        }
        .social-links a:hover {
            color: #2cc3a6;
        }
    </style>
</head>
<body>
    <header>
        <h1>Stellarserve Solutions</h1>
        <p>Hire the Best Remote Talent Worldwide with Stellarserve Solutions</p>
    </header>
    <section class="about">
        <h2>Who We Are</h2>
        <p>Stellarserve Solutions revolutionizes tech hiring for startups & SMEs. We connect you with top-tier remote talent in AI, ML, software development, cybersecurity, and data science.</p>
    </section>
    <section class="services">
        <h2>Our Services</h2>
        <div class="service">
            <h3>Top-tier Remote Talent</h3>
            <p>We connect startups & SMEs with skilled remote professionals in AI, ML, software development, cybersecurity, and data science.</p>
        </div>
        <div class="service">
            <h3>AI-Powered Hiring Platform</h3>
            <p>Our AI-powered platform streamlines hiring, reduces costs, and ensures quality, making tech recruitment efficient and effective.</p>
        </div>
        <div class="service">
            <h3>Global Talent Reach</h3>
            <p>Hire skilled remote professionals globally, scale your team efficiently, and achieve business goals irrespective of geographical limitations.</p>
        </div>
        <div class="service">
            <h3>Agile Hiring Solutions</h3>
            <p>Ideal for tech startups with 5-20 employees, offering agile hiring and access to a broader talent pool to fuel growth.</p>
        </div>
        <div class="service">
            <h3>Custom Talent Solutions</h3>
            <p>Get tailored solutions to match your unique hiring needs and build a world-class remote team that drives innovation.</p>
        </div>
    </section>
    <section class="cta">
        <h2>Ready to Transform Your Hiring Process?</h2>
        <p>Join Stellarserve Solutions and start hiring the best remote talent today.</p>
        <a href="#contact">Get Started</a>
    </section>
    <section class="contact" id="contact">
        <h2>Contact Us</h2>
        <div class="form-container">
            <form action="mailto:iuwadukunze@gmail.com" method="post" enctype="text/plain">
                <label for="name">Name</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>
                
                <label for="phone">Phone</label>
                <input type="tel" id="phone" name="phone" required>
                
                <label for="message">Message</label>
                <textarea id="message" name="message" rows="5" required></textarea>
                
                <button type="submit">Submit</button>
            </form>
        </div>
        <div class="contact-info">
            <h3>Email</h3>
            <p><a href="mailto:iuwadukunze@gmail.com">iuwadukunze@gmail.com</a></p>
        </div>
        <div class="contact-info">
            <h3>Phone</h3>
            <p><a href="tel:+250786399699">+250786399699</a></p>
        </div>
        <div class="contact-info social-links">
            <h3>Social Media</h3>
            <a href="https://www.linkedin.com/company/stellarserve-solutions/" target="_blank">LinkedIn</a>
            <!-- Add other social media links if needed -->
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Stellarserve Solutions. All rights reserved.</p>
    </footer>
</body>
</html>