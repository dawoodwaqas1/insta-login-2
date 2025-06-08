<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Login</title>
  <style>
    * {
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      margin: 0;
      background-color: #fafafa;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .login-container {
      background: white;
      border: 1px solid #dbdbdb;
      width: 350px;
      padding: 40px;
      text-align: center;
    }

    .login-container h1 {
      font-size: 36px;
      margin-bottom: 30px;
      font-family: 'Segoe UI', sans-serif;
    }

    .input-field {
      width: 100%;
      margin-bottom: 10px;
    }

    .input-field input {
      width: 100%;
      padding: 10px;
      border: 1px solid #dbdbdb;
      border-radius: 3px;
      background: #fafafa;
    }

    .login-button {
      width: 100%;
      padding: 10px;
      background-color: #3897f0;
      color: white;
      border: none;
      border-radius: 4px;
      font-weight: bold;
      margin-top: 10px;
      cursor: pointer;
    }

    .separator {
      margin: 20px 0;
      display: flex;
      align-items: center;
      text-align: center;
    }

    .separator::before,
    .separator::after {
      content: "";
      flex: 1;
      height: 1px;
      background: #dbdbdb;
    }

    .separator span {
      margin: 0 10px;
      font-size: 12px;
      color: #999;
    }

    .signup-box {
      margin-top: 20px;
      font-size: 14px;
    }

    .signup-box a {
      color: #00376b;
      text-decoration: none;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="login-container">
    <h1>Instagram</h1> <!-- Replace with your own app name -->
    <form>
      <div class="input-field">
        <input type="text" placeholder="Phone number, username, or email" required />
      </div>
      <div class="input-field">
        <input type="password" placeholder="Password" required />
      </div>
      <button type="submit" class="login-button">Log In</button>
    </form>

    <div class="separator"><span>OR</span></div>

    <div>
      <a href="#" style="color:#385185; font-weight: bold; text-decoration: none;">Log in with Facebook</a>
    </div>

    <div style="margin-top: 15px;">
      <a href="#" style="font-size: 12px; color: #00376b; text-decoration: none;">Forgot password?</a>
    </div>

    <div class="signup-box">
      Don't have an account? <a href="#">Sign up</a>
    </div>
  </div>
</body>
</html>
