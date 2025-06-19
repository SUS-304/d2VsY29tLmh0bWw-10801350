<!DOCTYPE html>
<html lang="en">
<head>
<meta http‑equiv="Content‑Security‑Policy" 
content="default-src 'self'; style-src 'self' 'unsafe-inline'; script-src 'self' 'unsafe-inline'; img-src 'self' data:;">
</head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1" />
<title>VOID-CROWN - Elite Hacking Nexus</title>
<meta name="description" content="VOID-CROWN | Elite Hacking Services Hub. Stealth. Power. Control." />
<meta name="author" content="MRX" />
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500;700&family=Roboto+Mono&display=swap" rel="stylesheet" />
<style>
  /* Reset & Base */
  * {
    margin: 0; padding: 0; box-sizing: border-box;
  }
  html, body {
    height: 100%;
    background: linear-gradient(135deg, #0a0a0a 0%, #121212 100%);
    font-family: 'Orbitron', 'Roboto Mono', monospace, sans-serif;
    color: #e0e0e0;
    overflow-x: hidden;
  }
  a {
    color: #ff2e2e;
    text-decoration: none;
    transition: color 0.3s ease;
  }
  a:hover {
    color: #ff6161;
  }
  /* Scrollbar */
  ::-webkit-scrollbar {
    width: 10px;
  }
  ::-webkit-scrollbar-track {
    background: #121212;
  }
  ::-webkit-scrollbar-thumb {
    background: #ff2e2e;
    border-radius: 10px;
  }

  /* Splash Gate */
  #splashGate {
    position: fixed;
    inset: 0;
    background: #000;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    z-index: 99999;
    color: #ff2e2e;
    font-size: 1.7rem;
    letter-spacing: 4px;
    text-align: center;
    padding: 0 20px;
  }
  #splashGate h1 {
    font-size: 4rem;
    margin-bottom: 15px;
    text-shadow: 0 0 30px #ff2e2e;
  }
  #splashGate p {
    max-width: 520px;
    margin-bottom: 40px;
    font-weight: 500;
    line-height: 1.3;
  }
  #splashGate button {
    background: transparent;
    border: 3px solid #ff2e2e;
    color: #ff2e2e;
    padding: 16px 48px;
    margin: 8px;
    font-size: 1.3rem;
    font-weight: 700;
    border-radius: 10px;
    cursor: pointer;
    text-transform: uppercase;
    letter-spacing: 3px;
    box-shadow: 0 0 15px #ff2e2e;
    transition: background-color 0.3s ease, color 0.3s ease;
  }
  #splashGate button:hover {
    background: #ff2e2e;
    color: #121212;
  }
  #splashGate .btn-danger {
    border-color: #661111;
    color: #661111;
    box-shadow: 0 0 10px #661111;
  }
  #splashGate .btn-danger:hover {
    background: #661111;
    color: #fff;
  }

  /* Main container hidden initially */
  #mainContainer {
    display: none;
    min-height: 100vh;
    background: linear-gradient(90deg, #0a0a0a 10%, #181818 90%);
    padding: 20px 40px 80px;
    position: relative;
    overflow-x: hidden;
  }

  /* Header */
  header {
    position: sticky;
    top: 0;
    background: #0c0c0c;
    border-bottom: 3px solid #ff2e2e;
    padding: 20px 0;
    z-index: 1000;
    display: flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0 0 20px #ff2e2e44;
  }
  .logo {
    font-size: 3.2rem;
    color: #b0b0b0;
    font-weight: 700;
    letter-spacing: 8px;
    text-shadow: 0 0 12px #ff2e2e;
    user-select: none;
    text-transform: uppercase;
  }
  .warning {
    font-family: 'Orbitron', sans-serif;
    color: #ff2e2e;
    font-weight: 900;
    font-size: 1.6rem;
    letter-spacing: 5px;
    display: flex;
    align-items: center;
    gap: 18px;
    user-select: none;
  }
  .warning .red-x {
    font-size: 2.6rem;
    color: #ff0000;
    text-shadow: 0 0 20px #ff0000;
    user-select: none;
  }
  .header-subtext {
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    top: 75px;
    font-family: 'Roboto Mono', monospace;
    font-size: 1.05rem;
    color: #ff3a3a;
    letter-spacing: 2px;
    text-shadow: 0 0 10px #ff2e2eaa;
    user-select: none;
  }

  /* Intro mission text */
  #missionIntro {
    max-width: 900px;
    margin: 70px auto 50px auto;
    font-size: 1.35rem;
    line-height: 1.6;
    text-align: center;
    font-weight: 600;
    color: #ddd;
    padding: 0 15px;
    text-shadow:
      0 0 10px #ff2e2e88,
      0 0 15px #ff4444aa;
  }

  /* Services grid */
  #servicesGrid {
    max-width: 960px;
    margin: 0 auto 80px auto;
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(320px,1fr));
    gap: 32px;
  }

  /* Single service card */
  .serviceCard {
    background: #1a1a1a;
    border: 3px solid #330000;
    border-radius: 18px;
    box-shadow:
      0 0 10px #440000,
      inset 0 0 12px #ff2e2e88;
    padding: 30px 25px 40px 25px;
    color: #ffdddd;
    display: flex;
    flex-direction: column;
    cursor: pointer;
    transition: border-color 0.35s ease, box-shadow 0.35s ease;
    user-select: none;
    position: relative;
    overflow: hidden;
  }
  .serviceCard:hover {
    border-color: #ff2e2e;
    box-shadow:
      0 0 25px #ff2e2e,
      inset 0 0 20px #ff4444bb;
  }
  .serviceCard h3 {
    font-size: 1.9rem;
    font-weight: 900;
    margin-bottom: 14px;
    letter-spacing: 2px;
    text-shadow: 0 0 10px #ff3a3a;
  }
  .serviceCard .desc {
    font-family: 'Roboto Mono', monospace;
    font-size: 1rem;
    margin-bottom: 18px;
    color: #f0cfcf;
    min-height: 72px;
  }
  .serviceCard .price {
    font-weight: 700;
    font-size: 1.2rem;
    color: #ff5555;
    letter-spacing: 1.2px;
    margin-bottom: 20px;
  }
  .serviceCard .walletLink {
    font-family: monospace;
    font-size: 0.95rem;
    background: #330000cc;
    border-radius: 8px;
    padding: 10px 15px;
    color: #ffcccc;
    word-break: break-all;
    margin-bottom: 15px;
    user-select: text;
    box-shadow: inset 0 0 8px #ff2e2eaa;
  }
  .serviceCard .copyBtn {
    position: absolute;
    top: 18px;
    right: 18px;
    background: #ff2e2e;
    border: none;
    border-radius: 8px;
    color: white;
    font-weight: 700;
    padding: 6px 14px;
    cursor: pointer;
    box-shadow: 0 0 12px #ff2e2e;
    transition: background-color 0.3s ease;
  }
  .serviceCard .copyBtn:hover {
    background: #ff0000;
  }
  .serviceCard .buyBtn {
    background: #ff2e2e;
    border: none;
    padding: 14px 30px;
    border-radius: 14px;
    font-weight: 900;
    font-size: 1.15rem;
    color: white;
    cursor: pointer;
    user-select: none;
    box-shadow: 0 0 25px #ff2e2e;
    transition: background-color 0.35s ease;
    margin-top: auto;
    align-self: center;
  }
  .serviceCard .buyBtn:hover {
    background: #ff0000;
  }

  /* Modal Overlay */
  #modalOverlay {
    position: fixed;
    inset: 0;
    background: rgba(10,10,10,0.98);
    backdrop-filter: blur(5px);
    display: none;
    justify-content: center;
    align-items: center;
    z-index: 9999999;
  }

  /* Modal Content */
  #modalContent {
    background: #121212;
    max-width: 520px;
    width: 90%;
    border: 3px solid #ff2e2e;
    border-radius: 22px;
    padding: 30px 40px 40px 40px;
    box-shadow: 0 0 35px #ff2e2e;
    color: #f0f0f0;
    position: relative;
    user-select: none;
    text-align: center;
    font-family: 'Roboto Mono', monospace;
  }
  #modalContent h2 {
    font-family: 'Orbitron', sans-serif;
    font-size: 2.8rem;
    color: #ff2e2e;
    margin-bottom: 25px;
    letter-spacing: 3px;
    text-shadow: 0 0 20px #ff3a3a;
  }
  #modalContent p {
    font-size: 1.15rem;
    line-height: 1.5;
    margin-bottom: 25px;
    color: #ddd;
  }
  #modalContent .walletAddr {
    background: #330000cc;
    border-radius: 10px;
    padding: 15px 22px;
    font-size: 1.05rem;
    font-family: monospace;
    user-select: all;
    word-break: break-word;
    color: #ffbbbb;
    box-shadow: inset 0 0 10px #ff2e2eaa;
    margin-bottom: 30px;
  }
  #modalContent .instructions {
    font-size: 1rem;
    font-style: italic;
    color: #ff7b7b;
    margin-bottom: 40px;
  }

  /* Modal Buttons */
  #modalContent .modalButtons {
    display: flex;
    justify-content: center;
    gap: 30px;
  }
  #modalContent .btn {
    padding: 14px 38px;
    font-size: 1.2rem;
    border-radius: 16px;
    border: none;
    font-weight: 700;
    cursor: pointer;
    box-shadow: 0 0 15px #ff2e2e;
    text-transform: uppercase;
    letter-spacing: 2px;
    transition: background-color 0.3s ease;
    user-select: none;
  }
  #modalContent .btn.buy {
    background: #ff2e2e;
    color: #fff;
  }
  #modalContent .btn.buy:hover {
    background: #ff0000;
  }
  #modalContent .btn.return {
    background: #660000;
    color: #fdd;
  }
  #modalContent .btn.return:hover {
    background: #990000;
  }

  /* Close X */
  #modalClose {
    position: absolute;
    top: 14px;
    right: 20px;
    font-size: 2rem;
    color: #ff2e2e;
    cursor: pointer;
    font-weight: 900;
    text-shadow: 0 0 15px #ff0000;
    user-select: none;
    transition: color 0.3s ease;
  }
  #modalClose:hover {
    color: #ff4444;
  }

  /* Footer */
  footer {
    background: #121212;
    border-top: 3px solid #ff2e2e;
    padding: 40px 30px;
    text-align: center;
    color: #bb5555;
    font-family: 'Roboto Mono', monospace;
    font-weight: 600;
    letter-spacing: 1.5px;
    box-shadow: inset 0 10px 20px #ff2e2e44;
    user-select: none;
  }
  footer .echoLaw {
    margin-bottom: 25px;
    font-size: 1.05rem;
    color: #ff5555;
    font-weight: 700;
    line-height: 1.5;
    max-width: 960px;
    margin-left: auto;
    margin-right: auto;
    text-shadow:
      0 0 8px #ff2e2e88,
      0 0 12px #ff4444aa;
  }
  footer .shadowFoot {
    font-size: 0.95rem;
    color: #cc4444cc;
  }
  footer .shadowFoot a {
    color: #ff2e2e;
    margin: 0 14px;
    font-weight: 700;
    transition: color 0.3s ease;
  }
  footer .shadowFoot a:hover {
    color: #ff6161;
  }

  /* Neon animated background lines top & bottom */
  #neonLinesTop, #neonLinesBottom {
    position: fixed;
    left: 0; right: 0;
    height: 12px;
    pointer-events: none;
    z-index: 500;
  }
  #neonLinesTop {
    top: 0;
    background:
      repeating-linear-gradient(
        90deg,
        transparent,
        transparent 5px,
        #ff2e2e88 6px,
        #ff2e2e88 8px
      );
    animation: neonMove 5s linear infinite;
  }
  #neonLinesBottom {
    bottom: 0;
    background:
      repeating-linear-gradient(
        90deg,
        transparent,
        transparent 7px,
        #ff2e2eaa 8px,
        #ff2e2eaa 10px
      );
    animation: neonMoveReverse 6s linear infinite;
  }
  @keyframes neonMove {
    0% { background-position: 0 0; }
    100% { background-position: 100% 0; }
  }
  @keyframes neonMoveReverse {
    0% { background-position: 100% 0; }
    100% { background-position: 0 0; }
  }

  /* Responsive */
  @media (max-width: 720px) {
    #mainContainer {
      padding: 15px 20px 60px 20px;
    }
    header {
      flex-direction: column;
      padding: 20px 0 40px 0;
      gap: 10px;
      position: relative;
    }
    .header-subtext {
      top: 110px;
      font-size: 0.95rem;
    }
    .logo {
      font-size: 2.4rem;
    }
    .warning {
      font-size: 1.3rem;
    }
    #missionIntro {
      font-size: 1.15rem;
      margin: 60px 15px 40px 15px;
    }
    #servicesGrid {
      grid-template-columns: 1fr;
      gap: 24px;
      max-width: 90vw;
    }
    .serviceCard h3 {
      font-size: 1.5rem;
    }
    .serviceCard .desc {
      font-size: 0.95rem;
      min-height: auto;
    }
    .serviceCard .price {
      font-size: 1.05rem;
    }
    .serviceCard .buyBtn {
      font-size: 1rem;
      padding: 12px 24px;
    }
    #modalContent {
      padding: 25px 25px 35px 25px;
    }
    #modalContent h2 {
      font-size: 2rem;
    }
    #modalContent p, #modalContent .instructions {
      font-size: 1rem;
    }
    footer {
      font-size: 0.85rem;
      padding: 30px 20px;
    }
  }
