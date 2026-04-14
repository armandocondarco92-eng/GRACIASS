<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Sorpresa</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: linear-gradient(135deg, #ffdde1, #ee9ca7);
      font-family: Arial, sans-serif;
      flex-direction: column;
    }button {
  padding: 15px 30px;
  font-size: 18px;
  border: none;
  border-radius: 10px;
  background-color: #ff4d6d;
  color: white;
  cursor: pointer;
  transition: 0.3s;
}

button:hover {
  background-color: #e63950;
}

#mensaje {
  margin-top: 20px;
  font-size: 24px;
  display: none;
  color: #333;
  text-align: center;
}

.rosa {
  font-size: 50px;
  margin-top: 10px;
}

  </style>
</head>
<body><button onclick="mostrarMensaje()">Apretá aquí</button>

  <div id="mensaje">
    <p>GRACIAS Jhisel 🫂<br>Una rosita para ti 🌹</p>
    <div class="rosa">🌹</div>
  </div>  <script>
    function mostrarMensaje() {
      document.getElementById('mensaje').style.display = 'block';
    }
  </script></body>
</html>
