# html-assignment
## AIM:
 To Create a Webpage with Email and Phone Link. Use mailto: and tel: links to make contact info clickable.
 ## CODE :
 ```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .contact-box {
      background-color: #ffffff;
      padding: 40px;
      border-radius: 16px;
      box-shadow: 0 8px 16px rgba(0,0,0,0.1);
      text-align: center;
      width: 350px;
    }

    .contact-box h1 {
      font-size: 28px;
      margin-bottom: 20px;
    }

    .contact-box p {
      margin-bottom: 20px;
      font-size: 16px;
      color: #555;
    }

    .contact-link {
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 18px;
      color: #007BFF;
      text-decoration: none;
      margin: 10px 0;
    }

    .contact-link:hover {
      text-decoration: underline;
    }

    .contact-link img {
      width: 20px;
      height: 20px;
      margin-right: 10px;
    }
  </style>
</head>
<body>

  <div class="contact-box">
    <h1>Contact Us</h1>
    <p>You can reach us via email or phone:</p>

    <a href="mailto:info@example.com" class="contact-link">
      <img src="360_F_181003490_CxW4fQ0H3VypIIsPkFGpMDviO8ysWjOZ.jpg" alt="Email Icon">
      Email: info@example.com
    </a>

    <a href="tel:+1234567890" class="contact-link">
      <img src="phone-icon-flat-style-vector-illustration-round-blue-back-background-shadow-96385350.webp" alt="Phone Icon">
      Phone: +1 (234) 567-890
    </a>
  </div>

</body>
</html>
```
## OUTPUT :
![WhatsApp Image 2025-07-01 at 13 39 55_92656682](https://github.com/user-attachments/assets/292678a6-8d71-436c-90a4-637201e6dfc3)

 
