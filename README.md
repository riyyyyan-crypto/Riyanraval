<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Riyan Raval | Cyber World</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:Arial, sans-serif;
    }

    body{
      background:black;
      color:white;
      overflow-x:hidden;
    }

    header{
      height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;
      text-align:center;
      background:
      linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.9)),
      url('https://images.unsplash.com/photo-1518770660439-4636190af475');
      background-size:cover;
      background-position:center;
    }

    .hero{
      max-width:800px;
      padding:20px;
      animation:fadeIn 2s ease;
    }

    .hero h1{
      font-size:70px;
      color:#00ff99;
      text-shadow:0 0 20px #00ff99;
    }

    .hero p{
      margin-top:20px;
      font-size:22px;
      color:#ddd;
      line-height:1.6;
    }

    .btn{
      display:inline-block;
      margin-top:35px;
      padding:15px 35px;
      background:#00ff99;
      color:black;
      text-decoration:none;
      border-radius:40px;
      font-weight:bold;
      transition:0.4s;
      box-shadow:0 0 20px #00ff99;
    }

    .btn:hover{
      transform:scale(1.1);
      background:white;
      box-shadow:0 0 30px white;
    }

    section{
      padding:100px 10%;
    }

    .about{
      display:flex;
      flex-wrap:wrap;
      gap:40px;
      align-items:center;
      justify-content:center;
    }

    .about-text{
      flex:1;
      min-width:300px;
    }

    .about-text h2{
      font-size:45px;
      margin-bottom:20px;
      color:#00ff99;
    }

    .about-text p{
      color:#bbb;
      line-height:1.8;
      font-size:18px;
    }

    .card{
      flex:1;
      min-width:280px;
      background:#111;
      padding:40px;
      border-radius:20px;
      border:1px solid #00ff99;
      box-shadow:0 0 20px rgba(0,255,153,0.3);
    }

    .card h3{
      margin-bottom:20px;
      color:#00ff99;
      font-size:28px;
    }

    .skills{
      text-align:center;
      background:#050505;
    }

    .skills h2{
      font-size:50px;
      margin-bottom:50px;
      color:#00ff99;
    }

    .skill-boxes{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
      gap:25px;
    }

    .box{
      background:#111;
      padding:35px;
      border-radius:20px;
      transition:0.4s;
      border:1px solid #222;
    }

    .box:hover{
      transform:translateY(-10px);
      border-color:#00ff99;
      box-shadow:0 0 25px rgba(0,255,153,0.5);
    }

    .box h3{
      color:white;
      font-size:24px;
    }

    footer{
      text-align:center;
      padding:30px;
      background:#000;
      color:#777;
      border-top:1px solid #111;
    }

    @keyframes fadeIn{
      from{
        opacity:0;
        transform:translateY(30px);
      }
      to{
        opacity:1;
        transform:translateY(0);
      }
    }

    @media(max-width:768px){
      .hero h1{
        font-size:45px;
      }

      .hero p{
        font-size:18px;
      }

      .about{
        flex-direction:column;
      }
    }

  </style>
</head>
<body>

  <header>
    <div class="hero">
      <h1>Riyan Raval</h1>

      <p>
        12th Science Student • Future Cyber Security Explorer <br>
        Exploring the digital universe and building a future in cyber security.
      </p>

      <a href="#" class="btn">Explore More</a>
    </div>
  </header>

  <section class="about">

    <div class="about-text">
      <h2>About Me</h2>

      <p>
        Hello! I'm Riyan Raval, passionate about cyber security,
        ethical hacking, and technology. I love exploring how systems work,
        protecting digital platforms, and learning future technologies.
      </p>
    </div>

    <div class="card">
      <h3>My Mission</h3>

      <p>
        Learn • Explore • Protect <br><br>
        My dream is to enter the cyber world and create a strong future in technology.
      </p>
    </div>

  </section>

  <section class="skills">

    <h2>My Interests</h2>

    <div class="skill-boxes">

      <div class="box">
        <h3>Cyber Security</h3>
      </div>

      <div class="box">
        <h3>Ethical Hacking</h3>
      </div>

      <div class="box">
        <h3>Networking</h3>
      </div>

      <div class="box">
        <h3>Future Tech</h3>
      </div>

    </div>

  </section>

  <footer>
    © 2026 Riyan Raval | Cyber World
  </footer>

</body>
</html>
