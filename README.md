<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <title>Aman | My Page</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      max-width: 800px;
      margin: 40px auto;
      padding: 0 20px;
      background-color: #f4f4f9;
      color: #333;
    }
    h1 { text-align: center; color: #2c3e50; }
    h2 {
      color: #2c3e50;
      border-bottom: 2px solid #3498db;
      padding-bottom: 10px;
      margin-top: 30px;
    }
    ul { list-style-type: none; padding: 0; }
    li {
      margin-bottom: 10px;
      padding: 12px;
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    /* Контейнер для адаптивности видео */
    .video-responsive {
      position: relative;
      padding-bottom: 56.25%; 
      height: 0;
      overflow: hidden;
      margin: 20px 0;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
    }
    .video-responsive iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      border: 0;
    }
  </style>
</head>
<body>

  <h1>Welcome to Aman's Page</h1>

  <h2>My Hobbies</h2>
  <ul>
    <li>📺 <b>Anime:</b> Watch anime (Isekai)</li>
    <li>🌅 <b>Nature:</b> Watch the sunset</li>
    <li>🎮 <b>Gaming:</b> Mobile Legends, Roblox TDS, Minecraft</li>
  </ul>

  <h2>Favorite Media</h2>
  <ul>
    <li>🎬 <b>Top Anime:</b> Tensei Shitara Slime Datta Ken</li>
    <li>🕹️ <b>Current Game:</b> Cyberpunk 2077</li>
    <li>🎵 <b>Best Song:</b> PXLAP - Unforgettable</li>
  </ul>

  <h2>Atmosphere</h2>
  <div class="video-responsive">
    <iframe 
      src="https://www.youtube-nocookie.com/embed/0Lk-Dvxuyc0?si=lc4zAMC7utIwRzWb&amp;controls=0" 
      title="YouTube video player" 
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
      referrerpolicy="strict-origin-when-cross-origin" 
      allowfullscreen>
    </iframe>
  </div>

  <h2>Recommended Video</h2>
  <div class="video-responsive">
    <iframe 
      src="https://www.youtube-nocookie.com/embed/dQw4w9WgXcQ?si=owP5YXXEfHhDpuyj&amp;start=42" 
      title="YouTube video player" 
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
      referrerpolicy="strict-origin-when-cross-origin" 
      allowfullscreen>
    </iframe>
  </div>

</body>
</html>
