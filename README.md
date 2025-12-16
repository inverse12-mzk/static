<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>HTML Document Template</title>
  <style>
    p {
      font-family: Arial, sans-serif;
    }
  </style>
</head>
<body>
  <p>Hello, world!</p>
<label for="name">Name (4 to 8 characters):</label>

<input
  type="text"
  id="name"
  name="name"
  required
  minlength="4"
  maxlength="8"
  size="10" />

  <script>
    var input = document.getElementById('name');
    input.focus();
  </script>
</body>
</html>
