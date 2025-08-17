# <!DOCTYPE html>
<html>
<head>
  <title>Test Login Page</title>
</head>
<body>
  <h2>Account Verification</h2>
  <form id="loginForm">
    <label>Username:</label><br>
    <input type="text" name="username"><br>
    <label>Password:</label><br>
    <input type="password" name="password"><br><br>
    <input type="submit" value="Verify Account">
  </form>

  <script>
    const form = document.getElementById('loginForm');
    form.addEventListener('submit', (e) => {
      e.preventDefault();
      alert('This is a safe test! Data not sent anywhere.');
    });
  </script>
</body>
</html>