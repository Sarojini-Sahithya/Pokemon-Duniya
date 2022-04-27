# Pokemon-Duniya
<!DOCTYPE>
<html>
<head>
<title>Pokemon Duniya</title>
<style>
img{width: 500px;
height: 250px;
margin-top: 100px;
}
body{font-family: arial;}
form {
        background-color: rgb(3,108,174);
        width: 300px;
        height: 44px;
        border-radius: 5px;
        display: flex;
        flex-direction: row;
        text-align: center;
        margin-left: 620px;
        margin-right: 620px;
        margin-top: 25px;
      }

      input {
        all: unset;
        font: 16px system-ui;
        color: #fff;
        height: 100%;
        width: 100%;
        padding: 6px 10px;
      }

      ::placeholder {
        color: #fff;
        opacity: 0.7; 
      }

      svg {
        color: #fff;
        fill: currentColor;
        width: 24px;
        height: 24px;
        padding: 10px;
      }

      .button1 {
        all: unset;
        cursor: pointer;
        width: 44px;
        height: 44px;
      }
.mainpage{text-align: center; 
background-image: url('Main.jpg');
background-repeat: no-repeat;
background-attachment: fixed;
background-size: 100% 100%;
backdrop-filter: blur(2px);
float: left;
padding-bottom: 200px;
margin: 0px;
}
.button2{margin-top: 50px;
padding: 10px;
border-radius: 5px;
background-color: white;
}
.mainpage2{
background-image: url('MainBlur.jpg');
background-repeat: no-repeat;
background-attachment: fixed;
background-size: 100% 100%;
float: left;
margin: 0px;
}
div.main1{margin: 10px;}
div.main2{margin: 30px; margin-top: 250px;}
div.gallery {
  margin: 20px;
  float: left;
  width: 180px;
  padding: 0px;
}

div.gallery img {
  width: 100%;
  height: auto;
}

div.desc {
  padding: 10px;
  text-align: center;
  background: white;
}
li{text-align: left; font-size: 20px; padding-right: 50px;}
h1{font-size: 40px; color: white;}
table{background: rgba(0,0,0,0.3); border: solid 1px white;}
h2{margin: 20px; padding: 20px; color: white; font-size: 40px;}
th{color: white;}
    </style>
  </head>
  <body>
<div class= "mainpage">
<img src= "pokemon.png">
    <form role="search" id="form">
      <input type="search" id="query" name="q" placeholder="Google Search..." aria-label="Search through site content">
      <button class="button1">
        <svg viewBox="0 0 1024 1024"><path class="path1" d="M848.471 928l-263.059-263.059c-48.941 36.706-110.118 55.059-177.412 55.059-171.294 0-312-140.706-312-312s140.706-312 312-312c171.294 0 312 140.706 312 312 0 67.294-24.471 128.471-55.059 177.412l263.059 263.059-79.529 79.529zM189.623 408.078c0 121.364 97.091 218.455 218.455 218.455s218.455-97.091 218.455-218.455c0-121.364-103.159-218.455-218.455-218.455-121.364 0-218.455 97.091-218.455 218.455z"></path></svg>
      </button>
    </form>
<p><button class="button2"><a href= "#allpoki" style= "text-decoration: none; color: black;">All Pokemons</button></p>
</div>
<div class= "mainpage2">
<div class="main1">
<h2><a id= "allpoki">List</a></h2>
<div class="gallery">
  <a target="_blank" href="Bulbasaur.jpg">
    <img src="Bulbasaur.jpg" alt="Bulbasaur" width="800" height="500">
  </a>
  <div class="desc"><a href= "#bulbasaur" style= "color: black;">Bulbasaur</a></div>
</div>

<div class="gallery">
  <a target="_blank" href="Ivysaur.jfif">
    <img src="Ivysaur.jfif" alt="Ivysaur" width="800" height="500">
  </a>
  <div class="desc"><a href= "#ivysaur" style= "color: black;">Ivysaur</a></div>
</div>

<div class="gallery">
  <a target="_blank" href="Venusaur.jfif">
    <img src="Venusaur.jfif" alt="Venusaur" width="800" height="500">
  </a>
  <div class="desc"><a href= "#venusaur" style= "color: black;">Venusaur</a></div>
