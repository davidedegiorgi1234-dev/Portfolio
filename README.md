# Portfolio

<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Il Mio Sito Moderno</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: url('https://source.unsplash.com/1600x800/?technology,office') no-repeat center center/cover;
      color: white;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 0 20px;
    }
    header h1 {
      font-size: 3rem;
      margin: 0;
    }
    header p {
      font-size: 1.2rem;
      margin: 15px 0;
    }
    .btn {
      background: #ff6600;
      color: white;
      padding: 12px 25px;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.3s;
    }
    .btn:hover {
      background: #e65500;
    }
    nav {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      background: rgba(0,0,0,0.7);
      padding: 15px;
      display: flex;
      justify-content: center;
      z-index: 1000;
    }
    nav a {
      color: white;
      margin: 0 20px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 60px 20px;
      text-align: center;
    }
    .services {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .card {
      background: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      width: 300px;
      transition: transform 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .card h3 {
      margin: 15px 0 10px;
    }
    .card p {
      padding: 0 15px 20px;
      font-size: 0.95rem;
    }
    form input, form textarea {
      width: 90%;
      max-width: 400px;
      margin: 10px 0;
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    form button {
      margin-top: 10px;
    }
    footer {
      background: #222;
      color: #ccc;
      text-align: center;
      padding: 30px 20px;
    }
  </style>
</head>
<body>

  <nav>
    <a href="#about">Chi Sono</a>
    <a href="#services">Servizi</a>
    <a href="#contact">Contatti</a>
  </nav>

  <header>
    <h1>Benvenuto nel Mio Sito</h1>
    <p>Soluzioni digitali moderne per il tuo business</p>
    <a href="#services" class="btn">Scopri di più</a>
  </header>

  <section id="about">
    <h2>Chi Sono</h2>
    <p>Sono un professionista appassionato di tecnologia e innovazione. Aiuto aziende e privati a creare una forte presenza online.</p>
  </section>

  <section id="services">
    <h2>I miei servizi</h2>
    <div class="services">
      <div class="card">
        <img src="https://source.unsplash.com/600x400/?web,design" alt="Web Design">
        <h3>Web Design</h3>
        <p>Creo siti web moderni, responsive e veloci per ogni esigenza.</p>
      </div>
      <div class="card">
        <img src="https://source.unsplash.com/600x400/?marketing,digital" alt="Marketing">
        <h3>Marketing Digitale</h3>
        <p>Strategie mirate per aumentare la tua visibilità e i tuoi clienti.</p>
      </div>
      <div class="card">
        <img src="https://source.unsplash.com/600x400/?consulting,business" alt="Consulenza">
        <h3>Consulenza</h3>
        <p>Supporto personalizzato per far crescere la tua attività online.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contattami</h2>
    <form>
      <input type="text" placeholder="Il tuo nome" required><br>
      <input type="email" placeholder="La tua email" required><br>
      <textarea placeholder="Il tuo messaggio" required></textarea><br>
      <button type="submit" class="btn">Invia</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Il Mio Sito Moderno - Tutti i diritti riservati</p>
  </footer>

</body>
</html>
