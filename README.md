<!DOCTYPE html>
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
    <a href="#">Labaran Wasanni</a>
    <a href="#">Kai Tsaye(live)</a>
    <a href="#">Fixtures</a>
  </div>

  <main style="padding:20px;">
    <h1>Tottenham na son Savinho, Ƙungiyoyi na rububin Rodrygo</h1>
<img src="https://ichef.bbci.co.uk/ace/ws/800/cpsprodpb/139d/live/fbed6fd0-813f-11f0-b7e1-f39ec0dca198.jpg.webp"></img>
    <p>Ɗan wasa Savinho daga Manchester City ya kasance wanda Tottenham ke so ido rufe, yayinda kocinsu Thomas Frank ya dage don ganin lallai ya saye matashin mai shekara 21 daga Brazil, musamman ganin sun yi rashin nasarar daidaitawa kan Eberechi Eze mai shekara 27, da ya je Arsenal. (Independent)</p>

<p> ta gabatar da tayi kan ɗan wasan Manchester City, kuma ta ce za ta biya fam miliyan 60.7 don ganin ta mallake Savinho, wanda ke burin komawa Landan. (Talksport)</p>
<p>A kokarin ganin ta ɗauko sabbin 'yanwasa biyu, Tottenham ta amince da yarjejeniyar fam miliyan 43 kan ɗan wasan Como da Argentina, Nico Paz mai shekara 20, amma ƙungiyarsa ta Italiya na neman fam miiyan 60.(Sky Sports Italia - in Italian)</p>
<p>Manchester City da Arsenal da Liverpool na son ɗan wasan Real Madrid da Brazil, Rodrygo mai shekara 24, amma ƙungiyarsa ta Sifaniya ba ta karɓi tayi daga kowa ba tukkunan. (Marca - in Spanish)</p>
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
