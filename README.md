# Guardivity
Where financial and insurance companies find ultimate peace of mind
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guardivity - Cybersecurity You Can Trust</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            background-color: #0b0c10;
            color: #fff;
        }
        header {
            background-color: #1f2833;
            padding: 20px 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header h1 {
            margin: 0;
            color: #66fcf1;
        }
        nav a {
            color: #fff;
            margin-left: 20px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: #66fcf1;
        }
        .hero {
            text-align: center;
            padding: 150px 20px;
            background: linear-gradient(135deg, #1f2833 0%, #0b0c10 100%);
        }
        .hero h2 {
            font-size: 3em;
            margin-bottom: 20px;
            color: #66fcf1;
        }
        .hero p {
            font-size: 1.2em;
            margin-bottom: 40px;
        }
        .hero button {
            padding: 15px 30px;
            font-size: 1em;
            background-color: #66fcf1;
            border: none;
            color: #0b0c10;
            font-weight: bold;
            cursor: pointer;
            border-radius: 5px;
        }
        .hero button:hover {
            background-color: #45a29e;
        }
        section {
            padding: 80px 50px;
        }
        section h3 {
            font-size: 2em;
            margin-bottom: 20px;
            color: #66fcf1;
        }
        .services, .contact {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
        }
        .card {
            background-color: #1f2833;
            padding: 30px;
            flex: 1 1 300px;
            border-radius: 10px;
        }
        footer {
            background-color: #1f2833;
            text-align: center;
            padding: 30px;
            color: #fff;
        }
    </style>
</head>
<body>

<header>
    <h1>Guardivity</h1>
    <nav>
        <a href="#services">Services</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Your Security, Our Mission</h2>
    <p>Providing a safe digital environment so your business can thrive without threats.</p>
    <button>Get Started</button>
</section>

<section id="services">
    <h3>Our Services</h3>
    <div class="services">
        <div class="card">
            <h4>Cybersecurity Consulting</h4>
            <p>Expert guidance to secure your digital infrastructure and prevent breaches.</p>
        </div>
        <div class="card">
            <h4>Penetration Testing</h4>
            <p>Simulating attacks to identify vulnerabilities before hackers do.</p>
        </div>
        <div class="card">
            <h4>24/7 Monitoring</h4>
            <p>Real-time threat detection and response to keep your business safe.</p>
        </div>
    </div>
</section>

<section id="about">
    <h3>About Guardivity</h3>
    <p>Guardivity is committed to creating a secure environment for businesses to operate without fear. With our team of experts, cutting-edge technology, and proactive approach, your data and systems are always protected.</p>
</section>

<section id="contact">
    <h3>Contact Us</h3>
    <div class="contact">
        <div class="card">
            <p>Email: contact@guardivity.com</p>
            <p>Phone: +1 234 567 890</p>
            <p>Address: 123 Cyber Lane, Silicon Valley, CA</p>
        </div>
        <div class="card">
            <form>
                <input type="text" placeholder="Your Name" style="width:100%;padding:10px;margin-bottom:10px;border-radius:5px;border:none;">
                <input type="email" placeholder="Your Email" style="width:100%;padding:10px;margin-bottom:10px;border-radius:5px;border:none;">
                <textarea placeholder="Message" style="width:100%;padding:10px;border-radius:5px;border:none;"></textarea>
                <button type="submit" style="margin-top:10px;padding:10px 20px;background-color:#66fcf1;border:none;color:#0b0c10;font-weight:bold;border-radius:5px;cursor:pointer;">Send</button>
            </form>
        </div>
    </div>
</section>

<footer>
    &copy; 2025 Guardivity. All Rights Reserved.
</footer>

</body>
</html>
