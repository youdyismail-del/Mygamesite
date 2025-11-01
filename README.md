<!doctype html>
<html lang="hi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Buttons List - Instagram Style</title>
  <style>
    :root{
      --bg-start: #dbeef6;
      --bg-end: #f7d9c3;
      --button-height: 66px;
      --button-radius: 999px;
      --button-padding: 18px 28px;
      --shadow-offset-x: 10px;
      --shadow-offset-y: 10px;
      --shadow-blur: 0px;
    }
    html,body{height:100%;}
    body{
      margin:0;
      font-family: 'Helvetica Neue', Arial, sans-serif;
      background: linear-gradient(180deg,var(--bg-start), var(--bg-end));
      display:flex;
      align-items:flex-start;
      justify-content:center;
      padding:28px 12px 100px 12px;
    }

    .wrap{
      width:100%;
      max-width:420px;
    }

    .list{
      display:flex;
      flex-direction:column;
      gap:18px;
    }

    .btn{
      height:var(--button-height);
      display:flex;
      align-items:center;
      justify-content:center;
      border-radius:var(--button-radius);
      padding:var(--button-padding);
      font-size:18px;
      font-weight:500;
      color:#fff;
      border:4px solid rgba(0,0,0,0.95);
      box-shadow: var(--shadow-offset-x) var(--shadow-offset-y) var(--shadow-blur) rgba(0,0,0,0.9);
      position:relative;
      text-decoration:none;
      overflow:visible;
      transition:transform .08s ease, box-shadow .08s ease;
    }

    .btn:active{ transform:translateY(2px); box-shadow:6px 7px 0 rgba(0,0,0,0.75); }

    .btn-block{ width:100%; }

    /* 🎨 Different colors for each group */
    .btn-red{ background:#ff4c4c; }
    .btn-blue{ background:#007bff; }
    .btn-green{ background:#28a745; }

    .wa{
      position:fixed;
      right:18px;
      bottom:24px;
      width:64px;
      height:64px;
      border-radius:50%;
      background:#25D366;
      display:flex;
      align-items:center;
      justify-content:center;
      box-shadow:0 6px 18px rgba(0,0,0,0.22);
      z-index:50;
      border:4px solid rgba(255,255,255,0.9);
    }
    .wa svg{ width:36px; height:36px; }

    @media (max-width:420px){
      :root{ --button-height:64px; }
      body{ padding-bottom:140px; }
    }

  </style>
</head>
<body>
  <div class="wrap">
    <div class="list">
      <a class="btn btn-block btn-red" href="#">Truck Game</a>
      <a class="btn btn-block btn-blue" href="#">Bus Game</a>
      <a class="btn btn-block btn-green" href="#">Car Games</a>
      <a class="btn btn-block btn-red" href="#">Tractor Games</a>
      <a class="btn btn-block btn-blue" href="#">Play Games Online</a>
      <a class="btn btn-block btn-green" href="#">Bike Games</a>
      <a class="btn btn-block btn-red" href="#">DJ Games</a>
      <a class="btn btn-block btn-blue" href="#">JCB Games</a>
      <a class="btn btn-block btn-green" href="#">Train Games</a>
      <a class="btn btn-block btn-red" href="#">Open World Games</a>
      <a class="btn btn-block btn-blue" href="#">Rikshaw Games</a>
    </div>
  </div>

  <a class="wa" href="https://wa.me/" aria-label="WhatsApp">
    <svg viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
      <path d="M16 3C9.372 3 4 8.372 4 15c0 2.644.83 5.09 2.257 7.126L4 29l6.09-2.247A11.94 11.94 0 0 0 16 27c6.628 0 12-5.372 12-12S22.628 3 16 3z" fill="#fff" opacity="0.06"/>
      <path d="M16 3C9.372 3 4 8.372 4 15c0 2.644.83 5.09 2.257 7.126L4 29l6.09-2.247A11.94 11.94 0 0 0 16 27c6.628 0 12-5.372 12-12S22.628 3 16 3z" stroke="rgba(0,0,0,0.08)"/>
      <path d="M21.7 20.3c-.5-.25-2.9-1.4-3.35-1.55-.45-.15-.78-.25-1.1.25-.33.5-1.3 1.55-1.6 1.88-.3.33-.6.37-1.1.12-.5-.25-2- .74-3.8-2.36-1.4-1.26-2.36-2.82-2.64-3.32-.28-.5-.03-.77.2-1.01.2-.2.45-.5.68-.75.22-.25.3-.42.45-.7.15-.28.08-.52-.04-.74-.12-.22-1.1-2.64-1.5-3.6-.4-.95-.8-.8-1.1-.82l-1-.02c-.3 0-.76.1-1.16.5-.4.4-1.5 1.46-1.5 3.56s1.54 4.12 1.75 4.4c.2.28 3 4.9 7.27 6.84 4.27 1.94 4.27 1.3 5.03 1.22.76-.08 2.5-.98 2.86-1.94.36-.96.36-1.78.25-1.94-.12-.17-.45-.28-.95-.53z" fill="#fff"/>
    </svg>
  </a>

</body>
</html>
