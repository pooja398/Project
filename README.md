<!DOCTYPE html>
<html lang="en">
<head>
    
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exclusive Login & Register Page</title>
  <link rel="stylesheet" href="F:\Documents\Desktop\sass\Shopping\index.css">
  <script src="F:\Documents\Desktop\sass\Shopping\index.js" defer></script>
</head>
<body>
  
    
  <!-- Login Page -->

  <div id="login-section" class="auth-section">
    <div class="logo"><img src="WhatsApp Image 2024-12-22 at 10.59.18 PM.jpeg" width="200px"></div>

    <div class="auth-container">
 
      <h2>Login</h2>
      
      <form id="login-form">
        <label for="login-email">Email:</label>
        <input type="email" id="login-email" name="email" placeholder="Enter your email" required>
        
        <label for="login-password">Password:</label>
        <input type="password" id="login-password" name="password" placeholder="Enter your password" required>
        
        <button type="submit" class="auth-btn"><a href="F:\Documents\Desktop\sass\Shopping\pooz.html">Login</a></button>
      </form>
      <p>New user? <span id="show-register" class="auth-link" href="F:\Documents\Desktop\sass\Shopping\pooz.html">Register Now</span></p>
    </div>
  </div>

  <!-- Register Page -->
  <div id="register-section" class="auth-section">
    <div class="logo"><img src="WhatsApp Image 2024-12-22 at 10.59.18 PM.jpeg" width="200px"></div>

    <div class="auth-container">
      <h2>Register</h2>
      <form id="register-form">
        <label for="register-name">Full Name:</label>
        <input type="text" id="register-name" name="name" placeholder="Enter your full name" required>
        
        <label for="register-email">Email:</label>
        <input type="email" id="register-email" name="email" placeholder="Enter your email" required>
        
        <label for="register-password">Password:</label>
        <input type="password" id="register-password" name="password" placeholder="Create a password" required>
        
        <label for="register-confirm-password">Confirm Password:</label>
        <input type="password" id="register-confirm-password" name="confirm-password" placeholder="Confirm your password" required>
        
        <button type="submit" class="auth-btn"><a href="F:\Documents\Desktop\sass\Shopping\pooz.html"></a>Register</button>
      </form>
      <p>Already have an account? <span id="show-login" class="auth-link">Login Here</span></p>
    </div>
  </div>
</body>
</html>
