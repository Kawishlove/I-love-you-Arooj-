# I-love-you-Arooj-
<!DOCTYPE html>
<html>
<head>
<title>Valentine ❤️</title>
<style>
body { text-align:center; font-family:Arial; background: pink; height:100vh; display:flex; flex-direction:column; justify-content:center; align-items:center; padding:20px; }
button { padding:15px 30px; margin:10px; font-size:22px; border:none; border-radius:25px; cursor:pointer; }
#yes{background:red;color:white;} #no{background:white;color:red;}
p { font-size:20px; color:white; margin-top:30px; }
</style>
</head>
<body>

<h1>Will you be my Valentine? ❤️</h1>
<button id="yes">Yes ❤️</button>
<button id="no">No 💔</button>

<script>
yes.onclick = () => {
  document.body.innerHTML = `
    <h1>She is My Wife Now! 🥰💖</h1>
    <p>
      From the moment I met you, I knew you were the one.  
      You make every day brighter, every moment sweeter.  
      Today, I promise to cherish you forever.  
      My heart is yours, my love is yours… welcome to our life together. 💘
    </p>
  `;
}

no.onclick = () => {
  const no = document.getElementById('no');
  no.style.position='absolute';
  no.style.left=Math.random()*(window.innerWidth-100)+'px';
  no.style.top=Math.random()*(window.innerHeight-50)+'px';
};
</script>

</body>
</html>
