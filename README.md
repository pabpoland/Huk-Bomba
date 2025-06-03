<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>PSTO Huk Bomba</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 900px;
      margin: 0 auto;
      background-color: #f7f7f7;
      color: #333;
      padding: 20px;
    }

    header, footer {
      text-align: center;
      padding: 20px;
      background-color: #111;
      color: white;
      border-radius: 10px;
    }

    .logo {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      object-fit: cover;
    }

    section {
      margin-top: 40px;
    }

    .player {
      margin-bottom: 10px;
    }

    /* Zmniejszony rozmiar SVG boiska o połowę */
    svg {
      max-width: 150px;
      height: auto;
      margin: 20px auto;
      display: block;
    }

    .team-photo {
      width: 100%;
      max-width: 600px;
      border-radius: 10px;
      display: block;
      margin: 20px auto;
      object-fit: cover;
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
      max-width: 400px;
      margin: 0 auto;
    }

    input, textarea {
      padding: 10px;
      font-size: 1em;
      border: 1px solid #ccc;
      border-radius: 5px;
      resize: vertical;
    }

    input[type="submit"] {
      background-color: #222;
      color: white;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    input[type="submit"]:hover {
      background-color: #555;
    }

    table {
      width: 100%;
      max-width: 600px;
      border-collapse: collapse;
      margin: 0 auto;
    }

    th, td {
      border: 1px solid #ccc;
      padding: 10px;
      text-align: center;
    }

    th {
      background-color: #222;
      color: white;
    }

    /* Kolory wyników */
    .win {
      color: green;
      font-weight: bold;
    }

    .loss {
      color: red;
      font-weight: bold;
    }

    .draw {
      color: goldenrod;
      font-weight: bold;
    }

    ul {
      padding-left: 20px;
      max-width: 600px;
      margin: 0 auto;
    }

    a {
      color: #006600;
      text-decoration: none;
      font-weight: bold;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <header>
    <img src="logo.jpg" alt="Logo PSTO Huk Bomba" class="logo" />
    <h1>PSTO Huk Bomba</h1>
    <p>🔥 "Z nami zawsze po bombie!"</p>
  </header>

  <section>
    <h2>Skład drużyny</h2>
    <div class="player"><strong>Pimpek (pomocnik):</strong> Mówi więcej niż biega. Wiecznie bez siły, bo „rzygał”. Jedyny z B-klasy.</div>
    <div class="player"><strong>Lichu (obrona/bramkarz):</strong> Brodaty profesor futbolu i prawa. Technika lepsza niż kodeks karny.</div>
    <div class="player"><strong>Szymon (ofensywny):</strong> Błyskawica z problemem celności – jak kopnie, to nie wiadomo gdzie piłka poleci.</div>
    <div class="player"><strong>Mati Miśki (ofensywny):</strong> Tricki? Próbuje. Skuteczność? Różnie. Ale atmosfera? 10/10.</div>
    <div class="player"><strong>Mati Kuchta (neutralny):</strong> Gra tylko jak się go uprosi. Znany z Tourana i niespodziewanych zagrań.</div>
    <div class="player"><strong>Julu (obrończyni):</strong> Zmuszana do gry, ale jak już zagra – ściana nie do przejścia. Twarda babka!</div>
    <div class="player"><strong>Pawełek (uniwersalny):</strong> Mały, ale wariat. Gra wszędzie i wszędzie dobrze.</div>
  </section>

  <section>
    <h2>Pozycje na boisku</h2>
    <svg viewBox="0 0 300 500" width="150" height="250" aria-label="Boisko i pozycje graczy">
      <rect x="0" y="0" width="300" height="500" fill="#a8d08d"/>
      <line x1="0" y1="250" x2="300" y2="250" stroke="white" stroke-width="2"/>
      <circle cx="150" cy="250" r="30" stroke="white" stroke-width="2" fill="none"/>
      <circle cx="150" cy="250" r="2" fill="white"/>
      <text x="150" y="60" text-anchor="middle" fill="black" font-size="18">Lichu</text>
      <text x="80" y="200" text-anchor="middle" fill="black" font-size="14">Julu</text>
      <text x="220" y="200" text-anchor="middle" fill="black" font-size="14">Pimpek</text>
      <text x="80" y="300" text-anchor="middle" fill="black" font-size="14">Mati Miśki</text>
      <text x="220" y="300" text-anchor="middle" fill="black" font-size="14">Szymon</text>
      <text x="150" y="400" text-anchor="middle" fill="black" font-size="14">Pawełek</text>
      <text x="150" y="470" text-anchor="middle" fill="black" font-size="14">Kuchta</text>
    </svg>
  </section>

  <section>
    <h2>Zdjęcie drużynowe</h2>
    <img src="zdjęcie.jpeg" alt="Zdjęcie drużyny" class="team-photo" />
  </section>

  <section>
    <h2>Wyniki meczów</h2>
    <table>
      <thead>
        <tr>
          <th>Kolejka</th>
          <th>Wynik</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Kolejka 1</td>
          <td><span class="loss">PSTO Huk Bomba 8 - 10 Stary Żmigród</span></td>
        </tr>
        <tr>
          <td>Kolejka 2</td>
          <td><span class="loss">PSTO Huk Bomba 5 - 10 Stary Żmigród</span></td>
        </tr>
        <tr>
          <td>Puchar Korony Królów</td>
          <td><span class="win">PSTO Huk Bomba 13 - 12 Stary Żmigród</span></td>
        </tr>
        <tr>
          <td>Kolejka 4</td>
          <td><span class="win">PSTO Huk Bomba 9 - 8 Stary Żmigród</span></td>
        </tr>
      </tbody>
    </table>
  </section>

  <section>
    <h2>Kontakt</h2>
    <form action="mailto:lokatorzymojrzeszow@gmail.com" method="post" enctype="text/plain">
      <input type="text" name="name" placeholder="Twoje imię" required />
      <input type="email" name="email" placeholder="Twój email" required />
      <textarea name="message" placeholder="Wiadomość" rows="4" required></textarea>
      <input type="submit" value="Wyślij" />
    </form>
  </section>

  <section>
    <h2>Instagram</h2>
    <p>Obserwuj nas na <a href="https://www.instagram.com/psto_huk_bomba/" target="_blank" rel="noopener noreferrer">Instagramie</a>!</p>
  </section>

  <section>
    <h2>Hasła Klubu</h2>
    <ul>
      <li>🔥 "Z nami zawsze po bombie!"</li>
      <li>⚽ "Więcej stylu niż skilla!"</li>
      <li>🚬 "Nie ważne jak grasz, ważne że z nami!"</li>
      <li>🍻 "Przegraliśmy? Ale przynajmniej był grill!"</li>
    </ul>
  </section>

  <footer>
    &copy; 2025 PSTO Huk Bomba – Wszystkie prawa zastrzeżone.
  </footer>

</body>
</html>
