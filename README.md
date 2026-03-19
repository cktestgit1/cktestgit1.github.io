<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eldi Landscaping Services LLC</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
        }

        header {
            background: #2e7d32;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background: #1b5e20;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        .hero {
            background: url('https://images.unsplash.com/photo-1597007030739-6d2e7bde91c5') no-repeat center center/cover;
            color: white;
            padding: 100px 20px;
            text-align: center;
        }

        .hero h1 {
            font-size: 40px;
        }

        .btn {
            background: #ff9800;
            color: white;
            padding: 12px 20px;
            text-decoration: none;
            display: inline-block;
            margin-top: 15px;
            border-radius: 5px;
        }

        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }

        .services, .reviews {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background: #f4f4f4;
            padding: 20px;
            border-radius: 8px;
        }

        footer {
            background: #2e7d32;
            color: white;
            text-align: center;
            padding: 20px;
        }

        input, textarea {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            margin-bottom: 10px;
        }

        button {
            background: #2e7d32;
            color: white;
            border: none;
            padding: 12px;
            cursor: pointer;
        }
    </style>
</head>

<body>

<header>
    <h1>Eldi Landscaping Services LLC</h1>
    <p>Transform Your Outdoor Space</p>
</header>

<nav>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#reviews">Reviews</a>
    <a href="#contact">Contact</a>
</nav>

<div class="hero">
    <h1>Professional Hardscaping in Clifton Park</h1>
    <p>Patios, Walkways, Retaining Walls & More</p>
    <a href="#contact" class="btn">Get a Free Estimate</a>
</div>

<section id="services">
    <h2>Our Services</h2>
    <div class="services">
        <div class="card">
            <h3>Paver Patios</h3>
            <p>Custom patios designed to upgrade your outdoor living space.</p>
        </div>
        <div class="card">
            <h3>Walkways & Steps</h3>
            <p>Beautiful and durable walkways and outdoor steps.</p>
        </div>
        <div class="card">
            <h3>Retaining Walls</h3>
            <p>Strong and attractive retaining walls built to last.</p>
        </div>
        <div class="card">
            <h3>Stone Masonry</h3>
            <p>High-quality stonework with attention to every detail.</p>
        </div>
    </div>
</section>

<section id="about">
    <h2>About Us</h2>
    <p>
        Eldi Landscaping Services LLC is a family-owned and operated business based in Clifton Park, NY.
        We specialize in high-quality hardscaping with years of experience delivering reliable and professional service.
    </p>
    <p>
        We take pride in offering fair pricing, and we will beat or match competitor quotes. Our goal is to exceed expectations
        on every project while keeping job sites clean and completing work efficiently.
    </p>
</section>

<section id="reviews">
    <h2>Customer Reviews</h2>
    <div class="reviews">
        <div class="card">
            <p>"Showed up on time, worked efficiently, and finished our patio in one day. Everything came out perfect!"</p>
        </div>
        <div class="card">
            <p>"Very easy to work with and brought our vision to life. Highly recommend."</p>
        </div>
        <div class="card">
            <p>"Fair pricing and amazing results. Completely transformed our walkway."</p>
        </div>
        <div class="card">
            <p>"Hard-working, honest team. The project exceeded our expectations."</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Get a Free Estimate</h2>
    <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <input type="tel" placeholder="Your Phone">
        <textarea placeholder="Tell us about your project"></textarea>
        <button type="submit">Submit</button>
    </form>
</section>

<footer>
    <p>© 2026 Eldi Landscaping Services LLC | Clifton Park, NY</p>
</footer>

</body>
</html>