</style>
</head>
<body>
<link rel="stylesheet" href="https://fonts.googleapis.com/…">
<script src="https:// … react / dexie / simplepeer …"></script>

<!-- Neon animated lines -->
<div id="neonLinesTop"></div>
<div id="neonLinesBottom"></div>

<!-- Splash Gate -->
<section id="splashGate" aria-label="Access Gate">
  <h1>VOID-CROWN</h1>
  <p>Only the shadow warriors may enter...<br>Do you have what it takes?</p>
  <div>
    <button id="enterBtn" aria-label="Enter VOID-CROWN">Enter VOID-CROWN</button>
    <button id="leaveBtn" class="btn-danger" aria-label="Leave Site">Leave</button>
  </div>
</section>

<!-- Main content container -->
<main id="mainContainer" role="main" aria-label="VOID-CROWN Main Content">

  <!-- Header -->
  <header>
    <div class="logo" aria-label="Site Logo">VOID-CROWN</div>
    <div class="warning" aria-live="polite">
      MRX BLACK-WARNING <span class="red-x">✖</span>
    </div>
    <div class="header-subtext" aria-hidden="true">"This is the realm of MRX. We don't forgive, we don't forget."</div>
  </header>

  <!-- Mission Intro -->
  <section id="missionIntro" aria-label="Site Mission Introduction">
    VOID-CROWN is the ultimate hub for taking down the untouchables.<br>
    From corporate giants to street gangs, we bring darkness to their doorstep.<br>
    Choose your weapon, pay in Bitcoin, and watch the empire fall.
  </section>

  <!-- Services Grid -->
  <section id="servicesGrid" aria-label="Services Listing">

    <!-- Service Template Example, will replicate for multiple services -->

    <article class="serviceCard" tabindex="0" role="region" aria-labelledby="service1Title" aria-describedby="service1Desc">
      <h3 id="service1Title">Silent Remote Access Trojan (RAT)</h3>
      <p class="desc" id="service1Desc">Stealthily control any device remotely without detection. Full access, real-time commands, and covert data extraction.</p>
      <div class="price">Price: 0.0085 BTC</div>
      <div class="walletLink" id="wallet1">3AaCExHLfXdF63wNqdCEgrJsWMtVqRfNr5</div>
      <button class="copyBtn" aria-label="Copy Wallet Address">COPY</button>
      <button class="buyBtn" aria-label="Buy Silent Remote Access Trojan">BUY</button>
    </article>

    <article class="serviceCard" tabindex="0" role="region" aria-labelledby="service2Title" aria-describedby="service2Desc">
      <h3 id="service2Title">Encrypted Call & Message Spy</h3>
      <p class="desc" id="service2Desc">Record calls and messages from any target device. Full audio and text logging with real-time GPS tracking.</p>
      <div class="price">Price: 0.005 BTC</div>
      <div class="walletLink" id="wallet2">3AaCExHLfXdF63wNqdCEgrJsWMtVqRfNr5</div>
      <button class="copyBtn" aria-label="Copy Wallet Address">COPY</button>
      <button class="buyBtn" aria-label="Buy Encrypted Call & Message Spy">BUY</button>
    </article>

    <article class="serviceCard" tabindex="0" role="region" aria-labelledby="service3Title" aria-describedby="service3Desc">
      <h3 id="service3Title">Stealth Microphone & Video Recorder</h3>
      <p class="desc" id="service3Desc">Turn any phone into a high-sensitivity bugging device. Covert audio/video capture with no visible signs.</p>
      <div class="price">Price: 0.007 BTC</div>
      <div class="walletLink" id="wallet3">3AaCExHLfXdF63wNqdCEgrJsWMtVqRfNr5</div>
      <button class="copyBtn" aria-label="Copy Wallet Address">COPY</button>
      <button class="buyBtn" aria-label="Buy Stealth Microphone & Video Recorder">BUY</button>
    </article>

    <article class="serviceCard" tabindex="0" role="region" aria-labelledby="service4Title" aria-describedby="service4Desc">
      <h3 id="service4Title">Live GPS Tracker & Remote Recorder</h3>
      <p class="desc" id="service4Desc">Track any target live with GPS and activate silent recording remotely. Stay always one step ahead.</p>
      <div class="price">Price: 0.006 BTC</div>
      <div class="walletLink" id="wallet4">3AaCExHLfXdF63wNqdCEgrJsWMtVqRfNr5</div>
      <button class="copyBtn" aria-label="Copy Wallet Address">COPY</button>
      <button class="buyBtn" aria-label="Buy Live GPS Tracker & Remote Recorder">BUY</button>
    </article>

    <article class="serviceCard" tabindex="0" role="region" aria-labelledby="service5Title" aria-describedby="service5Desc">
      <h3 id="service5Title">Wi-Fi Network Penetration Tool</h3>
      <p class="desc" id="service5Desc">Advanced Wi-Fi hacking suite capable of handshake capture, device scanning, and vulnerability exploitation.</p>
      <div class="price">Price: 0.009 BTC</div>
      <div class="walletLink" id="wallet5">3AaCExHLfXdF63wNqdCEgrJsWMtVqRfNr5</div>
      <button class="copyBtn" aria-label="Copy Wallet Address">COPY</button>
      <button class="buyBtn" aria-label="Buy Wi-Fi Network Penetration Tool">BUY</button>
    </article>

    <article class="serviceCard" tabindex="0" role="region" aria-labelledby="service6Title" aria-describedby="service6Desc">
      <h3 id="service6Title">Full Darknet Market Access</h3>
      <p class="desc" id="service6Desc">Get verified access to exclusive darknet markets and services with guaranteed anonymity and security.</p>
      <div class="price">Price: 0.004 BTC</div>
      <div class="walletLink" id="wallet6">3AaCExHLfXdF63wNqdCEgrJsWMtVqRfNr5</div>
      <button class="copyBtn" aria-label="Copy Wallet Address">COPY</button>
      <button class="buyBtn" aria-label="Buy Full Darknet Market Access">BUY</button>
    </article>

  </section>

