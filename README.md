<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>XofounderHub - Connect Founders & Co-Founders</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>XofounderHub</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#find-founder">Find Founder</a>
            <a href="#find-cofounder">Find Co-Founder</a>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to XofounderHub</h2>
        <p>Founders find co-founders, and co-founders find founders. Start building your dream team today!</p>
    </section>

    <section id="find-founder">
        <h2>Find a Founder</h2>
        <p>If you're a co-founder looking for a founder, post your skills or search profiles.</p>
        <form id="cofounder-form">
            <input type="text" id="cofounder-name" placeholder="Your Name" required>
            <input type="text" id="cofounder-skills" placeholder="Your Skills (e.g., coding, marketing)" required>
            <button type="submit">Post Profile</button>
        </form>
        <div id="cofounder-results"></div>
    </section>

    <section id="find-cofounder">
        <h2>Find a Co-Founder</h2>
        <p>If you're a founder looking for a co-founder, post your idea or search profiles.</p>
        <form id="founder-form">
            <input type="text" id="founder-name" placeholder="Your Name" required>
            <input type="text" id="founder-idea" placeholder="Your Idea (e.g., AI startup)" required>
            <button type="submit">Post Profile</button>
        </form>
        <div id="founder-results"></div>
    </section>

    <footer>
        <p>&copy; 2023 XofounderHub. Built with passion.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
