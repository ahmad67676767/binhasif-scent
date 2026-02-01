<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Binhasif Scents | Let the smoke speak peace</title>

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">

<style>
:root {
  --black: #0b0b0b;
  --gold: #c9a24d;
  --soft-gold: #e6d39a;
  --white: #f5f5f5;
  --gray: #b0b0b0;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-color: var(--black);
  color: var(--white);
  font-family: 'Inter', sans-serif;
  line-height: 1.7;
}

/* ---------- HEADER ---------- */
header {
  padding: 70px 10%;
  text-align: center;
  border-bottom: 1px solid rgba(201,162,77,0.2);
}

header h1 {
  font-family: 'Playfair Display', serif;
  font-size: 3rem;
  color: var(--gold);
  letter-spacing: 2px;
}

header p {
  margin-top: 12px;
  color: var(--gray);
  font-size: 1rem;
}

/* ---------- HERO ---------- */
.hero {
  padding: 80px 10%;
  text-align: center;
}

.hero h2 {
  font-family: 'Playfair Display', serif;
  font-size: 2.5rem;
  margin-bottom: 25px;
}

.hero p {
  max-width: 800px;
  margin: auto;
  color: var(--gray);
  font-size: 1.05rem;
}

/* ---------- SECTION ---------- */
section {
  padding: 80px 10%;
}

/* ---------- STORY ---------- */
.story h3,
.products h3 {
  font-family: 'Playfair Display', serif;
  font-size: 2rem;
  color: var(--gold);
  margin-bottom: 30px;
}

.story p {
  max-width: 900px;
  color: var(--gray);
  margin-bottom: 18px;
}

/* ---------- PRODUCTS ---------- */
.products-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 30px;
}

.product-card {
  background: rgba(255,255,255,0.03);
  border: 1px solid rgba(201,162,77,0.25);
  padding: 30px;
  border-radius: 12px;
  transition: transform 0.3s ease, border 0.3s ease;
}

.product-card:hover {
  transform: translateY(-6px);
  border: 1px solid var(--gold);
}

.product-card h4 {
  font-family: 'Playfair Display', serif;
  font-size: 1.4rem;
  color: var(--soft-gold);
  margin-bottom: 12px;
}

.product-card p {
  color: var(--gray);
  margin-bottom: 18px;
  font-size: 0.95rem;
}

.price {
  font-size: 1.2rem;
  font-weight: 500;
  color: var(--gold);
}

/* ---------- FOOTER ---------- */
footer {
  padding: 50px 10%;
  border-top: 1px solid rgba(201,162,77,0.2);
  text-align: center;
}

footer p {
  color: var(--gray);
  font-size: 0.9rem;
}

@media (max-width: 600px) {
  header h1 {
    font-size: 2.3rem;
  }

  .hero h2 {
    font-size: 2rem;
  }
}
</style>
</head>

<body>

<header>
  <h1>Binhasif Scents</h1>
  <p>Let the smoke speak peace</p>
</header>

<section class="hero">
  <h2>Incense Made With Intention</h2>
  <p>
    Binhasif Scents is not about overpowering fragrance.
    It is about calm. About purity. About incense made the
    way it has always been — slow, natural, and respectful
    of tradition.
  </p>
</section>

<section class="story">
  <h3>Our Story</h3>
  <p>
    I didn’t plan to start selling incense — I was simply making it
    the way I grew up with. In my family, incense was part of daily life.
    It wasn’t just for scent, but for peace, prayer, and clarity of space.
  </p>
  <p>
    Over time, I noticed that much of what was on the market lacked soul.
    Too many shortcuts. Too many artificial touches. I knew the difference,
    because I had lived with the real thing.
  </p>
  <p>
    Binhasif Scents exists to restore incense that feels honest, grounding,
    and meaningful — incense that belongs in a quiet room.
  </p>
</section>

<section class="products">
  <h3>Our Incense</h3>

  <div class="products-grid">

    <div class="product-card">
      <h4>Nihla Halut</h4>
      <p>
        A rare and deep incense with a warm, grounding smoke.
        Best suited for reflection, prayer, and intimate spaces.
      </p>
      <div class="price">30,000</div>
    </div>

    <div class="product-card">
      <h4>Dhufr</h4>
      <p>
        A powerful, premium incense with strong presence and clarity.
        Long-lasting smoke with a noble and traditional character.
      </p>
      <div class="price">80,000</div>
    </div>

    <div class="product-card">
      <h4>Sandal Flakes</h4>
      <p>
        Soft, smooth, and calming. Sandal flakes release a gentle aroma
        that purifies the space without overwhelming it.
      </p>
      <div class="price">45,000</div>
    </div>

  </div>
</section>

<footer>
  <p>© 2026 Binhasif Scents — Crafted with care and intention</p>
</footer>

</body>
</html>
