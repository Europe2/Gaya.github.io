# Gaya.github.io
<!doctype html>
<html lang="fr">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>MASTER ZONE</title>
<link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&family=VT323&display=swap" rel="stylesheet">
<style>
:root{--yellow:#ffdf4d}
*{box-sizing:border-box}
body{margin:0;font-family:'Share Tech Mono';background:linear-gradient(135deg,#fff3c0,#ffd34d);height:100vh;display:flex;align-items:center;justify-content:center;color:#111}
.container{width:720px;max-width:94vw;padding:28px;border-radius:18px;background:rgba(255,255,255,0.9);box-shadow:0 18px 40px rgba(0,0,0,0.12);text-align:center}
.title{font-family:'VT323';font-size:48px;letter-spacing:6px;margin-bottom:6px}
.welcome{margin-bottom:18px; font-size:16px}
.icons{display:flex;gap:18px;justify-content:center;flex-wrap:wrap}
.icon{width:100px;height:100px;border-radius:16px;display:flex;align-items:center;justify-content:center;font-weight:700;cursor:pointer;transition:transform .18s}
.icon:hover{transform:translateY(-8px)}
.fb{background:linear-gradient(180deg,#3b5998,#2d4373);color:white}
.ig{background:linear-gradient(180deg,#feda75,#d62976);color:#111}
.tt{background:linear-gradient(180deg,#25f4ee,#1da1f2);color:#071028}
.sc{background:linear-gradient(180deg,#fffc00,#ff8c00);color:#111}
.wa{background:linear-gradient(180deg,#25D366,#128C7E);color:white}
.back{display:inline-block;margin-top:18px;padding:12px 16px;background:#111;color:var(--yellow);border-radius:12px;cursor:pointer}
</style>
</head>
<body>
<div class="container">
  <div class="title">MASTER ZONE</div>
  <div class="welcome">Bienvenue dans le réseau Master Zone — connectez-vous avec nos réseaux.</div>
  <div class="icons">
    <a class="icon fb" href="#" title="Facebook">FACEBOOK</a>
    <a class="icon ig" href="#" title="Instagram">INSTAGRAM</a>
    <a class="icon tt" href="#" title="TikTok">TIKTOK</a>
    <a class="icon sc" href="#" title="Snapchat">SNAPCHAT</a>
    <a class="icon wa" href="#" title="WhatsApp">WHATSAPP</a>
  </div>
  <div><span class="back" id="back">Retour à MASTEX</span></div>
</div>

<script>
document.getElementById('back').addEventListener('click', function(){ window.location.href = 'index.html'; });

// small animated halo effect
(function(){
  const el = document.querySelector('.container');
  let t = 0;
  setInterval(()=>{ t+=0.03; el.style.boxShadow = `0 18px 40px rgba(0,0,0,0.12), 0 0 120px rgba(255,223,77,${0.06+0.04*Math.sin(t)})`; },40);
})();
</script>
</body>
</html>
