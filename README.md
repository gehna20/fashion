<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fashion Forward</title>
    <!-- Font Links -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Raleway:wght@300;500&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap" rel="stylesheet">

    <style>
        /* Body Styles */
        body {
            background-color: #F8E1F4;
            text-align: center;
            font-family: 'Roboto', sans-serif;
        }

        /* Heading Styles */
        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 48pt;
            color: #8C4B8E;
        }
        h2 {
            font-family: 'Playfair Display', serif;
            font-size: 36pt;
            color: #8C4B8E;
        }

        /* Paragraph Style */
        p {
            font-family: 'Raleway', sans-serif;
            font-size: 20pt;
            color: #6A1B9A;
            margin: 20px 0;
        }

        /* Dropdown Menu Styles */
        .dropdown {
            display: inline-block;
            margin: 20px;
        }

        .dropbtn {
            background-color: #D81B60;
            color: white;
            padding: 10px 20px;
            font-size: 18px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }

        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #F3E5F5;
            min-width: 200px;
            box-shadow: 0px 8px 16px rgba(0,0,0,0.2);
            border-radius: 5px;
            z-index: 1;
        }

        .dropdown-content a {
            color: #8E24AA;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
        }

        .dropdown-content a:hover {
            background-color: #F1C4E8;
        }

        .dropdown:hover .dropdown-content {
            display: block;
        }

        .dropdown-content p {
            padding: 10px;
            color: #6A1B9A;
            font-size: 16px;
        }

        /* Image Styles */
        img {
            margin-top: 20px;
            border-radius: 10px;
            width: 80%;
            max-width: 600px;
        }

        /* Footer Text Style */
        .footer-text {
            color: black;
            font-size: 20pt;
            font-family: 'Raleway', sans-serif;
            margin-top: 30px;
        }

        /* Fashion News Section */
        .news-section {
            background-color: #E1BEE7;
            padding: 30px 0;
        }

        .news-title {
            font-size: 32pt;
            font-family: 'Playfair Display', serif;
            color: #8C4B8E;
        }

        .news-item {
            background-color: #F3E5F5;
            margin: 10px;
            padding: 20px;
            border-radius: 8px;
        }

        /* Poll Section */
        .poll-section {
            background-color: #F3E5F5;
            padding: 30px 0;
        }

        .poll-title {
            font-size: 28pt;
            color: #8C4B8E;
            font-family: 'Raleway', sans-serif;
        }

        .poll-option {
            margin: 10px 0;
            font-size: 20px;
        }

        /* Instagram Feed Section */
        .instagram-feed {
            background-color: #E1BEE7;
            padding: 30px 0;
        }

        .instagram-title {
            font-size: 32pt;
            color: #8C4B8E;
            font-family: 'Playfair Display', serif;
        }

        .instagram-gallery {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        .instagram-gallery img {
            width: 30%;
            margin: 10px;
            border-radius: 8px;
        }

        /* Newsletter Subscription */
        .newsletter {
            background-color: #D81B60;
            padding: 30px 0;
            color: white;
        }

        .newsletter input[type="email"] {
            padding: 10px;
            font-size: 16px;
            border-radius: 5px;
            width: 60%;
        }

        .newsletter button {
            background-color: #8C4B8E;
            padding: 10px 20px;
            font-size: 16px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            color: white;
        }

        .hashtag-section {
            background-color: #F8E1F4;
            padding: 20px 0;
        }

        .hashtag-title {
            font-size: 28pt;
            color: #8C4B8E;
            font-family: 'Raleway', sans-serif;
        }

        .hashtag-list {
            display: flex;
            justify-content: center;
            gap: 10px;
            font-size: 20px;
            color: #8E24AA;
        }
    </style>
</head>
<body>
    <h1>Fashion Forward</h1>
    <h2>Stay ahead of the trends, create your own style!</h2>
    
    <p>
        Fashion is an art, and it is constantly evolving. It's about expressing yourself, having fun, and experimenting with styles that suit your personality. Explore the world of fashion with me as I dive into the latest trends, must-have outfits, and much more!
    </p>

    <!-- Dropdown Menus -->
    <div class="dropdown">
        <button class="dropbtn">Trendy Outfits</button>
        <div class="dropdown-content">
            <a href="#">Street Style</a>
            <p>Urban fashion and streetwear are all about comfort and creativity. Get inspired by the latest street trends from around the world.</p>
            <a href="#">Office Wear</a>
            <p>Discover chic and professional outfits for the workplace that blend style and elegance with comfort.</p>
            <a href="#">Evening Glam</a>
            <p>Glamorous outfits that shine during the night. Perfect for a night out or special events.</p>
            <a href="#">Casual Cool</a>
            <p>Casual styles that still have a fashion-forward edge. Perfect for lounging around or weekend getaways.</p>
        </div>
    </div>

    <!-- Fashion News Section -->
    <div class="news-section">
        <h2 class="news-title">Fashion News</h2>
        <div class="news-item">
            <h3>New York Fashion Week Recap</h3>
            <p>Catch up on all the highlights from this year's NYFW, featuring cutting-edge designers and incredible street style!</p>
        </div>
        <div class="news-item">
            <h3>Summer Trends: What’s In?</h3>
            <p>Explore the hottest summer fashion trends from oversized shirts to bold prints that will make you stand out.</p>
        </div>
    </div>

    <!-- Poll Section -->
    <div class="poll-section">
        <h2 class="poll-title">Which fashion trend are you most excited about?</h2>
        <div class="poll-option">
            <input type="radio" id="trend1" name="fashionTrend" value="Streetwear">
            <label for="trend1">Streetwear</label>
        </div>
        <div class="poll-option">
            <input type="radio" id="trend2" name="fashionTrend" value="Office Chic">
            <label for="trend2">Office Chic</label>
        </div>
        <div class="poll-option">
            <input type="radio" id="trend3" name="fashionTrend" value="Evening Glam">
            <label for="trend3">Evening Glam</label>
        </div>
    </div>

    <!-- Instagram Feed Section -->
    <div class="instagram-feed">
        <h2 class="instagram-title">Latest Instagram Posts</h2>
        <div class="instagram-gallery">
            <img src="image 3.jpg" alt="Instagram Post 1">
            <img src="images 2.jpeg" alt="Instagram Post 2">
            <img src="images 4.jpeg" alt="Instagram Post 3">
        </div>
    </div>

    <!-- Newsletter Subscription Section -->
    <div class="newsletter">
        <h2>Subscribe for Fashion Updates</h2>
        <input type="email" placeholder="Enter your email" required>
        <button type="submit">Subscribe</button>
    </div>

    <!-- Trending Hashtags Section -->
    <div class="hashtag-section">
        <h2 class="hashtag-title">Trending Fashion Hashtags</h2>
        <div class="hashtag-list">
            <span>#FashionForward</span>
            <span>#StreetStyle</span>
            <span>#OOTD</span>
            <span>#SustainableFashion</span>
        </div>
    </div>

    <p class="footer-text">
        Don't forget to check out my other inspirations on <a href="https://www.behance.net" target="_blank">Behance</a>!
    </p>

</body>
</html>
