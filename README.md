# for-Wim

<!DOCTYPE html>
<html>
  <head>
    <title>The Whiskey Diet</title>
    <style>
      body {
        background-color: #4b4b4b;
        font-family: Arial, sans-serif;
      }
      .meme {
        position: relative;
        width: 600px;
        height: 600px;
        margin: auto;
        border: 2px solid black;
        background: linear-gradient(145deg, #ff7979, #ffbe76, #64b5f6, #3dc1d3, #3c40c6);
        background-size: 400% 400%;
        animation: gradient 15s ease infinite;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
      }
      .meme h2 {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        margin: 0;
        padding: 30px;
        font-size: 48px;
        text-align: center;
        color: #fff;
        text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
        border: 3px solid #fff;
      }
      @keyframes gradient {
        0% {
          background-position: 0% 50%;
        }
        50% {
          background-position: 100% 50%;
        }
        100% {
          background-position: 0% 50%;
        }
      }
    </style>
  </head>
  <body>
    <div class="meme">
      <h2>I'm on a whiskey diet. I've lost three days already.</h2>
    </div>
  </body>
</html>
