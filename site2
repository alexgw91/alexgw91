<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alex Golder-Wood - Official Website</title>
    <style>
        /* Base styles */
        body {
            font-family: 'Georgia', serif;
            line-height: 1.6;
            color: #333;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header styles */
        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        
        .nav {
            background-color: #34495e;
            padding: 10px 0;
        }
        
        .nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        
        .nav li {
            margin: 0 15px;
        }
        
        .nav a {
            color: white;
            text-decoration: none;
            font-size: 16px;
            font-weight: bold;
            padding: 5px 10px;
            border-radius: 3px;
            transition: background-color 0.3s;
        }
        
        .nav a:hover {
            background-color: #4a6278;
        }
        
        /* Hero section */
        .hero {
            display: flex;
            align-items: center;
            padding: 60px 0;
            background-color: #ecf0f1;
        }
        
        .author-image {
            flex: 1;
            text-align: center;
        }
        
        .author-image img {
            width: 250px;
            height: 250px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid #fff;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .author-intro {
            flex: 2;
            padding: 0 40px;
        }
        
        /* Featured book section */
        .featured-book {
            padding: 60px 0;
            text-align: center;
            background-color: #fff;
        }
        
        .book-display {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-top: 30px;
        }
        
        .book-cover {
            flex: 1;
            text-align: right;
            padding-right: 40px;
        }
        
        .book-cover img {
            max-height: 400px;
            box-shadow: 5px 5px 15px rgba(0,0,0,0.2);
        }
        
        .book-info {
            flex: 1;
            text-align: left;
            padding-left: 40px;
        }
        
        .cta-button {
            display: inline-block;
            background-color: #e74c3c;
            color: white;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            margin-top: 20px;
            transition: background-color 0.3s;
        }
        
        .cta-button:hover {
            background-color: #c0392b;
        }
        
        /* Newsletter section */
        .newsletter {
            background-color: #3498db;
            color: white;
            padding: 50px 0;
            text-align: center;
        }
        
        .newsletter-form {
            max-width: 500px;
            margin: 20px auto;
        }
        
        .newsletter-form input[type="email"] {
            width: 70%;
            padding: 12px;
            border: none;
            border-radius: 5px 0 0 5px;
            font-size: 16px;
        }
        
        .newsletter-form button {
            width: 30%;
            padding: 12px;
            background-color: #2980b9;
            color: white;
            border: none;
            border-radius: 0 5px 5px 0;
            cursor: pointer;
            font-size: 16px;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        
        .newsletter-form button:hover {
            background-color: #1c638f;
        }
        
        /* Social media section */
        .social-media {
            padding: 40px 0;
            text-align: center;
            background-color: #f9f9f9;
        }
        
        .social-icons {
            margin-top: 20px;
        }
        
        .social-icons a {
            display: inline-block;
            margin: 0 10px;
            padding: 10px 20px;
            background-color: #2c3e50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        
        .social-icons a:hover {
            background-color: #1a252f;
        }
        
        /* Books page */
        .books-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 30px;
            padding: 40px 0;
        }
        
        .book-card {
            background-color: white;
            border-radius: 5px;
            overflow: hidden;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        
        .book-card:hover {
            transform: translateY(-5px);
        }
        
        .book-card img {
            width: 100%;
            height: auto;
            display: block;
        }
        
        .book-card-content {
            padding: 20px;
        }
        
        /* Contact page */
        .contact-info {
            background-color: white;
            padding: 40px;
            border-radius: 5px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            margin: 40px 0;
        }
        
        .contact-social {
            margin-top: 30px;
        }
        
        .contact-social a {
            display: block;
            margin: 10px 0;
            padding: 10px;
            background-color: #f5f5f5;
            border-radius: 5px;
            text-decoration: none;
            color: #333;
            transition: background-color 0.3s;
        }
        
        .contact-social a:hover {
            background-color: #e0e0e0;
        }
        
        /* Footer */
        footer {
            background-color: #2c3e50;
            color: white;
            padding: 30px 0;
            text-align: center;
        }
        
        footer p {
            margin: 5px 0;
        }
        
        .footer-links a {
            color: #bdc3c7;
            margin: 0 10px;
            text-decoration: none;
        }
        
        .footer-links a:hover {
            color: white;
            text-decoration: underline;
        }
        
        /* Tabs for pages */
        #home-content, #about-content, #books-content, #contact-content {
            display: none;
        }
        
        #home-content.active, #about-content.active, #books-content.active, #contact-content.active {
            display: block;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <h1>Alex Golder-Wood</h1>
            <p>Mystery & Psychological Thriller Author</p>
        </div>
    </header>
    
    <!-- Navigation -->
    <nav class="nav">
        <div class="container">
            <ul>
                <li><a href="#" class="nav-link active" data-tab="home">Home</a></li>
                <li><a href="#" class="nav-link" data-tab="about">About</a></li>
                <li><a href="#" class="nav-link" data-tab="books">Books</a></li>
                <li><a href="#" class="nav-link" data-tab="contact">Contact</a></li>
            </ul>
        </div>
    </nav>
    
    <!-- Home Content -->
    <div id="home-content" class="active">
        <!-- Hero Section -->
        <section class="hero">
            <div class="container">
                <div class="author-image">
                    <img src="/api/placeholder/400/400" alt="Alex Golder-Wood">
                </div>
                <div class="author-intro">
                    <h2>Welcome to my official website</h2>
                    <p>From the misty valleys and rugged landscapes of the Peak District comes the inspiration for my suspenseful tales of mystery and psychological intrigue.</p>
                    <p>With my debut novel, "Shadows of the Green" released in April 2025, I weave stories that explore the darker corners of the human mind against the backdrop of breathtaking natural beauty.</p>
                    <p>Currently, I'm crafting my second novel, "False Alarm," set to captivate readers later in 2025. Browse my website to discover my books, catch up on my latest writing journey, and find opportunities to connect at upcoming events.</p>
                </div>
            </div>
        </section>
        
        <!-- Featured Book Section -->
        <section class="featured-book">
            <div class="container">
                <h2>Featured Book</h2>
                <h3>Debut Novel - Out Now</h3>
                <div class="book-display">
                    <div class="book-cover">
                        <img src="/"images/Shadows.jpg" alt="images/Shadows.jpg">
                    </div>
                    <div class="book-info">
                        <h3>Shadows of the Green</h3>
                        <p>"A powerful, authentic portrait of working class masculinity and the weight of unspoken pain, Shadows of the Green grips you by the throat and doesn't let go."</p>
                        <p>— Mathew Walker, Author of 'Tips On How To Lose Your Spouse'</p>
                        <p>One phone call. A desperate mother. A friend gone missing.</p>
                        <p>Jay thought he'd escaped The Green, the rough Estate that shaped his childhood. Now, trapped in a dead end marriage and a life he barely recognises, he's dragged back when his old friend, George, disappears.</p>
                        <p>But finding George means confronting the past they both thought they escaped... and the secrets they left buried there.</p>
                        <p>With nothing but a few cryptic leads and a gut feeling something is wrong, Jay is forced to reunite with his old crew: Az, the cold and calculating gym obsessed enforcer, and Will, the reckless addict whose mouth is as dangerous as his habits. Together, they follow the shadows of their past, deep into a world of debts unpaid, violence unresolved, and the ghosts they tried to leave behind.</p>
                        <p>For fans of Shuggie Bain and Trainspotting, Shadows of the Green is a raw, unflinching exploration of Male Friendship, unspoken pain, and the courage it takes to break generational cycles.</p>
                        <a href="https://www.amazon.co.uk/Shadows-Green-Alex-Golder-Wood-ebook/dp/B0F194LBD3/ref=sr_1_1?sr=8-1" class="cta-button" target="_blank">Buy Now on Amazon</a>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Newsletter Section -->
        <section class="newsletter">
            <div class="container">
                <h2>Join My Newsletter</h2>
                <p>Subscribe to receive updates on new releases, exclusive behind-the-scenes content, and upcoming events directly to your inbox.</p>
                <div class="newsletter-form">
                    <input type="email" placeholder="Your email address">
                    <button type="submit">Subscribe</button>
                </div>
            </div>
        </section>
        
        <!-- Social Media Section -->
        <section class="social-media">
            <div class="container">
                <h2>Connect With Me</h2>
                <div class="social-icons">
                    <a href="https://instagram.com/alexgwauthor" target="_blank">Instagram</a>
                    <a href="https://tiktok.com/@alexgwauthor" target="_blank">TikTok</a>
                </div>
            </div>
        </section>
    </div>
    
    <!-- About Content -->
    <div id="about-content">
        <section class="container" style="padding: 60px 0;">
            <h2>About Alex Golder-Wood</h2>
            <div style="display: flex; gap: 40px; margin-top: 30px;">
                <div style="flex: 1;">
                    <img src="/api/placeholder/400/500" alt="Alex Golder-Wood" style="width: 100%; border-radius: 5px; box-shadow: 0 5px 15px rgba(0,0,0,0.1);">
                </div>
                <div style="flex: 2;">
                    <p>Alex Golder-Wood is a biomedical engineer for the NHS and resides in Chesterfield, Derbyshire.</p>
                    <p>After many years of crafting the story, he released his debut novel 'Shadows of the Green' in April 2025, a powerful psychological drama that explores mental health, trauma, and redemption.</p>
                    <p>His work blends contemporary literary fiction with unflinching social realism, examining how childhood experiences shape our adult lives and the courage it takes to break destructive cycles.</p>
                    <p>His 2nd novel, False Alarm, is coming later in 2025, and is a psychological thriller.</p>
                    <p>Thank you for visiting my website and joining me on this literary adventure. I look forward to sharing more stories with you in the years to come.</p>
                </div>
            </div>
        </section>
    </div>
    
    <!-- Books Content -->
    <div id="books-content">
        <section class="container" style="padding: 60px 0;">
            <h2>My Books</h2>
            <div class="books-grid">
                <div class="book-card">
                    <a href="https://www.amazon.co.uk/Shadows-Green-Alex-Golder-Wood-ebook/dp/B0F194LBD3/ref=sr_1_1?sr=8-1" target="_blank">
                        <img src="/api/placeholder/400/600" alt="Shadows of the Green">
                    </a>
                    <div class="book-card-content">
                        <h3>Shadows of the Green</h3>
                        <p>My debut thriller set in the heart of the Peak District.</p>
                        <p>Released: April 2025</p>
                        <a href="https://www.amazon.co.uk/Shadows-Green-Alex-Golder-Wood-ebook/dp/B0F194LBD3/ref=sr_1_1?sr=8-1" class="cta-button" target="_blank">Buy on Amazon</a>
                    </div>
                </div>
                <div class="book-card">
                    <img src="/api/placeholder/400/600" alt="False Alarm">
                    <div class="book-card-content">
                        <h3>False Alarm</h3>
                        <p>The thrilling sequel to Shadows of the Green.</p>
                        <p>Coming: Late 2025</p>
                        <a href="#" class="cta-button" style="background-color: #7f8c8d;">Coming Soon</a>
                    </div>
                </div>
            </div>
        </section>
    </div>
    
    <!-- Contact Content -->
    <div id="contact-content">
        <section class="container" style="padding: 60px 0;">
            <h2>Get in Touch</h2>
            <div class="contact-info">
                <p>I love hearing from readers! For inquiries about events, interviews, or just to say hello, you can reach me through social media or email.</p>
                <h3>Connect on Social Media</h3>
                <div class="contact-social">
                    <a href="https://instagram.com/alexgwauthor" target="_blank">Instagram: @alexgwauthor</a>
                    <a href="https://tiktok.com/@alexgwauthor" target="_blank">TikTok: @alexgwauthor</a>
                </div>
                <h3>Email</h3>
                <p><a href="mailto:alexgwauthor@googlemail.com">alexgwauthor@googlemail.com</a></p>
            </div>
        </section>
    </div>
    
    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2025 Alex Golder-Wood. All Rights Reserved.</p>
            <div class="footer-links">
                <a href="#">Privacy Policy</a>
                <a href="#">Terms of Use</a>
                <a href="#" class="nav-link" data-tab="contact">Contact</a>
            </div>
        </div>
    </footer>

    <script>
        // Simple JavaScript for tab navigation
        document.addEventListener('DOMContentLoaded', function() {
            const tabs = document.querySelectorAll('.nav-link');
            
            tabs.forEach(tab => {
                tab.addEventListener('click', function(e) {
                    e.preventDefault();
                    
                    // Remove active class from all tabs and content
                    tabs.forEach(t => t.classList.remove('active'));
                    document.querySelectorAll('#home-content, #about-content, #books-content, #contact-content').forEach(content => {
                        content.classList.remove('active');
                    });
                    
                    // Add active class to clicked tab and corresponding content
                    this.classList.add('active');
                    document.getElementById(this.dataset.tab + '-content').classList.add('active');
                    
                    // Scroll to top
                    window.scrollTo(0, 0);
                });
            });
            
            // Also handle footer links
            document.querySelectorAll('.footer-links .nav-link').forEach(link => {
                link.addEventListener('click', function(e) {
                    e.preventDefault();
                    
                    tabs.forEach(t => {
                        if(t.dataset.tab === this.dataset.tab) {
                            t.click();
                        }
                    });
                });
            });
        });
    </script>
</body>
</html>
