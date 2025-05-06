<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pratik's Portfolio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }
    body {
      background: #f0f0f0;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 50px;
      background: #333;
      color: #fff;
    }
    header .logo {
      font-size: 24px;
      font-weight: bold;
    }
    nav a {
      margin-left: 30px;
      text-decoration: none;
      color: #fff;
      transition: 0.3s;
    }
    nav a:hover {
      color: #00adb5;
      text-decoration: underline;
    }
    .hero {
      display: flex;
      height: 90vh;
      align-items: center;
      justify-content: space-between;
      padding: 0 50px;
    }
    .hero .left {
      flex: 1;
    }
    .hero .right {
      flex: 1;
      display: flex;
      justify-content: center;
    }
    .hero .left h1 {
      font-size: 36px;
      margin-bottom: 20px;
    }
    .hero .left h1 span {
      color: #ff5722;
    }
    .hero .left .typing {
      font-size: 20px;
      color: #555;
    }
    .hero .right img {
      width: 80%;
      max-width: 400px;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">Pratik's Portfolio</div>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#services">My Services</a>
      <a href="#contact">Contact Me</a>
    </nav>
  </header>  <section class="hero" id="home">
    <div class="left">
      <h1>Hi my name is <span>Pratik</span> and I am a</h1>
      <div class="typing">
        <span id="typed"></span>
      </div>
    </div>
    <div class="right">
      <img src="https://cdn-icons-png.flaticon.com/512/1055/1055687.png" alt="Web Developer">
    </div>
  </section>  <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>  <script>
    const typed = new Typed('#typed', {
      strings: ["passionate web developer", "graphic designer", "video editor", "freelancer"],
      typeSpeed: 60,
      backSpeed: 40,
      loop: true
    });
  </script></body>
</html>
