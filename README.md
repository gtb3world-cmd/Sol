<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SolWave - Decentralized Future</title>
  <style>
    /* Reset */
    * {margin:0; padding:0; box-sizing:border-box; font-family:Arial, sans-serif;}

    body {
      background: #0a0a1a;
      color: white;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #3b82f6, #9333ea);
      text-align: center;
      padding: 80px 20px;
    }

    header img {
      width: 100px;
      margin-bottom: 20px;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    section h2 {
      font-size: 2rem;
      margin-bottom: 20px;
      text-align: center;
      color: #3b82f6;
    }

    /* About */
    .about {
      text-align: center;
    }

    .about p {
      font-size: 1.1rem;
      max-width: 800px;
      margin: auto;
    }

    /* Founder */
    .founder {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: center;
      gap: 20px;
      text-align: center;
    }

    .founder img {
      width: 180px;
      border-radius: 50%;
      border: 4px solid #3b82f6;
    }

    .founder-info {
      max-width: 500px;
    }

    .founder-info h3 {
      margin-bottom: 10px;
    }

    /* Roadmap */
    .roadmap {
      position: relative;
      padding-left: 20px;
    }

    .roadmap::before {
      content: "";
      position: absolute;
      left: 10px;
      top: 0;
      width: 4px;
      height: 100%;
      background: #3b82f6;
    }

    .roadmap-item {
      margin-bottom: 30px;
      padding-left: 20px;
    }

    .roadmap-item h4 {
      color: #9333ea;
      margin-bottom: 5px;
    }

    /* Tokenomics */
    .tokenomics {
      text-align: center;
    }

    .tokenomics-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .tokenomics-item {
      background: rgba(255,255,255,0.05);
      padding: 20px;
      border-radius: 12px;
    }

    .tokenomics-item h4 {
      color: #3b82f6;
      margin-bottom: 5px;
    }

    /* CTA */
    .cta {
      text-align: center;
      padding: 60px 20px;
      background: linear-gradient(135deg, #9333ea, #3b82f6);
      border-radius: 12px;
      margin: 40px 0;
    }

    .cta h2 {
      color: white;
      margin-bottom: 20px;
    }

    .cta button {
      padding: 15px 30px;
      font-size: 1rem;
      border: none;
      border-radius: 8px;
      background: #0a0a1a;
      color: white;
      cursor: pointer;
      transition: 0.3s;
    }

    .cta button:hover {
      background: #1e1e3a;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 20px;
      background: #111;
      font-size: 0.9rem;
      opacity: 0.8;
    }

    @media (max-width: 768px) {
      .founder {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>

  <!-- Hero -->
  <header>
    <img src="solwave-logo.png" alt="SolWave Logo" />
    <h1>SolWave</h1>
    <p>Riding the Wave of Decentralization</p>
  </header>

  <!-- About -->
  <section class="about">
    <h2>About SolWave</h2>
    <p>
      SolWave is a blockchain project designed to revolutionize decentralized finance (DeFi).
      By focusing on transparency, security, and scalability, SolWave empowers users
      to take control of their financial future with confidence.
    </p>
  </section>

  <!-- Founder -->
  <section class="founder">
    <img src="founder-photo.jpg" alt="John Michael - Founder" />
    <div class="founder-info">
      <h3>John Michael</h3>
      <p>
        Founder & Visionary of SolWave. John is passionate about blockchain innovation
        and bringing sustainable value to investors and the community.
      </p>
    </div>
  </section>

  <!-- Roadmap -->
  <section class="roadmap">
    <h2>Roadmap</h2>
    <div class="roadmap-item">
      <h4>Q4 2025</h4>
      <p>Token Presale Launch & Community Growth</p>
    </div>
    <div class="roadmap-item">
      <h4>Q1 2026</h4>
      <p>Exchange Listings & Strategic Partnerships</p>
    </div>
    <div class="roadmap-item">
      <h4>Q2 2026</h4>
      <p>DeFi Platform Expansion</p>
    </div>
    <div class="roadmap-item">
      <h4>Q3 2026</h4>
      <p>Global Marketing & Ecosystem Scaling</p>
    </div>
  </section>

  <!-- Tokenomics -->
  <section class="tokenomics">
    <h2>Tokenomics</h2>
    <div class="tokenomics-grid">
      <div class="tokenomics-item">
        <h4>40%</h4>
        <p>Presale</p>
      </div>
      <div class="tokenomics-item">
        <h4>20%</h4>
        <p>Team & Development</p>
      </div>
      <div class="tokenomics-item">
        <h4>25%</h4>
        <p>Liquidity & Exchange</p>
      </div>
      <div class="tokenomics-item">
        <h4>15%</h4>
        <p>Marketing & Community</p>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section class="cta">
    <h2>Join the SolWave Presale Today</h2>
    <button>Buy Tokens Now</button>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 SolWave. All rights reserved.</p>
  </footer>

</body>
</html>
