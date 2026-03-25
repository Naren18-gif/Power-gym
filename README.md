[web.html](https://github.com/user-attachments/files/26238315/web.html)![gymback](https://github.com/user-attachments/assets/fd522ed6-db93-4fcd-b136-03334460bb10)
[Uploading we
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Power Gym</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>Power Gym</h1>
  <nav>
    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#pricing">Pricing</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="home" class="hero">
  <h2>Build Your power</h2>
  <p>Join the best gym in town</p>
  <button onclick="joinNow()">Join Now</button>
</section>

<section id="services">
  <h2>Our Services</h2>
  <div class="cards">
    <div class="card">💪 Weight Training</div>
    <div class="card">🏃 Running</div>
    <div class="card">🧘 Engligthment</div>
  </div>
</section>

<section id="pricing">
  <h2>Pricing Plans</h2>
  <div class="cards">
    <div class="card">
      <h3>Basic</h3>
      <p>₹999 / month</p>
    </div>
    <div class="card">
      <h3>Pro</h3>
      <p>₹1999 / month</p>
    </div>
    <div class="card">
      <h3>Elite</h3>
      <p>₹2999 / month</p>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Contact Us</h2>

  <!-- FORM REDIRECT -->
  <form action="success.html">
    <input type="text" placeholder="Your Name" required>
    <input type="email" placeholder="Your Email" required>
    <textarea placeholder="Message" required></textarea>
    <button type="submit">Send</button>
  </form>

</section>

<footer>
  <p>© 2026 Power Gym</p>
</footer>

<script src="script.js"></script>
</body>
</html>
b.html…]()
[success.html](https://github.com/user-attachments/files/26238345/success.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Success</title>
  <style>
    body {
      background: linear-gradient(to right, #11998e, #38ef7d);
      color: white;
      text-align: center;
      padding-top: 150px;
      font-family: Arial;
    }

    h1 {
      font-size: 40px;
    }

    a {
      display: inline-block;
      margin-top: 20px;
      padding: 10px 20px;
      background: black;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }
  </style>
</head>
<body>

<h1>🎉 Congratulations!</h1>
<p>You are joined in our team 💪</p>

<a href="web.html">Go Back Home</a>

</body>
</html>
[style.css](https://github.com/user-attachments/files/26238373/style.css)

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: linear-gradient(to right, #1e1e2f, #2c3e50);
  color: white;
}

header {
  background: #000;
  color: white;
  padding: 15px;
  display: flex;
  justify-content: space-between;
}

nav a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
}

.hero {
  background: url('gymback.jpg') no-repeat center/cover;
  text-align: center;
  padding: 100px 20px;
}

.hero button {
  padding: 10px 20px;
  background: red;
  color: white;
  border: none;
  cursor: pointer;
}

section {
  padding: 40px;
  text-align: center;
}

.cards {
  display: flex;
  justify-content: center;
  gap: 20px;
  flex-wrap: wrap;
}

.card {
  padding: 20px;
  background: white;
  color: black;
  border-radius: 10px;
  width: 180px;
}

form input, form textarea {
  display: block;
  margin: 10px auto;
  padding: 10px;
  width: 250px;
  border-radius: 5px;
  border: none;
}

button {
  padding: 10px;
  background: red;
  color: white;
  border: none;
  cursor: pointer;
}
[nk.js](https://github.com/user-attachments/files/26238389/nk.js)

function joinNow() {
  alert("Welcome to Power Gym! Let's get started 💪");
}
