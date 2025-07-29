DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Dwi Surya Saputra - Biodata</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@500;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="aurora-background"></div>

  <div class="card">
    <img src="Dwi.jpg" alt="Foto Dwi" />
    <h1>Dwi Surya Saputra</h1>
    <h2>16 Tahun • Programmer</h2>
    <div class="info">
      <p><span class="label">Nama:</span> Dwi Surya Saputra</p>
      <p><span class="label">Umur:</span> 16 Tahun</p>
      <p><span class="label">Profesi:</span> Programmer</p>
      <p><span class="label">Hobi:</span> Ngoding, menggambar, Bermain Game</p>
      <p><span class="label">Motto:</span> “Sukses Itu Pilihan."</p>
    </div>
  </div>

<div class="quotes-box">
  <div class="quote">"Setiap Kekalahan Adalah Sebuah Pelajaran."</div>
  <div class="quote">"Jago Bukan Karena Hoki, Tapi karena Latihan tanpa henti."</div>
  <div class="quote">"Rank Turun Itu Biasa, Tetapi Mental Tetap Harus Juara."</div>
  <div class="quote">"Rank Hanyalah Angka, Skill-Lah Yang Berbicara."</div>
  <div class="quote">"Bintang Hilang Bisa dicari, Mental hilang? Tamatlah kami."</div>
</div>

  <button id="playButton">Putar Musik</button>
  <audio id="bgMusic" loop>
    <source src="music.mp3" type="audio/mp3">
  </audio>
  <script>
    const playButton = document.getElementById('playButton');
    const music = document.getElementById('bgMusic');
    playButton.addEventListener('click', () => {
      if (music.paused) {
        music.play();
        playButton.textContent = 'Pause Musik';
      } else {
        music.pause();
        playButton.textContent = 'Putar Musik';
      }
    });
  </script>
</body>
</html>
