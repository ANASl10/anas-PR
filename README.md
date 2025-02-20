<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FC Barcelona - Official</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        a {
            text-decoration: none;
            color: #004D98;
        }

        a:hover {
            color: #A50044;
        }

        /* Header and Navbar */
        header {
            background-color: #004D98;
            padding: 10px 20px;
            color: white;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header .logo {
            font-size: 24px;
            font-weight: bold;
        }

        header nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }

        header nav ul li {
            margin-left: 20px;
        }

        header nav ul li a {
            color: white;
            font-weight: bold;
        }

        header nav ul li a:hover {
            color: #da3737;
        }

        /* Hero Section */
        .hero {
            background-image: url('blue.jpeg');
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: rgb(20, 17, 18);
            text-align: center;
            box-shadow: #cf1313;
        }

        .hero h1 {
            font-size: 48px;
            margin: 0;
        }

        .hero p {
            font-size: 24px;
            margin: 10px 0 0;
        }

        /* Featured Content */
        .featured {
            padding: 40px 20px;
            text-align: center;
        }

        .featured h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }

        .featured .cards {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .featured .card {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            width: 30%;
            padding: 20px;
            margin: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .featured .card img {
            width: 100%;
            border-radius: 8px;
        }

        .featured .card h3 {
            font-size: 24px;
            margin: 15px 0 10px;
        }

        .featured .card p {
            font-size: 16px;
            color: #666;
        }

        /* Footer */
        footer {
            background-color: #004D98;
            color: white;
            padding: 20px;
            text-align: center;
            background-image: url(blue.jpeg);
        }

        footer .social-links a {
            color: white;
            margin: 0 10px;
            font-size: 20px;
        }

        footer .social-links a:hover {
            color: #A50044;
        }
        .featured .card button {
            background-color: #004D98;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            margin-top: 15px;
        }

        .featured .card button:hover {
            background-color: #A50044;  }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="logo">FC Barcelona</div>
        <nav>
            <ul>
                <li><a href="anas.html">Home </a></li>
                <li><a href="https://www.fcbarcelona.com/en/football/first-team/news">News</a></li>
                <li><a href="team.html">Teams</a></li>
                <li><a href="teckets.html">Tickets</a></li>
                <li><a href="clother.html">Shop</a></li>
                <li><a href="CONTACT.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <div>
            <h1>Welcome to FC Barcelona</h1>
            <p>that Club not normal club this is life</p>
        </div>
    </section>
  
    <section class="featured">
        <h2>Featured</h2>
        <div class="cards">
            <div class="card">
                <img src="capno.webp" alt="Match">
                <h3>Upcoming Matches</h3>
                <p>Check out the schedule for our next games.</p>
                <a href="teckets.html">
                <button>GET TICKETS NOW</button>
                </a>
            </div>
            <div class="card">
                <img src="barca site.webp" alt="Shop">
                <h3>Official Store</h3>
                <p>Get the latest FC Barcelona merchandise.</p>
                <a href="clother.html">
                <button>SHOP NOW</button>
                </a>
            </div>
            <div class="card">
                <img src="hestori.jpg" alt="History">
                <h3>Club History</h3>
                <p>Discover the rich history of FC Barcelona.</p>
                <a href="https://www.fcbarcelona.com/en/club/history/decade-by-decade">
                <button>MORE</button>
            </a>
            </div>
        </div>
    </section>

 
    <footer>
        <div class="social-links">
            <a href="https://es-es.facebook.com/fcbarcelona/">Facebook</a>
            <a href="https://x.com/FCBarcelona">Twitter</a>
            <a href="https://www.instagram.com/fcbarcelona/">Instagram</a>
        </div>
        <p> 2025 FC Barcelona. All rights reserved.</p>
    </footer>
</body>
</html>
