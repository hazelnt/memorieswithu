# memorieswithu
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>365 days: #vol 1</title>
  <style>
    body {
      font-family: 'Comic Sans MS', cursive;
      background-color: #74a3b7;
      color: #333;
      text-align: center;
      padding: 40px;
    }

    h1 {
      color: #eda0f0;
      font-size: 3em;
    }

    p {
      font-size: 1.4em;
    }

    button {
      padding: 10px 20px;
      background-color: #ff6699;
      color: white;
      border: none;
      border-radius: 8px;
      font-size: 1.2em;
      cursor: pointer;
      margin-top: 20px;
    }

    #surprise-container {
  margin-top: 30px;
  display: flex;
  flex-direction: column; /* ini penting */
  align-items: center;
  gap: 30px; /* jarak antar item */
}


    #surprise-container img {
      width: 200px;
      border-radius: 15px;
      box-shadow: 0 0 10px #ff6699;
    }

    #surprise-container .text {
      font-size: 18px;
      color: #444;
      text-align: left;
      max-width: 400px;
    }
  </style>
</head>

<body>

  <h1>Hai Sayang </h1>
  <p>Ini website kecil aku buat spesial untuk kamu</p>
  <p>Klik tombol di bawah ya!</p>

  <button onclick="showMessage()">Klik Aku</button>

  <div id="surprise-container"></div>

  <script>
  function showMessage() {
  document.getElementById("surprise-container").innerHTML = `
    <div class="item">
      <img src="percobaan2.JPG" alt="Foto Kita Lagi">
      <div class="text">
        <p>
          fine shyt<br>
          hmmzzz
        </p>
      </div>
    </div>
  `;
}

  </script>

</body>
</html>
