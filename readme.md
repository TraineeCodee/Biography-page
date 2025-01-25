create a biography above used by html and css


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biography</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }

        header {
            background-color: #6200ea;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        .container {
            max-width: 800px;
            margin: 2rem auto;
            padding: 1rem;
            background: white;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        .bio-image {
            text-align: center;
            margin-bottom: 1.5rem;
        }

        .bio-image img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        h2 {
            color: #6200ea;
            margin-top: 0;
        }

        p {
            line-height: 1.6;
            margin: 1rem 0;
        }

        .hobbies {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }

        .hobby {
            flex: 1 1 calc(50% - 1rem);
            background-color: #f4f4f9;
            border: 1px solid #ddd;
            padding: 1rem;
            border-radius: 8px;
            text-align: center;
        }

        .hobby img {
            max-width: 50px;
            margin-bottom: 0.5rem;
        }

        footer {
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
            font-size: 0.9rem;
            background-color: #6200ea;
            color: white;
        }

        footer a {
            color: #ffcc00;
            text-decoration: none;
        }
    </style>
</head>
<body>

<header>
    <h1>Ashiq Muhammed</h1>
    <p>A Brief Story of My Life</p>
</header>

<div class="container">
    <div class="bio-image">
        <img src="https://via.placeholder.com/150" alt="John Doe">
    </div>
    <h2>About Me</h2>
    <p>Hi! I'm Ashiq Muhammed , a passionate web developer with a love for creating beautiful and functional websites. I have been in the tech industry for over 5 years and enjoy solving problems through code. Outside of work, I enjoy hiking, photography, and exploring new cuisines.</p>

    <h2>My Hobbies</h2>
    <div class="hobbies">
        <div class="hobby">
            <img src="https://via.placeholder.com/50" alt="Hiking">
            <h3>Hiking</h3>
            <p>Exploring the beauty of nature and staying fit.</p>
        </div>
        <div class="hobby">
            <img src="https://via.placeholder.com/50" alt="Photography">
            <h3>Photography</h3>
            <p>Capturing moments that tell a story.</p>
        </div>
        <div class="hobby">
            <img src="https://via.placeholder.com/50" alt="Cooking">
            <h3>Cooking</h3>
            <p>Experimenting with flavors and trying new recipes.</p>
        </div>
        <div class="hobby">
            <img src="https://via.placeholder.com/50" alt="Gaming">
            <h3>Gaming</h3>
            <p>Unwinding with some fun video games.</p>
        </div>
    </div>
</div>

<footer>
    <p>&copy; 2025 Ashiq Muhammed. Connect with me on <a href="#">LinkedIn</a>!</p>
</footer>

</body>
</html>