</div>

<div class="gallery">
  <a target="_blank" href="Charmander.jpg">
    <img src="Charmander.jpg" alt="Charmander" width="800" height="500">
  </a>
  <div class="desc"><a href= "#charmander" style= "color: black;">Charmander</a></div>
</div>

<div class="gallery">
  <a target="_blank" href="Charmeleon.png">
    <img src="Charmeleon.png" alt="Charmeleon" width="800" height="500">
  </a>
  <div class="desc"><a href= "#charmeleon" style= "color: black;">Charmeleon</a></div>
</div>

<div class="gallery">
  <a target="_blank" href="Charizard.jpg">
    <img src="Charizard.jpg" alt="Charizard" width="800" height="500">
  </a>
  <div class="desc"><a href= "#charizard" style= "color: black;">Charizard</a></div>
</div>

<div class="gallery">
  <a target="_blank" href="Squirtle.jfif">
    <img src="Squirtle.jfif" alt="Squirtle" width="800" height="500">
  </a>
  <div class="desc"><a href= "#squirtle" style= "color: black;">Squirtle</a></div>
</div>

<div class="gallery">
  <a target="_blank" href="Wartortle.jpg">
    <img src="Wartortle.jpg" alt="Wartortle" width="800" height="500">
  </a>
  <div class="desc"><a href= "#wartortle" style= "color: black;">Wartortle</a></div>
</div>

<div class="gallery">
  <a target="_blank" href="Blastoise.jpg">
    <img src="Blastoise.jpg" alt="Blastoise" width="800" height="500">
  </a>
  <div class="desc"><a href= "#blastoise" style= "color: black;">Blastoise</a></div>
</div>

<div class="gallery">
  <a target="_blank" href="Caterpie.jfif">
    <img src="Caterpie.jfif" alt="Caterpie" width="800" height="500">
  </a>
  <div class="desc"><a href= "#caterpie" style= "color: black;">Caterpie</a></div>
</div>

<div class="gallery">
  <a target="_blank" href="Metapod.jpg">
    <img src="Metapod.jpg" alt="Metapod" width="800" height="500">
  </a>
  <div class="desc"><a href= "#metapod" style= "color: black;">Metapod</a></div>
</div>

<div class="gallery">
  <a target="_blank" href="Butterfree.jfif">
    <img src="Butterfree.jfif" alt="Butterfree" width="800" height="500">
  </a>
  <div class="desc"><a href= "#butterfree" style= "color: black;">Butterfree</a></div>
</div>

<div class="gallery">
  <a target="_blank" href="Weedle.jfif">
    <img src="Weedle.jfif" alt="Weedle" width="800" height="500">
  </a>
  <div class="desc"><a href= "#weedle" style= "color: black;">Weedle</a></div>
</div>

<div class="gallery">
  <a target="_blank" href="Kakuna.jfif">
    <img src="Kakuna.jfif" alt="Kakuna" width="800" height="500">
  </a>
  <div class="desc"><a href= "#kakuna" style= "none; color: black;">Kakuna</a></div>
</div>

<div class="gallery">
  <a target="_blank" href="Beedrill.jpg">
    <img src="Beedrill.jpg" alt="Beedrill" width="800" height="500">
  </a>
  <div class="desc"><a href= "#beedrill" style= "color: black;">Beedrill</a></div>
</div>

<div class="gallery">
  <a target="_blank" href="Rattata.jpg">
    <img src="Rattata.jpg" alt="Rattata" width="800" height="500">
  </a>
  <div class="desc"><a href= "#rattata" style= "color: black;">Rattata</a></div>
</div>

<div class="gallery">
  <a target="_blank" href="Raticate.jfif">
    <img src="Raticate.jfif" alt="Raticate" width="800" height="500">
  </a>
  <div class="desc"><a href= "#raticate" style= "color: black;">Raticate</a></div>
</div>

<div class="gallery">
  <a target="_blank" href="Pidgey.jfif">
    <img src="Pidgey.jfif" alt="Pidgey" width="800" height="500">
  </a>
  <div class="desc"><a href= "#pidgey" style= "color: black;">Pidgey</a></div>
</div>

