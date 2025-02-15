<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anime Hub</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        /* Navbar */
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: #333;
            padding: 10px 20px;
        }
        
        .navbar a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
        }
        
        .navbar a:hover {
            background-color: #555;
        }

        /* Banner Section */
        .banner {
            background-image: url('https://example.com/anime-banner.jpg'); /* Replace with an actual anime image */
            background-size: cover;
            background-position: center;
            height: 400px;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .banner h1 {
            font-size: 50px;
            text-shadow: 2px 2px 8px #000;
        }

        /* Anime Cards Section */
        .anime-section {
            padding: 20px;
        }
        
        .anime-card {
            display: inline-block;
            width: 23%;
            margin: 1%;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            overflow: hidden;
        }
        
        .anime-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .anime-card h3 {
            text-align: center;
            padding: 10px;
        }

        /* Footer */
        .footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        @media only screen and (max-width: 768px) {
            .anime-card {
                width: 48%;
            }
        }
        
        @media only screen and (max-width: 480px) {
            .anime-card {
                width: 98%;
            }
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <div class="navbar">
        <a href="#">Home</a>
        <a href="#">Anime List</a>
        <a href="#">Latest Episodes</a>
        <a href="#">Contact</a>
    </div>

    <!-- Banner Section -->
    <div class="banner">
        <h1>Welcome to Anime Hub</h1>
    </div>

    <!-- Anime Cards Section -->
    <div class="anime-section">
        <div class="anime-card">
            <img src="https://example.com/anime1.jpg" alt="Anime 1">
            <h3>Anime Title 1</h3>
        </div>
        <div class="anime-card">
            <img src="https://example.com/anime2.jpg" alt="Anime 2">
            <h3>Anime Title 2</h3>
        </div>
        <div class="anime-card">
            <img src="https://example.com/anime3.jpg" alt="Anime 3">
            <h3>Anime Title 3</h3>
        </div>
        <div class="anime-card">
            <img src="https://example.com/anime4.jpg" alt="Anime 4">
            <h3>Anime Title 4</h3>
        </div>
    </div>

    <!-- Footer -->
    <div class="footer">
        <p>&copy; 2025 Anime Hub. All Rights Reserved.</p>
    </div>

</body>
</html># sohag
Here I and my timber will upload different types of anime dubbed in Bengali on this website
