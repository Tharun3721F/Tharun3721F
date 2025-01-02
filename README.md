
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Presidency College Results</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin-top: 20%;
      background-color: #f5f5f5;
    }
    a {
      text-decoration: none;
      color: white;
      background-color: #007BFF;
      padding: 10px 20px;
      border-radius: 5px;
      font-size: 18px;
    }
    a:hover {
      background-color: #0056b3;
    }
    #funny-face {
      display: none;
      font-size: 100px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <h1>Presidency College 1st Semester Final Examination Result</h1>
  <a href="#" onclick="showFunnyFace()">Click to View Result</a>
  <div id="funny-face">😛</div>

  <script>
    function showFunnyFace() {
      const face = document.getElementById('funny-face');
      face.style.display = 'block';
      alert('Gotcha! No results here  , jaa ke 2nd semester ka kaam karo , salo sharm athi bhi nhi kya😛');
    }
  </script>
</body>
</html>
