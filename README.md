<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Redirecting...</title>
  <script>
    // Add your survey URLs here
    const links = [
      "https://forms.office.com/r/YnbZD8gbJR",
      "https://forms.office.com/r/0r1475wMwa"
    ];

    // Randomly select a link
    const randomLink = links[Math.floor(Math.random() * links.length)];

    // Redirect to the selected link
    window.location.href = randomLink;
  </script>
</head>
<body>
  <p>Redirecting to survey…</p>
</body>
</html>
