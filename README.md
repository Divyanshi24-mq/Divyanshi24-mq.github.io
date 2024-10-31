<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Main Page - Buying Under Pressure</title>
    <style>
        /* General body styling */
        body {
            margin: 0;
            padding: 0;
            overflow: hidden; /* Prevent scrolling */
        }
        /* Navigation bar styling */
        nav {
            background-color: rgba(51, 51, 51, 0.7); /* Make navigation semi-transparent */
            padding: 10px;
            text-align: center;
            position: relative; /* Ensure navigation is above the background */
            z-index: 1; /* Higher than video */
        }
        nav a {
            color: #FFF;
            margin: 0 15px;
            text-decoration: none;
            font-size: 18px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        /* Section styles */
        .section-orange-peel {
            background-color: rgba(255, 159, 28, 0.8); /* Made sections slightly transparent */
            padding: 20px;
            color: #FFF;
            position: relative; /* Layer section above the background video */
            z-index: 1; /* Higher than video */
        }
        .section-hunyadi-yellow {
            background-color: rgba(255, 191, 105, 0.8);
            padding: 20px;
            position: relative;
            z-index: 1;
        }
        .section-white {
            background-color: rgba(255, 255, 255, 0.9);
            padding: 20px;
            color: #000;
            position: relative;
            z-index: 1;
        }
        .section-mint-green {
            background-color: rgba(203, 243, 240, 0.8);
            padding: 20px;
            position: relative;
            z-index: 1;
        }
        .section-light-sea-green {
            background-color: rgba(46, 196, 182, 0.8);
            padding: 20px;
            color: #FFF;
            position: relative;
            z-index: 1;
        }
        /* Text styling */
        h2 {
            margin: 0;
            padding-bottom: 10px;
            font-size: 24px;
        }
        p {
            margin: 0;
            font-size: 18px;
        }
    </style>
</head>
<body>
    <!-- Background Video -->
    <iframe 
        width="100%" 
        height="100%" 
        src="https://www.youtube.com/embed/miXRW9rWpDM?autoplay=1&mute=1&loop=1&playlist=miXRW9rWpDM" 
        frameborder="0" 
        allow="autoplay; encrypted-media" 
        style="position: fixed; top: 0; left: 0; width: 100%; height: 100%; z-index: -1;">
    </iframe>
    <!-- Navigation -->
    <nav>
        <a href="index.html">Home</a>
        <a href="ourteam.html">Our Team</a>
        <a href="findings.html">Findings</a>
        <a href="methodology.html">Methodology</a>
    </nav>
    <h1 style="font-size: 3em; text-align: center; margin-top: 20px;">Buying Under Pressure</h1>
    <!-- Orange Peel Section -->
    <div class="section-orange-peel">
        <h2>Introduction</h2>
        <p>"Buying Under Pressure" – a guide to navigating Sydney's challenging housing market.</p>
    </div>
    <!-- Hunyadi Yellow Section -->
    <div class="section-hunyadi-yellow">
        <h2>What Experts Are Saying</h2>
        <p>Insights from industry experts on the current state of Sydney's housing market.</p>
    </div>
    <!-- White Section -->
    <div class="section-white">
        <h2>4 Major Challenges</h2>
        <p>An overview of the primary challenges faced by first-time buyers and renters.</p>
    </div>
    <!-- Mint Green Section -->
    <div class="section-mint-green">
        <h2>How It's Affecting People</h2>
        <p>Understanding the impact of the housing market crisis on people's lives and financial stability.</p>
    </div>
    <!-- Light Sea Green Section -->
    <div class="section-light-sea-green">
        <h2>Solution</h2>
        <p>Exploring potential solutions and strategies to make homeownership more achievable.</p>
    </div>
</body>
</html>

