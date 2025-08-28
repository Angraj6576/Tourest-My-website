<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel Buddy - Travel Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Navbar -->
    <header>
        <div class="logo">Travel Buddy</div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#destinations">Destinations</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <h1>Explore The World With Us</h1>
        <p>Your adventure starts here!</p>
        <a href="#destinations" class="btn">View Destinations</a>
    </section>

    <!-- Destinations -->
    <section id="destinations">
        <h2>Popular Destinations</h2>
        <div class="destinations-container">
            <div class="card">
                <img src="https://source.unsplash.com/400x300/?paris" alt="Paris">
                <h3>Paris</h3>
                <p>Romantic city with Eiffel Tower and art.</p>
            </div>
            <div class="card">
                <img src="https://source.unsplash.com/400x300/?maldives" alt="Maldives">
                <h3>Maldives</h3>
                <p>Beautiful beaches and crystal clear water.</p>
            </div>
            <div class="card">
                <img src="https://source.unsplash.com/400x300/?switzerland" alt="Switzerland">
                <h3>Switzerland</h3>
                <p>Snowy mountains and scenic beauty.</p>
            </div>
        </div>
    </section>

    <!-- Services -->
    <section id="services">
        <h2>Our Services</h2>
        <div class="services-container">
            <div class="service-card">
                <h3>Tour Packages</h3>
                <p>Customized travel plans for every budget.</p>
            </div>
            <div class="service-card">
                <h3>Flight Booking</h3>
                <p>Book flights at the best prices.</p>
            </div>
            <div class="service-card">
                <h3>Hotel Booking</h3>
                <p>Comfortable stays in top-rated hotels.</p>
            </div>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Angraj Singh. All Rights Reserved.</p>
        <div class="social-links">
            <a href="https://www.facebook.com/your-facebook" target="_blank">
                <img src="https://img.icons8.com/ios-filled/30/ffffff/facebook-new.png"/>
            </a>
            <a href="https://www.instagram.com/abhi_rajputt__?igsh=YjdqZGN2azQydmty" target="_blank">
                <img src="https://img.icons8.com/ios-filled/30/ffffff/instagram-new.png"/>
            </a>
            <a href="https://www.linkedin.com/in/angraj-singh-a5bba2265/" target="_blank">
                <img src="https://img.icons8.com/ios-filled/30/ffffff/linkedin.png"/>
            </a>
            <a href="https://twitter.com/your-twitter" target="_blank">
                <img src="https://img.icons8.com/ios-filled/30/ffffff/twitter.png"/>
            </a>
            <a href="https://www.youtube.com/channel/your-youtube" target="_blank">
                <img src="https://img.icons8.com/ios-filled/30/ffffff/youtube-play.png"/>
            </a>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
