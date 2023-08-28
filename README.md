<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css"> <!-- Include your CSS file here -->
    <title>CETS - Quiz and Test Taking</title>
</head>
<body>
    <header>
        <nav>
            <div class="logo"> <!-- Logo and branding elements -->
                <img src="logo.png" alt="CETS Logo">
            </div>
            <ul class="navigation">
                <li><a href="#about">About</a></li>
                <li><a href="#register">Register</a></li>
                <li><a href="#login">Login</a></li>
                <!-- Add more navigation links here -->
            </ul>
        </nav>
    </header>
    <section id="about">
        <h1>Welcome to CETS</h1>
        <p>Your platform for interactive quizzes and tests.</p>
    </section>
    <section id="register">
        <h2>Register</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <!-- Add more registration fields here -->
            <button type="submit">Register</button>
        </form>
    </section>
    <section id="login">
        <h2>Login</h2>
        <form>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <!-- Add more login fields here -->
            <button type="submit">Login</button>
        </form>/* Reset some default browser styles */
body, h1, h2, h3, p {
    margin: 0;
    padding: 0;
}

/* Header styles */
header {
    background-color: #333;
    color: white;
    padding: 1rem;
}

.logo img {
    width: 100px;
}

.navigation {
    list-style: none;
}

.navigation li {
    display: inline;
    margin-right: 20px;
}

.navigation a {
    color: white;
    text-decoration: none;
}

/* Main section styles */
section {
    padding: 2rem;
}

/* Form styles */
form {
    max-width: 400px;
    margin: 0 auto;
}

form label {
    display: block;
    margin-bottom: 5px;
}

form input {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    background-color: #333;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

/* Footer styles */
footer {
    background-color: #eee;
    padding: 1rem;
    display: flex;
    justify-content: space-between;
}

.faq, .contact {
    flex-basis: 45%;
}

/* Media queries for responsiveness */
@media screen and (max-width: 768px) {
    form {
        max-width: 100%;
    }
}

    </section>
    <!-- Add more sections for other features -->
    <footer>
        <div class="faq">
            <h3>FAQ</h3>
            <!-- Add FAQ content here -->
        </div>
        <div class="contact">
            <h3>Contact Us</h3>
            <!-- Add contact information here -->
        </div>
    </footer>
</body>
</html>
