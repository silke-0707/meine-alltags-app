
<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Mein kleiner Alltagszauber</title>
<style>
:root{
 --lila:#e9ddf5;
 --tuerkis:#d9f3ef;
 --schrift:#625575;
}
*{box-sizing:border-box}
body{
 margin:0;
 font-family:Arial,sans-serif;
 color:var(--schrift);
 background:linear-gradient(145deg,#e3f8f4,#f5eafa);
 min-height:100vh;
}
main{max-width:760px;margin:auto;padding:18px}
header{text-align:center;padding:18px 0}
h1{font:italic 30px Georgia,serif;margin:10px 0}
h2{font-size:17px;margin:0 0 15px}
p{line-height:1.5}
.calla{width:135px;height:150px}
.karte{
 background:#ffffffd9;
 border-radius:24px;
 padding:21px;
 margin:14px 0;
 box-shadow:0 5px 22px #77668812;
}
.zeile{
 display:flex;gap:10px;align-items:center;
 flex-wrap:wrap;
}
button{
 border:0;border-radius:14px;
 padding:10px 14px;
 background:var(--lila);
 color:var(--schrift);
 cursor:pointer;
}
button:active{transform:scale(.97)}
input,textarea{
 font:inherit;color:inherit;
 border:1px solid #e4ddea;
 border-radius:13px;padding:11px;
 background:#fff;
}
input[type=text]{flex:1;min-width:120px}
input[type=date]{max-width:190px}
textarea{width:100%;min-height:150px;resize:vertical}
.stimmung{display:flex;justify-content:space-between;gap:5px}
.stimmung button{font-size:23px;padding:10px}
.aktiv{background:#c8eee7!important}
.temperaturen{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-top:15px}
.temp{padding:15px;border-radius:18px;text-align:center}
.temp input{width:85px;margin-top:8px}
.tagtemp{background:#e3f6f2}
.nachttemp{background:#f0e7f8}
details summary{
 cursor:pointer;
 font-weight:bold;
 padding:7px 0;
 list-style:none;
}
details summary:after{content:"⌄";float:right}
details[open] summary:after{content:"⌃"}
.inhalt{padding-top:15px}
.eintrag{padding:10px 0;border-bottom:1px solid #eee7f2}
.eintrag button{float:right;padding:4px 9px}
footer{text-align:center;padding:22px;font:italic 15px Georgia,serif}
small{color:#897b95}
</style>
</head>
<body>
<main>
<header>
<svg class="calla" viewBox="0 0 140 160" xmlns="http://www.w3.org/2000/svg">
<path d="M72 150 Q68 100 84 51" fill="none" stroke="#78b4a2" stroke-width="4"/>
<path d="M71 123 Q28 112 25 82 Q64 88 71 123" fill="#b4d9c9"/>
<path d="M77 98 Q113 92 119 70 Q88 72 77 98" fill="#9acbb8"/>
<path d="M84 68 C40 52 45 5 91 12 C123 15 127 49 84 68Z" fill="#fff" stroke="#d8c7e7" stroke-width="2"/>
<path d="M84 68 Q112 29 91 12 Q98 45 84 68" fill="#e8dcf3"/>
<path d="M84 57 L92 25" stroke="#e9bf62" stroke-width="6" stroke-linecap="round"/>
</svg>
<h1>Mein kleiner Alltagszauber</h1>
<p>Ein bisschen Zeit nur für mich 💜</p>
</header>

<section class="karte">
<div class="zeile">
<button onclick="wechsel(-1)">❮</button>
<input type="date" id="datum">
<button onclick="wechsel(1)">❯</button>
<button onclick="heute()">Heute</button>
</div>
<h2 id="tag" style="margin-top:18px"></h2>
<p id="spruch"></p>
</section>

<section class="karte">
<h2>💜 Wie fühle ich mich heute?</h2>
<div class="stimmung" id="stimmung">
<button onclick="wahl('stimmung','😍')">😍</button>
<button onclick="wahl('stimmung','😊')">😊</button>
<button onclick="wahl('stimmung','😐')">😐</button>
<button onclick="wahl('stimmung','😔')">😔</button>
<button onclick="wahl('stimmung','😴')">😴</button>
</div>
</section>

<section class="karte">
<h2>🌤️ Mein Wetter</h2>
<div class="stimmung" id="wetter">
<button onclick="wahl('wetter','☀️')">☀️</button>
<button onclick="wahl('wetter','⛅')">⛅</button>
<button onclick="wahl('wetter','☁️')">☁️</button>
<button onclick="wahl('wetter','🌧️')">🌧️</button>
<button onclick="wahl('wetter','❄️')">❄️</button>
</div>
<div class="temperaturen">
<div class="temp tagtemp">
☀️ Tag<br>
<input type="number" id="tempTag" placeholder="°C">
</div>
<div class="temp nachttemp">
🌙 Nacht<br>
<input type="number" id="tempNacht" placeholder="°C">
</div>
</div>
<p><small>Automatische Wetterdaten ergänzen wir später.</small></p>
</section>

<section class="karte">
<details>
<summary>🌷 Nicht vergessen</summary>
<div class="inhalt">
<div class="zeile">
<input id="termin" type="text" placeholder="Termin oder Erinnerung">
<button onclick="hinzu('termin')">＋</button>
</div>
<div id="termine"></div>
</div>
</details>
</section>

<section class="karte">
<details>
<summary>📝 Meine To-dos</summary>
<div class="inhalt">
<div class="zeile">
<input id="todo" type="text" placeholder="Was möchte ich erledigen?">
<button onclick="hinzu('todo')">＋</button>
</div>
<div id="todos"></div>
</div>
</details>
</section>

<section class="karte">
<details>
<summary>🎂 Geburtstage</summary>
<div class="inhalt">
<div class="zeile">
<input id="geburtstag" type="text" placeholder="Wer hat Geburtstag?">
<button onclick="hinzu('geburtstag')">＋</button>
</div>
<div id="geburtstage"></div>
</div>
</details>
</section>

<section class="karte">
<details>
<summary>📖 Mein Tagebuch</summary>
<div class="inhalt">
<p>Was hat meinen Tag besonders gemacht?</p>
<textarea id="tagebuch" placeholder="Meine Gedanken..."></textarea>
</div>
</details>
</section>

<footer>🌸 Die kleinen Dinge machen das Leben schön. 💜</footer>
</main>

<script>
const datum=document.getElementById('datum');
const felder=['tempTag','tempNacht','tagebuch'];
const listen={
 termin:'termine',
 todo:'todos',
 geburtstag:'geburtstage'
};
const sprueche=[
 'Auch kleine Schritte bringen dich weiter.',
 'Heute darfst du einfach du selbst sein.',
 'Die kleinen Dinge machen das Leben schön.',
 'Ein neuer Tag, eine neue Möglichkeit.',
 'Schenk dir heute ein Lächeln.'
];
let daten={};

function schluessel(){
 return 'alltag-'+datum.value;
}
function speichern(){
 localStorage.setItem(schluessel(),JSON.stringify(daten));
}
function laden(){
 try{
  daten=JSON.parse(localStorage.getItem(schluessel()))||{};
 }catch(e){daten={};}
 felder.forEach(id=>{
  document.getElementById(id).value=daten[id]||'';
 });
 document.querySelectorAll('.stimmung button').forEach(b=>{
  const art=b.parentElement.id;
  b.classList.toggle('aktiv',b.textContent===daten[art]);
 });
 Object.keys(listen).forEach(anzeigen);
 const d=new Date(datum.value+'T12:00:00');
 document.getElementById('tag').textContent=
 d.toLocaleDateString('de-DE',{
 weekday:'long',day:'numeric',month:'long',year:'numeric'
 });
 const nummer=Math.floor(d.getTime()/86400000);
 document.getElementById('spruch').textContent=
 '✨ '+sprueche[Math.abs(nummer)%sprueche.length];
}
function wahl(art,wert){
 daten[art]=wert;
 speichern();
 laden();
}
function hinzu(art){
 const feld=document.getElementById(art);
 const wert=feld.value.trim();
 if(!wert)return;
 if(!Array.isArray(daten[art]))daten[art]=[];
 daten[art].push(wert);
 feld.value='';
 speichern();
 anzeigen(art);
}
function entfernen(art,index){
 daten[art].splice(index,1);
 speichern();
 anzeigen(art);
}
function anzeigen(art){
 const ziel=document.getElementById(listen[art]);
 ziel.replaceChildren();
 (daten[art]||[]).forEach((wert,index)=>{
  const zeile=document.createElement('div');
  zeile.className='eintrag';
  const text=document.createElement('span');
  text.textContent='• '+wert;
  const knopf=document.createElement('button');
  knopf.textContent='✕';
  knopf.onclick=()=>entfernen(art,index);
  zeile.append(text,knopf);
  ziel.append(zeile);
 });
}
function wechselnDatum(d){
 datum.value=d.toLocaleDateString('sv-SE');
 laden();
}
function wechsel(tage){
 const d=new Date(datum.value+'T12:00:00');
 d.setDate(d.getDate()+tage);
 wechselnDatum(d);
}
function heute(){wechselnDatum(new Date())}
datum.addEventListener('change',laden);
felder.forEach(id=>{
 document.getElementById(id).addEventListener('input',e=>{
  daten[id]=e.target.value;
  speichern();
 });
});
heute();
</script>
</body>
</html>
