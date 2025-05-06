<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hacker Login</title>
  <style>
    body {
      background-color: black;
      color: #00ff00;
      font-family: 'Courier New', Courier, monospace;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .login-container {
      border: 2px solid #00ff00;
      padding: 30px;
      width: 300px;
      text-align: center;
    }
    input[type="text"],
    input[type="password"] {
      background-color: black;
      color: #00ff00;
      border: 1px solid #00ff00;
      padding: 10px;
      width: 100%;
      margin-bottom: 15px;
    }
    input[type="submit"] {
      background-color: black;
      color: #00ff00;
      border: 1px solid #00ff00;
      padding: 10px;
      width: 100%;
      cursor: pointer;
    }
    input[type="submit"]:hover {
      background-color: #00ff00;
      color: black;
    }
    h2 {
      margin-bottom: 20px;
    }
  </style>
</head>
<body>
  <div class="login-container">
    <h2>Access Terminal</h2>
    <form>
      <input type="text" placeholder="Username" required />
      <input type="password" placeholder="Password" required />
      <input type="submit" value="LOGIN" />
    </form>
  </div>
</body>
</html>
