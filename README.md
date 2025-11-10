💰 Make More Money Through Smart Investments
Welcome! This platform is designed to help you grow your wealth safely and efficiently through smart investment opportunities. Whether you’re a beginner or an experienced investor, you’ll find tools, tips, and strategies to maximize your returns.
🚀 Features
Easy Investment Options – Choose from a variety of vetted investment opportunities.
Track Your Growth – Monitor your investments and watch your money grow over time.
Secure & Transparent – All transactions are safe, with full transparency in how your money is managed.
Guides & Tips – Learn how to invest smarter with practical advice and strategies.
📈 How It Works
Sign Up – Create your account in just a few minutes.
Choose Your Plan – Pick an investment plan that suits your goals and budget.
Invest & Grow – Put your money to work and track your earnings.
Withdraw Anytime – Easily access your profits whenever you need.
🌟 Why Choose Us
Reliable and trusted investment platform
Expert advice to maximize returns
Simple and user-friendly interface
⚠️ Important Note
Investing involves risks. Always invest responsibly and only with money you can afford to put at risk. Past performance does not guarantee future results.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #f0f2f5;
    }
    .login-container {
      background-color: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0px 4px 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    input[type="password"] {
      padding: 10px;
      width: 80%;
      margin: 10px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    button {
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      background-color: #007bff;
      color: white;
      cursor: pointer;
    }
    button:hover {
      background-color: #0056b3;
    }
    .error {
      color: red;
      display: none;
    }
  </style>
</head>
<body>
  <div class="login-container">
    <h2>Login</h2>
    <input type="password" id="password" placeholder="Enter password">
    <br>
    <button onclick="checkPassword()">Login</button>
    <p class="error" id="error-msg">Incorrect password. Try again!</p>
  </div>

  <script>
    function checkPassword() {
      const password = document.getElementById('password').value;
      const correctPassword = "1234"; // Change this to your password
      const errorMsg = document.getElementById('error-msg');

      if(password === correctPassword){
        window.location.href = "index.html"; // Redirect to your main page
      } else {
        errorMsg.style.display = "block";
      }
    }
  </script>
</body>
</html>
