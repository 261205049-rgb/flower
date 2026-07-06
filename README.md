<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="utf-8">
  <title>花畑の家と蝶</title>
  <style>
    body {
      margin: 0;
      background-color: #f0f0f0;
      font-family: sans-serif;
    }

    .container {
      position: relative;
      width: 100%;
      max-width: 900px;
      margin: 0 auto;
    }

    .bg {
      width: 100%;
      display: block;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
    }

    .butterfly {
      position: absolute;
      width: 80px;
    }
  </style>
</head>
<body>

  <div class="container">
    <!-- 背景画像（家＋花畑） -->
    <img src="bg0.png" class="bg">

    <!-- 蝶の画像を重ねる -->
    <img src="butterfly.gif" class="butterfly" style="left: 150px; top: 200px;">
    <img src="butterfly.gif" class="butterfly" style="left: 400px; top: 250px;">
    <img src="butterfly.gif" class="butterfly" style="left: 600px; top: 180px;">
  </div>

</body>
</html>

