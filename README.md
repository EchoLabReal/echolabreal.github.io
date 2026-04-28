<!DOCTYPE html>
<html>
<head>
  <title>Min sjove side 😂</title>

  <style>
    body {
      background-color: black;
      color: lime;
      text-align: center;
      font-family: Arial;
    }

    button {
      padding: 10px;
      font-size: 18px;
      margin-top: 20px;
      cursor: pointer;
    }
  </style>
</head>

<body>

  <h1>😂 Velkommen til min sjove hjemmeside 😂</h1>

  <p>Klik på knappen hvis du tør...</p>

  <button onclick="skræm()">Klik mig 😈</button>

  <h2 id="tekst"></h2>

  <script>
    function skræm() {
      document.body.style.backgroundColor = "red";
      document.getElementById("tekst").innerText = "BOOO! 👻😂";
    }
  </script>

</body>
</html>
