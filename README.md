<html>
<head>
  <title>My Webpage</title>
  <style>
    body {
      background-color: #ffffff;
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
    }
    .navigation {
      background-color: #2f2f32;
      overflow: hidden;
    }
    .navigation a {
      float: left;
      color: #ffffff;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
      font-weight: bold;
    }
    .navigation a:hover {
      background-color: #505760be;
    }

    .container {
     position: relative;
    }

   .center {
     position: absolute;
     top: 50%;
     left: 50%;
     transform: translate(-50%, -50%);
     font-size: 50px;
    }

    img { 
     width: 100%;
     height: auto;
     opacity: 0.5;
    }
    
    .content {
      background-color: #fff;
      padding: 20px;
    }
    h1 {
      text-align: center;
      font-size: 30px;
      color: #333;
      margin-top: 0;
    }

    h2 {
        text-align: center;
    }
    p {
        text-align: center;
        font-family: 'Arial', sans-serif;
        margin-left: 10;
        color: #555;

    }
    .article-link img {
      display: block;
      margin: 0 auto;
      width: 700px;
      height: 350px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 5px;
      opacity: 1;
    }
    .footer {
      background-color: #f5f8fa;
      color: #777;
      padding: 10px;
      text-align: center;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <div class="navigation">
    <a href="#home">HOME</a>
    <a href="#article1">ARTICLE 1</a>
    <a href="#article2">ARTICLE 2</a>
    <a href="#article3">ARTICLE 3</a>
    <a href="#report">REPORT</a>
  </div>

  <div class="container">
    <img src="music.jpg" alt="music" width="1000" height="300">
    <div class="center">TITLE</div>
  </div>

  <div class="content">
    <h2>Title</h2>
    <p>aggiungi intro.</p>
    <a href="#article1" class="article-link"><img src="picture.jpg" alt="Article 1"></a>
    <a href="#article2" class="article-link"><img src="females.jpg" alt="Article 2"></a>
    <a href="#article3" class="article-link"><img src="image3.jpg" alt="Article 3"></a>
  </div>

  <div class="footer">
    All rights reserved to My Webpage
  </div>
</body>
</html>