<div class="gallery">
  <a target="_blank" href="Pidgeotto.png">
    <img src="Pidgeotto.png" alt="Pidgeotto" width="800" height="500">
  </a>
  <div class="desc"><a href= "#pidgeotto" style= "color: black;">Pidgeotto</a></div>
</div>

<div class="gallery">
  <a target="_blank" href="Pidgeot.jfif">
    <img src="Pidgeot.jfif" alt="Pidgeot" width="800" height="500">
  </a>
  <div class="desc"><a href= "#pidgeot" style= "color: black;">Pidgeot</a></div>
</div>

<div class="pokemon">
    <img src="Pokemon.png" alt="Pokemon" width="650" height="200">
</div>
</div>

<br>

<div class= "main2">
<h1><a id= "bulbasaur">Bulbasaur</a></h1>
<table <a>
<tr>
<th><img src="Bulbasaur.gif" width="800" height="600" style= "border: solid 5px white;" ></th>
<th><p><ul>
<li>Height: 71.1cm</li><br>
<li>Weight: 6.9kg</li><br>
<li>Evolves to: Ivysaur</li><br>
<li>Ability: Overgrow</li><br>
<li>Category: Seed</li><br>
<li>Type: Grass, Poison</li><br>
<li>Weakness: Psychic, Flying, Ice, Fire</li><br>
</ul></p></th>
</tr>
</table>

<br>
<h1><a id= "ivysaur">Ivysaur</a></h1>
<table>
<tr>
<th><p><ul>
<li>Height: 99.1cm</li><br>
<li>Weight: 13kg</li><br>
<li>Evolves to: Venusaur</li><br>
<li>Evolves from: Bulbasaur</li><br>
<li>Ability: Overgrow</li><br>
<li>Category: Seed</li><br>
<li>Type: Grass, Poison</li><br>
<li>Weakness: Psychic, Flying, Ice, Fire</li><br>
</ul></p></th>
<th><img src="Ivysaur.gif" width="600" height="400" style= "border: solid 5px white;"></th>
</tr>
</table>

<br>
<h1><a id= "venusaur">Venusaur</a></h1>
<table>
<tr>
<th><img src="Venusaur.gif" width="600" height="400" style= "border: solid 5px white;"></th>
<th><p><ul>
<li>Height: 2.01m</li><br>
<li>Weight: 100kg</li><br>
<li>Evolves from: Ivysaur</li><br>
<li>Ability: Overgrow</li><br>
<li>Category: Seed</li><br>
<li>Type: Grass, Poison</li><br>
<li>Weakness: Psychic, Flying, Ice, Fire</li><br>
</ul></p></th>
</tr>
</table>

<br>
<h1><a id= "charmander">Charmander</a></h1>
<table>
<tr>
<th><p><ul>
<li>Height: 61cm</li><br>
<li>Weight: 8.5kg</li><br>
<li>Evolves to: Charmeleon</li><br>
<li>Ability: Blaze</li><br>
<li>Category: Lizard</li><br>
<li>Type: Fire</li><br>
<li>Weakness: Water, Ground, Rock</li><br>
</ul></p></th>
<th><img src="Charmander.gif" width="600" height="400" style= "border: solid 5px white;"></th>
</tr>
</table>

<br>
<h1><a id= "charmeleon">Charmeleon</a></h1>
<table>
<tr>
<th><img src="Charmeleon.gif" width="600" height="400" style= "border: solid 5px white;"></th>
<th><p><ul>
<li>Height: 1.09m</li><br>
<li>Weight: 19kg</li><br>
<li>Evolves to: Charizard</li><br>
<li>Evolves from: Charmander</li><br>
<li>Ability: Blaze</li><br>
<li>Category: Lizard</li><br>
<li>Type: Fire</li><br>
<li>Weakness: Water, Ground</li><br>
</ul></p></th>
</tr>
</table>

<br>
<h1><a id= "charizard">Charizard</a></h1>
<table>
<tr>
<th><p><ul>
<li>Height: 1.7m</li><br>
<li>Weight: 90kg</li><br>
<li>Evolves from: Charmeleon</li><br>
<li>Ability: Blaze</li><br>
<li>Category: Lizard</li><br>
<li>Type: Fire, Flying</li><br>
<li>Weakness: Water, Rock, Electric</li><br>
</ul></p></th>
<th><img src="Charizard.gif" width="600" height="400" style= "border: solid 5px white;"></th>
</tr>
</table>

