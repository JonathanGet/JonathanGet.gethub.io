# JonathanGet.gethub.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Automated Lighting Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            transition: background-color 1s ease;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: #333;
        }

        main {
            padding: 20px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
    </style>
    <script>
        window.onload = function() {
            setTimeout(function() {
                document.body.style.backgroundColor = "#f0f0f0"; // Change background color to light gray
            }, 3000); // Delay in milliseconds (3 seconds in this example)
        };
    </script>
</head>
<body>
    <header>
        <h1>Welcome to Automated Lighting Website</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <main>
        <section id="home">
            <h2>Home Section</h2>
            <p>This is the home section of the website.</p>
        </section>
        <section id="about">
            <h2>About Section</h2>
            <p>This is the about section of the website.</p>
        </section>
        <section id="contact">
            <h2>Contact Section</h2>
            <p>This is the contact section of the website.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Automated Lighting Website</p>
    </footer>
</body>
</html>
