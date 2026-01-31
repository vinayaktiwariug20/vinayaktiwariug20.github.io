<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Vinayak Tiwari</title>

  <style>
    body {
      margin: 0;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: "Segoe UI", sans-serif;
      background: url('assets/bubground.png') no-repeat center / cover fixed;
      color: #000;
    }

    main.container {
      background: rgba(255, 255, 255, 0.75);
      border-radius: 30px;
      padding: 2.5rem;
      max-width: 640px;
      width: 90%;
      box-shadow: 0 0 20px rgba(0, 200, 255, 0.4);
      backdrop-filter: blur(8px);
    }

    section.card {
      margin-bottom: 2rem;
    }

    h1 {
      font-size: 3rem;
      margin-bottom: 0.3em;
    }

    p {
      font-size: 1.2rem;
      margin-bottom: 1.2em;
    }

    nav.links {
      display: flex;
      gap: 1rem;
      justify-content: center;
      flex-wrap: wrap;
    }

    a.button {
      padding: 0.7em 1.6em;
      background: linear-gradient(to bottom right, #a0e6ff, #50c0e0);
      border-radius: 25px;
      color: #004466;
      text-decoration: none;
      font-weight: 600;
      box-shadow: 0 3px 8px rgba(0, 150, 255, 0.3);
      transition: transform 0.2s ease;
    }

    a.button:hover {
      transform: scale(1.05);
    }

    a.button:focus-visible {
      outline: 3px solid #50c0e0;
      outline-offset: 4px;
    }
  </style>
</head>

<body>
  <main class="container">

    <section class="card intro">
      <h1>Vinayak Tiwari</h1>
      <p>Welcome to my GitHub Pages site.</p>

      <nav class="links">
        <a class="button" href="https://www.linkedin.com/in/vinayak09" target="_blank" rel="noopener noreferrer">LinkedIn</a>
        <a class="button" href="https://github.com/vinayaktiwariug20" target="_blank" rel="noopener noreferrer">GitHub</a>
      </nav>
    </section>

    <section class="card">
      <a class="button" href="https://vinayaktiwariug20.github.io/waste-classify" target="_blank" rel="noopener noreferrer">
        Machine Learning: Waste Image Classification
      </a>
    </section>

    <section class="card">
      <a class="button" href="https://vinayaktiwariug20.github.io/StrideSync-demo" target="_blank" rel="noopener noreferrer">
        Retail Product Webpage Demo
      </a>
    </section>

  </main>
</body>
</html>
