<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Kalyani | Words & Whispers</title>
  <style>
    :root {
      --bg: #fdfaf6;
      --text: #2c2c2c;
      --accent: #b08ea2;
      --light-accent: #e3d5d9;
      --font: 'Georgia', serif;
    }

    body {
      margin: 0;
      font-family: var(--font);
      background-color: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    header {
      padding: 2rem;
      text-align: center;
      background-color: var(--light-accent);
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
      color: var(--accent);
    }

    header p {
      font-size: 1.2rem;
      margin-top: 0.5rem;
    }

    nav {
      text-align: center;
      padding: 1rem;
    }

    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: var(--accent);
      font-weight: bold;
    }

    section {
      max-width: 800px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    h2 {
      border-bottom: 2px solid var(--light-accent);
      padding-bottom: 0.3rem;
      color: var(--accent);
    }

    .poem {
      margin: 1.5rem 0;
      padding: 1rem;
      background-color: #fff;
      border-left: 4px solid var(--accent);
    }

    footer {
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      color: #999;
    }

    a.email {
      color: var(--accent);
      text-decoration: none;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Kalyani</h1>
    <p>Singing soul. Wandering words. Whispered worlds.</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#poems">Poems & Quotes</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>
      Hi, I'm Kalyani. I find solace in melodies and meaning in metaphors. Singing is how I breathe, and writing is how I dream aloud. 
      This space is where I share fragments of my thoughts — poems, quotes, and reflections that flutter from my soul to yours.
    </p>
  </section>

  <section id="poems">
    <h2>Poems & Quotes</h2>

    <div class="poem">
      <p><em>"In the quiet corners of the sky,<br>
      I stitched a poem with stars and sighs."</em></p>
    </div>

    <div class="poem">
      <p><em>"She didn’t just sing; she echoed across lifetimes,<br>
      her notes carrying stories no words could hold."</em></p>
    </div>

    <!-- Add more poems or quotes below -->
    <!-- Example:
    <div class="poem">
      <p><em>"Your new quote or poem goes here."</em></p>
    </div>
    -->

  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>If you'd like to reach out or collaborate, feel free to write to me at <a class="email" href="mailto:hummingquill.kalyani@gmail.com">hummingquill.kalyani@gmail.com</a>.</p>
  </section>

  <footer>
    &copy; 2025 Kalyani. Made with love and a little stardust.
  </footer>
</body>
</html>