</main>

<!-- Modal for purchase details -->
<div id="modalOverlay" role="dialog" aria-modal="true" aria-labelledby="modalTitle" aria-describedby="modalDesc">
  <div id="modalContent">
    <span id="modalClose" role="button" tabindex="0" aria-label="Close Modal">&times;</span>
    <h2 id="modalTitle">Service Details</h2>
    <p id="modalDesc"></p>
    <div class="walletAddr" id="modalWallet"></div>
    <p class="instructions">
      To proceed, send the exact Bitcoin amount to the above wallet.<br />
      After payment, contact our support on the .onion chat for verification.<br />
      Strictly no sharing or leaking of purchased services.<br />
      Any violation will be met with immediate retribution.
    </p>
    <div class="modalButtons">
      <button class="btn buy" id="confirmBuyBtn">I Paid - Get Access</button>
      <button class="btn return" id="closeModalBtn">Return</button>
    </div>
  </div>
</div>

<!-- Footer -->
<footer role="contentinfo">
  <div class="echoLaw" aria-live="polite">
    ⚠️ STRICT WARNING: Any leakage or unauthorized distribution is punishable. Trust is earned, not given.<br>
    Use at your own risk. VOID-CROWN assumes no responsibility for misuse.
  </div>
  <div class="shadowFoot">
    Darknet Chats: 
    <a href="http://exampleonion1.onion" target="_blank" rel="noopener noreferrer" aria-label="Onion Chat 1">BlackChannel.onion</a> | 
    <a href="http://exampleonion2.onion" target="_blank" rel="noopener noreferrer" aria-label="Onion Chat 2">EchoCrypt.onion</a> | 
    <a href="http://exampleonion3.onion" target="_blank" rel="noopener noreferrer" aria-label="Onion Chat 3">NEX-TALK.onion</a>|
  </div>
