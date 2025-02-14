<!DOCTYPE html>  
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TAG Tech Solutions/ቲኤጂ ቴክ ሶሊዩሽን</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
            color: #333;
            transition: background-color 0.3s ease;
        }

        h1, h2, h3 {
            font-weight: bold;
        }

        p {
            font-size: 1em;
            line-height: 1.5;
            color: #555;
        }

        /* Header */
        header {
            background-color: #1E3A8A;
            color: white;
            text-align: center;
            padding: 60px 20px;
        }

        header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2em;
        }

        /* About Section */
        #about {
            background-color: white;
            padding: 40px 20px;
            text-align: center;
        }

        #about h2 {
            font-size: 2em;
            margin-bottom: 20px;
        }

        #about p {
            max-width: 700px;
            margin: 0 auto;
            font-size: 1.1em;
        }

        /* Services Section */
        #services {
            background-color: #f0f0f0;
            padding: 60px 20px;
        }

        #services h2 {
            font-size: 2.2em;
            margin-bottom: 40px;
            text-align: center;
        }

        .service {
            display: flex;
            justify-content: space-around;
            gap: 20px;
            flex-wrap: wrap;
        }

        .service div {
            width: 30%;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .service div:hover {
            transform: scale(1.05);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }

        .service h3 {
            font-size: 1.8em;
            margin-bottom: 15px;
        }

        .service p {
            font-size: 1.1em;
        }

        /* Contact Section */
        #contact {
            background-color: #1E3A8A;
            color: white;
            padding: 50px 20px;
        }

        #contact h2 {
            font-size: 2.2em;
            margin-bottom: 20px;
        }

        #contact p {
            font-size: 1.1em;
            margin-bottom: 20px;
        }

        .contact-form {
            display: flex;
            flex-direction: column;
            gap: 12px;
            max-width: 500px;
            margin: 0 auto;
        }

        .contact-form input, .contact-form textarea {
            padding: 12px;
            font-size: 1em;
            border: 2px solid #ddd;
            border-radius: 8px;
            resize: none;
        }

        .contact-form button {
            background-color: #ff3b30;
            color: white;
            padding: 12px;
            border: none;
            border-radius: 8px;
            font-size: 1.1em;
            cursor: pointer;
        }

        .contact-form button:hover {
            background-color: #d02c27;
        }

        .response-message {
            text-align: center;
            margin-top: 15px;
            font-size: 1.1em;
            color: green;
        }

        /* Web Apps Development Section */
        .web-apps {
            background-color: #ffffff;
            padding: 40px 20px;
            text-align: center;
            border-radius: 8px;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
        }

        .web-apps h3 {
            font-size: 2.2em;
            color: #1E3A8A;
            margin-bottom: 15px;
        }

        .web-apps p {
            font-size: 1.1em;
            color: #555;
            line-height: 1.5;
            margin-bottom: 20px;
        }

        .web-apps ul {
            text-align: left;
            display: inline-block;
            font-size: 1.1em;
            color: #333;
        }

        .web-apps ul li {
            padding: 6px 0;
        }

        /* Dark Mode */
        body.dark-mode {
            background-color: #333;
            color: #fff;
        }

        /* Smooth Scrolling */
        html {
            scroll-behavior: smooth;
        }

        /* Client Testimonials Section */
        #testimonials {
            background-color: #f0f0f0;
            padding: 60px 20px;
        }

        #testimonials h2 {
            font-size: 2.2em;
            margin-bottom: 30px;
            text-align: center;
        }

        .testimonial {
            display: flex;
            justify-content: space-around;
            gap: 20px;
            flex-wrap: wrap;
        }

        .testimonial div {
            width: 30%;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
        }

        .testimonial h4 {
            font-size: 1.5em;
            margin-bottom: 10px;
        }

        .testimonial p {
            font-size: 1.1em;
            color: #555;
        }

    </style>
</head>
<body>

<header>
    <h1>TAG Tech Solutions/ቲኤጂ ቴክ ሶሊዩሽን</h1>
    <p>Innovating and Empowering Businesses for a Brighter Future</p>
</header>

<section id="about">
    <h2>About Us</h2>
    <p>We are dedicated to delivering innovative tech solutions that transform businesses, enhance productivity, and drive growth.</p>
    <p><strong>Phone:</strong> 0991856292</p>
    <p><strong>Email:</strong> <a href="mailto:info@tagtech.com">Contact Us via Email</a></p>
</section>

<section id="services">
    <h2>Our Services</h2>
    <div class="service">
        <!-- Web Apps Development -->
        <div class="web-apps">
            <h3>Web Apps Development</h3>
            <p>We design and develop custom web applications tailored to meet your business needs, from concept to deployment.</p>
            <h4>Products We Develop:</h4>
            <ul>
                <li>Website Development</li>
                <li>Rent Collection System</li>
                <li>Finance Management System</li>
                <li>Material Management System</li>
                <li>Customer Relationship Management (CRM) System</li>
            </ul>
        </div>

        <!-- Social Media Management -->
        <div class="service-category">
            <h3>🚀 Social Media Management</h3>
            <p>Boost your online presence with our expert social media solutions.</p>
            <div class="services-list">
                <span>📢 Facebook Boost</span> | 
                <span>📸 Instagram Boost</span> | 
                <span>🎵 TikTok Buy & Sell</span> | 
                <span>📹 YouTube Buy & Sell</span> | 
                <span>🐦 Twitter Marketing</span>
            </div>
        </div>

        <!-- Corporate Training -->
        <div class="service-category">
            <h3>Corporate Training</h3>
            <p>Tailored training for your team's development</p>
            <div class="dropdown-content">
                <h4>Training Topics We Offer:</h4>
                <ul>
                    <li>Cryptocurrency & Blockchain</li>
                    <li>Graphic Design</li>
                    <li>Programming & Software Development</li>
                    <li>Forex Trading</li>
                    <li>Digital Marketing</li>
                </ul>
            </div>
        </div>
    </div>
</section>

<!-- Testimonials Section -->
<section id="testimonials">
    <h2>What Our Clients Say</h2>
    <div class="testimonial">
        <div>
            <h4>Alemu Hailu</h4>
            <p>"TAG Tech Solutions provided us with an excellent web solution that transformed our business."</p>
        </div>
        <div>
            <h4>w/ro Guna Getu</h4>
            <p>"The team at TAG Tech was highly professional, and their services exceeded our expectations."</p>
        </div>
    </div>
</section>

<!-- Contact Section -->
<section id="contact">
    <h2>Contact Us</h2>
    <p>We'd love to hear from you. Reach out for any questions or inquiries.</p>
    <form class="contact-form">
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea placeholder="Your Message" rows="4" required></textarea>
        <button type="submit">Send Message</button>
    </form>
    <div class="response-message" style="display:none;">Thank you for reaching out. We will get back to you shortly.</div>
</section>

</body>
</html>

