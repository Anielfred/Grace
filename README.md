 <html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>For Mimi: A Love That Crosses Oceans and Time</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      background-color: #ffe5ec;
      color: #333;
      position: relative;
      overflow-x: hidden;
    }
    .background-image {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: -1;
      overflow: hidden;
      pointer-events: none;
    }
    .background-image img {
      position: absolute;
      opacity: 0.15;
      animation: float 20s infinite ease-in-out;
    }
    @keyframes float {
      0% { transform: translateY(0px); }
      50% { transform: translateY(-20px); }
      100% { transform: translateY(0px); }
    }
    header {
      background-color: #ffb6c1;
      padding: 20px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    header h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 3em;
      margin: 0;
      color: white;
    }
    .chapter {
      padding: 30px;
      max-width: 800px;
      margin: auto;
      background-color: white;
      margin-top: 20px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    .chapter h2 {
      font-family: 'Great Vibes', cursive;
      color: #ff69b4;
      text-align: center;
    }
    .chapter p {
      line-height: 1.8;
      text-align: justify;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #ffb6c1;
      color: white;
      margin-top: 40px;
    }
    .music-player {
      text-align: center;
      margin: 20px;
    }
    .message-box {
      max-width: 800px;
      margin: 20px auto;
      text-align: center;
    }
    .message-box textarea {
      width: 90%;
      height: 100px;
      padding: 10px;
      border-radius: 10px;
      border: 1px solid #ccc;
    }
    .message-box button {
      margin-top: 10px;
      padding: 10px 20px;
      background-color: #ff69b4;
      border: none;
      border-radius: 8px;
      color: white;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="background-image">
    <img src="mimi1.jpg" style="top: 10%; left: 5%; width: 100px;">
    <img src="mimi2.jpg" style="top: 30%; left: 70%; width: 120px;">
    <img src="mimi3.jpg" style="top: 60%; left: 20%; width: 80px;">
    <img src="mimi4.jpg" style="top: 80%; left: 50%; width: 150px;">
    <img src="mimi5.jpg" style="top: 40%; left: 40%; width: 90px;">
  </div>

  <header>
    <h1>For Mimi: A Love That Crosses Oceans and Time</h1>
  </header>

  <div class="music-player">
    <p>Play a song while you read:</p>
    <audio controls>
      <source src= "At The Beginning - Richard Marx & Donna Lewis (Lyrics).mp3" type="audio/mp3">
      Your browser does not support the audio element.
    </audio>
  </div>

  <div class="chapter">
    <h2>Chapter 1: The Beginning</h2>
    <p>From the moment we met, something sparked inside me—a quiet but powerful pull toward you, Mimi...</p>
  </div>
  <div class="chapter">
    <h2>Chapter 2: The Challenges</h2>
    <p>Long-distance is never easy, yet you stood by me through every lonely night, every petty argument...</p>
  </div>
  <div class="chapter">
    <h2>Chapter 3: My Promise</h2>
    <p>Mimi, I promise that one day, the oceans won’t keep us apart. I will build a future where we can...</p>
  </div>
  <div class="chapter">
    <h2>Chapter 4: Grateful Heart</h2>
    <p>I thank you, Mimi, for your never-ending patience. For embracing my flaws, soothing my insecurities...</p>
  </div>
  <div class="chapter">
    <h2>Chapter 5: Always and Forever</h2>
    <p>No matter where life takes us, you are my home. I see a lifetime with you—sunsets, travels...</p>
  </div>
  <div class="chapter">
    <h2>Chapter 6: Our Shared Dreams</h2>
    <p>We have whispered dreams through calls and typed them in messages, planning the life we want to live together. From a cozy little house to stargazing on the roof, every shared dream with you feels alive and possible.</p>
  </div>
  <div class="chapter">
    <h2>Chapter 7: The Little Things</h2>
    <p>Your good morning messages, your laughter over silly jokes, the way you say my name—all the little things add up to something big. You make ordinary moments feel like magic.</p>
  </div>
  <div class="chapter">
    <h2>Chapter 8: Through My Eyes</h2>
    <p>When I look at you, I see someone brave, beautiful, and full of love. You’re not just my girlfriend—you’re my safe place, my greatest joy, my home. You inspire me every day to be better.</p>
  </div>
  <div class="chapter">
    <h2>Chapter 9: What I’ve Learned</h2>
    <p>Loving you has taught me patience, trust, and commitment. It’s not always easy, but it’s always worth it. You’ve helped me grow in ways I never expected, and I’m thankful for every lesson we’ve shared.</p>
  </div>
  <div class="chapter">
    <h2>Chapter 10: A Love That Lasts</h2>
    <p>This is just the beginning of our forever, Mimi. Our story doesn’t end with this book—it lives on in every call, every visit, every dream we chase. I will love you always, across oceans and time.</p>
  </div>

  <div class="message-box">
    <h2>Leave a Message for Dadi</h2>
    <textarea placeholder="Type your sweet message..."></textarea><br>
    <button onclick="alert('Your message has been sent to Dadi (in your heart).')">Send</button>
  </div>

  <footer>
    Made with love by You, for Mimi.
  </footer>
</body>
</html>
