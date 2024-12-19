<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Author's Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Author Name</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#books">Books</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About the Author</h2>
        <p>This is a brief bio about the author.</p>
    </section>

    <section id="books">
        <h2>Books</h2>
        <div class="book">
            <img src="book1.jpg" alt="Book 1">
            <h3>Book Title 1</h3>
            <p>Description of Book 1.</p>
        </div>
        <div class="book">
            <img src="book2.jpg" alt="Book 2">
            <h3>Book Title 2</h3>
            <p>Description of Book 2.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email">
            <label for="message">Message:</label>
            <textarea id="message" name="message"></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Author Name. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