<br>
<h1><a id= "squirtle">Squirtle</a></h1>
<table>
<tr>
<th><img src="Squirtle.gif" width="600" height="400" style= "border: solid 5px white;"></th>
<th><p><ul>
<li>Height: 50.8cm</li><br>
<li>Weight: 9kg</li><br>
<li>Evolves to: Wartortle</li><br>
<li>Ability: Torrent</li><br>
<li>Origin: Kanto</li><br>
<li>Type: Water</li><br>
<li>Weakness: Grass, Electric</li><br>
</ul></p></th>
</tr>
</table>

<br>
<h1><a id="wartortle">Wartortle</a></h1>
<table>
<tr>
<th><p><ul>
<li>Height: 99.1cm</li><br>
<li>Weight: 22kg</li><br>
<li>Evolves to: Blastoise</li><br>
<li>Evolves from: Squirtle</li><br>
<li>Ability: Torrent</li><br>
<li>Type: Water</li><br>
<li>Weakness: Grass, Electric</li><br>
</ul></p></th>
<th><img src="Wartortle.gif" width="600" height="400" style= "border: solid 5px white;"></th>
</tr>
</table>

<br>
<h1><a id= "blastoise">Blastoise</a></h1>
<table>
<tr>
<th><img src="Blastoise.gif" width="600" height="400" style= "border: solid 5px white;"></th>
<th><p><ul>
<li>Height: 1.6m</li><br>
<li>Weight: 86kg</li><br>
<li>Evolves from: Wartortle</li><br>
<li>Ability: Torrent</li><br>
<li>Type: Water</li><br>
<li>Category: Shellfish</li><br>
<li>Weakness: Grass, Electric</li><br>
</ul></p></th>
</tr>
</table>

<br>
<h1><a id= "caterpie">Caterpie</a></h1>
<table>
<tr>
<th><p><ul>
<li>Height: 30.5cm</li><br>
<li>Weight: 2.9kg</li><br>
<li>Evolves to: Metapod</li><br>
<li>Type: Bug</li><br>
<li>Weakness: Flying, Fire, Rock</li><br>
</ul></p></th>
<th><img src="Caterpie.gif" width="600" height="400" style= "border: solid 5px white;"></th>
</tr>
</table>

<br>
<h1><a id= "metapod">Metapod</a></h1>
<table>
<tr>
<th><img src="Metapod.gif" width="600" height="400" style= "border: solid 5px white;"></th>
<th><p><ul>
<li>Height: 71.1cm</li><br>
<li>Weight: 9.9kg</li><br>
<li>Evolves to: Butterfree</li><br>
<li>Evolves from: Caterpie</li><br>
<li>Type: Bug</li><br>
<li>Ability: Shed Skin</li><br>
<li>Weakness: Flying, Fire, Rock</li><br>
</ul></p></th>
</tr>
</table>

<br>
<h1><a id="butterfree">Butterfree</a></h1>
<table>
<tr>
<th><p><ul>
<li>Height: 1.1m</li><br>
<li>Weight: 32kg</li><br>
<li>Evolves from: Metapod</li><br>
<li>Type: Bug, Flying</li><br>
<li>Ability: Compound Eyes</li><br>
<li>Weakness: Flying, Fire, Electric, Ice</li><br>
</ul></p></th>
<th><img src="Butterfree.gif" width="600" height="400" style= "border: solid 5px white;"></th>
</tr>
</table>

<br>
<h1><a id= "weedle">Weedle</a></h1>
<table>
<tr>
<th><img src="Weedle.gif" width="600" height="400" style= "border: solid 5px white;"></th>
<th><p><ul>
<li>Height: 30.5cm</li><br>
<li>Weight: 3.2kg</li><br>
<li>Evolves to: Kakuna</li><br>
<li>Type: Bug, Poison</li><br>
<li>Ability: Shield Dust</li><br>
<li>Weakness: Flying, Fire, Rock, Psychic</li><br>
</ul></p></th>
</tr>
</table>

