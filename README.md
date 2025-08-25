<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Golden-e-sport</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }
    header {
      background: #000;
      color: #FFD700;
      padding: 15px;
      display: flex;
      align-items: center;
    }
    .menu-icon {
      font-size: 24px;
      cursor: pointer;
      margin-right: 15px;
    }
    .sidebar {
      height: 100%;
      width: 0;
      position: fixed;
      top: 0;
      left: 0;
      background-color: #111;
      overflow-x: hidden;
      transition: 0.3s;
      padding-top: 60px;
    }
    .sidebar a {
      padding: 10px 20px;
      text-decoration: none;
      font-size: 18px;
      color: #FFD700;
      display: block;
      transition: 0.2s;
    }
    .sidebar a:hover {
      background: #FFD700;
      color: #000;
    }
    .closebtn {
      position: absolute;
      top: 10px;
      right: 20px;
      font-size: 28px;
      cursor: pointer;
      color: #FFD700;
    }
  </style>
</head>
<body>
  <header>
    <span class="menu-icon" onclick="openNav()">☰</span>
    <h2>Golden E-sport</h2>
  </header>

  <div id="mySidebar" class="sidebar">
    <span class="closebtn" onclick="closeNav()">×</span>
    <a href="#labarai">Labaran Wasanni</a>
    <a href="#">Kai Tsaye (Live)</a>
    <a href="#">Fixtures</a>
  </div>

  <main style="padding:20px;">
    <h1>Tottenham na son Savinho, Ƙungiyoyi na rububin Rodrygo</h1>
    <img src="https://ichef.bbci.co.uk/ace/ws/800/cpsprodpb/139d/live/fbed6fd0-813f-11f0-b7e1-f39ec0dca198.jpg.webp" alt="Tottenham News" style="max-width:100%;height:auto;">
    <p>Ɗan wasa Savinho daga Manchester City ya kasance wanda Tottenham ke so ido rufe, yayinda kocinsu Thomas Frank ya dage don ganin lallai ya saye matashin mai shekara 21 daga Brazil...</p>

    <!-- SABON SASHE NA LABARAN WASANNI -->
    <section id="labarai">
      <h2>Labaran Wasanni</h2>
      <iframe src="https://https://labarangolden.blogspot.com/" width="100%" height="600" style="border:none;"></iframe>
    </section>
  </main>

  <script>
    function openNav() {
      document.getElementById("mySidebar").style.width = "250px";
    }
    function closeNav() {
      document.getElementById("mySidebar").style.width = "0";
    }
  </script>
</body>
</html>
