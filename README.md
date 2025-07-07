<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>charity: water</title>
  <style>
    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      color: #fff;
      background-color: #f5f5f5;
    }

    header {
      background-color: #fdd429;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
    }

    .logo {
      font-weight: bold;
      font-size: 1.5rem;
      color: #222;
    }

    .donate-btn {
      background-color: #b96536;
      color: white;
      border: none;
      padding: 0.6rem 1.2rem;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
    }

    .hero {
      background-image: url('https://via.placeholder.com/1200x600'); /* Replace with actual image */
      background-size: cover;
      background-position: center;
      position: relative;
      padding: 4rem 2rem;
      display: flex;
      flex-direction: column;
      justify-content: center;
      height: 80vh;
    }

    .overlay {
      background-color: rgba(0, 0, 0, 0.4);
      padding: 2rem;
      max-width: 600px;
      border-radius: 8px;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }

    p {
      font-size: 1.1rem;
      line-height: 1.6;
      margin-bottom: 2rem;
    }

    .cta-buttons {
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
    }

    .cta-buttons .secondary {
      background-color: white;
      color: #222;
      border: none;
      padding: 0.75rem 1.5rem;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
      letter-spacing: 1px;
    }

    .cta-buttons .primary {
      background-color: #b96536;
      color: white;
      border: none;
      padding: 0.75rem 1.5rem;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
      letter-spacing: 1px;
    }

    @media (max-width: 768px) {
      h1 {
        font-size: 2rem;
      }
      .hero {
        padding: 2rem 1rem;
        height: auto;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">charity: water</div>
    <button class="donate-btn">DONATE</button>
  </header>

  <section class="hero">
    <div class="overlay">
      <h1>Water Connects Us All. Let’s Ensure It Reaches Everyone.</h1>
      <p>
        We believe everyone should have access to clean water. That’s why 100% of donations go straight to our water accessibility projects—because change should be as clear as the water we fight for.
      </p>
      <div class="cta-buttons">
        <button class="secondary">BE THE RIPPLE OF CHANGE TODAY</button>
        <button class="primary">DONATE</button>
      </div>
    </div>
  </section>

</body>
</html>

