# Restaurant_project
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Header Section -->
  <header class="header">
    <h1>Welcome to My Restaurant</h1>
    <p>Enjoy delicious food at affordable prices!</p>
  </header>

  <!-- About Section -->
  <section class="about">
    <img src="https://th.bing.com/th/id/OIP.q4lKiBsBMBeRbYReHJvI-QHaE4?w=288&h=216&c=7&r=0&o=5&dpr=2&pid=1.7" alt="Restaurant Image">
    <p>Our restaurant offers a cozy ambiance with a variety of dishes crafted to delight your taste buds.</p>
  </section>

  <!-- Menu Section -->
  <section class="menu">
    <h2>Our Menu</h2>
    <div class="menu-item">
      <img src="https://th.bing.com/th?id=OIP.ZZsn6lD6PCjocBzx1tuu1QHaEo&w=288&h=216&c=8&rs=1&qlt=90&o=6&dpr=2&pid=3.1&rm=2" alt="Pizza">
      <h3>Pizza</h3>
      <p>Price: 250</p>
    </div>
    <div class="menu-item">
      <img src="https://th.bing.com/th?id=OIP.64vXNk6FRg6TzVCW7u2zLAHaFj&w=288&h=216&c=8&rs=1&qlt=90&o=6&dpr=2&pid=3.1&rm=2" alt="Pasta">
      <h3>Pasta</h3>
      <p>Price: 150</p>
    </div>
    <div class="menu-item">
      <img src="https://www.bing.com/th?id=OIP.TyFXb0SqI3Im2zsEOAcqEwHaLH&w=288&h=216&c=8&rs=1&qlt=90&o=6&dpr=2&pid=3.1&rm=2" alt="Burger">
      <h3>Burger</h3>
      <p>Price: 90</p>
    </div>
  </section>

  <!-- Contact Section -->
  <footer class="footer">
    <h2>Contact Us</h2>
    <p>Address: 123 Food Street, Cityville</p>
    <p>Phone:91-9876543643</p>
    <button onclick="showAlert()">Call Now</button>
  </footer>

  <script src="script.js"></script>
</body>
</html>
<style>
    /* General Styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f2f2f2;
  color: #333;
}

/* Header Section */
.header {
  text-align: center;
  background-color: #333;
  color: white;
  padding: 20px;
}

/* About Section */
.about {
  display: flex;
  align-items: center;
  padding: 20px;
}

.about img {
  width: 300px;
  margin-right: 20px;
  border-radius: 8px;
}

/* Menu Section */
.menu {
  text-align: center;
  margin-top: 30px;
}

.menu h2 {
  font-size: 28px;
  margin-bottom: 20px;
}

.menu-item {
  display: inline-block;
  width: 200px;
  margin: 10px;
  text-align: center;
}

.menu-item img {
  width: 100%;
  border-radius: 8px;
}

/* Footer Section */
.footer {
  text-align: center;
  background-color: #333;
  color: white;
  padding: 20px;
}

button {
  padding: 10px 20px;
  background-color: #28a745;
  color: white;
  border: none;
  cursor: pointer;
}

button:hover {
  background-color: #218838;
}
</style>
<script>
    // Show an alert when the "Call Now" button is clicked
function showAlert() {
  alert('Calling the restaurant now!');
}
</script>
