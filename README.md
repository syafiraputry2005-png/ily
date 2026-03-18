<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Prettiest Thing</title>
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <style>
    body {
      margin: 0;
      padding: 0;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      background: linear-gradient(135deg, #1a1a2e 60%, #22223b 100%);
      color: #f8f0f5;
      font-family: 'Inter', 'Segoe UI', sans-serif;
      transition: background 1s;
    }
    main {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      animation: fadein 1.8s cubic-bezier(.77,0,.18,1) 1;
    }
    h1 {
      font-size: 2.2rem;
      font-weight: 300;
      letter-spacing: 0.07em;
      margin-bottom: 2.5rem;
      text-align: center;
      color: #ffe6e6;
      text-shadow: 0 3px 30px #a7b4fa22, 0 2px 8px #ce7b7b11;
      animation: softGlow 2.5s ease-in-out infinite alternate;
    }
    @keyframes fadein {
      0% { opacity: 0; transform: translateY(24px);}
      100% { opacity: 1; transform: translateY(0);}
    }
    @keyframes softGlow {
      from { text-shadow: 0 3px 30px #a7b4fa22, 0 2px 8px #ce7b7b11; }
      to   { text-shadow: 0 6px 80px #debadf44, 0 3px 18px #ded8ff44; }
    }
    .spotify {
      border-radius: 14px;
      overflow: hidden;
      box-shadow: 0 6px 24px #00000040;
      margin-bottom: 1.5rem;
      animation: fadein 2.2s 0.5s backwards;
      width: 320px;
      max-width: 92vw;
    }
    @media (max-width: 480px) {
      h1 { font-size: 1.2rem; }
      .spotify { width: 98vw; }
    }
  </style>
</head>
<body>
  <main>
    <h1>you’re the prettiest thing i’ve ever seen</h1>
    <div class="spotify">
      <iframe src="https://open.spotify.com/embed/track/6BNkRxF4uJ1Nhy8ynZGY9R?theme=dark"
        width="100%" height="80" frameborder="0" allowtransparency="true"
        allow="encrypted-media"></iframe>
    </div>
  </main>
</body>
</html>



ini diapain
