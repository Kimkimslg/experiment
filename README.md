<!DOCTYPE html>
<html>
 <head>
 <meta charset="UTF-8">
 <title>Experiment Redirect</title>
 <script>
  const rand = Math.random();
  if (rand < 0.5) {
  window.location.href = "https://docs.google.com/forms/d/e/1FAIpQLScfyLBF0Fj5zXEw4wI8swo-6d9VsufYeT_RF3CLuI7bMgknvA/viewform?usp=header"; // 일반
  } else {
  window.location.href = "https://docs.google.com/forms/d/e/1FAIpQLSeUZNCuuH3yTNUYFgGUwajQyYtaWiLnexPnOhKho9xzZa7O8A/viewform?usp=header"; // 친환경
  }
 </script>
 </head>
  <body>
   <p>Redirecting...</p>
  </body>
</html>
