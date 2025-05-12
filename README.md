<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Global Trending News</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>🌍 Global Trending News</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">World</a></li>
                <li><a href="#">Politics</a></li>
                <li><a href="#">Technology</a></li>
                <li><a href="#">Entertainment</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="headline">
            <h2>🌟 Top Story: Peace Talks Resume in Middle East</h2>
            <p>Leaders from several nations have resumed negotiations in hopes of resolving the ongoing crisis. The talks are being held in Geneva with international observers in attendance.</p>
        </section>

        <section class="news-grid">
            <article>
                <h3>🚀 Tech: AI Set to Transform Global Economy</h3>
                <p>Experts predict AI will contribute $15 trillion to the global economy by 2030. Read more about how it's already shaping industries.</p>
            </article>
            <article>
                <h3>🎬 Entertainment: Global Film Wins Big at Cannes</h3>
                <p>A powerful drama from South Korea has taken the top prize at the prestigious Cannes Film Festival, capturing hearts worldwide.</p>
            </article>
            <article>
                <h3>🗳️ Politics: Elections in Europe Shake Status Quo</h3>
                <p>Several European countries have seen major shifts in power as voters demand change. Analysts say it could affect EU policies.</p>
            </article>
        </section>
    </main>

    <footer>
        <p>© 2025 Global Trending News | All rights reserved.</p>
    </footer>
</body>
</html>
# Global-treading-newsbody {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #1e90ff;
    color: white;
    padding: 20px;
    text-align: center;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    padding: 0;
    margin-top: 10px;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

.headline {
    background-color: white;
    padding: 20px;
    margin: 20px auto;
    max-width: 800px;
    border-radius: 8px;
}

.news-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    margin: 0 auto 40px;
    max-width: 1000px;
}

.news-grid article {
    background-color: white;
    padding: 15px;
    border-radius: 8px;
    width: 300px;
}

footer {
    background-color: #1e90ff;
    color: white;
    text-align: center;
    padding: 15px;
    position: relative;
    bottom: 0;
    width: 100%;
}
