<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <title>Smiley-Button</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin-top: 100px;
    }
    #smiley {
      font-size: 50px;
      margin-top: 20px;
      display: none;
    }
    button {
      font-size: 20px;
      padding: 10px 20px;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <h1>Klick auf den Knopf!</h1>
  <button onclick="zeigeSmiley()">Smiley zeigen</button>
  <div id="smiley">😊</div>

  <script>
    function zeigeSmiley() {
      document.getElementById("smiley").style.display = "block";
    }
  </script>

</body>
</html>

