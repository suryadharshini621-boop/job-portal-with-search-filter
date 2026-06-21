<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Simple Web Page</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }

    header {
      background: #333;
      color: white;
      padding: 15px;
      text-align: center;
    }

    nav {
      background: #444;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
    }

    .container {
      padding: 40px;
      text-align: center;
    }

    .btn {
      background: #007bff;
      color: white;
      padding: 12px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    .btn:hover {
      background: #0056b3;
    }

    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 10px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>

<body>

  <header>
    <h1>My Website</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>

  <div class="container">
    <h2>Welcome!</h2>
    <p>This is a simple HTML webpage example.</p>

    <button class="btn" onclick="showMessage()">
      Click Me
    </button>
  </div>

  <footer>
    <p>&copy; 2026 My Website</p>
  </footer>

  <script>
    function showMessage() {
      alert("Hello! Welcome to the website.");
    }
  </script>

</body>
</html>
