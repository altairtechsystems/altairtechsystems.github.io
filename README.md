<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Altair Tech & Systems</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background-color: #0a1b2e;
      color: #fff;
      display: flex;
    }
    .sidebar {
      width: 260px;
      background-color: #081423;
      height: 100vh;
      position: fixed;
      left: 0;
      top: 0;
      padding-top: 40px;
      box-shadow: 4px 0 12px rgba(0,0,0,0.4);
    }
    .sidebar h2 { text-align: center; margin-bottom: 40px; font-weight: 700; }
    .sidebar a { display: block; padding: 18px 30px; color: #c8d7ef; text-decoration: none; font-size: 1.1em; transition: 0.3s; }
    .sidebar a:hover { background-color: #123055; color: #fff; }
    .main { margin-left: 260px; width: calc(100% - 260px); padding: 40px; }
    section { margin-bottom: 120px; animation: fadeIn 1.2s ease forwards; opacity: 0; }
    @keyframes fadeIn { from {opacity: 0; transform: translateY(40px);} to {opacity: 1; transform: translateY(0);} }
    /* Hero aggiornato */
    .hero {
      background: url("https://naturabenesserecultura.it/wp-content/uploads/2024/09/carta_topografica_12.jpg") center/cover no-repeat;
      height: 480px;
      border-radius: 14px;
      display: flex;
      align-items: flex-start; /* titolo in alto */
      justify-content: flex-start;
      padding: 40px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.5);
    }
    .hero-content {
      display: flex;
      flex-direction: column;
      gap: 20px; /* spazio tra titolo e pulsante */
    }
    .hero h1 {
      margin: 0;
      font-size: 3em;
      font-weight: 700;
      max-width: 600px;
      text-shadow: 2px 2px 8px rgba(0,0,0,0.8);
    }
    .hero .button {
      width: fit-content; /* pulsante non allarga tutto il div */
    }
    .button { 
      padding: 12px 28px; 
      background-color: #1f6feb; 
      border: none; 
      color: white; 
      border-radius: 8px; 
      cursor: pointer; 
      font-size: 1.1em; 
      transition: 0.3s; 
      text-decoration: none; 
      display: inline-block; 
    }
    .button:hover { background-color: #3b82f6; }
    .card-container, .component-card-container, .ai-card-container, .team-card-container { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 30px; }
    .card, .component-card, .ai-card, .team-card { background-color: #102137; padding: 20px; border-radius: 12px; box-shadow: 0 8px 20px rgba(0,0,0,0.3); text-align: center; }
    .card img, .component-card img, .ai-card img, .team-card img { width: 80%; border-radius: 10px; margin-bottom: 15px; }
    input, textarea { width: 100%; padding: 12px; margin-top: 10px; border-radius: 6px; border: none; }
    .download-btn { background-color: #34a0ff; padding: 12px 20px; display: inline-block; border-radius: 6px; margin-top: 20px; text-decoration: none; color: #fff; }
  </style>
</head>
<body>

<div class="sidebar">
  <h2>ALTΛIR</h2>
  <a href="#home">Home</a>
  <a href="#chi-siamo">Chi Siamo</a>
  <a href="#neurowing">Neurowing</a>
  <a href="#specifiche">Scheda Tecnica</a>
  <a href="#componenti">Componentistica</a>
  <a href="#ai">AI Integrata</a>
  <a href="#contatti">Contatti</a>
  <a href="#team">Team</a>
</div>

<div class="main">

  <!-- Hero aggiornata -->
  <section id="home" class="hero">
    <div class="hero-content">
      <h1>Neurowing. Tecnologia oltre i confini.</h1>
      <a href="presentazione_neurowing.html" class="button">Scopri il Progetto</a>
    </div>
  </section>

  <section id="chi-siamo">
    <h2>Chi Siamo</h2>
    <p>Altair Tech & Systems sviluppa piattaforme UAV professionali dedicate a missioni ISR, SAR, monitoraggio ambientale, supporto tattico e comunicazioni avanzate. Combiniamo ingegneria aeronautica, sensoristica di ultima generazione e sistemi di controllo autonomi per creare soluzioni affidabili, modulari e operative in scenari complessi. La nostra visione è portare le operazioni unmanned a un livello superiore, garantendo efficienza, precisione e resilienza anche nelle condizioni più difficili.</p>
  </section>

  <section id="neurowing">
    <h2>Neurowing — Il Primo Progetto Altair</h2>
    <div class="card-container">
      <div class="card">
        <img src="https://www.airmobi.com/wp-content/uploads/2023/03/V25-VTOL-Drone.jpg" alt="Drone ISR">
        <h3>Drone VTOL</h3>
        <p>Struttura ibrida ad ala fissa in alluminio 7075 T6, con capacità di decollo verticale e autonomia elevata.</p>
      </div>
      <div class="card">
        <img src="https://geosmartmagazine.it/wp-content/uploads/2022/10/Droni-UAS-emergenze-missioni-ricerca-soccorso-.jpg" alt="Missione SAR">
        <h3>Operazioni SAR/ISR</h3>
        <p>Progettato per missioni critiche, sorveglianza, ricognizione e ricerca dispersi.</p>
      </div>
    </div>
  </section>

  <!-- resto della pagina rimane uguale -->
  <!-- ... tutte le altre sezioni ... -->

</div>

</body>
</html>
