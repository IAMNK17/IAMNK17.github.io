<!DOCTYPE html>
<html>

<head>
  <title>Otakucase - Phone Cases for Otaku</title>
  <link rel="stylesheet" type="text/css" href="otakucase.css">
</head>

<body>
  <header>
    <h1>Otakucase</h1>
    <nav>
      <ul>
        <li><a href="#featured">Featured Cases</a></li>
        <li><a href="#collections">Collections</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact Us</a></li>
      </ul>
    </nav>
    <form>
      <label for="search">Search:</label>
      <input type="text" id="search" name="search">
      <button>Search</button>
    </form>
  </header>
  <main>
    <section id="featured">
      <h2>Featured Otakucase Phone Cases</h2>
      <div class="case">
        <img src="otakucase1.jpg" alt="Otakucase Phone Case 1">
        <h3>Otakucase Phone Case 1</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor, magna in faucibus.</p>
        <button>Buy Now</button>
      </div>
      <div class="case">
        <img src="otakucase2.jpg" alt="Otakucase Phone Case 2">
        <h3>Otakucase Phone Case 2</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor, magna in faucibus.</p>
        <button>Buy Now</button>
      </div>
    </section>
    <section id="collections">
      <h2>Otakucase Collections</h2>
      <ul>
        <li><a href="#collection1">Collection 1</a></li>
        <li><a href="#collection2">Collection 2</a></li>
        <li><a href="#collection3">Collection 3</a></li>
      </ul>
    </section>
    <section id="about">
      <h2>About Otakucase</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor, magna in faucibus.</p>
    </section>
    <section id="contact">
      <h2>Contact Otakucase</h2>
      <form action="submit-form.php" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name"><br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email"><br>
        <label for="
message">Message:</label>
<textarea id="message" name="message"></textarea><br>
<input type="submit" value="Send">
</form>
</section>

  </main>
  <footer>
    <p>Copyright © 2021 Otakucase. All rights reserved.</p>
    <ul>
      <li><a href="#">Terms of Use</a></li>
      <li><a href="#">Privacy Policy</a></li>
    </ul>
  </footer>
</body>
</html>
