<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="mw.png" type="image/png">
    <title>Best manga to read</title>
    <style>
      body {
    zoom: 100%;
}
    img{
        width: 600px;
        height: 300px;
       display: block;
        margin: 0 auto;
    }
    h3,div{
        font-family:Arial, Helvetica, sans-serif ;
        color: white;
    }
    h2{
        font-size: 40px;
    }
    h2,h1{
        color: white;
        text-align: center;

    }
    body{
        background-color: rgb(0, 0, 0)
    }
    img:hover {
  transform: scale(1.2);
  transition: 0.3s ease;
}
img {
  filter: grayscale(100%);
  transition: 0.5s;
}
img:hover {
  filter: grayscale(0%);
}

.fancy-quote {
  font-style: italic;
  font-size: 1.5em;
  border-left: 5px solid #aaa;
  padding-left: 15px;
  color: #444;
}
.fade-in {
  opacity: 0;
  animation: fadeIn 4s forwards;
}
@keyframes fadeIn {
  to { opacity: 1; }
}


.typing {
  font-family: 'Courier New', monospace;
  display: inline-block;
  width: 0;
  overflow: hidden;
  white-space: nowrap;
  border-right: 3px solid;
  animation: typing 3s steps(30) 1s forwards;
}

@keyframes typing {
  to {
    width: 100%;
  }
}

nav {
  position: sticky;
  top: 0;
  background-color: black;
  color: white;
  padding: 10px 0;
  text-align: center;
  z-index: 10; 
}


nav a {
  margin: 0 20px;
  color: white;
  text-decoration: none;
}


section {
  padding: 60px;
  margin: 20px 0;
  background-color: #333;
  color: white;
}


section h2 {
  font-size: 36px;
  color: #ff9900;
}


section:nth-child(even) {
  background-color: #444;
}

section:nth-child(odd) {
  background-color: #555;
}


body {
  background: black url('stars.png') repeat;
  animation: starScroll 60s linear infinite;
}
@keyframes starScroll {
  from { background-position: 0 0; }
  to { background-position: 1000px 1000px; }
}
img {
  border: 5px solid white;
  box-shadow: 0 0 0 5px black;
}

    </style>

</head>
<body>
  
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    nav {
      background-color: #222;
      padding: 10px 20px;
    }

    
    .menu-toggle {
      width: 30px;
      cursor: pointer;
      display: inline-block;
    }

    .menu-toggle div {
      background-color: white;
      height: 4px;
      margin: 5px 0;
    }

   
    .menu {
      display: none;
      flex-direction:row; 
      background-color: #333;
      justify-content: flex-start;
      flex-wrap: wrap;
      margin-top: 10px;
    }

    .menu a {
      color: white;
      text-decoration: none;
      padding: 15px 20px;
      border-left: 1px solid #444;
    }

    .menu a:first-child {
      border-left: none;
    }

    .menu a:hover {
      background-color: #444;
    }

    
    .menu.active {
      display: flex;
    }
  </style>
</head>
<body>



  
 <nav style="display: flex; flex-direction: column; align-items: flex-start;">
  <div class="menu-toggle" onclick="toggleMenu()">
    <div></div>
    <div></div>
    <div></div>
   
  </div>
  <div class="menu" id="menu">
    <a href="">Home page</a> 
    <a href="">New manga</a>
    <a href="">Manga news</a>
    <a href="">Anime</a>
    <a href="">Threads</a>
    <a href="">More</a>
  </div>
