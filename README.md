# Hoptac-

<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>siudepchai x jollibee ngo2</title>
  <style>
    body {
      background-color: black;
      color: #00ffcc;
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 0;
      padding: 0;
    }
    #loginBox { margin-top: 200px; }
    input[type="password"] {
      padding: 10px;
      font-size: 16px;
      border-radius: 5px;
      border: none;
      outline: none;
      width: 250px;
    }
    button {
      padding: 10px 20px;
      margin-top: 10px;
      border: none;
      background-color: #00ffcc;
      color: black;
      font-weight: bold;
      border-radius: 5px;
      cursor: pointer;
    }
    #content { display: none; margin-top: 50px; }
    .item { margin: 10px 0; font-size: 20px; }
  </style>
</head>
<body>
  <div id="loginBox">
    <h2>Nhập mật khẩu để vào</h2>
    <input type="password" id="password" placeholder="Nhập mật khẩu...">
    <br>
    <button onclick="checkPassword()">Xác nhận</button>
    <p id="msg"></p>
  </div>

  <div id="content">
    <h2>AIMLOCK VIP</h2>
    <div class="item">✅ AIMLOCK</div>
    <div class="item">✅ SHOTBOT</div>
    <div class="item">✅ BUFF NHẢY</div>
    <div class="item">✅ BUFF DEVICE</div>
    <div class="item">✅ AINTIBAN</div>
    <br>
    <p>⚙️ Chọn DPI: <b>2000</b></p>
    <p>👑 ADMIN: ghaodzz</p>
  </div>

  <script>
    function checkPassword() {
      let pass = document.getElementById("password").value.trim();
      let msg = document.getElementById("msg");
      if (pass === "HOPTACVUIVE") {
        msg.style.color = "lime";
        msg.textContent = "Đúng mật khẩu ✅";
        document.getElementById("loginBox").style.display = "none";
        document.getElementById("content").style.display = "block";
      } else {
        msg.style.color = "red";
        msg.textContent = "Sai mật khẩu ❌";
      }
    }
  </script>
</body>
</html>
