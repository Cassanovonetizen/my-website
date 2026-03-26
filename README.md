<!DOCTYPE html>
<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Register</title>
  <style>
    body {
      font-family: Arial;
      background: #eaf3f8;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .container {
      width: 320px;
      background: white;
      padding: 20px;
      border-radius: 20px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      text-align: center;
    }

    h2 {
      color: #2c7dbf;
    }

    .tabs {
      display: flex;
      justify-content: space-around;
      margin-bottom: 20px;
    }

    .tabs span {
      cursor: pointer;
      padding: 10px;
      color: gray;
    }

    .tabs .active {
      color: #2c7dbf;
      border-bottom: 2px solid #2c7dbf;
    }

    input {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border-radius: 25px;
      border: 1px solid #ccc;
      outline: none;
    }

    button {
      width: 100%;
      padding: 12px;
      border: none;
      border-radius: 25px;
      background: #2c7dbf;
      color: white;
      font-size: 16px;
      cursor: pointer;
    }

    button:hover {
      background: #1f5f94;
    }

    .note {
      font-size: 12px;
      margin-top: 10px;
      color: gray;
    }
  </style>
</head>

<body>

<div class="container">
  <h2>Welcome to My Site</h2>

  <div class="tabs">
    <span>Login</span>
    <span class="active">Register</span>
  </div>

  <input type="text" placeholder="Phone Number">
  <input type="password" placeholder="Password">
  <input type="password" placeholder="Confirm Password">

  <button>Create Account</button>

  <div class="note">
    By registering, you agree to our Terms
  </div>
</div>

</body>
</html>
