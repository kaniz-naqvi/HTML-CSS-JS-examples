<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nature Lovers Image Gallery</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" />
  <style>
    /* External Styling for the README */
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f0f8ff;
      color: #333;
      margin: 0;
      padding: 0;
    }

    .container {
      max-width: 800px;
      margin: 40px auto;
      background-color: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    h1, h2 {
      color: #2c6b2f;
      text-align: center;
    }

    p {
      line-height: 1.6;
    }

    .badge {
      background-color: #28a745;
      color: white;
    }

    code {
      background-color: #f4f4f4;
      padding: 2px 4px;
      border-radius: 5px;
    }

    .footer {
      text-align: center;
      margin-top: 40px;
      font-size: 0.9em;
      color: #aaa;
    }

    .footer a {
      color: #28a745;
      text-decoration: none;
    }

    .highlight {
      background-color: #eaf2e6;
      padding: 10px;
      border-radius: 5px;
      margin-bottom: 15px;
    }

    .button {
      display: block;
      width: 200px;
      margin: 20px auto;
      padding: 10px;
      text-align: center;
      background-color: #28a745;
      color: white;
      font-size: 18px;
      border-radius: 5px;
      text-decoration: none;
    }

    .button:hover {
      background-color: #218838;
    }

    h3 {
      margin-top: 40px;
    }

    .gallery img {
      max-width: 100%;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
    }
  </style>
</head>

<body>

  <div class="container">
    <h1>Welcome to the Nature Lovers Image Gallery 🌿</h1>
    <p>This project demonstrates how an image gallery can be built using HTML, CSS, and JavaScript. It showcases the beauty of nature through interactive images in three categories: Flowers, Forests, and Sky.</p>

    <h2>What You'll Find Here</h2>
    <p>There are three primary sections in this gallery:</p>
    <ul>
      <li><strong>Flowers 🌸:</strong> A vibrant collection of beautiful flowers.</li>
      <li><strong>Forests 🌳:</strong> A selection of peaceful and lush forest images.</li>
      <li><strong>Sky ☁️🌤️:</strong> Mesmerizing images of the sky in different times of the day.</li>
    </ul>

    <div class="highlight">
      <h3>Technologies Used:</h3>
      <ul>
        <li><strong>HTML:</strong> The structure of the gallery.</li>
        <li><strong>CSS:</strong> Styling for a beautiful and responsive gallery layout.</li>
        <li><strong>JavaScript:</strong> Adds interactivity, such as changing images and viewing images in fullscreen mode.</li>
      </ul>
    </div>

    <h2>How the Gallery Works</h2>
    <p>Each category has a main image, and you can interact with other images in that category to replace the main image. This allows you to browse through different pictures easily and view them in a larger format. JavaScript makes it interactive by allowing dynamic changes between images.</p>

    <div class="gallery">
      <h3>Example Preview</h3>
      <p>Here's how the gallery looks:</p>
      <img src="gallery-images/flowers1.png" alt="Flowers" class="img-fluid">
      <p><strong>Click the images to see them change!</strong></p>
    </div>

    <h2>Project Structure</h2>
    <pre><code>
📁 root
│
├── 📂 gallery-images
│   ├── flowers1.png
│   ├── flowers2.png
│   └── ...
│
├── 📄 index.html
├── 📄 gallery.css
└── 📄 gallery.js
    </code></pre>

    <h3>Steps to Run the Gallery Locally</h3>
    <ol>
      <li>Clone or download the repository.</li>
      <li>Navigate to the project folder and open <code>index.html</code> in your browser.</li>
      <li>Enjoy the interactive nature gallery!</li>
    </ol>

    <a href="https://github.com/your-repo-link" target="_blank" class="button">Visit GitHub Repo</a>

    <div class="footer">
      <p>&copy; 2024 Nature Lovers Gallery. All Rights Reserved.</p>
      <p>Built with ❤️ by <a href="https://github.com/kaniz-naqvi" target="_blank">Mehak Fatima Naqvi</a></p>
    </div>
  </div>

</body>

</html>