<br>
<h1><a id= "kakuna">Kakuna</a></h1>
<table>
<tr>
<th><p><ul>
<li>Height: 61cm</li><br>
<li>Weight: 10kg</li><br>
<li>Evolves to: Beedrill</li><br>
<li>Evolves from: Weedle</li><br>
<li>Type: Bug, Poison</li><br>
<li>Ability: Shed Skin</li><br>
<li>Weakness: Flying, Fire, Psychic</li><br>
</ul></p></th>
<th><img src="Kakuna.gif" width="600" height="400" style= "border: solid 5px white;"></th>
</tr>
</table>

<br>
<h1><a id= "beedrill">Beedrill</a></h1>
<table>
<tr>
<th><img src="Beedrill.gif" width="600" height="400" style= "border: solid 5px white;"></th>
<th><p><ul>
<li>Height: 99.1cm</li><br>
<li>Weight: 29kg</li><br>
<li>Evolves from: Kakuna</li><br>
<li>Type: Bug, Poison</li><br>
<li>Ability: Swam</li><br>
<li>Weakness: Flying, Fire, Psychic, Rock</li><br>
</ul></p></th>
</tr>
</table>

<br>
<h1><a id= "rattata">Rattata</a></h1>
<table>
<tr>
<th><p><ul>
<li>Height: 30.5cm</li><br>
<li>Weight: 3.5kg</li><br>
<li>Evolves to: Raticate</li><br>
<li>Type: Normal</li><br>
<li>Ability: Run Away, Guts</li><br>
<li>Weakness: Fighting</li><br>
</ul></p></th>
<th><img src="Rattata.gif" width="600" height="400" style= "border: solid 5px white;"></th>
</tr>
</table>

<br>
<h1><a id= "raticate">Raticate</a></h1>
<table>
<tr>
<th><img src="Raticate.gif" width="600" height="400" style= "border: solid 5px white;"></th>
<th><p><ul>
<li>Height: 71.1cm</li><br>
<li>Weight: 19kg</li><br>
<li>Evolves from: Rattata</li><br>
<li>Type: Normal</li><br>
<li>Ability: Run Away, Guts</li><br>
<li>Weakness: Fighting</li><br>
</ul></p></th>
</tr>
</table>

<br>
<h1><a id= "pidgey">Pidgey</a></h1>
<table>
<tr>
<th><p><ul>
<li>Height: 30.5cm</li><br>
<li>Weight: 1.8kg</li><br>
<li>Evolves to: Pidgeotto</li><br>
<li>Type: Flying, Normal</li><br>
<li>Ability: Tangled Feet, Keen Eye</li><br>
<li>Weakness: Ice, Electric, Rock</li><br>
</ul></p></th>
<th><img src="Pidgey.gif" width="600" height="400" style= "border: solid 5px white;"></th>
</tr>
</table>

<br>
<h1><a id= "pidgeotto">Pidgeotto</a></h1>
<table>
<tr>
<th><img src="Pidgeotto.gif" width="600" height="400" style= "border: solid 5px white;"></th>
<th><p><ul>
<li>Height: 1.09m</li><br>
<li>Weight: 30kg</li><br>
<li>Evolves to: Pidgeot</li><br>
<li>Evolves from: Pidgey</li><br>
<li>Type: Flying, Normal</li><br>
<li>Weakness: Ice, Electric, Rock</li><br>
</ul></p></th>
</tr>
</table>

<br>
<h1><a id= "pidgeot">Pidgeot</a></h1>
<table>
<tr>
<th><p><ul>
<li>Height: 1.5m</li><br>
<li>Weight: 40kg</li><br>
<li>Evolves from: Pidgeotto</li><br>
<li>Type: Flying, Normal</li><br>
<li>Weakness: Ice, Electric, Rock</li><br>
</ul></p></th>
<th><img src="Pidgeot.gif" width="600" height="400" style= "border: solid 5px white;"></th>
</tr>
</table>											/
</div>
</div>
    <script>
      const f = document.getElementById('form');
      const q = document.getElementById('query');
      const google = 'https://www.google.com/search?q=site%3A+';
      const site = 'All Pokemons.html';

      function submitted(event) {
        event.preventDefault();
        const url = google + site + '+' + q.value;
        const win = window.open(url, '_blank');
        win.focus();
      }

      f.addEventListener('submit', submitted);
    </script>
</body>
</html>
