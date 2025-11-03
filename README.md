# Surprise-for-you
It is just a surprise
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Will You Be Mine?</title>
  <style>
    body {
      background: linear-gradient(to right, #ffb6c1, #f8b195);
      font-family: 'Dancing Script', cursive;
      text-align: center;
      color: #fff;
      padding-top: 10vh;
    }
    h1 {
      font-size: 3em;
      margin-top: 2em;
    }
    p {
      font-size: 1.5em;
      margin: 2em auto;
      width: 60vw;
    }
    button {
      background: #f67280;
      color: #fff;
      font-size: 1.4em;
      border: none;
      border-radius: 30px;
      padding: 1em 2em;
      cursor: pointer;
      margin: 2em 0;
      transition: background 0.3s;
    }
    button:hover {
      background: #c06c84;
    }
  </style>
</head>
<body>
  <h1>Hey [Her Name],</h1>
  <p>
    I've liked you for a long time and couldn't hold these feelings anymore. You make my world brighter and happier. Will you be my girlfriend? ❤️
  </p>
  <button onclick="showAnswer()">Yes!</button>
  <button onclick="showAnswerNo()">No...</button>
  <script>
    function showAnswer() {
      alert("Thank you! You just made me the happiest person alive! 🥰");
    }
    function showAnswerNo() {
      alert("That's okay, I just wanted you to know how special you are to me.");
    }
  </script>
</body>
</html>
