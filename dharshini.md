# 

<!DOCTYPE html>

<html lang="en">

<head>

&nbsp; <meta charset="UTF-8" />

&nbsp; <meta name="viewport" content="width=device-width, initial-scale=1.0" />

&nbsp; <title>Simple Web Page</title>



&nbsp; <style>

&nbsp;   body {

&nbsp;     font-family: Arial, sans-serif;

&nbsp;     margin: 0;

&nbsp;     padding: 0;

&nbsp;     background-color: #f4f4f4;

&nbsp;   }



&nbsp;   header {

&nbsp;     background: #333;

&nbsp;     color: white;

&nbsp;     padding: 15px;

&nbsp;     text-align: center;

&nbsp;   }



&nbsp;   nav {

&nbsp;     background: #444;

&nbsp;     padding: 10px;

&nbsp;     text-align: center;

&nbsp;   }



&nbsp;   nav a {

&nbsp;     color: white;

&nbsp;     text-decoration: none;

&nbsp;     margin: 0 15px;

&nbsp;   }



&nbsp;   .container {

&nbsp;     padding: 40px;

&nbsp;     text-align: center;

&nbsp;   }



&nbsp;   .btn {

&nbsp;     background: #007bff;

&nbsp;     color: white;

&nbsp;     padding: 12px 20px;

&nbsp;     border: none;

&nbsp;     border-radius: 5px;

&nbsp;     cursor: pointer;

&nbsp;   }



&nbsp;   .btn:hover {

&nbsp;     background: #0056b3;

&nbsp;   }



&nbsp;   footer {

&nbsp;     background: #333;

&nbsp;     color: white;

&nbsp;     text-align: center;

&nbsp;     padding: 10px;

&nbsp;     position: fixed;

&nbsp;     bottom: 0;

&nbsp;     width: 100%;

&nbsp;   }

&nbsp; </style>

</head>



<body>



&nbsp; <header>

&nbsp;   <h1>My Website</h1>

&nbsp; </header>



&nbsp; <nav>

&nbsp;   <a href="#">Home</a>

&nbsp;   <a href="#">About</a>

&nbsp;   <a href="#">Contact</a>

&nbsp; </nav>



&nbsp; <div class="container">

&nbsp;   <h2>Welcome!</h2>

&nbsp;   <p>This is a simple HTML webpage example.</p>



&nbsp;   <button class="btn" onclick="showMessage()">

&nbsp;     Click Me

&nbsp;   </button>

&nbsp; </div>



&nbsp; <footer>

&nbsp;   <p>\&copy; 2026 My Website</p>

&nbsp; </footer>



&nbsp; <script>

&nbsp;   function showMessage() {

&nbsp;     alert("Hello! Welcome to the website.");

&nbsp;   }

&nbsp; </script>



</body>

</html>



