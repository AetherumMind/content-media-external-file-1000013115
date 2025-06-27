<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>FireGate Lions Tree</title>
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background: linear-gradient(to bottom, #000000, #1a1a1a);
      color: #ffd700;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      overflow: hidden;
    }
    h1 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }
    .video-container {
      width: 90%;
      max-width: 720px;
      border: 2px solid #ffd700;
      border-radius: 12px;
      overflow: hidden;
    }
    .audio-hidden {
      display: none;
    }
  </style>
</head>
<body>
  <h1>🦁 FireGate Access Granted</h1>
  <div class="video-container">
    <video width="100%" controls autoplay muted loop>
      <source src="./video/lion_firegate_trees.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
  <audio class="audio-hidden" autoplay loop>
    <source src="./public/audio/blessing_whisper_locked.mp3" type="audio/mp3">
    Your browser does not support the audio element.
  </audio>
</body>
</html>