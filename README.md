<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      /* Skin color to grey gradient */
      background: linear-gradient(135deg, #f2d1b3, #b0b0b0);
      background-attachment: fixed;
      color: #1a1a1a;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }

    .container {
      background: rgba(255, 255, 255, 0.08);
      backdrop-filter: blur(15px);
      border-radius: 20px;
      box-shadow: 0 0 25px rgba(0, 0, 0, 0.2);
      max-width: 800px;
      width: 90%;
      padding: 40px;
      text-align: left; /* Left-align text */
      transition: 0.3s ease;
    }

    .container:hover {
      transform: scale(1.02);
      box-shadow: 0 0 40px rgba(255, 255, 255, 0.15);
    }

    h1 {
      font-size: 2.4em;
      color: #1a1a1a;
      letter-spacing: 1px;
      margin-bottom: 25px;
    }

    .profile-pic {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 4px solid rgba(255, 255, 255, 0.8);
      background: url('https://w0.peakpx.com/wallpaper/226/672/HD-wallpaper-anime-demon-slayer-kimetsu-no-yaiba-kyojuro-rengoku.jpg') center/cover no-repeat;
      margin: 0 0 25px 0;
      box-shadow: 0 0 25px rgba(0, 0, 0, 0.3);
    }

    h2 {
      color: #1a1a1a;
      font-size: 1.3em;
      margin-top: 20px;
      border-bottom: 2px solid rgba(0,0,0,0.2);
      display: inline-block;
      padding-bottom: 5px;
    }

    p {
      color: #1a1a1a;
      margin: 8px 0;
      line-height: 1.6;
    }

    ul {
      list-style: none;
      padding: 0;
      margin: 10px 0;
    }

    li {
      margin: 6px 0;
      color: #1a1a1a;
    }

    li::before {
      content: "• ";
      color: #8b5e3c;
    }

    textarea {
      width: 100%;
      height: 100px;
      margin-top: 15px;
      border-radius: 10px;
      border: none;
      background: rgba(255, 255, 255, 0.15);
      color: #1a1a1a;
      padding: 10px;
      font-size: 1em;
      outline: none;
      resize: none;
      transition: 0.2s;
    }

    textarea:focus {
      background: rgba(255, 255, 255, 0.25);
      box-shadow: 0 0 10px rgba(0,0,0,0.4);
    }

    .footer {
      margin-top: 25px;
      color: #1a1a1a;
      font-weight: bold;
      font-size: 1.1em;
    }

  </style>
</head>
<body>
  <div class="container">
    <h1>My Portfolio</h1>

    <div class="profile-pic"></div>

    <h2>About Me</h2>
    <p><strong>Name:</strong> Aman</p>
    <p><strong>Age:</strong> 15</p>
    <p><strong>Class:</strong> 10</p>
    <p><strong>School:</strong> Govt. Model Senior Secondary School, MM CHD</p>

    <h2>Skills</h2>
    <ul>
      <li>Python</li>
      <li>Java</li>
      <li>HTML, CSS, JavaScript</li>
      <li>C / C++</li>
    </ul>

    <h2>Goals & Ideas 💡</h2>
    <p>I love learning new things and building creative projects. My goal is to combine tech and imagination to create something powerful.</p>

    <textarea placeholder="What do you want to build? Write your idea here..."></textarea>

    <div class="footer">⚡ Built by Aman ⚡</div>
  </div>
</body>
</html>
