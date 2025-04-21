<!DOCTYPE html>
<html lang="id">
<head> SELAMAT DATANG
  <meta charset="UTF-8">
  <title>PAWANG PETIR</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
      background-color: #fffdf5;
    }

    h1 {
      color: crimson;
    }

    label {
      color: darkblue;
      font-weight: bold;
    }

    input, button {
      padding: 10px;
      font-size: 16px;
      margin-top: 10px;
    }

    button {
      background-color: darkorange;
      color: white;
      border: none;
      cursor: pointer;
    }

    button:hover {
      background-color: orangered;
    }

    #output {
      margin-top: 20px;
      font-weight: bold;
      color: green;
    }
  </style>
</head>
<body>

  <h1>Mbah Petir - Pestawin</h1>

  <label for="id">💥 Cheat Perkalian 1000:</label><br>
  <input type="text" id="Kuro" placeholder="Ketik user ID di sini">
  <button onclick="tampilkanNama()">AKTIFKAN</button>
  <div id="output"></div>
  <a href="https://pyw.maxrtpnew.com/index_2.html" target="_blank">
    <button>PLAY NOW</button>
  </a>

  <script>
    function tampilkanNama() {
      const nama = document.getElementById('Kuro').value;
      const output = document.getElementById('output');

      if (nama.trim() === "") {
        output.textContent = "⚠️ Silakan isi user ID terlebih dahulu.";
      } else {
        output.textContent = `🔥 Cheat aktif untuk user ID: ${nama}`;
      }
    }
  </script>

</body>
</html>
