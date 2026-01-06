# rick5007.github.io
Official gaming website for the Rick5007 YouTube channel
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Rick5007 | Gaming Channel</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      color: white;
      text-align: center;
      overflow-x: hidden;
      background: linear-gradient(270deg, #000000, #1a0000, #ff0000, #1a0000, #000000);
      background-size: 1000% 1000%;
      animation: neonMove 15s ease infinite;
    }

    @keyframes neonMove {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    /* INTRO */
    .intro {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      animation: fadeOut 1s forwards;
      animation-delay: 3.5s;
    }

    .intro img {
      width: 180px;
      filter: drop-shadow(0 0 30px red);
      animation: zoomIn 1.5s ease;
    }

    .intro h1 {
      font-size: 3em;
      color: #ff1a1a;
      text-shadow: 0 0 25px red;
      animation: pulse 1.2s infinite alternate;
    }

    @keyframes zoomIn {
      from { transform: scale(0); opacity: 0; }
      to { transform: scale(1); opacity: 1; }
    }

    @keyframes pulse {
      from { text-shadow: 0 0 10px red; }
      to { text-shadow: 0 0 35px red; }
    }

    @keyframes fadeOut {
      to { opacity: 0; visibility: hidden; height: 0; }
    }

    /* MAIN SITE */
    .site {
      opacity: 0;
      animation: show 1s forwards;
      animation-delay: 4s;
    }

    @keyframes show {
      to { opacity: 1; }
    }

    header {
      padding: 60px 20px;
    }

    header img {![image](https://github.com/user-attachments/assets/5753393b-d0d9-4edb-8cb3-83af746baa13)

      width: 140px;
      filter: drop-shadow(0 0 25px red);
    }

    h2 {
      font-size: 2.8em;
      color: #ff1a1a;
      text-shadow: 0 0 20px red;
    }

    .btn {
      margin-top: 25px;
      padding: 15px 35px;
      background: red;
      color: white;
      text-decoration: none;
      font-size: 1.1em;
      border-radius: 40px;
      box-shadow: 0 0 25px red;
      transition: 0.3s;
      display: inline-block;
    }

    .btn:hover {
      transform: scale(1.1);
      box-shadow: 0 0 40px red;
    }

    section {
      margin: 25px;
      padding: 45px 20px;
      background: rgba(0,0,0,0.6);
      border: 1px solid rgba(255,0,0,0.4);
      border-radius: 15px;
    }

    footer {
      padding: 25px;
      opacity: 0.6;
    }

    /* MUSIC BUTTON */
    .music-btn {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: red;
      border: none;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      font-size: 20px;
      color: white;
      box-shadow: 0 0 20px red;
      cursor: pointer;
    }
  </style>
</head>

<body>

  <!-- MUSIC -->
  <audio id="bgMusic" loop>
    <source src="music.mp3" type="audio/mpeg">
  </audio>

  <button class="music-btn" onclick="toggleMusic()">🎵</button>

  <!-- INTRO -->
  <div class="intro">
    <img src="logo.png" alt="Rick5007 Logo">
    <h1>Rick5007</h1>
  </div>

  <!-- SITE -->
  <div class="site">
    <header>
      <img src="logo.png">
      <h2>Rick5007</h2>
      <p>🎮 Gaming • 🔥 Neon Content • 🎥 YouTube Creator</p>

      <a class="btn"
        href="https://youtube.com/@riek5007?si=8RmXtyu-ABKnw99r"
        target="_blank">
        Subscribe on YouTube
      </a>
    </header>

    <section>
      <h3>About</h3>
      Epic gaming content, highlights, and fun moments.
      Welcome to the neon zone 🔴⚡
    </section>

    <section>
      🎮 Gaming Videos <br>
      🔥 Highlights <br>
      😂 Funny Clips <br>
      🚀 New uploads
    </section>

    <footer>
      © 2026 Rick5007 | Neon Gaming Website
    </footer>
  </div>

  <script>
    const music = https://youtu.be/JJzrBQGVa_c?si=jG31FDrjLh72E8QZdocument.getElementById("bgMusic");
    let playing = false;

    function toggleMusic() {
      if (!playing) {
        music.play();
        playing = true;
      } else {
        music.pause();
        playing = false;
      }
    }
  </script>

</body>
</html>
