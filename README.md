<English Teacher>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background: #f0f0f0;
    }
    header {
      text-align: center;
      padding: 20px;
    }
    .paragraphs {
      max-width: 800px;
      margin: auto;
      padding: 20px;
    }
    .gallery, .videos {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      justify-content: center;
      padding: 20px;
    }
    .gallery img, .videos iframe {
      width: 300px;
      height: auto;
      border-radius: 8px;
    }
    .videos iframe {
      height: 200px;
    }
    .login {
      max-width: 300px;
      margin: 30px auto;
      background: #fff;
      padding: 20px;
      border-radius: 8px;
    }
    .login input {
      width: 100%;
      padding: 8px;
      margin: 10px 0;
    }
    .login button {
      width: 100%;
      padding: 10px;
      background: #007bff;
      color: white;
      border: none;
      border-radius: 5px;
    }
    .search-bar {
      text-align: center;
      margin: 20px;
    }
    .search-bar input {
      padding: 8px;
      width: 300px;
    }
  </style>
</head>
<body>

<header>
  <h1>Welcome to My Website</h1>
</header>

<div class="search-bar">
  <input type="text" placeholder="Search...">
</div>

<section class="paragraphs">
  <p>Paragraph 1: This is the first paragraph. You can write any content you want here.</p>
  <p>Paragraph 2: Here's some more text for the second paragraph.</p>
  <p>Paragraph 3: Add interesting information or updates here.</p>
</section>

<section class="gallery">
  <img src="https://via.placeholder.com/300" alt="Image 1">
  <img src="https://via.placeholder.com/300" alt="Image 2">
  <img src="https://via.placeholder.com/300" alt="Image 3">
  <img src="https://via.placeholder.com/300" alt="Image 4">
  <img src="https://via.placeholder.com/300" alt="Image 5">
  <img src="https://via.placeholder.com/300" alt="Image 6">
  <img src="https://via.placeholder.com/300" alt="Image 7">
  <img src="https://via.placeholder.com/300" alt="Image 8">
  <img src="https://via.placeholder.com/300" alt="Image 9">
  <img src="https://via.placeholder.com/300" alt="Image 10">
</section>

<section class="videos">
  <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" allowfullscreen></iframe>
  <iframe src="https://www.youtube.com/embed/oHg5SJYRHA0" allowfullscreen></iframe>
</section>

<div class="login">
  <h3>Login</h3>
  <input type="text" placeholder="Username">
  <input type="password" placeholder="Password">
  <button>Login</button>
</div>

</body>
</html>
