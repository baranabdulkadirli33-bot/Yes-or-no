<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>Benimle randevuya çıkar mısın?</title>
  <style>
    body { background: #fafafa; font-family: Arial, sans-serif; text-align: center; padding-top: 100px;}
    .btn { padding: 12px 30px; margin: 20px; font-size: 20px; cursor: pointer; border-radius: 8px; border: none; }
    .yes { background: #9be7a2; }
    .no { background: #e79b9b; }
    #result { font-size: 28px; margin-top: 40px; color: #444; }
  </style>
</head>
<body>
  <h1>Kız arkadaşım, benimle randevuya çıkar mısın?</h1>
  <button class="btn yes" onclick="evet()">Evet</button>
  <button class="btn no" onclick="hayir()">Hayır</button>
  <div id="result"></div>

  <script>
    function evet() {
        document.getElementById('result').innerText = "Çok mutluyum! 🎉";
    }
    function hayir() {
        document.getElementById('result').innerText = "Hayır dedi ve kaçtı! 🏃‍♀️";
    }
  </script>
</body>
</html>
