<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Be My Valentine 💘</title>
  <style>
    body {
      background: #ffe6f0;
      font-family: Arial, sans-serif;
      text-align: center;
      padding-top: 80px;
    }
    h1 {
      color: #ff4d88;
      font-size: 40px;
    }
    p {
      font-size: 20px;
      color: #444;
    }
    button {
      font-size: 20px;
      padding: 12px 25px;
      margin: 15px;
      border: none;
      border-radius: 30px;
      cursor: pointer;
    }
    .yes {
      background-color: #ff4d88;
      color: white;
    }
    .yes:hover {
      background-color: #ff1f66;
    }
  </style>
</head>
<body>

  <h1>Hey you 💕</h1>
  <p>I have a very important question…</p>
  <h1>Will you be my Valentine? 💘</h1>

  <button class="yes" onclick="yesClicked()">Yes 💕</button>
  <button class="yes" onclick="yesClicked()">Of course 😘</button>

  <script>
    function yesClicked() {
      alert("YAY 💖 I knew you'd say yes! I love you 🥰");
    }
  </script>

</body>
</html>
