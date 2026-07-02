<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>画像</title>
  
  <style>
    /* 全体をくくる箱の基準設定 */
    .container {
      position: relative;
      display: inline-block; /* 背景画像のサイズに合わせる */
    }

    /* 背景画像 */
    .bg-img {
      display: block;
      width: 100%;       /* 横幅いっぱいに広げる */
      max-width: 700px;  /* 大きくなりすぎないように制限（お好みで変更可） */
      height: auto;
    }

    /* メッセージ（文字）を左上に重ねる */
    .message {
      position: absolute;
      top: 30px;         /* 上からの位置 */
      left: 30px;        /* 左からの位置 */
      color: #d14d64;    /* 見本に近い少し濃いピンク・赤系の色 */
      font-weight: bold;
      font-size: 18px;   /* 文字の大きさ */
      line-height: 1.6;  /* 行間 */
    }

    /* 蝶の画像を配置する共通設定 */
    .butterfly {
      position: absolute;
      width: 50px;       /* 蝶のサイズ（お好みで調整してください） */
    }

    /* 1匹目の蝶の位置 */
    .butterfly-1 {
      top: 65%;          /* 上から 65% の位置 */
      left: 25%;         /* 左から 25% の位置 */
    }

    /* 2匹目の蝶の位置 */
    .butterfly-2 {
      top: 55%;          /* 上から 55% の位置 */
      left: 42%;         /* 左から 42% の位置 */
    }
  </style>
</head>
<body>

  <div class="container">
    
    <img src="./bg0.png" alt="花畑の朝" class="bg-img">
    
    <div class="message">
      ぽかぽか陽気の穏やかな朝<br>
      花畑では、蝶々がのんびり飛んでいます
    </div>
    
    <img src="./butterfly.png" alt="蝶々1" class="butterfly butterfly-1">
    <img src="./butterfly.png" alt="蝶々2" class="butterfly butterfly-2">

  </div>

</body>
</html>
