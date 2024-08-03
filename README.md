
<html lang="en">

remote_theme: pages-themes/midnight@v0.2.0
plugins:
- jekyll-remote-theme # add this line to the plugins list if you already have one

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Car Detailing Company</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Car Detailing Company</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="services.html">Services</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="hero">
            <h2>Professional Car Detailing Services</h2>
            <p>Your car deserves the best care.</p>
        </section>
        <section id="overview">
            <h2>Our Services</h2>
            <p>We offer a range of detailing services to keep your car looking its best.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Car Detailing Company</p>
    </footer>
</body>
</html> 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Services - Car Detailing Company</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Our Services</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="services.html">Services</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="services">
            <h2>Exterior Detailing</h2>
            <p>Complete exterior wash, waxing, and polishing.</p>
            <h2>Interior Detailing</h2>
            <p>Thorough cleaning of the car’s interior, including seats, carpets, and dashboard.</p>
            <h2>Full Detailing</h2>
            <p>Combination of exterior and interior detailing for a complete car care package.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Car Detailing Company</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact - Car Detailing Company</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Contact Us</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="services.html">Services</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="contact-form">
            <h2>Get in Touch</h2>
            <form action="#" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </section>
        <section id="contact-info">
            <h2>Contact Information</h2>
            <p>Address: 123 Car Street, Auto City, CA 98765</p>
            <p>Phone: (123) 456-7890</p>
            <p>Email: contact@cardetailing.com</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Car Detailing Company</p>
    </footer>
</body>
</html>

document.addEventListener('DOMContentLoaded', () => {
    const form = document.querySelector('form');
    form.addEventListener('submit', (event) => {
        event.preventDefault();
        alert('Form submitted!');
    });
});
