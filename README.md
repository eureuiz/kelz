<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> hey, cutieeee </title>
  <style>
    body {
      background-color: #fff0f5;
      font-family: 'Arial', sans-serif;
      text-align: center;
      padding: 50px;
      margin: 0;
    }

    h1 {
      color: #ff66b2;
      font-size: 2.5em;
    }

    .message {
      background-color: #ffe6f0;
      border: 2px solid #ff99cc;
      border-radius: 15px;
      padding: 30px;
      margin: 30px auto;
      max-width: 600px;
      font-size: 20px;
      color: #333;
      display: none;
    }

    button {
      background-color: #ff66b2;
      color: white;
      padding: 15px 30px;
      border: none;
      border-radius: 10px;
      font-size: 18px;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background-color: #e60073;
    }
  </style>
</head>
<body>

  <h1>js wanna tell u something</h1>

  <div class="message" id="messageBox">
    i know we've been talking for only 2 weeks, but i just want u to know that i really like you.<br><br>
    hindi ko alam kung pano ko mae-explain sayo nang maayos para maniwala ka.<br><br>
    i like you a loooooot, not just because you're pretty and cute (though you are), but talking to u makes me feel good fr.<br><br>
    i mean, you're pretty, cute, hot nd funny plus ang gaan sa pakiramdam pag kausap kita. <br><br>
   idunno, pero feel ko tayo na para sa isa't isa hindi mo lang maramdaman HAHAAHAHAHAH<br><br>
   fuuckk handa akong sirain body clock ko para sayo cutiee WHAHAHAHAHHAHAHA
    
  </div>

  <button onclick="confess()">Reveal Message</button>

  <script>
    function confess() {
      var box = document.getElementById("messageBox");
      box.style.display = "block";
    }
  </script>

</body>
</html>
