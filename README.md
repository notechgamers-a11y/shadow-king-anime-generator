# shadow-king-anime-generator
/body

<section style="background:#17172b;padding:20px;border-radius:15px;margin-top:25px;color:white">
  <h2 style="color:#b58cff;text-align:center">⚔️ SHADOW KING ANIME CREATOR</h2>

  <h3>1. Anime Story Generator</h3>
  <input id="hero" placeholder="Hero name" value="Peter">
  <input id="anime" placeholder="Anime name" value="SHADOW KING">
  <button onclick="makeStory()">Generate Anime Story</button>
  <div id="story" style="white-space:pre-wrap"></div>

  <h3>2. Scene Generator</h3>
  <input id="episode" type="number" min="1" value="1" placeholder="Episode number">
  <button onclick="makeScenes()">Generate Scenes</button>
  <div id="scenes" style="white-space:pre-wrap"></div>
</section>

<script>
function makeStory(){
 const hero=document.getElementById("hero").value || "Peter";
 const anime=document.getElementById("anime").value || "SHADOW KING";
 document.getElementById("story").textContent=
 `${anime}\n\nEpisode 1: The Awakening\n\n`+
 `${hero} ek mysterious duniya mein jagta hai. `+
 `Usse pata chalta hai ki uske andar ek ancient shadow power chhupi hai. `+
 `Ek mysterious system uske saamne appear hota hai.\n\n`+
 `System: Welcome, Shadow King.\n`+
 `${hero}: Ye sab kya ho raha hai?\n`+
 `System: Your journey begins now.`;
}
function makeScenes(){
 const ep=document.getElementById("episode").value || 1;
 const hero=document.getElementById("hero").value || "Peter";
 document.getElementById("scenes").textContent=
 `EPISODE ${ep}\n\n`+
 `Scene 1: Dark fantasy world introduction.\n`+
 `Scene 2: ${hero} enters a mysterious dungeon.\n`+
 `Scene 3: A mysterious shadow system appears.\n`+
 `Scene 4: ${hero} discovers his hidden power.\n`+
 `Scene 5: Cinematic cliffhanger ending.\n\n`+
 `Har scene ke liye alag image aur animation create karo.`;
}
</script>

