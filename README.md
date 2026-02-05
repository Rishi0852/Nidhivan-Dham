[blackbox-output-code-G7XEELTCML.html](https://github.com/user-attachments/files/25090370/blackbox-output-code-G7XEELTCML.html)[blackbox-output-code-QDSPEK8YWV.css](https://github.com/user-attachments/files/25090371/blackbox-output-code-QDSPEK8YWV.css)
[Uploading blackbox-output-code<!DOCTYPE html>
<html lang="en">
<head>[Uploading blackbox-output-c/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Poppins', sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #fff;
    scroll-behavior: smooth;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Header */
#header {
    position: sticky;
    top: 0;
    background-color: #FF9933;
    color: white;
    padding: 10px 0;
    z-index: 1000;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

#header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 1.5rem;
    font-weight: 700;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: 500;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #FFD700;
}

/* Hero Section */
.hero {
    background-image: url('https://via.placeholder.com/1920x1080?text=Mathura+Temple+Vibe');
    background-size: cover;
    background-position: center;
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
    position: relative;
}

.hero::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: rgba(0,0,0,0.5);
}

.hero-content {
    position: relative;
    z-index: 1;
}

.hero h2 {
    font-size: 3rem;
    margin-bottom: 10px;
}

.hero p {
    font-size: 1.5rem;
    margin-bottom: 20px;
}

.btn-primary {
    background-color: #FFD700;
    color: #333;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    font-size: 1rem;
    cursor: pointer;
    transition: background-color 0.3s;
}

.btn-primary:hover {
    background-color: #FF9933;
    color: white;
}

.highlights {
    position: absolute;
    bottom: 20px;
    display: flex;
    justify-content: space-around;
    width: 100%;
    max-width: 800px;
}

.highlight-item {
    background-color: rgba(255,255,255,0.9);
    color: #333;
    padding: 10px;
    border-radius: 5px;
    font-size: 0.9rem;
}

/* Sections */
.section {
    padding: 60px 0;
    background-color: #f9f9f9;
}

.section:nth-child(even) {
    background-color: white;
}

.section h2 {
    text-align: center;
    margin-bottom: 40px;
    color: #FF9933;
    font-size: 2rem;
}

/* Rooms */
.rooms-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
}

.room-card {
    background-color: white;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    text-align: center;
}

.room-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.room-card h3 {
    margin: 20px 0 10px;
}

.room-card ul {
    list-style: none;
    padding: 0 20px;
}

.room-card li {
    margin-bottom: 5px;
}

.price {
    font-weight: 700;
    color: #FF9933;
    margin: 20px 0;
}

/* Amenities */
.amenities-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    text-align: center;
}

.amenity {
    background-color: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.amenity i {
    font-size: 2rem;
    color: #FF9933;
    margin-bottom: 10px;
}

/* Gallery */
.gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
}

.gallery-grid img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
}

/* Location */
.map-placeholder {
    margin-top: 20px;
}

/* Reviews */
.reviews-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
}