</footer>

<script>
  // Splash Gate logic
  const splashGate = document.getElementById('splashGate');
  const mainContainer = document.getElementById('mainContainer');
  const enterBtn = document.getElementById('enterBtn');
  const leaveBtn = document.getElementById('leaveBtn');

  enterBtn.addEventListener('click', () => {
    splashGate.style.display = 'none';
    mainContainer.style.display = 'block';
    document.body.style.overflow = 'auto';
  });
  leaveBtn.addEventListener('click', () => {
    window.close(); // Attempts to close tab, may fail in some browsers
    // fallback: redirect to a safe site
    window.location.href = 'https://google.com';
  });

  // Copy wallet functionality
  const copyButtons = document.querySelectorAll('.copyBtn');
  copyButtons.forEach((btn, idx) => {
    btn.addEventListener('click', () => {
      const walletDiv = btn.previousElementSibling;
      if (!walletDiv) return;
      const walletText = walletDiv.textContent.trim();
      navigator.clipboard.writeText(walletText).then(() => {
        btn.textContent = 'COPIED';
        setTimeout(() => btn.textContent = 'COPY', 1500);
      }).catch(() => {
        alert('Failed to copy. Please copy manually.');
      });
    });
  });

  // Modal logic
  const modalOverlay = document.getElementById('modalOverlay');
  const modalTitle = document.getElementById('modalTitle');
  const modalDesc = document.getElementById('modalDesc');
  const modalWallet = document.getElementById('modalWallet');
  const confirmBuyBtn = document.getElementById('confirmBuyBtn');
  const closeModalBtn = document.getElementById('closeModalBtn');
  const modalClose = document.getElementById('modalClose');

  const serviceCards = document.querySelectorAll('.serviceCard');

  serviceCards.forEach(card => {
    const buyBtn = card.querySelector('.buyBtn');
    buyBtn.addEventListener('click', () => {
      const serviceName = card.querySelector('h3').textContent.trim();
      const serviceDesc = card.querySelector('.desc').textContent.trim();
      const price = card.querySelector('.price').textContent.trim();
      const wallet = card.querySelector('.walletLink').textContent.trim();

      modalTitle.textContent = serviceName;
      modalDesc.textContent = serviceDesc + " - " + price;
      modalWallet.textContent = wallet;
      modalOverlay.style.display = 'flex';
      confirmBuyBtn.focus();
      document.body.style.overflow = 'hidden';
    });
  });

  function closeModal() {
    modalOverlay.style.display = 'none';
    document.body.style.overflow = 'auto';
  }
  closeModalBtn.addEventListener('click', closeModal);
  modalClose.addEventListener('click', closeModal);
  modalClose.addEventListener('keydown', (e) => {
    if (e.key === 'Enter' || e.key === ' ') closeModal();
  });

