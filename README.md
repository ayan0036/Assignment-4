<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>CSS Assignment</title>
    <style>
        body {
            background-color: #f0f8ff;
            font-family: Arial, sans-serif;
        }
        h1 {
            color: darkblue;
        }
        p {
            color: #333333;
            font-size: 18px;
            margin: 20px;
            padding: 10px;
        }
        .bordered {
            border: 2px solid black;
        }
    </style>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <h1 style="text-align: center; color: teal;">Welcome to My Styled Page</h1>

    <p class="bordered">This paragraph uses internal CSS for styling and has a border.</p>

    <p style="color: green; font-size: 20px;">This paragraph uses inline CSS for styling.</p>

    <div class="external-style">This section is styled using external CSS.</div>

</body>
</html>
.external-style {
    color: crimson;
    font-family: Verdana, sans-serif;
    font-size: 22px;
    margin: 25px;
    padding: 15px;
    border: 2px dashed crimson;
}
