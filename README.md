<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>San Joaquin Valley Town Hall</title>
    <link rel="icon" href="images/favicon.ico">
    <link rel="stylesheet" href="styles/main.css">

    <style>
        :root {
            --accent-color: #800000;
        }

        header {
            background-color: var(--accent-color);
            padding: 20px;
            color: white;
        }

        header h2 {
            font-size: 170%;
            text-indent: 30px;
        }

        header h3 {
            font-size: 130%;
            font-style: italic;
            text-indent: 30px;
        }

        header img {
            float: left;
        }

        main {
            clear: left;
        }

        footer {
            background-color: var(--accent-color);
            padding: 10px;
        }

        footer p {
            text-align: center;
            color: white;
        }

        .large {
            font-size: 125%;
            text-shadow: 2px 2px 4px gray;
        }

        a {
            color: var(--accent-color);
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
            font-style: italic;
        }
    </style>
</head>
<body>
<header>
    <img src="images/town_hall_logo.gif" alt="Town Hall Logo" height="80">
    <h1>San Joaquin Valley Town Hall</h1>
    <h2>Celebrating our <em class="large">75</em>th Year</h2>
</header>

<main>
    <h2>Our Mission</h2>

    <p>
        San Joaquin Valley Town Hall is a non-profit organization that is run by an all-volunteer board of directors.
        Our mission is to bring nationally and internationally renowned, thought-provoking speakers who inform,
        educate, and entertain our audience! As one of our members told us:
    </p>

    <blockquote>
        Each year I give a ticket package to each of our family members.
        I think of it as the gift of knowledge...and that is priceless.
    </blockquote>

    <h2>Our Ticket Packages</h2>
    <ul>
        <li>Season Package: $95</li>
        <li>Patron Package: $200</li>
        <li>Single Speaker: $25</li>
    </ul>

    <h1>Season's Guest Speakers</h1>

    <h3>October</h3>
    <a href="speakers/brancaccio.html">David Brancaccio</a><br>
    <img src="images/brancaccio75.jpg" alt="David Brancaccio Photo" height="150">

    <h3>November</h3>
    <a href="speakers/sorkin.html">Andrew Ross Sorkin</a><br>
    <img src="images/sorkin75.jpg" alt="Andrew Ross Sorkin Photo" height="150">

    <h3>January</h3>
    <a href="speakers/chua.html">Amy Chua</a><br>
    <img src="images/chua75.jpg" alt="Amy Chua Photo" height="150">
</main>

<footer>
    <p>&copy; Dhruval Rana, October 21, 2025</p>
</footer>
</body>
</html>
