<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Styled Web Page</title>
  <style>
    /* Set background color and font for the whole page */
    body {
      background-color: #f0f8ff; /* light blue background */
      font-family: 'Arial', sans-serif;
      color: #333; /* dark gray text */
      padding: 20px;
    }

    /* Style the heading */
    h1 {
      color: #2c3e50; /* dark blue */
      text-align: center;
      text-transform: uppercase;
      letter-spacing: 2px;
    }

    /* Style the paragraph */
    p {
      font-size: 18px;
      line-height: 1.6;
      text-align: justify;
    }

    /* Style the link */
    a {
      color: #e74c3c; /* red */
      text-decoration: none;
      font-weight: bold;
    }

    a:hover {
      text-decoration: underline;
      color: #c0392b;
    }

    /* Add a styled image */
    img {
      display: block;
      margin: 20px auto;
      border: 5px solid #3498db;
      border-radius: 10px;
      max-width: 300px;
    }
  </style>
</head>
<body>

  <h1>Welcome to My Styled Page</h1>

  <p>This web page demonstrates basic <strong>CSS styling techniques</strong> including colors, fonts, and text formatting. CSS allows us to make our pages more attractive and easier to read.</p>

  <p>Visit my <a href="https://example.com" target="_blank">website</a> for more tutorials.</p>

  <img src="https://via.placeholder.com/300" alt="Placeholder Image">

</body>
</html>
