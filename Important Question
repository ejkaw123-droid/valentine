<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Valentine 💘</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      background-color: pink;
      text-align: center;
      font-family: Arial, sans-serif;
      height: 100vh;
      margin: 0;
      position: relative;
    }

    h1 {
      margin-top: 100px;
    }

    button {
      font-size: 20px;
      padding: 12px 24px;
      border-radius: 10px;
      border: none;
      position: absolute;
      cursor: pointer;
    }

    #yes {
      background-color: #ff4d6d;
      color: white;
      left: 30%;
      top: 55%;
    }

    #no {
      background-color: white;
      left: 55%;
      top: 55%;
    }
  </style>
</head>

<body>

  <h1 id="question">Will you be my Valentine? 💖</h1>

  <button id="yes" onclick="yesClicked()">Yes 💕</button>
  <button id="no">No 😢</button>

  <script>
    const messages = [
      "Are you sure? 🥺",
      "Think again 😌",
      "I brought chocolate 🍫",
      "My heart is fragile 💔",
      "Last chance 😏❤️"
    ];

    let i = 0;
    const noBtn = document.getElementById("no");
    const question = document.getElementById("question");

    function moveNo() {
      const x = Math.random() * 60 + 10;
      const y = Math.random() * 40 + 40;

      noBtn.style.left = x + "%";
      noBtn.style.top = y + "%";

      question.textContent = messages[i];
      i = (i + 1) % messages.length;
    }

    noBtn.addEventListener("mouseover", moveNo);
    noBtn.addEventListener("touchstart", moveNo);

    function yesClicked() {
      alert("YAY!!! 🥰💖\n\nHappy Valentine’s Day ❤️");
    }
  </script>

</body>
</html>