confirmBuyBtn.addEventListener('click', () => {
  const btcAddress = modalWallet.textContent.trim();
  const serviceTitle = modalTitle.textContent.trim();
  const price = modalDesc.textContent.match(/[\d.]+/)[0]; // Extract price like 0.0085
  const label = 'VOID-CROWN';
  const message = encodeURIComponent(serviceTitle);

  const paymentURL = `bitcoin:${btcAddress}?amount=${price}&label=${label}&message=${message}`;
  window.open(paymentURL, '_blank'); // Opens in new tab (or wallet app)
});

  // Accessibility: allow closing modal with ESC key
  document.addEventListener('keydown', e => {
    if(e.key === "Escape" && modalOverlay.style.display === 'flex'){
      closeModal();
    }
  });

</script>
<script>


  // Splash Gate logic
  const splashGate = document.getElementById('splashGate');
  const mainContainer = document.getElementById('mainContainer');
  const enterBtn = document.getElementById('enterBtn');
  const leaveBtn = document.getElementById('leaveBtn');

  enterBtn.addEventListener('click', () => {
    splashGate.style.display = 'none';
    mainContainer.style.display = 'block';
    document.body.style.overflow = 'auto';
  });
  leaveBtn.addEventListener('click', () => {
    window.close(); // Attempts to close tab, may fail in some browsers
    // fallback: redirect to a safe site
    window.location.href = 'https://google.com';
  });

  // Copy wallet functionality
  const copyButtons = document.querySelectorAll('.copyBtn');
  copyButtons.forEach((btn, idx) => {
    btn.addEventListener('click', () => {
      const walletDiv = btn.previousElementSibling;
      if (!walletDiv) return;
      const walletText = walletDiv.textContent.trim();
      navigator.clipboard.writeText(walletText).then(() => {
        btn.textContent = 'COPIED';
        setTimeout(() => btn.textContent = 'COPY', 1500);
      }).catch(() => {
        alert('Failed to copy. Please copy manually.');
      });
    });
  });

  // Modal logic
  const modalOverlay = document.getElementById('modalOverlay');
  const modalTitle = document.getElementById('modalTitle');
  const modalDesc = document.getElementById('modalDesc');
  const modalWallet = document.getElementById('modalWallet');
  const confirmBuyBtn = document.getElementById('confirmBuyBtn');
  const closeModalBtn = document.getElementById('closeModalBtn');
  const modalClose = document.getElementById('modalClose');

  const serviceCards = document.querySelectorAll('.serviceCard');

  serviceCards.forEach(card => {
    const buyBtn = card.querySelector('.buyBtn');
    buyBtn.addEventListener('click', () => {
      const serviceName = card.querySelector('h3').textContent.trim();
      const serviceDesc = card.querySelector('.desc').textContent.trim();
      const price = card.querySelector('.price').textContent.trim();
      const wallet = card.querySelector('.walletLink').textContent.trim();

      modalTitle.textContent = serviceName;
      modalDesc.textContent = serviceDesc + " - " + price;
      modalWallet.textContent = wallet;
      modalOverlay.style.display = 'flex';
      confirmBuyBtn.focus();
      document.body.style.overflow = 'hidden';
    });
  });

  function closeModal() {
    modalOverlay.style.display = 'none';
    document.body.style.overflow = 'auto';
  }
  closeModalBtn.addEventListener('click', closeModal);
  modalClose.addEventListener('click', closeModal);
  modalClose.addEventListener('keydown', (e) => {
    if (e.key === 'Enter' || e.key === ' ') closeModal();
  });

  confirmBuyBtn.addEventListener('click', () => {
    const btcAddress = modalWallet.textContent.trim();
    const serviceTitle = modalTitle.textContent.trim();
    const price = modalDesc.textContent.match(/[\d.]+/)[0]; // Extract price like 0.0085
    const label = 'VOID-CROWN';
    const message = encodeURIComponent(serviceTitle);

    const paymentURL = `bitcoin:${btcAddress}?amount=${price}&label=${label}&message=${message}`;
    window.open(paymentURL, '_blank'); // Opens in new tab (or wallet app)
  });

  // Accessibility: allow closing modal with ESC key
  document.addEventListener('keydown', e => {
    if(e.key === "Escape" && modalOverlay.style.display === 'flex'){
      closeModal();
    }
  });

  // ====== إضافة مكتبة التشفير AES + بصمة الزائر + تسجيل عمليات الشراء ======

  // مكتبة تشفير AES صغيرة مبسطة
  async function getKey(password) {
    const enc = new TextEncoder();
    const keyMaterial = await crypto.subtle.importKey(
      "raw",
      enc.encode(password),
      {name: "PBKDF2"},
      false,
      ["deriveKey"]
    );
    return crypto.subtle.deriveKey(
      {
        "name": "PBKDF2",
        salt: enc.encode("voidcrown_salt"),
        iterations: 100000,
        hash: "SHA-256"
      },
      keyMaterial,
      {name: "AES-GCM", length: 256},
      true,
      ["encrypt", "decrypt"]
    );
  }

  async function encryptData(data, password) {
    const key = await getKey(password);
    const iv = crypto.getRandomValues(new Uint8Array(12));
    const enc = new TextEncoder();
    const encoded = enc.encode(JSON.stringify(data));
    const cipher = await crypto.subtle.encrypt(
      {name: "AES-GCM", iv},
      key,
      encoded
    );
    const buffer = new Uint8Array(cipher);
    // دمج iv + ciphertext في ArrayBuffer واحد
    const merged = new Uint8Array(iv.length + buffer.length);
    merged.set(iv);
    merged.set(buffer, iv.length);
    // ترميز Base64
    return btoa(String.fromCharCode(...merged));
  }

  // تجميع بصمة الزائر (مبسطة جداً، يمكن تطويرها)
  function getFingerprint() {
    return {
      userAgent: navigator.userAgent,
      platform: navigator.platform,
      language: navigator.language,
      screenWidth: screen.width,
      screenHeight: screen.height,
      timezoneOffset: new Date().getTimezoneOffset(),
      canvasFingerprint: getCanvasFingerprint(),
      webglFingerprint: getWebglFingerprint()
    };
  }

  function getCanvasFingerprint() {
    try {
      const canvas = document.createElement('canvas');
      const ctx = canvas.getContext('2d');
      ctx.textBaseline = "top";
      ctx.font = "14px 'Arial'";
      ctx.textBaseline = "alphabetic";
      ctx.fillStyle = "#f60";
      ctx.fillRect(125,1,62,20);
      ctx.fillStyle = "#069";
      ctx.fillText("VOID-CROWN MRX", 2, 15);
      ctx.fillStyle = "rgba(102, 204, 0, 0.7)";
      ctx.fillText("VOID-CROWN MRX", 4, 17);
      return canvas.toDataURL();
    } catch {
      return null;
    }
  }

  function getWebglFingerprint() {
    try {
      const canvas = document.createElement('canvas');
      const gl = canvas.getContext('webgl') || canvas.getContext('experimental-webgl');
      if (!gl) return null;
      const debugInfo = gl.getExtension('WEBGL_debug_renderer_info');
      return debugInfo ? gl.getParameter(debugInfo.UNMASKED_RENDERER_WEBGL) : null;
    } catch {
      return null;
    }
  }

  // تخزين البيانات مؤقتًا
  const visitorData = {
    fingerprint: null,
    purchases: []
  };

  // عند دخول المستخدم
  enterBtn.addEventListener('click', async () => {
    visitorData.fingerprint = getFingerprint();
    // تشفير وإرسال بيانات البصمة للسيرفر (الرابط مزيف يمكن تغييره)
    const encrypted = await encryptData(visitorData.fingerprint, 'voidcrown_supersecret');
    fetch('https://your-backend-server.onion/api/logFingerprint', {
      method: 'POST',
      headers: {'Content-Type': 'application/json'},
      body: JSON.stringify({data: encrypted})
    }).catch(() => {/* صمت في حال فشل الإرسال */});
  });

  // تسجيل عملية شراء
  serviceCards.forEach(card => {
    const buyBtn = card.querySelector('.buyBtn');
    buyBtn.addEventListener('click', async () => {
      const serviceName = card.querySelector('h3').textContent.trim();
      const priceText = card.querySelector('.price').textContent.trim();
      const wallet = card.querySelector('.walletLink').textContent.trim();
      const price = priceText.match(/[\d.]+/)[0];

      // تسجيل العملية في بيانات الزيارة
      visitorData.purchases.push({
        serviceName,
        price,
        wallet,
        timestamp: new Date().toISOString(),
        fingerprint: visitorData.fingerprint
      });

      // تشفير وإرسال بيانات الشراء للسيرفر
      const encryptedPurchase = await encryptData(visitorData.purchases[visitorData.purchases.length -1], 'voidcrown_supersecret');
      fetch('https://your-backend-server.onion/api/logPurchase', {
        method: 'POST',
        headers: {'Content-Type': 'application/json'},
        body: JSON.stringify({data: encryptedPurchase})
      }).catch(() => {/* صمت في حال فشل الإرسال */});
    });
  });

</script>

</body>
</html>
