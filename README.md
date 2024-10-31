<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Main Page - Buying Under Pressure</title>
    <style>
        /* General styling */
        body, h1, h2, p {
            margin: 0;
            padding: 0;
        }
        body {
            overflow: hidden; /* Prevent scrolling */
        }
        nav {
            background-color: rgba(51, 51, 51, 0.7);
            padding: 10px;
            text-align: center;
            z-index: 1;
        }
        nav a {
            color: #FFF;
            margin: 0 10px;
            text-decoration: none;
            font-size: 18px;
        }
        /* Section styles */
        .section {
            padding: 20px;
            color: #FFF;
            position: relative;
            z-index: 1;
        }
        .orange { background-color: rgba(255, 159, 28, 0.8); }
        .yellow { background-color: rgba(255, 191, 105, 0.8); }
        .white { background-color: rgba(255, 255, 255, 0.9); color: #000; }
        .mint { background-color: rgba(203, 243, 240, 0.8); }
        .sea-green { background-color: rgba(46, 196, 182, 0.8); }
        /* Responsive adjustments */
        @media (max-width: 768px) {
            h1 {
                font-size: 2em;
                margin: 15px;
                text-align: center;
            }
            nav a {
                font-size: 16px;
                margin: 0 8px;
            }
            .section {
                padding: 15px;
                font-size: 16px;
            }
        }
    </style>
</head>
<body>
    <!-- Background Video -->
    <video autoplay muted loop style="position: fixed; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; z-index: -1;">
        <source src="background-video.mp4" type="video/mp4">
    </video>
    <!-- Navigation -->
    <nav>
        <a href="index.html">Home</a>
        <a href="ourteam.html">Our Team</a>
        <a href="findings.html">Findings</a>
        <a href="methodology.html">Methodology</a>
    </nav>
    <!-- Content Sections -->
    <h1 style="text-align: center; margin-top: 20px;">Buying Under Pressure</h1>
    <div class="section orange">
        <h2>Introduction</h2>
        <p>"Buying Under Pressure" – a guide to navigating Sydney's challenging housing market.</p>
    </div>
    <div class="section yellow">
        <h2>What Experts Are Saying</h2>
        <p>Insights from industry experts on the current state of Sydney's housing market.</p>
    </div>
    <div class="section white">
        <h2>4 Major Challenges</h2>
        <p>An overview of the primary challenges faced by first-time buyers and renters.</p>
    </div>
    <div class="section mint">
        <h2>How It's Affecting People</h2>
        <p>Understanding the impact of the housing market crisis on people's lives and financial stability.</p>
    </div>
    <div class="section sea-green">
        <h2>Solution</h2>
        <p>Exploring potential solutions and strategies to make homeownership more achievable.</p>
    </div>
</body>
</html>


