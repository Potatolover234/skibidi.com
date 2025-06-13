<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>💎 Fancy HTML Page</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Roboto:wght@400;500&display=swap');

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Roboto', sans-serif;
      background: linear-gradient(135deg, #1f1c2c, #928DAB);
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      overflow: hidden;
      color: white;
      animation: backgroundShift 20s ease infinite;
    }

    @keyframes backgroundShift {
      0%, 100% {
        background: linear-gradient(135deg, #1f1c2c, #928DAB);
      }
      50% {
        background: linear-gradient(135deg, #0f2027, #2c5364);
      }
    }

    .card {
      backdrop-filter: blur(14px);
      background: rgba(255, 255, 255, 0.05);
      border-radius: 20px;
      padding: 2rem;
      box-shadow: 0 8px 32px rgba(0,0,0,0.2);
      text-align: center;
      width: 90%;
      max-width: 600px;
      transition: transform 0.4s ease;
    }

    .card:hover {
      transform: scale(1.03);
    }

    h1 {
      font-family: 'Playfair Display', serif;
      font-size: 2.8rem;
      margin-bottom: 1rem;
      color: #ffffff;
      text-shadow: 0 2px 5px rgba(0,0,0,0.5);
    }

    p {
      font-size: 1.1rem;
      color: #ddd;
      margin-bottom: 2rem;
    }

    .fancy-btn {
      background: linear-gradient(135deg, #ff4e50, #f9d423);
      border: none;
      padding: 0.8rem 2rem;
      border-radius: 30px;
      font-size: 1rem;
      font-weight: bold;
      color: #fff;
      cursor: pointer;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
      transition: all 0.3s ease;
    }

    .fancy-btn:hover {
      transform: scale(1.1);
      box-shadow: 0 6px 20px rgba(255, 255, 255, 0.3);
    }

    .footer {
      margin-top: 2rem;
      font-size: 0.85rem;
      color: rgba(255,255,255,0.4);
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>🌟 Welcome to FancyLand</h1>
    <p>This isn't just an HTML page... it's an experience. ✨</p>
    <button class="fancy-btn" onclick="alert('You clicked fancy magic! 🪄')">✨ Click Me ✨</button>
    <div class="footer">Made with style by ChatGPT 💖</div>
  </div>
</body>
</html>
