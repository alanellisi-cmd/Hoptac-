# Hoptac

<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>MENU AIMLOCK VIP</title>
  <style>
    body {
      background: black;
      color: cyan;
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 0;
      overflow: hidden;
    }

    .background-code {
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      color: rgba(0, 255, 255, 0.03);
      font-size: 10px;
      font-family: monospace;
      white-space: pre-wrap;
      overflow: hidden;
      z-index: 0;
      pointer-events: none;
      user-select: none;
      padding: 20px;
      line-height: 1.2;
    }

    .background-text {
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%) rotate(0deg);
      font-size: 100px;
      color: rgba(0, 255, 255, 0.05);
      white-space: nowrap;
      z-index: 0;
      animation: rotateText 60s linear infinite;
      user-select: none;
      pointer-events: none;
    }

    @keyframes rotateText {
      0% { transform: translate(-50%, -50%) rotate(0deg); }
      100% { transform: translate(-50%, -50%) rotate(360deg); }
    }

    .container {
      position: relative;
      z-index: 1;
      padding: 40px 20px;
    }

    #passwordScreen, #menuScreen {
      display: none;
    }

    .button {
      background: none;
      border: 2px solid cyan;
      color: cyan;
      padding: 10px 20px;
      margin: 10px auto;
      font-size: 20px;
      display: block;
      border-radius: 10px;
      width: 200px;
      box-shadow: 0 0 8px cyan;
      transition: 0.3s ease;
    }

    .button:hover {
      background: cyan;
      color: black;
      box-shadow: 0 0 20px cyan;
    }

    input[type="password"], input[type="range"] {
      padding: 10px;
      font-size: 18px;
      width: 250px;
      border: 2px solid cyan;
      background: black;
      color: cyan;
      border-radius: 10px;
      margin-top: 20px;
      box-shadow: 0 0 8px cyan;
    }

    .checkbox-group label {
      display: block;
      margin: 10px auto;
      font-size: 18px;
    }

    input[type="checkbox"] {
      transform: scale(1.2);
      margin-right: 10px;
    }

    .slider-container {
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <div class="background-text">AIMLOCK VIP - HOPTACVV</div>
  <pre class="background-code">
`!iaiejx杙Zrngjm窺+rj؛(ק'vZ'rz{pauqﰉax~ƥ{[!)>~+gbWa!4Dح鞵ڙ
+v(קwځy-yhԭy%譫bvrK~)^Jx,)^hrK-Z)~kzZq鞞+)_zj-yz&yz,zwej~)^~)^z*'x...
...(toàn bộ đoạn mã gốc không rút gọn)...
</pre>

  <div class="container" id="passwordScreen" style="display:block;">
    <h2>Nhập mật khẩu để mở menu</h2>
    <input type="password" id="password" placeholder="Mật khẩu...">
    <button class="button" onclick="checkPassword()">Vào menu</button>
  </div>

  <div class="container" id="menuScreen">
    <h1>AIMLOCK VIP</h1>
    <div class="checkbox-group">
      <label><input type="checkbox"> 🔫 AIMLOCK</label>
      <label><input type="checkbox"> 🤖 SHOTBOT</label>
      <label><input type="checkbox"> ⚡ BUFF NHẠY</label>
      <label><input type="checkbox"> 📱 BUFF DEVICE</label>
      <label><input type="checkbox"> 🛡️ AINTIBAN</label>
    </div>

    <div class="slider-container">
      <label for="dpi">🎚️ Chọn DPI: <span id="dpiValue">1200</span></label><br>
      <input type="range" id="dpi" min="400" max="2000" value="1200" oninput="updateDPI()">
    </div>

    <p style="margin-top: 40px;">ADMIN: <b>siudeptrai+jollibeengo2</b></p>
  </div>

  <script>
    function checkPassword() {
      var pass = document.getElementById("password").value;
      if (pass === "ghaodzz") {
        document.getElementById("passwordScreen").style.display = "none";
        document.getElementById("menuScreen").style.display = "block";
      } else {
        alert("Sai mật khẩu!");
      }
    }
    function updateDPI() {
      document.getElementById("dpiValue").innerText = document.getElementById("dpi").value;
    }
  </script>

</body>
</html>
