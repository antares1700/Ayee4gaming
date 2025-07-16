<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ayee4Gaming</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <div class="logo">🎮 Ayee4Gaming 👑</div>
    <nav>
      <a href="#about">About</a>
      <a href="#mission">Mission</a>
      <a href="#vision">Vision</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section class="hero">
      <h1>Welcome to Ayee4Gaming</h1>
      <p class="slogan">1700Gaming – are you a gamer or you just bluffing?</p>
    </section>

    <section id="about">
      <h2>About Us</h2>
      <p>Ayee4Gaming is a rising force in the gaming world, founded by passionate players for players. We believe gaming is more than just entertainment — it's a future for the underdogs.</p>
    </section>

    <section id="mission">
      <h2>Our Mission</h2>
      <p>To show the value of gaming and provide opportunities for under-resourced gamers to reach their potential.</p>
    </section>

    <section id="vision">
      <h2>Our Vision</h2>
      <p>To make the company known all around the world and build a global empire starting from our hometown.</p>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:arnoldlunga34@gmail.com">arnoldlunga34@gmail.com</a></p>
      <p>Location: Bultfontein, Free State, South Africa</p>
    </section>
  </main>

  <footer>
    <p>© 2025 Ayee4Gaming. All rights reserved.</p>
  </footer>
</body>
</html>

body {
  margin: 0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background: #121212;
  color: #fff;
}

header {
  background: #1e1e1e;
  padding: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
  color: #facc15;
}

nav a {
  margin-left: 20px;
  text-decoration: none;
  color: #fff;
  transition: color 0.3s;
}

nav a:hover {
  color: #facc15;
}

.hero {
  text-align: center;
  padding: 60px 20px;
  background: #0f0f0f;
}

.slogan {
  font-style: italic;
  color: #facc15;
}

section {
  padding: 40px 20px;
  border-bottom: 1px solid #333;
}

h2 {
  color: #facc15;
}

footer {
  text-align: center;
  padding: 20px;
  background: #1e1e1e;
  color: #aaa;
}