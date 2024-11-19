<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Happy Birthday Card</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .card {
      width: 90%;
      max-width: 800px;
      background: #fff;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
      position: relative;
    }
    .card h1 {
      text-align: center;
      color: #ff4081;
      font-size: 36px;
    }
    .card p {
      text-align: center;
      color: #333;
      margin: 10px 0;
    }
    .photos {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      margin-top: 20px;
    }
    .photos img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 10px;
      margin: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      transition: transform 0.2s;
    }
    .photos img:hover {
      transform: scale(1.1);
    }
    .heart {
      width: 80px;
      height: 80px;
      background: #ff4081;
      clip-path: polygon(50% 0%, 100% 38%, 82% 100%, 50% 82%, 18% 100%, 0% 38%);
      margin: 20px auto;
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Happy Birthday, Doremon!</h1>
    <p>How can someone be so cute and lovable? ❤️</p>
    <div class="heart"></div>
    <div class="photos">
      <!-- Add your sister's photos here -->
      <img src="photo1.jpg" alt="Happy">
      <img src="photo2.jpg" alt="Birthday">
      <img src="photo3.jpg" alt="To you">
    </div>
    <p>Wishing you all the happiness and joy on your special day!</p>
  </div>
</body>
</html>
