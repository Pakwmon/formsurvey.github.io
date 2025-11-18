<!doctype html>
<html>
<head>
  <meta charset="utf-8">
  <title>Survey Start</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>
  <h2>Please wait — you will be sent to the survey now</h2>
  <p>If nothing happens, click the link manually.</p>
  <script>
    // Put your Microsoft Form links here:
    const linkA = "https://forms.office.com/r/0r1475wMwa"; // Real video
    const linkB = "https://forms.office.com/r/YnbZD8gbJR"; // AI video

    // Probability for each condition (0.5 for equal). Adjust if you want different split.
    const pA = 0.5;
    const rand = Math.random();

    // Optional small delay to improve UX
    setTimeout(() => {
      if (rand < pA) {
        window.location.href = linkA;
      } else {
        window.location.href = linkB;
      }
    }, 600); // 600 ms delay

    // Fallback links (in case redirect blocked)
    document.write('<p><a id="fallbackA" href="'+linkA+'">If you are not redirected, click here for survey (version A)</a></p>');
    document.write('<p><a id="fallbackB" href="'+linkB+'">If you are not redirected, click here for survey (version B)</a></p>');
  </script>
</body>
</html>


