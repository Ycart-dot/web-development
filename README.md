
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Styled Webpage</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    <section>
        <h2>About Us</h2>
        <p>This is a paragraph describing the purpose of the website.</p>
    </section>
    <section>
        <h2>Registration Form</h2>
        <form action="/submit" method="post">
            <div>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div>
                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone" required>
            </div>
            <div>
                <input type="submit" value="Register">
            </div>
        </form>
    </section>
    <section>
        <h2>User Information</h2>
        <table border="1">
            <tr>
                <th>Name</th>
                <th>Email</th>
                <th>Phone Number</th>
            </tr>
            <tr>
                <td>Jojo siwa</td>
                <td>siwajojoo@example.com</td>
                <td>123-456-7890</td>
            </tr>
            <!-- Add more rows as needed -->
        </table>
    </section>
    <section>
        <h2>Our Team</h2>
        <a href="https://google.com" target="_blank">
            <img src="c:\Users\pc\Desktop\desmond doss.webp" alt="desmond doss">
        </a>
    </section>
    <footer>
        <p>Visit <a href="https://google.com" target="_blank">Google</a> for more information.</p>
    </footer>
</body>
</html>


body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

h1 {
    font-size: 2em;
    margin: 0;
}

p {
    line-height: 1.6;
    margin: 10px 0;
}

