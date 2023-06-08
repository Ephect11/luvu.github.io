<!DOCTYPE html>
<html>
<head>
  <title>Love Poem for Sanja</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: Arial, sans-serif;
    }

    #poemContainer {
      text-align: center;
    }

    #poemButton {
      padding: 10px 20px;
      font-size: 20px;
      background-color: #ff69b4;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div id="poemContainer">
    <h1>Love Poem for Sanja</h1>
    <button id="poemButton">Click me :3</button>
    <p id="poemText"></p>
  </div>

  <script>
    const button = document.getElementById('poemButton');
    const poemText = document.getElementById('poemText');

    button.addEventListener('click', () => {
      poemText.textContent = "My dearest Sanja, you are the sunshine in my life, illuminating my world with your love and warmth. Your smile brightens up even the darkest days and your laughter is music to my ears. In your presence, I find comfort and peace, knowing that I am with the one I love unconditionally. Your kindness, compassion, and grace inspire me to be a better person each day. You are the epitome of beauty, both inside and out. I am grateful for every moment we spend together, cherishing the love we share. Forever and always, yours truly.";
    });
  </script>
</body>
</html>