</nav>
  


  <script>
    function toggleMenu() {
      document.getElementById("menu").classList.toggle("active");
    }
  </script>



    <h1 class="typing">Best manga to read in 2025</h1>


    
    <nav>
        <a href="#Gto" style="color: red;">Greate Teacher Onizuka</a>
        <a href="#Parasyte" style="color: red;">Parasyte</a>
        <a href="#initialD" style="color: red;">Initial D</a>
        <a href="#Hunter" style="color: red;">Hunter × Hunter</a>
        <a href="#jojo" style="color: red;">JoJo's Bizarre Adventure</a>
        <a href="#one-piece" style="color: red;">One Piece</a>
        <a href="#berserk" style="color: red;"> Berserk</a>
        <a href="#monster" style="color: red;">Monster </a>
        <a href="#vagabond" style="color: red;">Vagabond</a>
        <a href="#slam dunk" style="color: red;">Slam Dunk</a>
        <a href="#climber" style="color: red;"> The Climber</a>
        <a href="#vinlandsaga" style="color: red;">Vinland Saga</a>

      </nav>
      
      <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Manga Shelf – Dark Mode</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #121212;
      color: #f5f5f5;
      padding: 2rem;
    }

    h1 {
      margin-bottom: 1rem;
    }

    #addSection {
      margin-bottom: 2rem;
    }

    input[type="text"] {
      padding: 0.5rem;
      width: 250px;
      border: 1px solid #555;
      border-radius: 5px;
      background: #1e1e1e;
      color: #fff;
    }

    button {
      margin: 0.2rem;
      padding: 0.5rem 0.8rem;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    .add-btn {
      background-color: red;
      color: #000;
    }

    .manga {
      background: #1e1e1e;
      padding: 1rem;
      border-left: 6px solid #777;
      margin-bottom: 1rem;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(255, 255, 255, 0.05);
    }

    .status-read { border-left-color: #00e676; }
    .status-want { border-left-color: #ffd600; }
    .status-dropped { border-left-color: #ff5252; }

    .status-label {
      font-weight: bold;
      margin-top: 0.5rem;
      display: block;
    }

    .control-buttons button {
      font-size: 0.9rem;
      background-color: #333;
      color: #f5f5f5;
      border: 1px solid #555;
    }

    .control-buttons button:hover {
      background-color: #444;
    }
  </style>
</head>
<body>

  <h1 style="text-align: left;"> My Manga Shelf</h1>

  <div id="addSection">
    <input type="text" id="mangaTitle" placeholder="Enter manga title" />
    <button class="add-btn" onclick="addManga()">Add</button>
  </div>

  <div id="shelf">
    <!-- Manga entries will appear here -->
  </div>

  <script>
    function addManga() {
      const title = document.getElementById('mangaTitle').value.trim();
      if (!title) return;

      const div = document.createElement('div');
      div.className = 'manga';

      const titleElem = document.createElement('div');
      titleElem.textContent = title;
      titleElem.style.fontSize = '1.1rem';
      titleElem.style.fontWeight = 'bold';

      const statusLabel = document.createElement('span');
      statusLabel.className = 'status-label';
      statusLabel.textContent = 'Status: none';

      const controls = document.createElement('div');
      controls.className = 'control-buttons';

      const readBtn = createStatusButton('✅ Read', 'read', div, statusLabel);
      const wantBtn = createStatusButton('📖 Want to read', 'want', div, statusLabel);
      const dropBtn = createStatusButton('🚫 Dropped', 'dropped', div, statusLabel);

      controls.appendChild(readBtn);
      controls.appendChild(wantBtn);
      controls.appendChild(dropBtn);

      div.appendChild(titleElem);
      div.appendChild(statusLabel);
      div.appendChild(controls);

      document.getElementById('shelf').appendChild(div);
      document.getElementById('mangaTitle').value = '';
    }

    function createStatusButton(text, status, container, label) {
      const btn = document.createElement('button');
      btn.textContent = text;
      btn.onclick = () => {
        container.classList.remove('status-read', 'status-want', 'status-dropped');
        container.classList.add(`status-${status}`);
        label.textContent = 'Status: ' + statusText(status);
      };
      return btn;
    }

    function statusText(code) {
      switch (code) {
        case 'read': return 'Read';
        case 'want': return 'Want to read';
        case 'dropped': return 'Dropped';
        default: return 'None';
      }
    }
  </script>

</body>
</html>

<h2 class="fade-in" style="color: white;" id="Gto">12.Great Teacher Onizuka</h2>
    <h2 style="color: gray; text-align: center; ">Status: Complete</h2><br>
    <img src="ced8240c27f6fad7bff9bc478a50e085.jpg"><br>
    <blockquote class="fancy-quote">"Class 2-C, idiot."</blockquote>
    <h3>Great Teacher Onizuka, officially abbreviated as GTO, is a Japanese manga series written and illustrated by Tooru Fujisawa. It was originally serialized in Kodansha's shōnen manga magazine Weekly Shōnen Magazine from January 1997 to February 2002, with its chapters collected in 25 tankōbon volumes. The story focuses on 22-year-old ex-bōsōzoku member Eikichi Onizuka, who becomes a teacher at a private middle school, Holy Forest Academy, in Tokyo, Japan. It is a standalone sequel to Fujisawa's earlier manga series Shonan Junai Gumi and Bad Company, both of which focus on the life of Onizuka before becoming a teacher. </h3>
    
    <hr style="width: 100%; border: 1px solid rgb(255, 255, 255);">


    <style>
      .container {
        display: flex;
        align-items: center;
      }
      .container img {
        width: 200px; 
        margin-right: 40px;
        
      }
      .text {
        max-width: 600px;
       
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="sekcja-ciekawostka-obrazek">
        <div class="tekst-ciekawostki">
          <h3> Did you know that...</h3>
          <p>Eikichi Onizuka, the main character of GTO, is actually based on a real stereotype in Japanese culture — the "Yankī" (ヤンキー), or delinquent youth. His look, attitude, and background as a former biker gang member reflect this rebellious archetype. <br>

But what’s fascinating is that despite being rough, loud, and unorthodox, Onizuka ends up becoming one of the most caring, clever, and impactful teachers his students have ever had — flipping the stereotype on its head!</p>
        </div>
        <img src="GTO_volume_1.jpg" alt="JoJo Bizarre Adventure" class="obrazek-ciekawostka">
      </div>
 <style>
 .sekcja-ciekawostka-obrazek {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 30px;
  padding: 30px;
  background-color: #1c1c1c;
  color: white;
  border-radius: 16px;
  max-width: 600px;
  margin: 40px auto;
  flex-wrap: wrap;
}

.tekst-ciekawostki {
  flex: 1;
  min-width: 300px;
}

.tekst-ciekawostki h3 {
  margin-bottom: 10px;
  color: #ff3366;
}

.tekst-ciekawostki p {
  font-size: 1.1em;
  line-height: 1.6;
}

.obrazek-ciekawostka {
  flex: 1;
  max-width: 400px;
  border-radius: 12px;
  width: 100%;
  height: auto;
}

 </style>      
      <div class="text" style="padding-left: 20px; max-width: 600px; text-align:left;">
        <h2 style="color: red;margin-right: 200px">Great Teacher Onizuka</h2>
        <h3>Autor: Tōru Fujisawa   </h3>
        <h3>Genre: Comedy,School Life,Drama</h3>
        <h3>Published by:   Kodansha</h3>
        <h3 style="margin-right: 200px; " >Release Date: May 16, 1997</h3>
    


      <a href="https://xbato.com/title/19054/364450" target="_blank">
        <button style="background-color: #252323; color: white; padding:  15px 75px; border-radius: 5px; margin-top: 10px;">
          Start reading
        </button>
      </a>
      </div>
    </div>
  
<h2>A few words about the author:</h2>
     <style>
    .on {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1200px;
      margin: 0 auto;
    }

    .textor {
      flex: 1;
      padding: 20px;
      font-size: 25px;
    }

    .imagete {
      flex: 1;
      padding: 20px;
      text-align: left; 
    }

  </style>
</head>
<body>

  <div class="on">
    <div class="textor">
      <h2 style="color: red;">Tōru Fujisawa </h2>
     <p>Tōru Fujisawa is a Japanese manga artist, born in 1967 in Hokkaido. He’s best known for creating Great Teacher Onizuka (GTO), a hit series about a former gangster who becomes an unorthodox but inspiring teacher. <br><br>

Before GTO, he wrote Shōnan Junai Gumi, which tells the story of Onizuka’s youth. His manga often mix comedy, drama, and social themes, focusing on rebellious characters and school life. <br><br>

He also created series like Tokko and GTO: Paradise Lost (a sequel to GTO).

</p>

    </div>
    <div class="imagete">
      <img src="ZF_gz1ZikqXwykdQGZrfkJc9Lw5wzvCR777Ln8NIPu2KsKJjQAJYctXnFrzAR3OX7P48AtoyyT453NrXpSjJbQ.webp" style="height:300px ;width: 210px; margin: 0;">
    </div>
  </div>
   <h2>Anime Adaptation:</h2>
<style>
    .cont {
      display: flex;
      align-items: center;
      max-width: 1100px;
      margin: 20px auto;
      gap: 20px;
    }
    .textop {
      flex: 1;
      font-family: Arial, sans-serif;
      line-height: 1.5;
    }
    .imagekol {
      flex: 1;
      text-align: right;
    }
    .image img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
  </style>
</head>
<body>

  <div class="cont">
    <div class="textop">
      <h2 style="font-size: 30px;">GTO Anime adaptation</h2>
      <p style="font-size: 20px;">
       The Great Teacher Onizuka anime, based on the manga by Tōru Fujisawa, aired from 1999 to 2000 and has 43 episodes. Produced by Studio Pierrot, it follows Eikichi Onizuka, a 22-year-old ex-gang member who becomes a high school teacher. Although rude and immature, Onizuka is deeply committed to helping his troubled students in unconventional but effective ways. <br><br>

The anime blends comedy, drama, and real-life issues, making it both entertaining and emotional. While it stays close to the manga's spirit, some arcs were changed or omitted. Interestingly, a live-action version of GTO aired in 1998, even before the anime. GTO remains a classic among school-life and coming-of-age anime series.
      </p>
    </div>
    <div class="imagekol">
      <img style="width:270px ; height:400px ;" src="Great_Teacher_Onizuka.webp" />
    </div>
  </div>
  </div>
 
   <h2 class="fade-in" style="color: white;" id="Parasyte">11.Parasyte</h2>
    <h2 style="color: gray; text-align: center; ">Status: Complete</h2><br>
    <img src="Featured-image-6.avif"><br>
    <blockquote class="fancy-quote">"Humans are the only animals that don't sleep when tired and eat when not hungry"</blockquote>
    <h3>Parasyte is a Japanese science fiction horror manga series written and illustrated by Hitoshi Iwaaki. It was published in Kodansha's Morning Open Zōkan (1989) and Monthly Afternoon (1989 to 1994).The manga was published in North America first by Tokyopop, then Del Rey, and finally Kodansha USA. The series follows Shinichi Izumi, a high school senior who is the victim of a failed attempt by a parasitic organism to take over his brain.  </h3>
    
    <hr style="width: 100%; border: 1px solid rgb(255, 255, 255);">


    <style>
      .container {
        display: flex;
        align-items: center;
      }
      .container img {
        width: 200px; 
        margin-right: 40px;
        
      }
      .text {
        max-width: 600px;
       
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="sekcja-ciekawostka-obrazek">
        <div class="tekst-ciekawostki">
          <h3> Did you know that...</h3>
          <p>In Parasyte, the main character Shinichi originally loses his right hand to the alien parasite Migi—but in the original manga, the story was created in the late 1980s, long before body-horror themes became more mainstream in anime. Despite its age, Parasyte inspired many modern sci-fi horror series and even got a live-action film adaptation and a 2014 anime reboot, nearly 25 years after the manga ended!</p>
        </div>
        <img src="Parasyte_4.png" alt="JoJo Bizarre Adventure" class="obrazek-ciekawostka">
      </div>
 <style>
 .sekcja-ciekawostka-obrazek {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 30px;
  padding: 30px;
  background-color: #1c1c1c;
  color: white;
  border-radius: 16px;
  max-width: 600px;
  margin: 40px auto;
  flex-wrap: wrap;
}

.tekst-ciekawostki {
  flex: 1;
  min-width: 300px;
}

.tekst-ciekawostki h3 {
  margin-bottom: 10px;
  color: #ff3366;
}

.tekst-ciekawostki p {
  font-size: 1.1em;
  line-height: 1.6;
}

.obrazek-ciekawostka {
  flex: 1;
  max-width: 400px;
  border-radius: 12px;
  width: 100%;
  height: auto;
}

 </style>      
      <div class="text" style="padding-left: 20px; max-width: 600px; text-align:left;">
        <h2 style="color: red;margin-right: 200px">Parasyte</h2>
        <h3>Autor: Hitoshi Iwaaki   </h3>
        <h3>Genre: Science fiction horror</h3>
        <h3>Published by:   Kodansha</h3>
        <h3 style="margin-right: 200px; " >Release Date:  May 1988</h3>
    


      <a href="https://w9.parasytemanga.com/" target="_blank">
        <button style="background-color: #252323; color: white; padding:  15px 75px; border-radius: 5px; margin-top: 10px;">
          Start reading
        </button>
      </a>
      </div>
    </div>
  
<h2>A few words about the author:</h2>
     <style>
    .on {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1200px;
      margin: 0 auto;
    }

    .textor {
      flex: 1;
      padding: 20px;
      font-size: 25px;
    }

    .imagete {
      flex: 1;
      padding: 20px;
      text-align: left; 
    }

  </style>
</head>
<body>

  <div class="on">
    <div class="textor">
      <h2 style="color: red;">Hitoshi Iwaaki</h2>
     <p>Hitoshi Iwaaki is a Japanese manga artist born on July 28, 1960. He is best known for creating the sci-fi horror manga Parasyte (Kiseijuu), which ran from 1988 to 1995. The series became a cult hit and gained renewed popularity with its 2014 anime adaptation. Iwaaki is known for blending horror, philosophy, and human psychology in his storytelling. His other works include Historie, a historical manga about the life of Eumenes, a general under Alexander the Great.

</p>

    </div>
    <div class="imagete">
      <img src="main_alt-47ca7b143c4d80713196e98f8a6ef3c0.jpeg" style="height:300px ;width: 200px; margin: 0;">
    </div>
  </div>
   <h2>Anime Adaptation:</h2>
<style>
    .cont {
      display: flex;
      align-items: center;
      max-width: 1100px;
      margin: 20px auto;
      gap: 20px;
    }
    .textop {
      flex: 1;
      font-family: Arial, sans-serif;
      line-height: 1.5;
    }
    .imagekol {
      flex: 1;
      text-align: right;
    }
    .image img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
  </style>
</head>
<body>

  <div class="cont">
    <div class="textop">
      <h2 style="font-size: 30px;">Parasyte -the maxim- (Kiseijuu: Sei no Kakuritsu)</h2>
      <p style="font-size: 20px;">
        The anime adaptation of Parasyte aired from October 2014 to March 2015. It was produced by Madhouse and directed by Kenichi Shimizu, with music by Ken Arai.<br><br>
        The anime closely follows the original manga, modernizing some elements (like smartphones) to match the 2010s setting. It ran for 24 episodes and was praised for its animation, voice acting, and faithful adaptation of the manga’s psychological and ethical themes.
      </p>
    </div>
    <div class="imagekol">
      <img style="width:300px ; height:400px ;" src="Kiseijuu_Anime_Poster.webp" />
    </div>
  </div>
  </div>
<h2 class="fade-in" style="color: white;" id="initialD">10.Initial D</h2>
    <h2 style="color: gray; text-align: center; ">Status: Complete</h2><br>
    <img src="p88kgbd4uxd71.webp" style="height: 340px;"><br>
    <blockquote class="fancy-quote">"The One With The Stronger Heart, Always Wins the Battle!"</blockquote>
    <h3>Initial D is a Japanese street racing manga series written and illustrated by Shuichi Shigeno. It was serialized in Kodansha's seinen manga magazine Weekly Young Magazine from 1995 to 2013, with the chapters collected into 48 tankōbon volumes.The story focuses on the world of illegal Japanese street racing, where all the action is concentrated in the mountain passes and rarely in cities or urban areas, and with the drifting racing style emphasized in particular. </h3>
    
    <hr style="width: 100%; border: 1px solid rgb(255, 255, 255);">


    <style>
      .container {
        display: flex;
        align-items: center;
      }
      .container img {
        width: 200px; 
        margin-right: 40px;
        
      }
      .text {
        max-width: 600px;
       
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="sekcja-ciekawostka-obrazek">
        <div class="tekst-ciekawostki">
          <h3> Did you know that...</h3>
          <p>The iconic car driven by Takumi Fujiwara in Initial D — the Toyota AE86 Trueno — became a cult legend thanks to the series. In real life, the AE86 was just a modest, lightweight car from the 1980s, but Initial D turned it into one of the most beloved drift cars in the world. Its popularity even boosted sales of tofu in Japan because Takumi's family runs a tofu shop!</p>
        </div>
        <img src="91oZ6lnLL-L._UF1000,1000_QL80_.jpg" alt="JoJo Bizarre Adventure" class="obrazek-ciekawostka">
      </div>
 <style>
 .sekcja-ciekawostka-obrazek {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 30px;
  padding: 30px;
  background-color: #1c1c1c;
  color: white;
  border-radius: 16px;
  max-width: 600px;
  margin: 40px auto;
  flex-wrap: wrap;
}

.tekst-ciekawostki {
  flex: 1;
  min-width: 300px;
}

.tekst-ciekawostki h3 {
  margin-bottom: 10px;
  color: #ff3366;
}

.tekst-ciekawostki p {
  font-size: 1.1em;
  line-height: 1.6;
}

.obrazek-ciekawostka {
  flex: 1;
  max-width: 400px;
  border-radius: 12px;
  width: 100%;
  height: auto;
}

 </style>      
      <div class="text" style="padding-left: 20px; max-width: 600px; text-align:left;">
        <h2 style="color: red;margin-right: 200px">Initial D</h2>
        <h3>Autor: Shuichi Shigeno   </h3>
        <h3>Genre: Action, coming-of-age, and sports</h3>
        <h3>Published by:  Shūkan Young Magazine</h3>
        <h3 style="margin-right: 200px; " >Release Date:  June 26, 1995</h3>
    


      <a href="https://mangadex.org/chapter/12d49511-fa35-4859-b832-0b8c37ae7bb8" target="_blank">
        <button style="background-color: #252323; color: white; padding:  15px 75px; border-radius: 5px; margin-top: 10px;">
          Start reading
        </button>
      </a>
      </div>
    </div>
  
<h2>A few words about the author:</h2>
     <style>
    .on {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1200px;
      margin: 0 auto;
    }

    .textor {
      flex: 1;
      padding: 20px;
      font-size: 25px;
    }

    .imagete {
      flex: 1;
      padding: 20px;
      text-align: left; 
    }

  </style>
</head>
<body>

  <div class="on">
    <div class="textor">
      <h2 style="color: red;">Shuichi Shigeno</h2>
     <p>Shuichi Shigeno was born in Matsunoyama , Tokamachi City , Niigata Prefecture. When Shigeno was in high school, he was obsessed with motorcycles, which resulted in one of his best-selling series, Bari Bari Densetsu. Before Shigeno became a manga artist, he was a poor student. Still, after Baribari Densetsu sold well and got a lot of money from royalties on the first edition, he bought his first car (Toyota AE86) and lived in a small apartment.</p>

    </div>
    <div class="imagete">
      <img src="Shigeno.webp" style="height:300px ;width: 200px; margin: 0;">
    </div>
  </div>
    <h2>Anime Adaptation:</h2>
<style>
    .cont {
      display: flex;
      align-items: center;
      max-width: 1100px;
      margin: 20px auto;
      gap: 20px;
    }
    .textop {
      flex: 1;
      font-family: Arial, sans-serif;
      line-height: 1.5;
    }
    .imagekol {
      flex: 1;
      text-align: right;
    }
    .image img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
  </style>
</head>
<body>

  <div class="cont">
    <div class="textop">
      <h2 style="font-size: 30px;">Initial D Anime Adaptation</h2>
      <p style="font-size: 20px;">
        Initial D is a popular anime series based on Shuichi Shigeno's manga about street racing in the mountains of Japan. The first anime adaptation aired in 1998 as a 26-episode series called Initial D First Stage. It was produced by Studio Gallop and focused on the early racing career of Takumi Fujiwara, a talented teenage driver. <br><br>

The series continued with several sequels and movies, including Second Stage (1999-2000), Third Stage (2001 movie), Fourth Stage (2004-2006), and Fifth Stage (2012-2013). The anime is famous for its intense racing scenes, detailed car models, and iconic Eurobeat soundtrack that perfectly matches the high-energy races. <br><br>

Initial D helped popularize drifting culture worldwide and remains a cult classic among racing and anime fans.
      </p>
    </div>
    <div class="imagekol">
      <img style="width:300px ; height:400px ;" src="MV5BZmM0MTI5MjAtYWI4YS00MmUzLWEyYWEtOGQ0YjZjYzQ0NzI3XkEyXkFqcGc@._V1_.jpg" />
    </div>
  </div>


    <h2 class="fade-in" style="color: white;" id="Hunter">9.Hunter × Hunter</h2>
    <h2 style="color: gray; text-align: center; ">Status: Ongoing</h2><br>
    <img src="gon-leorio-and-kurapika-on-a-hunter-x-hunter-manga-cover.jpg"><br>
    <blockquote class="fancy-quote">"Something more important than the thing you're hunting could be right there by the side of the road."</blockquote>
    <h3>Hunter × Hunter is a manga by Yoshihiro Togashi. The manga has been published since March 8, 1998 in Weekly Shonen Jump magazine, although since 2006 the publication has been frequently interrupted for long periods. As of September 2024, 400 chapters and 38 volumes have been published. The manga was on hiatus for a long time; chapter 390 was published on November 26, 2018.</h3>
    
    <hr style="width: 100%; border: 1px solid rgb(255, 255, 255);">


    <style>
      .container {
        display: flex;
        align-items: center;
      }
      .container img {
        width: 200px; 
        margin-right: 40px;
        
      }
      .text {
        max-width: 600px;
       
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="sekcja-ciekawostka-obrazek">
        <div class="tekst-ciekawostki">
          <h3> Did you know that...</h3>
          <p>Since 2006, Yoshihiro Togashi has repeatedly put the series on hiatus due to health issues. Fans often joke that a new chapter is “due” every autumn—but Togashi works at his own pace.</p>
        </div>
        <img src="hunter.jpg" alt="JoJo Bizarre Adventure" class="obrazek-ciekawostka">
      </div>
 <style>
 .sekcja-ciekawostka-obrazek {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 30px;
  padding: 30px;
  background-color: #1c1c1c;
  color: white;
  border-radius: 16px;
  max-width: 600px;
  margin: 40px auto;
  flex-wrap: wrap;
}

.tekst-ciekawostki {
  flex: 1;
  min-width: 300px;
}

.tekst-ciekawostki h3 {
  margin-bottom: 10px;
  color: #ff3366;
}

.tekst-ciekawostki p {
  font-size: 1.1em;
  line-height: 1.6;
}

.obrazek-ciekawostka {
  flex: 1;
  max-width: 400px;
  border-radius: 12px;
  width: 100%;
  height: auto;
}

 </style>      
      <div class="text" style="padding-left: 20px; max-width: 600px; text-align:left;">
        <h2 style="color: red;margin-right: 200px">Hunter x Hunter</h2>
        <h3>Autor: Yoshihiro Togashi   </h3>
        <h3>Genre: Adventure Fantasy Martial arts</h3>
        <h3>Published by: Shueisha</h3>
        <h3 style="margin-right: 200px; " >Release Date:  June 4, 1998</h3>
    


      <a href="https://hunterxhuntermanga.online/" target="_blank">
        <button style="background-color: #252323; color: white; padding:  15px 75px; border-radius: 5px; margin-top: 10px;">
          Start reading
        </button>
      </a>
      </div>
    </div>
  
<h2>A few words about the author:</h2>
     <style>
    .on {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1200px;
      margin: 0 auto;
    }

    .textor {
      flex: 1;
      padding: 20px;
      font-size: 25px;
    }

    .imagete {
      flex: 1;
      padding: 20px;
      text-align: left; 
    }

  </style>
</head>
<body>

  <div class="on">
    <div class="textor">
      <h2 style="color: red;">Yoshihiro Togashi</h2>
     <p>Togashi is known for his creativity, deep storytelling, and willingness to explore psychological and philosophical themes in shōnen manga. He is married to Naoko Takeuchi, the creator of Sailor Moon. Despite challenges, Togashi remains one of the most respected and influential manga artists of his generation.</p>

    </div>
    <div class="imagete">
      <img src="n96893-QixoFuZYSkpq.png" style="height:300px ;width: 200px; margin: 0;">
    </div>
  </div>
    
<h2>Anime Adaptation:</h2>
<style>
    .cont {
      display: flex;
      align-items: center;
      max-width: 1100px;
      margin: 20px auto;
      gap: 20px;
    }
    .textop {
      flex: 1;
      font-family: Arial, sans-serif;
      line-height: 1.5;
    }
    .imagekol {
      flex: 1;
      text-align: right;
    }
    .image img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
  </style>
</head>
<body>

  <div class="cont">
    <div class="textop">
      <h2 style="font-size: 30px;">Hunter × Hunter Anime Adaptation - Old 1999</h2>
      <p style="font-size: 20px;">
       Hunter × Hunter has two major anime adaptations. The first one aired from 1999 to 2001, produced by Nippon Animation, with a total of 62 episodes. This version covers the story from the beginning up to the start of the Greed Island arc. It features classic 90s animation style with a slower pacing and a nostalgic feel. The soundtrack by Toshihiko Sahashi is well-loved, and many longtime fans appreciate this adaptation for its faithful retelling of the early manga chapters.
      </p>
    </div>
    <div class="imagekol">
      <img style="width:300px ; height:400px ;" src="1V5BNDBiMzMyMWItNDFkYy00MjBmLTk2ZDAtYmE2N2U4YzFlZDRmXkEyXkFqcGc@._V1_.jpg" />
    </div>
  </div>
  <br>
  <div class="cont">
    <div class="textop">
      <h2 style="font-size: 30px;">Hunter × Hunter Anime Adaptation - New 2011</h2>
      <p style="font-size: 20px;">
       The second adaptation, produced by Madhouse, aired from 2011 to 2014 and consists of 148 episodes. It covers almost the entire manga storyline up to the end of the 13th Hunter Chairman Election arc, including major arcs like the Hunter Exam, Heavens Arena, Greed Island, Chimera Ant, and Election arcs. This version features modern, polished animation with updated character designs and faster pacing. The music, composed by Yoshihisa Hirano and Hideki Taniuchi, adds an atmospheric and intense mood to the series. It is praised for its high-quality animation, faithful storytelling, and strong character development, and is considered by many fans as the definitive Hunter × Hunter adaptation.
      </p>
    </div>
    <div class="imagekol">
      <img style="width:300px ; height:400px ;" src="MV5BYzYxOTlkYzctNGY2MC00MjNjLWIxOWMtY2QwYjcxZWIwMmEwXkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg" />
    </div>
  </div>


    <h2 class="fade-in" style="color: white;" id="jojo">8.JoJo's Bizarre Adventure</h2>
    <h2 style="color: gray; text-align: center; ">Status: Ongoing</h2><br>
    <img src="Joestar-Family-JoJos-Bizarre-Adventure-Featured.avif"><br>
    <blockquote class="fancy-quote">"I’ve returned from hell, Dio!"</blockquote>
    <h3>JoJo's Bizarre Adventure is a Japanese manga series written and illustrated by Hirohiko Araki. It was originally serialized in Shueisha's shōnen manga magazine Weekly Shōnen Jump from 1987 to 2004, and was transferred to the monthly seinen manga magazine Ultra Jump in 2005. The series is divided into a total of nine main story arcs, each following a new protagonist bearing the "JoJo" nickname. JoJo's Bizarre Adventure is the largest ongoing manga series published by Shueisha by number of volumes, with its chapters collected in 136 tankōbon volumes as of December 2024.</h3> 
    <hr style="width: 100%; border: 1px solid rgb(255, 255, 255);">


    <style>
      .container {
        display: flex;
        align-items: center;
      }
      .container img {
        width: 200px; 
        margin-right: 40px;
        
      }
      .text {
        max-width: 600px;
       
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="sekcja-ciekawostka-obrazek">
        <div class="tekst-ciekawostki">
          <h3> Did you know that...</h3>
          <p>JoJo’s Bizarre Adventure author Hirohiko Araki designed a cover for Vogue magazine and collaborated with Gucci.</p>
        </div>
        <img src="jojo1.jpg" alt="JoJo Bizarre Adventure" class="obrazek-ciekawostka">
      </div>
      
 <style>
 .sekcja-ciekawostka-obrazek {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 30px;
  padding: 30px;
  background-color: #1c1c1c;
  color: white;
  border-radius: 16px;
  max-width: 600px;
  margin: 40px auto;
  flex-wrap: wrap;
}

.tekst-ciekawostki {
  flex: 1;
  min-width: 300px;
}

.tekst-ciekawostki h3 {
  margin-bottom: 10px;
  color: #ff3366;
}

.tekst-ciekawostki p {
  font-size: 1.1em;
  line-height: 1.6;
}

.obrazek-ciekawostka {
  flex: 1;
  max-width: 400px;
  border-radius: 12px;
  width: 100%;
  height: auto;
}

 </style>      
      <div class="text" style="padding-left: 20px; max-width: 600px; text-align:left;">
        <h2 style="color: red;margin-right: 200px">JoJo's Bizarre Adventure</h2>
        <h3>Autor: Hirohiko Araki </h3>
        <h3>Genre: Adventure Supernatural</h3>
        <h3>Published by: Shueisha</h3>
        <h3 style="margin-right: 200px; " >Release Date: January 1, 1987</h3>
    


      <a href="https://readjojos.com/" target="_blank">
        <button style="background-color: #252323; color: white; padding:  15px 75px; border-radius: 5px; margin-top: 10px;">
          Start reading
        </button>
      </a>
      </div>
    </div>
  

     <h2>A few words about the author:</h2>
     <style>
    .on {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1200px;
      margin: 0 auto;
    }

    .textor {
      flex: 1;
      padding: 20px;
      font-size: 25px;
    }

    .imagete {
      flex: 1;
      padding: 20px;
      text-align: left; 
    }

  </style>
</head>
<body>

  <div class="on">
    <div class="textor">
      <h2 style="color: red;">Hirohiko Araki</h2>
     <p>Hirohiko Araki is a Japanese manga artist, born on June 7, 1960. He is best known for creating the long-running series JoJo’s Bizarre Adventure, which began in 1987. Araki’s unique art style and imaginative storytelling have made JoJo a cult classic worldwide. His work often blends action, fashion, and surrealism. He continues to expand the JoJo universe through new story arcs.</p>

    </div>
    <div class="imagete">
      <img src="img_prof.webp" style="height:300px ;width: 240px; margin: 0;">
    </div>
  </div>

<h2>Anime Adaptation:</h2>
<style>
    .cont {
      display: flex;
      align-items: center;
      max-width: 1100px;
      margin: 20px auto;
      gap: 20px;
    }
    .textop {
      flex: 1;
      font-family: Arial, sans-serif;
      line-height: 1.5;
    }
    .imagekol {
      flex: 1;
      text-align: right;
    }
    .image img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
  </style>
</head>
<body>

  <div class="cont">
    <div class="textop">
      <h2 style="font-size: 30px;">JoJo’s Bizarre Adventure Anime Adaptation Old Anime (1993 & 2000)</h2>
      <p style="font-size: 20px;">
       Before the modern 2012 adaptation, JoJo’s Bizarre Adventure had an earlier anime version in the form of an OVA (Original Video Animation). The first episodes were released in 1993, with a prequel set of episodes released in 2000, making a total of 13 episodes. The OVA was produced by Studio A.P.P.P. and covers only Part 3 of the manga – Stardust Crusaders. <br><br>

Interestingly, the 1993 OVA starts in the middle of the story, while the 2000 episodes later filled in the beginning. This version had a much darker and more serious tone than the later adaptations. The art style was more realistic and subdued, and the pacing was slower. <br><br>

Although it only covers one part of the Joestar family’s adventures, this was the first animated portrayal of the JoJo universe and introduced many fans to the series in the 1990s.
      </p>
    </div>
    <div class="imagekol">
      <img style="width:300px ; height:400px ;" src="JoJo's_Bizarre_Adventure_OVA.jpg" />
    </div>
  </div>
   <div class="cont">
    <div class="textop">
      <h2 style="font-size: 30px;">JoJo’s Bizarre Adventure – New Anime (2012–present)</h2>
      <p style="font-size: 20px;">
      The modern adaptation of JoJo’s Bizarre Adventure began airing in 2012, produced by David Production. It starts from Part 1: Phantom Blood and faithfully adapts the manga in chronological order, with high-quality animation, vibrant colors, and iconic music. <br><br>

Each part focuses on a different member of the Joestar bloodline and their battles involving supernatural powers, especially Stands (starting in Part 3). As of now, the anime has adapted: <br><br>

Part 1: Phantom Blood (2012) <br>

Part 2: Battle Tendency (2012–2013) <br>

Part 3: Stardust Crusaders (2014–2015)<br>

Part 4: Diamond is Unbreakable (2016)<br>

Part 5: Golden Wind (2018–2019)<br>

Part 6: Stone Ocean (2021–2022)<br><br>

The series is praised for its stylish animation, creative fights, faithful adaptation of Araki’s manga, and memorable characters and poses. It helped JoJo gain massive popularity worldwide and has become a cultural phenomenon.
      </p>
    </div>
    <div class="imagekol">
      <img style="width:300px ; height:400px ;" src="qV5BMzIyNzY4NTMtNmVhYS00OWFhLTkwMWMtOGFkNTdmNWU2ZDdiXkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg" />
    </div>
  </div>








    <h2 class="fade-in" style="color: white;" id="one-piece">7.One Piece </h2>
    <h2 style="color: gray; text-align: center; ">Status: Ongoing</h2><br>
    <img src="Chapter_1.webp" style="height: 400px; width: 600px;"><br>
    <blockquote class="fancy-quote">"One Piece does exist!"</blockquote>
    <h3>One Piece (stylized in all caps) is a Japanese manga series written and illustrated by Eiichiro Oda. It follows the adventures of Monkey D. Luffy and his crew, the Straw Hat Pirates, as he explores the Grand Line in search of the mythical treasure known as the "One Piece" to become the next King of the Pirates."One Piece. Big Score" is a shonen manga authored by Eiichiro Oda.</h3>
    <hr style="width: 100%; border: 1px solid rgb(255, 255, 255);">

    <style>
      .container {
        display: flex;
        align-items: center;
      }
      .container img {
        width: 200px; 
        margin-right: 40px;
        
      }
      .text {
        max-width: 600px;
       
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="sekcja-ciekawostka-obrazek">
        <div class="tekst-ciekawostki">
          <h3> Did you know that...</h3>
          <p>As of 2024, One Piece has sold over 500 million copies worldwide.

            It holds a Guinness World Record for “The most copies published for the same comic book series by a single author.”
            
            </p>
        </div>
        <img src="one piece.jpg" alt="JoJo Bizarre Adventure" class="obrazek-ciekawostka">
      </div>
 <style>
 .sekcja-ciekawostka-obrazek {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 30px;
  padding: 30px;
  background-color: #1c1c1c;
  color: white;
  border-radius: 16px;
  max-width: 600px;
  margin: 40px auto;
  flex-wrap: wrap;
}

.tekst-ciekawostki {
  flex: 1;
  min-width: 300px;
}

.tekst-ciekawostki h3 {
  margin-bottom: 10px;
  color: #ff3366;
}

.tekst-ciekawostki p {
  font-size: 1.1em;
  line-height: 1.6;
}

.obrazek-ciekawostka {
  flex: 1;
  max-width: 400px;
  border-radius: 12px;
  width: 100%;
  height: auto;
}

 </style>      
      <div class="text" style="padding-left: 20px; max-width: 600px; text-align:left;">
        <h2 style="color: red;margin-right: 200px">One Piece</h2>
        <h3>Autor: Eiichiro Oda    </h3>
        <h3>Genre: Adventure Fantasy comedy Science fiction </h3>
        <h3>Published by: Shueisha</h3>
        <h3 style="margin-right: 200px; " >Release Date: July 22, 1997</h3>
    


      <a href="https://w025.1piecemanga.com/" target="_blank">
        <button style="background-color: #252323; color: white; padding:  15px 75px; border-radius: 5px; margin-top: 10px;">
          Start reading
        </button>
      </a>
      </div>
    </div>
    
    
    <h2>A few words about the author:</h2>
     <style>
    .on {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1200px;
      margin: 0 auto;
    }

    .textor {
      flex: 1;
      padding: 20px;
      font-size: 25px;
    }

    .imagete {
      flex: 1;
      padding: 20px;
      text-align: left; 
    }

  </style>
</head>
<body>

  <div class="on">
    <div class="textor">
      <h2 style="color: red;">Eiichiro Oda</h2>
     <p>Eiichiro Oda is a Japanese manga artist born on January 1, 1975. He is the creator of One Piece, one of the most successful manga series of all time. Oda began his career as an assistant before launching One Piece in 1997. Known for his rich world-building, humor, and emotional storytelling, Oda has become one of the most influential figures in manga history.</p>

    </div>
    <div class="imagete">
      <img src="wewq.jpg" style="height:300px ;width: 200px; margin: 0;">
    </div>
  </div>
   <h2>Anime Adaptation:</h2>
<style>
    .cont {
      display: flex;
      align-items: center;
      max-width: 1100px;
      margin: 20px auto;
      gap: 20px;
    }
    .textop {
      flex: 1;
      font-family: Arial, sans-serif;
      line-height: 1.5;
    }
    .imagekol {
      flex: 1;
      text-align: right;
    }
    .image img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
  </style>
</head>
<body>

  <div class="cont">
    <div class="textop">
      <h2 style="font-size: 30px;">One Piece Anime Adaptation</h2>
      <p style="font-size: 20px;">
       One Piece, created by Eiichiro Oda, is one of the longest-running and most popular anime series in the world. The anime began airing in October 1999 and is produced by Toei Animation. <br><br>

The story follows Monkey D. Luffy and his crew of pirates as they search for the legendary treasure called "One Piece" in order to become the Pirate King. The series is known for its adventurous spirit, colorful characters, emotional storytelling, and imaginative world-building. <br><br>

With over 1000 episodes and counting, One Piece has captivated audiences worldwide and is praised for its consistency, humor, and ability to balance action with heartfelt moments.
      </p>
    </div>
    <div class="imagekol">
      <img style="width:300px ; height:400px ;" src="wV5BMTNjNGU4NTUtYmVjMy00YjRiLTkxMWUtNzZkMDNiYjZhNmViXkEyXkFqcGc@._V1_.jpg" />
    </div>
  </div> 
   
    <h2 class="fade-in" style="color: white;" id="berserk">6.Berserk </h2>
    <h2 style="color: gray; text-align: center; ">Status: Ongoing</h2><br>
    <img src="guts-berserk-manga-cover.jpg" style="height: 300px; width: 600px;"><br>
    <blockquote class="fancy-quote">"He Died Doing What He Wanted, No Matter What, Right?"</blockquote>
    <h3>Berserk is a fantasy manga written by Kentaro Miura. The first volume was published in 1989. According to a survey conducted in 2007 by the Japanese Ministry of Culture, it ranks as the 25th best manga of all time.Miura premiered a prototype of Berserk in 1988. The series began the following year in Hakusensha's manga magazine Monthly Animal House , which was replaced in 1992 by the semimonthly magazine Young Animal, where Berserk has continued its publication. Following Miura's death in May 2021, the final chapter that he worked on was published posthumously in September of the same year; the series resumed in June 2022, under supervision of Miura's fellow manga artist and childhood friend Kouji Mori.</h3>
    <hr style="width: 100%; border: 1px solid rgb(255, 255, 255);">


    <style>
      .container {
        display: flex;
        align-items: center;
      }
      .container img {
        width: 200px; 
        margin-right: 40px;
        
      }
      .text {
        max-width: 600px;
       
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="sekcja-ciekawostka-obrazek">
        <div class="tekst-ciekawostki">
          <h3> Did you know that...</h3>
          <p>Griffith’s ethereal look was inspired by 1980s singer Takanori Nishikawa (of T.M. Revolution) and the feminine beauty ideal in shojo manga.

            His tragic charisma and ambition are central to the story’s themes of sacrifice and power.
            
            </p>
        </div>
        <img src="Berserk_vol01.jpg" alt="JoJo Bizarre Adventure" class="obrazek-ciekawostka">
      </div>
 <style>
 .sekcja-ciekawostka-obrazek {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 30px;
  padding: 30px;
  background-color: #1c1c1c;
  color: white;
  border-radius: 16px;
  max-width: 600px;
  margin: 40px auto;
  flex-wrap: wrap;
}

.tekst-ciekawostki {
  flex: 1;
  min-width: 300px;
}

.tekst-ciekawostki h3 {
  margin-bottom: 10px;
  color: #ff3366;
}

.tekst-ciekawostki p {
  font-size: 1.1em;
  line-height: 1.6;
}

.obrazek-ciekawostka {
  flex: 1;
  max-width: 400px;
  border-radius: 12px;
  width: 100%;
  height: auto;
}

 </style>      
      <div class="text" style="padding-left: 20px; max-width: 600px; text-align:left;">
        <h2 style="color: red;margin-right: 200px">Berserk</h2>
        <h3>Autor: Kentaro Miura  </h3>
        <h3>Genre:  Dark fantasy or grimdark</h3>
        <h3>Published by: Hakusensha</h3>
        <h3 style="margin-right: 200px; " >Release Date:  August 25, 1989</h3>
    


      <a href="https://theberserkmanga.com/" target="_blank">
        <button style="background-color: #252323; color: white; padding:  15px 75px; border-radius: 5px; margin-top: 10px;">
          Start reading
        </button>
      </a>
      </div>
    </div>

    <h2>A few words about the author:</h2>
     <style>
    .on {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1200px;
      margin: 0 auto;
    }

    .textor {
      flex: 1;
      padding: 20px;
      font-size: 25px;
    }

    .imagete {
      flex: 1;
      padding: 20px;
      text-align: left; 
    }

  </style>
</head>
<body>

  <div class="on">
    <div class="textor">
      <h2 style="color: red;">Kentaro Miura</h2>
     <p>Kentaro Miura was a Japanese manga artist, born on July 11, 1966, and best known for creating the dark fantasy series Berserk. He began drawing manga at a young age and launched Berserk in 1989. The series became famous for its detailed art, deep themes, and emotional intensity. Miura passed away in 2021, but his work remains highly influential in manga and beyond.

</p>

    </div>
    <div class="imagete">
      <img src="n96868-R5aBOYlTExZR.jpg" style="height:300px ;width: 200px; margin: 0;">
    </div>
  </div>
  <h2>Anime Adaptation:</h2>
<style>
    .cont {
      display: flex;
      align-items: center;
      max-width: 1100px;
      margin: 20px auto;
      gap: 20px;
    }
    .textop {
      flex: 1;
      font-family: Arial, sans-serif;
      line-height: 1.5;
    }
    .imagekol {
      flex: 1;
      text-align: right;
    }
    .image img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
  </style>
</head>
<body>

  <div class="cont">
    <div class="textop">
      <h2 style="font-size: 30px;">Berserk (1997 Anime – Old)</h2>
      <p style="font-size: 20px;">
       Berserk has received several anime adaptations, though none fully capture the depth and detail of Kentaro Miura’s original manga. The first adaptation aired from 1997 to 1998, consisting of 25 episodes, produced by studio OLM. It covers the iconic Golden Age Arc, one of the most important parts of the story. Despite a limited animation budget, the series stands out for its dark atmosphere, strong character development, and emotional storytelling. However, it ends abruptly at the Eclipse, leaving the rest of the story untold.
      </p>
    </div>
    <div class="imagekol">
      <img style="width:280px ; height:400px ;" src="MeV5BZmE1YTFlZWMtYzRkYi00MWU0LWIwODctZmYzMDExZGRkM2NmXkEyXkFqcGc@._V1_.jpg" />
    </div>
  </div>
  <div class="cont">
    <div class="textop">
      <h2 style="font-size: 30px;">Berserk (2016–2017 Anime – New)</h2>
      <p style="font-size: 20px;">
       The newer anime aired in 2016 and 2017, produced by studios GEMBA and Millepensee. It includes 24 episodes and continues the plot, covering the Conviction Arc and part of the Falcon of the Millennium Empire Arc. Unfortunately, it received heavy criticism for its awkward blend of 3D and 2D animation, which many fans found clunky and visually unappealing. Despite adapting important events from the manga, the poor animation quality overshadowed the narrative. <br><br>

For many fans, the manga remains the definitive way to experience Berserk, praised for its breathtaking artwork and powerful storytelling.
      </p>
    </div>
    <div class="imagekol">
      <img style="width:280px ; height:400px ;" src="BV5BOTY0ZGMwZmEtNDVmMy00OWJmLWFlNjEtMGZkNTdlN2EzOWVmXkEyXkFqcGc@._V1_.jpg" />
    </div>
  </div>


    <h2 class="fade-in" style="color: white;" id="monster">5.Monster </h2>
    <h2 style="color: gray; text-align: center; ">Status: Complete</h2><br>
    <img src="monster (1).jpg" style="height: 300px; width: 600px;"><br>
    <blockquote class="fancy-quote">"When you’re in the darkness, you only sink deeper into it… Keep the light shining"</blockquote>
    <h3>Monster (stylized in all caps) is a Japanese manga series written and illustrated by Naoki Urasawa. It was published by Shogakukan in its seinen manga magazine Big Comic Original between December 1994 and December 2001, with its chapters collected in 18 tankōbon volumes. The story revolves around Kenzo Tenma, a Japanese surgeon living in Düsseldorf, Germany whose life enters turmoil after he gets himself involved with Johan Liebert, one of his former patients, who is revealed to be a psychopathic serial killer.</h3>
    <hr style="width: 100%; border: 1px solid rgb(255, 255, 255);">


    <style>
      .container {
        display: flex;
        align-items: center;
      }
      .container img {
        width: 200px; 
        margin-right: 40px;
        
      }
      .text {
        max-width: 600px;
       
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="sekcja-ciekawostka-obrazek">
        <div class="tekst-ciekawostki">
          <h3> Did you know that...</h3>
          <p>Monster is more than a mystery—it's a philosophical exploration of good vs. evil, free will, and the value of a human life.

            The story asks: “If you save a life, are you responsible for what that person becomes?”
            
            </p>
        </div>
        <img src="monst.jpg" alt="JoJo Bizarre Adventure" class="obrazek-ciekawostka">
      </div>
 <style>
 .sekcja-ciekawostka-obrazek {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 30px;
  padding: 30px;
  background-color: #1c1c1c;
  color: white;
  border-radius: 16px;
  max-width: 600px;
  margin: 40px auto;
  flex-wrap: wrap;
}

.tekst-ciekawostki {
  flex: 1;
  min-width: 300px;
}

.tekst-ciekawostki h3 {
  margin-bottom: 10px;
  color: #ff3366;
}

.tekst-ciekawostki p {
  font-size: 1.1em;
  line-height: 1.6;
}

.obrazek-ciekawostka {
  flex: 1;
  max-width: 400px;
  border-radius: 12px;
  width: 100%;
  height: auto;
}

 </style>      
      <div class="text" style="padding-left: 20px; max-width: 600px; text-align:left;">
        <h2 style="color: red;margin-right: 200px">Monster</h2>
        <h3>Autor: Naoki Urasawa </h3>
        <h3>Genre: Crime Mystery Psychological thriller</h3>
        <h3>Published by: Shogakukana</h3>
        <h3 style="margin-right: 200px; " >Release Date:  30 June 1995</h3>
    


      <a href="https://www.monstermangafree.com/index.html" target="_blank">
        <button style="background-color: #252323; color: white; padding:  15px 75px; border-radius: 5px; margin-top: 10px;">
          Start reading
        </button>
      </a>
      </div>
    </div>
    <h2>A few words about the author:</h2>
     <style>
    .on {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1200px;
      margin: 0 auto;
    }

    .textor {
      flex: 1;
      padding: 20px;
      font-size: 25px;
    }

    .imagete {
      flex: 1;
      padding: 20px;
      text-align: left; 
    }

  </style>
</head>
<body>

  <div class="on">
    <div class="textor">
      <h2 style="color: red;">Naoki Urasawa</h2>
     <p>Naoki Urasawa is a Japanese manga artist born on January 2, 1960. He is best known for creating critically acclaimed series like Monster, 20th Century Boys, and Pluto. Urasawa is known for his complex plots, deep characters, and suspenseful storytelling. His work often blends mystery, psychology, and social themes, earning him numerous awards and international recognition.</p>

    </div>
    <div class="imagete">
      <img src="JGen-Naoki-Urasawa-Japan-House-interview-2019-1A.jpg" style="height:300px ;width: 230px; margin: 0;">
    </div>
  </div>
  <h2>Anime Adaptation:</h2>
<style>
    .cont {
      display: flex;
      align-items: center;
      max-width: 1100px;
      margin: 20px auto;
      gap: 20px;
    }
    .textop {
      flex: 1;
      font-family: Arial, sans-serif;
      line-height: 1.5;
    }
    .imagekol {
      flex: 1;
      text-align: right;
    }
    .image img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
  </style>
</head>
<body>

  <div class="cont">
    <div class="textop">
      <h2 style="font-size: 30px;">Monster Anime Adaptation</h2>
      <p style="font-size: 20px;">
       Monster is a psychological thriller manga by Naoki Urasawa. The anime adaptation aired from 2004 to 2005 and was produced by Madhouse. It consists of 74 episodes. <br><br>

The story follows Dr. Kenzo Tenma, a talented brain surgeon whose life changes after saving a young boy who later becomes a dangerous serial killer. The series explores themes of morality, identity, and the nature of evil. <br><br>

The anime was praised for its deep, suspenseful storytelling, complex characters, and mature themes, making it a standout in the thriller genre.
      </p>
    </div>
    <div class="imagekol">
      <img style="width:300px ; height:400px ;" src="yMV5BYzU2MWQ5NGQtYmNlMC00ZjJkLWJmODItZDM5MDM3YmUyMWJkXkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg" />
    </div>
  </div>


    <h2 class="fade-in" style="color: white;" id="vagabond">4.Vagabond</h2>
    <h2 style="color: gray; text-align: center; ">Status: Complete</h2><br>
    <img src="ujazp4qsrsj21.jpg" style="height: 400px; width: 600px;" ><br>
    <blockquote class="fancy-quote">"Preoccupied with a single leaf... you won't see the tree. Preoccupied with a single tree... you'll miss the entire forest."</blockquote>
    <h3>Vagabond is an artistically reimagined story of the life of one of Japan's most famous swordsmen, the "Saint of Sword" Miyamoto Musashi. The story tells about the formation of a great warrior, his path to understanding friendship, life, and himself. Early 17th century in Japan. Shimmen Takezo is a rude and uncouth young man in all his manifestations. Simmen's aggressive nature causes fear and rejection among the residents of his native village, which pushes him and his friend, Matahachi Hon'iden, in search of a better life. The thirst for glory brings friends into the Toyotomi army, but a brutal defeat at the Battle of Sekigahara leaves them on the brink of death.</h3>
    <hr style="width: 100%; border: 1px solid rgb(255, 255, 255);">


    <style>
      .container {
        display: flex;
        align-items: center;
      }
      .container img {
        width: 200px; 
        margin-right: 40px;
        
      }
      .text {
        max-width: 600px;
       
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="sekcja-ciekawostka-obrazek">
        <div class="tekst-ciekawostki">
          <h3> Did you know that...</h3>
          <p>Vagabond tells the story of Miyamoto Musashi, Japan’s most famous swordsman.

            It’s adapted from the novel Musashi by Eiji Yoshikawa, itself a fictionalized biography.
            
            </p>
        </div>
        <img src="vagabond23.jpg" alt="JoJo Bizarre Adventure" class="obrazek-ciekawostka">
      </div>
 <style>
 .sekcja-ciekawostka-obrazek {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 30px;
  padding: 30px;
  background-color: #1c1c1c;
  color: white;
  border-radius: 16px;
  max-width: 600px;
  margin: 40px auto;
  flex-wrap: wrap;
}

.tekst-ciekawostki {
  flex: 1;
  min-width: 300px;
}

.tekst-ciekawostki h3 {
  margin-bottom: 10px;
  color: #ff3366;
}

.tekst-ciekawostki p {
  font-size: 1.1em;
  line-height: 1.6;
}

.obrazek-ciekawostka {
  flex: 1;
  max-width: 400px;
  border-radius: 12px;
  width: 100%;
  height: auto;
}

 </style>      
      <div class="text" style="padding-left: 20px; max-width: 600px; text-align:left;">
        <h2 style="color: red;margin-right: 200px">Vagabond</h2>
        <h3>Autor: Takehiko Inoue </h3>
        <h3>Genre: Epic Historical Martial arts</h3>
        <h3>Published by: Kodansha</h3>
        <h3 style="margin-right: 200px; " >Release Date:   September 3, 1998</h3>
    


      <a href="https://readvagabond-manga.online/" target="_blank">
        <button style="background-color: #252323; color: white; padding:  15px 75px; border-radius: 5px; margin-top: 10px;">
          Start reading
        </button>
      </a>
      </div>
    </div>
    <h2>A few words about the author:</h2>
     <style>
    .on {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1200px;
      margin: 0 auto;
    }

    .textor {
      flex: 1;
      padding: 20px;
      font-size: 25px;
    }

    .imagete {
      flex: 1;
      padding: 20px;
      text-align: left; 
    }

  </style>
</head>
<body>

  <div class="on">
    <div class="textor">
      <h2 style="color: red;">Takehiko Inoue</h2>
     <p>Takehiko Inoue is a Japanese manga artist born on January 12, 1967. He is best known for the basketball manga Slam Dunk, as well as Vagabond and Real. Inoue's work is praised for its realistic art, emotional depth, and inspiring stories. His manga has had a major impact both in Japan and around the world, especially in promoting basketball culture.</p>

    </div>
    <div class="imagete">
      <img src="48570.jpg" style="height:300px ;width: 200px; margin: 0;">
    </div>
  </div>
    <h2 class="fade-in" style="color: white;" id="slam dunk">3.Slam Dunk</h2>
    <h2 style="color: gray; text-align: center; ">Status: Complete</h2><br>
    <img src="slam-dunk-cover2-scaled.jpg.webp" style="height: 330px; width: 600px;"><br>
    <blockquote class="fancy-quote">"It is not too late to change ourselves and have a meaningful life"</blockquote>
    <h3>Slam Dunk (stylized in all caps) is a Japanese sports manga series written and illustrated by Takehiko Inoue. It was serialized in Shueisha's shōnen manga magazine Weekly Shōnen Jump from October 1990 to June 1996, with the chapters collected into 31 tankōbon volumes. The story follows Hanamichi Sakuragi, a brash and impulsive high school student who joins a basketball team at Shōhoku High School.</h3>
    <hr style="width: 100%; border: 1px solid rgb(255, 255, 255);">


    <style>
      .container {
        display: flex;
        align-items: center;
      }
      .container img {
        width: 200px; 
        margin-right: 40px;
        
      }
      .text {
        max-width: 600px;
       
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="sekcja-ciekawostka-obrazek">
        <div class="tekst-ciekawostki">
          <h3> Did you know that...</h3>
          <p>Before Slam Dunk, basketball wasn't hugely popular in Japan.

            The manga sparked a national boom in basketball’s popularity during the 1990s.
            
            Schools saw a spike in basketball club memberships, nicknamed the "Slam Dunk effect".</p>
        </div>
        <img src="slam dunk.jpg" alt="JoJo Bizarre Adventure" class="obrazek-ciekawostka">
      </div>
 <style>
 .sekcja-ciekawostka-obrazek {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 30px;
  padding: 30px;
  background-color: #1c1c1c;
  color: white;
  border-radius: 16px;
  max-width: 600px;
  margin: 40px auto;
  flex-wrap: wrap;
}

.tekst-ciekawostki {
  flex: 1;
  min-width: 300px;
}

.tekst-ciekawostki h3 {
  margin-bottom: 10px;
  color: #ff3366;
}

.tekst-ciekawostki p {
  font-size: 1.1em;
  line-height: 1.6;
}

.obrazek-ciekawostka {
  flex: 1;
  max-width: 400px;
  border-radius: 12px;
  width: 100%;
  height: auto;
}

 </style>      
      <div class="text" style="padding-left: 20px; max-width: 600px; text-align:left;">
        <h2 style="color: red;margin-right: 200px">Slam Dunk</h2>
        <h3>Autor: Takehiko Inoue   </h3>
        <h3>Genre: Sports, Comedy, and Drama</h3>
        <h3>Published by: Shueisha</h3>
        <h3 style="margin-right: 200px; " >Release Date:   February 8, 1991</h3>
    


      <a href="https://read-slamdunk.online/" target="_blank">
        <button style="background-color: #252323; color: white; padding:  15px 75px; border-radius: 5px; margin-top: 10px;">
          Start reading
        </button>
      </a>
      </div>
    </div>
    <h2>A few words about the author:</h2>
     <style>
    .on {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1200px;
      margin: 0 auto;
    }

    .textor {
      flex: 1;
      padding: 20px;
      font-size: 25px;
    }

    .imagete {
      flex: 1;
      padding: 20px;
      text-align: left; 
    }

  </style>
</head>
<body>

  <div class="on">
    <div class="textor">
      <h2 style="color: red;">Takehiko Inoue</h2>
     <p>Takehiko Inoue is a Japanese manga artist born in 1967. He is famous for Slam Dunk, Vagabond, and Real. Known for realistic art and deep stories, Inoue helped popularize basketball in Japan and is highly respected worldwide.</p>

    </div>
    <div class="imagete">
      <img src="5008.webp" style="height:300px ;width: 220px; margin: 0;">
    </div>
  </div>
  <h2>Anime Adaptation:</h2>
<style>
    .cont {
      display: flex;
      align-items: center;
      max-width: 1100px;
      margin: 20px auto;
      gap: 20px;
    }
    .textop {
      flex: 1;
      font-family: Arial, sans-serif;
      line-height: 1.5;
    }
    .imagekol {
      flex: 1;
      text-align: right;
    }
    .image img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
  </style>
</head>
<body>

  <div class="cont">
    <div class="textop">
      <h2 style="font-size: 30px;">Slam Dunk Anime Adaptation</h2>
      <p style="font-size: 20px;">
       Slam Dunk, created by Takehiko Inoue, is a classic basketball manga that was adapted into an anime series from 1993 to 1996. The anime was produced by Toei Animation and consists of 101 episodes. <br><br>

The story follows Hanamichi Sakuragi, a high school delinquent who joins the basketball team to impress a girl but soon discovers his passion and talent for the sport. The series is known for its exciting basketball games, humor, and strong character development. <br><br>

Slam Dunk played a major role in popularizing basketball in Japan and remains beloved by fans worldwide for its inspiring story and memorable characters.
      </p>
    </div>
    <div class="imagekol">
      <img style="width:300px ; height:400px ;" src="MqwV5BMmI0Njg0MzctYjk2Yy00YzZlLWEzMWEtMjkxZWQxMjczZjhjXkEyXkFqcGc@._V1_.jpg" />
    </div>
  </div>


    <h2 class="fade-in" style="color: white;" id="climber">2.The Climber</h2>
    <h2 style="color: gray; text-align: center; ">Status: Complete</h2><br>
    <img src="fqxttn50mx281.jpg" style="height: 400px; width: 600px;" ><br>
    <blockquote class="fancy-quote">"Climb the mountain not to plant your flag, but to embrace the challenge, enjoy the air and behold the view. Climb it so you can see the world, not so the world can see you."</blockquote>
    <h3>The Climber is a Japanese manga series written by Shin-ichi Sakamoto, Yoshio Nabeta (first two volumes), and Hiroshi Takano (volumes 2–4), and illustrated by Sakamoto, based on a two-volume 1973 novel by Jirō Nitta. It was originally serialized in Shueisha's seinen manga magazine Weekly Young Jump from November 2007 to October 2012, with its chapters collected in 17 tankōbon volumes.</h3>
    <hr style="width: 100%; border: 1px solid rgb(255, 255, 255);">


    <style>
      .container {
        display: flex;
        align-items: center;
      }
      .container img {
        width: 200px; 
        margin-right: 40px;
        
      }
      .text {
        max-width: 600px;
       
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="sekcja-ciekawostka-obrazek">
        <div class="tekst-ciekawostki">
          <h3> Did you know that...</h3>
          <p>Unlike most sports manga, The Climber explores themes of isolation, depression, and obsession.

            It focuses on the internal struggles of Mori Buntarō more than just the physical challenge of climbing.
            
            </p>
        </div>
        <img src="the climber.jpg" alt="JoJo Bizarre Adventure" class="obrazek-ciekawostka">
      </div>
 <style>
 .sekcja-ciekawostka-obrazek {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 30px;
  padding: 30px;
  background-color: #1c1c1c;
  color: white;
  border-radius: 16px;
  max-width: 600px;
  margin: 40px auto;
  flex-wrap: wrap;
}

.tekst-ciekawostki {
  flex: 1;
  min-width: 300px;
}

.tekst-ciekawostki h3 {
  margin-bottom: 10px;
  color: #ff3366;
}

.tekst-ciekawostki p {
  font-size: 1.1em;
  line-height: 1.6;
}

.obrazek-ciekawostka {
  flex: 1;
  max-width: 400px;
  border-radius: 12px;
  width: 100%;
  height: auto;
}
</style>
    <div class="text" style="padding-left: 20px; max-width: 600px; text-align:left;">
      <h2 style="color: red;margin-right: 200px">The Climber</h2>
      <h3>Illustrator: Shin-ichi Sakamoto </h3>
      <h3>Idea: Jiro Nitta </h3>
      <h3>Author: Yoshio Nabeta </h3>
      <h3>Author: Hiroshi Takano </h3>
      <h3>Genre: Adventure Drama Sports</h3>
      <h3>Published by: Shueisha</h3>
      <h3 style="margin-right: 200px; ">Release Date: 18 April 2008</h3>
  
   

<a href="https://theclimber.club/" target="_blank">
  <button style="background-color: #252323; color: white; padding:  15px 75px; border-radius: 5px; margin-top: 10px;">
    Start reading
  </button>
</a>
</div>
</div>
</div>

<h2>A few words about the author:</h2>
     <style>
    .on {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1200px;
      margin: 0 auto;
    }

    .textor {
      flex: 1;
      padding: 20px;
      font-size: 25px;
    }

    .imagete {
      flex: 1;
      padding: 20px;
      text-align: left; 
    }

  </style>
</head>
<body>

  <div class="on">
    <div class="textor">
      <h2 style="color: red;">Shin-ichi Sakamoto</h2>
     <p>Shin-ichi Sakamoto is a Japanese manga artist known for his detailed and expressive art style. He gained recognition with works like Innocent and Innocent Rouge, which focus on historical themes and complex characters. Sakamoto’s storytelling is praised for its emotional depth and striking visuals.</p>

    </div>
    <div class="imagete">
      <img src="shinichi.jpg" style="height:300px ;width: 260px; margin: 0;">
    </div>
  </div>
  <div class="on">
    <div class="textor">
      <h2 style="color: red;">Jiro Nitta</h2>
     <p>Jiro Nitta (born 1912, died 1980) was a Japanese writer known for his historical novels and mountain literature. His works often combined historical events with the dramatic power of nature. Many of his stories focused on mountain expeditions and figures from the Meiji era. One of his most famous works is Death March on the Ice Field (Hakkōda-san), which tells the story of a tragic 1902 military expedition in the snow-covered Hakkōda Mountains.</p>

    </div>
    <div class="imagete">
      <img src="rg1W2_5c.jpg" style="height:300px ;width: 230px; margin: 0;">
    </div>
  </div>
  <div class="on">
    <div class="textor">
      <h2 style="color: red;">Yoshio Nabeta</h2>
     <p>Yoshio Nabeta is a Japanese writer and manga scriptwriter, best known for The Climber (Kokō no Hito), a story about a solitary mountain climber. He also wrote biographical manga such as The LKY Story about Lee Kuan Yew. His work often explores themes of solitude, perseverance, and personal transformation.</p>

    </div>
    <div class="imagete">
      <img src="nabeta_yoshio_1.jpg" style="height:330px ;width: 230px; margin: 0;">
    </div>
  </div>
  <div class="on">
    <div class="textor">
      <h2 style="color: red;">Hiroshi Takano</h2>
     <p>Hiroshi Takano (born 1964) is a Japanese singer-songwriter and producer known for blending pop, rock, and funk. Since the 1980s, he has released many albums featuring smooth vocals, catchy melodies, and thoughtful lyrics. He also collaborates with other artists and is respected for his work as a producer and arranger.
</p>

    </div>
    <div class="imagete">
      <img src="1517-1475939223.jpg" style="height:310px ;width: 230px; margin: 0;">
    </div>
  </div>

      
    <h2 class="fade-in" style="color: white;" id="vinlandsaga">1.Vinland Saga</h2>
    <h2 style="color: gray; text-align: center; ">Status: Ongoing</h2><br>
    <img src="nfHU4l8.png" style="height: 350px; width: 600px;"><br>
    <blockquote class="fancy-quote"  >"You have no enemies"</blockquote>
    <h3 >Vinland Saga is a Japanese manga series written and illustrated by Makoto Yukimura. The series is published by Kodansha, and was first serialized in the boys-targeted manga magazine Weekly Shōnen Magazine before moving to Monthly Afternoon, aimed at young adult men. As of June 2024, its chapters have been collected in 28 tankōbon volumes. Vinland Saga has been licensed for English-language publication by Kodansha USA. The story is a dramatization of the story of Thorfinn Karlsefni and his expedition to find Vinland, with the majority of the story covering his fictional counterpart's transition from a bloodthirsty, revenge-filled teenager into a pacifistic young man.</h3>
    <hr style="width: 100%; border: 1px solid rgb(255, 255, 255);">


    <style>
      .container {
        display: flex;
        align-items: center;
      }
      .container img {
        width: 200px; 
        margin-right: 40px;
        
      }
      .text {
        max-width: 600px;
       
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="sekcja-ciekawostka-obrazek">
        <div class="tekst-ciekawostki">
          <h3> Did you know that...</h3>
          <p>The protagonist Thorfinn is based on Thorfinn Karlsefni, a real Icelandic explorer who attempted to colonize North America.

            Several characters, like Leif Erikson, Canute, and Thorkell, are also based on historical figures from Viking sagas. </p>
        </div>
        <img src="vinland saga.jpg" alt="JoJo Bizarre Adventure" class="obrazek-ciekawostka">
      </div>
 <style>
 .sekcja-ciekawostka-obrazek {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 30px;
  padding: 30px;
  background-color: #1c1c1c;
  color: white;
  border-radius: 16px;
  max-width: 600px;
  margin: 40px auto;
  flex-wrap: wrap;
}

.tekst-ciekawostki {
  flex: 1;
  min-width: 300px;
}

.tekst-ciekawostki h3 {
  margin-bottom: 10px;
  color: #ff3366;
}

.tekst-ciekawostki p {
  font-size: 1.1em;
  line-height: 1.6;
}

.obrazek-ciekawostka {
  flex: 1;
  max-width: 400px;
  border-radius: 12px;
  width: 100%;
  height: auto;
}
</style>
<div class="text" style="padding-left: 20px; max-width: 600px; text-align:left;">
  <h2 style="color: red;margin-right: 200px">Vinland Saga</h2>
  <h3 >Autor: Makoto Yukimura </h3>
  <h3>Genre: Adventure Epic Historica</h3>
  <h3>Published by: Kodansha</h3>
  <h3 style="margin-right: 200px; ">Release Date: October 19, 2005.</h3>


 

<a href="https://vinlandsaga.site/" target="_blank">
  <button style="background-color: #252323; color: white; padding:  15px 75px; border-radius: 5px; margin-top: 10px;">
    Start reading
  </button>
</a>
</div>
</div>

<h2>A few words about the author:</h2>
     <style>
    .on {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1200px;
      margin: 0 auto;
    }

    .textor {
      flex: 1;
      padding: 20px;
      font-size: 25px;
    }

    .imagete {
      flex: 1;
      padding: 20px;
      text-align: left; 
    }

  </style>
</head>
<body>

  <div class="on">
    <div class="textor">
      <h2 style="color: red;">Makoto Yukimura</h2>
     <p>Makoto Yukimura is a Japanese manga artist born in 1976. He is best known for creating Vinland Saga, a historical manga about Vikings that combines action, drama, and deep character development. Yukimura’s work is praised for its detailed artwork and compelling storytelling.</p>

    </div>
    <div class="imagete">
      <img src="n97034-MZ2ExmRHhXtb.png" style="height:300px ;width: 200px; margin: 0;">
    </div>
  </div>

  <h2>Anime Adaptation:</h2>
<style>
    .cont {
      display: flex;
      align-items: center;
      max-width: 1100px;
      margin: 20px auto;
      gap: 20px;
    }
    .textop {
      flex: 1;
      font-family: Arial, sans-serif;
      line-height: 1.5;
    }
    .imagekol {
      flex: 1;
      text-align: right;
    }
    .image img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
  </style>
</head>
<body>

  <div class="cont">
    <div class="textop">
      <h2 style="font-size: 30px;">Vinland Saga Anime Adaptation</h2>
      <p style="font-size: 20px;">
        Vinland Saga, created by Makoto Yukimura, is a historical manga that was adapted into an anime in 2019. The anime was produced by Wit Studio and consists of 24 episodes in its first season. <br><br>

The story is set in the Viking Age and follows Thorfinn, a young warrior seeking revenge for his father’s death while facing the harsh realities of war, loyalty, and honor. The series is praised for its detailed historical setting, complex characters, and intense action scenes. <br><br>

Vinland Saga has been acclaimed for its storytelling, animation quality, and emotional depth, making it a standout historical anime.
      </p>
    </div>
    <div class="imagekol">
      <img style="width:300px ; height:400px ;" src="aV5BNDA3MGNmZTEtMzFiMy00ZmViLThhNmQtMjQ4ZDc5MDEyN2U1XkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg" />
    </div>
  </div>
</body>
</html>
 
     
