<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>IPL Website - Ankur Goswami</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:Arial, sans-serif;
    }

    body{
      background:#0f172a;
      color:white;
    }

    header{
      background:linear-gradient(90deg,#ff6b00,#ff0000);
      padding:20px;
      text-align:center;
    }

    header h1{
      font-size:40px;
    }

    nav{
      display:flex;
      justify-content:center;
      gap:20px;
      background:#111827;
      padding:15px;
    }

    nav a{
      color:white;
      text-decoration:none;
      font-weight:bold;
    }

    .hero{
      height:400px;
      background:url('https://images.unsplash.com/photo-1540747913346-19e32dc3e97e?q=80&w=1200&auto=format&fit=crop') center/cover;
      display:flex;
      align-items:center;
      justify-content:center;
      text-align:center;
    }

    .hero h2{
      font-size:50px;
      background:rgba(0,0,0,0.6);
      padding:20px;
      border-radius:10px;
    }

    .teams{
      padding:40px;
      text-align:center;
    }

    .teams h2{
      margin-bottom:30px;
      font-size:35px;
    }

    .team-container{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
      gap:20px;
    }

    .team-card{
      background:#1e293b;
      padding:20px;
      border-radius:15px;
      transition:0.3s;
    }

    .team-card:hover{
      transform:scale(1.05);
      background:#334155;
    }

    .team-card img{
      width:100%;
      border-radius:10px;
      height:180px;
      object-fit:cover;
    }

    footer{
      background:#111827;
      text-align:center;
      padding:20px;
      margin-top:40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>IPL 2026</h1>
    <p>Created by Ankur Goswami</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">Teams</a>
    <a href="#">Matches</a>
    <a href="#">Points Table</a>
    <a href="#">Contact</a>
  </nav>

  <section class="hero">
    <h2>Welcome to IPL Fan Website</h2>
  </section>

  <section class="teams">
    <h2>Popular Teams</h2>

    <div class="team-container">

      <div class="team-card">
        <img src="https://wallpaperaccess.com/full/1631874.jpg">
        <h3>Chennai Super Kings</h3>
      </div>

      <div class="team-card">
        <img src="https://wallpapercave.com/wp/wp4056410.jpg">
        <h3>Mumbai Indians</h3>
      </div>

      <div class="team-card">
        <img src="https://wallpapercave.com/wp/wp7418453.jpg">
        <h3>Royal Challengers Bangalore</h3>
      </div>

      <div class="team-card">
        <img src="https://wallpapercave.com/wp/wp7009968.jpg">
        <h3>Kolkata Knight Riders</h3>
      </div>

    </div>
  </section>

  <footer>
    <p>© 2026 IPL Website | Made by Ankur Goswami</p>
  </footer>

</body>
</html>
