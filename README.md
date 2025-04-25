<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Unyx - Innovate the Now</title>
</head>
<body>
  <header>
    <div class="logo">
      <span class="text-logo">U</span>
      <h2>Unyx</h2>
    </div>
    <nav>
      <a href="#produkte">Produkte</a>
      <a href="#lösungen">Lösungen</a>
      <a href="#überuns">Über uns</a>
      <a href="#kontakt">Kontakt</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Innovative Technologien für Ihr Unternehmen</h1>
    <p>Wir bieten Lösungen für die Herausforderungen von morgen</p>
    <button>Mehr Erfahren</button>
  </section>

  <section class="features">
    <div class="feature" id="produkte">
      <h3>Unsere Produkte</h3>
      <p>Innovative Softwarelösungen für Ihr Unternehmen</p>
    </div>
    <div class="feature" id="lösungen">
      <h3>Unsere Lösungen</h3>
      <p>Effiziente Lösungen für Ihre Dienstleistungen</p>
    </div>
    <div class="feature" id="überuns">
      <h3>Über uns</h3>
      <p>Unser Engagement für technologische Innovation</p>
    </div>
  </section>
  <section id="kontakt">
    <h3>Kontakt</h3>
  </section>
</body>
</html>
<link rel="stylesheet" href="style.css"/>

function main() {
  console.log("Hello, World!");

  const heroButton = document.querySelector('.hero button');
  if (heroButton) {
    heroButton.addEventListener('click', () => {
      window.scrollTo({
        top: 0,
        behavior: 'smooth'
      });
    });
  }
}

main();
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #ffffff;
}
header {
  background-color: #eaeaea;
  padding: 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  border-bottom: 2px solid #1e4ba5;
}
.logo {
  display: flex;
  align-items: center;
}
.logo img {
  height: 40px;
  margin-right: 10px;
}
nav a {
  margin-left: 20px;
  color: #1e4ba5;
  text-decoration: none;
  font-weight: bold;
}
.hero {
  padding: 60px 20px;
  text-align: center;
  background-color: #f5f5f5;
}
.hero h1 {
  font-size: 48px;
  margin-bottom: 10px;
}
.hero p { font-size: 20px; margin-bottom: 30px; } .hero button { padding: 10px 20px; font-size: 16px; background-color: #1e4ba5; color: white; border: none; cursor: pointer; } .features { display: flex; justify-content: space-around; padding: 40px 20px; background-color: #e0e8f8; } .feature { max-width: 300px; } .feature h3 { color: #1e4ba5; margin-bottom: 10px; }
.text-logo {
  font-size: 2em;
  color: #1e4ba5;
  font-weight: bold;
  border: 2px solid #1e4ba5;
  padding: 5px 10px;
  border-radius: 50%;
}