.review-card {
    background-color: white;
    padding: 20px;ode-QDSPEK8YWV.css…]()

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotel Nidhivan Dham - Peaceful Stay Near Prem Mandir, Vrindavan</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <!-- Header with Sticky Navigation -->
    <header id="header">
        <div class="container">
            <h1 class="logo">Hotel Nidhivan Dham</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#rooms">Rooms</a></li>
                    <li><a href="#amenities">Amenities</a></li>
                    <li><a href="#gallery">Gallery</a></li>
                    <li><a href="#location">Location</a></li>
                    <li><a href="#reviews">Reviews</a></li>
                    <li><a href="#contact">Contact Us</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Home Section (Hero) -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h2>Welcome to Hotel Nidhivan Dham</h2>
            <p>Peaceful Stay Near Prem Mandir, Vrindavan</p>
            <button class="btn-primary" onclick="alert('Booking feature coming soon!')">Book Now</button>
        </div>
        <div class="highlights">
            <div class="highlight-item"><i class="fas fa-map-marker-alt"></i> Near Shri Krishn Janambhoomi Mandir</div>
            <div class="highlight-item"><i class="fas fa-users"></i> Family Rooms</div>
            <div class="highlight-item"><i class="fas fa-wifi"></i> Free WiFi</div>
            <div class="highlight-item"><i class="fas fa-snowflake"></i> AC Rooms</div>
            <div class="highlight-item"><i class="fas fa-headset"></i> 24x7 Help Desk</div>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="section">
        <div class="container">
            <h2>About Us</h2>
            <p>Hotel Nidhivan Dham is the ideal choice for families and pilgrims seeking a safe, peaceful, and budget-friendly stay near the spiritual heart of Vrindavan. Located in walking distance from Shri Krishn Janambhoomi Mandir in Mathura, Uttar Pradesh, India, our hotel offers a serene environment to rejuvenate your soul amidst the divine aura of Lord Krishna's birthplace.</p>
        </div>
    </section>

    <!-- Rooms Section -->
    <section id="rooms" class="section">
        <div class="container">
            <h2>Our Rooms</h2>
            <div class="rooms-grid">
                <div class="room-card">
                    <img src="https://via.placeholder.com/300x200?text=Deluxe+AC+Room" alt="Deluxe AC Room">
                    <h3>Deluxe AC Room</h3>
                    <ul>
                        <li>Air Conditioning</li>
                        <li>Attached Bathroom</li>
                        <li>Free WiFi</li>
                        <li>Room Service</li>
                    </ul>
                    <p class="price">₹2,500 per night</p>
                </div>
                <div class="room-card">
                    <img src="https://via.placeholder.com/300x200?text=Family+Room" alt="Family Room">
                    <h3>Family Room</h3>
                    <ul>
                        <li>Spacious for Families</li>
                        <li>Attached Bathroom</li>
                        <li>Free WiFi</li>
                        <li>Extra Beds Available</li>
                    </ul>
                    <p class="price">₹3,000 per night</p>
                </div>
                <div class="room-card">
                    <img src="https://via.placeholder.com/300x200?text=Standard+Room" alt="Standard Room">
                    <h3>Standard Room</h3>
                    <ul>
                        <li>Basic Amenities</li>
                        <li>Attached Bathroom</li>
                        <li>Free WiFi</li>
                        <li>Budget-Friendly</li>
                    </ul>
                    <p class="price">₹1,800 per night</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Amenities Section -->
    <section id="amenities" class="section">
        <div class="container">
            <h2>Amenities</h2>
            <div class="amenities-list">
                <div class="amenity"><i class="fas fa-wifi"></i> Free WiFi</div>
                <div class="amenity"><i class="fas fa-snowflake"></i> AC Rooms</div>
                <div class="amenity"><i class="fas fa-shower"></i> Attached Bathroom</div>
                <div class="amenity"><i class="fas fa-concierge-bell"></i> 24 Hours Front Desk</div>
                <div class="amenity"><i class="fas fa-car"></i> Parking</div>
                <div class="amenity"><i class="fas fa-utensils"></i> Room Service</div>
                <div class="amenity"><i class="fas fa-praying-hands"></i> Temple Guidance for Guests</div>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="section">
        <div class="container">
            <h2>Gallery</h2>
            <div class="gallery-grid">
                <img src="https://via.placeholder.com/300x200?text=Hotel+Exterior" alt="Hotel Exterior">
                <img src="https://via.placeholder.com/300x200?text=Deluxe+Room" alt="Deluxe Room">
                <img src="https://via.placeholder.com/300x200?text=Family+Room" alt="Family Room">
                <img src="https://via.placeholder.com/300x200?text=Nearby+Temple" alt="Nearby Temple">
                <img src="https://via.placeholder.com/300x200?text=Dining+Area" alt="Dining Area">
                <img src="https://via.placeholder.com/300x200?text=Reception" alt="Reception">
            </div>
        </div>
    </section>

    <!-- Location Section -->
    <section id="location" class="section">
        <div class="container">
            <h2>Location</h2>
            <p>Near Prem Mandir, Vrindavan, Uttar Pradesh, India</p>
            <div class="map-placeholder">
                <!-- Placeholder for Google Maps embed -->
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3532.123456789012!2d77.123456789!3d27.123456789!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMjfCsDA3JzI0LjQiTiA3N8KwMDcnMjQuMyJF!5e0!3m2!1sen!2sin!4v1234567890123!5m2!1sen!2sin" width="100%" height="400" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
            </div>
        </div>
    </section>

    <!-- Reviews Section -->
    <section id="reviews" class="section">
        <div class="container">
            <h2>Guest Reviews</h2>
            <div class="reviews-grid">
                <div class="review-card">
                    <div class="stars">
                        <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                    </div>
                    <p>"A peaceful retreat near the temple. Highly recommended for families!" - Rajesh Kumar</p>
                </div>
                <div class="review-card">
                    <div class="stars">
                        <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                    </div>
                    <p>"Clean rooms and excellent service. Felt blessed staying here." - Priya Sharma</p>
                </div>
                <div class="review-card">
                    <div class="stars">
                        <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                    </div>
                    <p>"Budget-friendly and close to Shri Krishn Janambhoomi. Will visit again!" - Anil Gupta</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Us Section -->
    <section id="contact" class="section">
        <div class="container">
            <h2>Contact Us</h2>
            <form id="contact-form">
                <input type="text" placeholder="Your Name" required>
                <input type="tel" placeholder="Your Phone" required>
                <textarea placeholder="Your Message" required></textarea>
                <button type="submit" class="btn-primary">Send Message</button>
            </form>
            <div class="contact-info">
                <p>Phone: +91-1234567890</p>
                <p>Email: info@hotelnidivandham.com</p>
                <a href="https://wa.me/911234567890" class="whatsapp-btn"><i class="fab fa-whatsapp"></i> WhatsApp Us</a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="quick-links">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#about">About Us</a></li>
                        <li><a href="#rooms">Rooms</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
                <div class="social-media">
                    <h3>Follow Us</h3>
                    <a href="#"><i class="fab fa-facebook"></i></a>
                    <a href="#"><i class="fab fa-instagram"></i></a>
                    <a href="#"><i class="fab fa-twitter"></i></a>
                </div>
            </div>
            <p>&copy; 2023 Hotel Nidhivan Dham. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>-G7XEELTCML.html…]()
