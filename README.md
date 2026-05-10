# Take-food-restaurant-
Responsive website for Take Food Restaurant Lagos Island - 24/7 food, delivery, dine-in
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Take Food Restaurant Lagos Island | 24/7 Restaurant & Delivery</title>
<meta name="description" content="Take Food Restaurant Lagos Island. Open 24 hours. Dine-in, Drive-through, Delivery via Glovo. Call 0913 363 2817. 5 Upper Campus, Lagos Island.">
<style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif; }
  body { background: #0f0f0f; color: #fff; line-height: 1.6; }
  .container { max-width: 900px; margin: 0 auto; padding: 20px; }
  header { text-align: center; padding: 40px 20px; background: linear-gradient(135deg, #ff4d00, #ff8800); border-radius: 16px; }
  header h1 { font-size: 2.2rem; margin-bottom: 8px; }
  .rating { display: flex; justify-content: center; align-items: center; gap: 8px; margin: 10px 0; }
  .stars { color: #ffc107; }
  .tags { display: flex; flex-wrap: wrap; gap: 8px; justify-content: center; margin-top: 12px; }
  .tag { background: rgba(255,255,255,0.2); padding: 6px 12px; border-radius: 20px; font-size: 0.9rem; }
  
  .actions { display: grid; grid-template-columns: repeat(3, 1fr); gap: 12px; margin: 30px 0; }
  .btn { display: flex; flex-direction: column; align-items: center; justify-content: center; padding: 16px; background: #1e1e1e; border-radius: 12px; text-decoration: none; color: #fff; transition: 0.2s; }
  .btn:hover { background: #2a2a2a; transform: translateY(-2px); }
  .btn-primary { background: #ff4d00; }
  .btn-primary:hover { background: #e64400; }
  .btn-icon { font-size: 24px; margin-bottom: 6px; }
  
  section { margin: 40px 0; }
  h2 { font-size: 1.5rem; margin-bottom: 16px; color: #ff8800; }
  .info-grid { display: grid; gap: 12px; }
  .info-item { display: flex; gap: 12px; align-items: flex-start; background: #1e1e1e; padding: 16px; border-radius: 12px; }
  
  .gallery { display: grid; grid-template-columns: repeat(3, 1fr); gap: 8px; }
  .gallery img { width: 100%; height: 120px; object-fit: cover; border-radius: 8px; background: #2a2a2a; }
  
  footer { text-align: center; padding: 30px 20px; color: #888; font-size: 0.9rem; }
  
  @media (min-width: 768px) {
    header h1 { font-size: 3rem; }
    .actions { grid-template-columns: repeat(5, 1fr); }
    .gallery { grid-template-columns: repeat(6, 1fr); }
  }
</style>
</head>
<body>
  <div class="container">
    <header>
      <h1>Take Food Restaurant</h1>
      <p>Lagos Island</p>
      <div class="rating">
        <span class="stars">★★☆</span>
        <span>3.7</span>
        <span>• 97 reviews</span>
        <span>• ₦1–10,000</span>
      </div>
      <div class="tags">
        <span class="tag">Dine-in</span>
        <span class="tag">Drive-through</span>
        <span class="tag">Delivery</span>
        <span class="tag">Open 24 Hours</span>
      </div>
    </header>

    <div class="actions">
      <a href="https://www.google.com/maps/search/?api=1&query=5+Upper+Campus+Lagos+Island" class="btn" target="_blank">
        <span class="btn-icon">📍</span>
        <span>Directions</span>
      </a>
      <a href="tel:09133632817" class="btn btn-primary">
        <span class="btn-icon">📞</span>
        <span>Call</span>
      </a>
      <a href="https://glovoapp.com" class="btn" target="_blank">
        <span class="btn-icon">🛵</span>
        <span>Order on Glovo</span>
      </a>
      <a href="#" class="btn">
        <span class="btn-icon">💾</span>
        <span>Save</span>
      </a>
      <a href="whatsapp://send?text=Check out Take Food Restaurant Lagos Island!" class="btn">
        <span class="btn-icon">📤</span>
        <span>Share</span>
      </a>
    </div>

    <section>
      <h2>About</h2>
      <div class="info-grid">
        <div class="info-item">
          <span>📍</span>
          <div>
            <strong>Address</strong><br>
            5 Upper Campus, Lagos Island, 102273, Lagos
          </div>
        </div>
        <div class="info-item">
          <span>🕒</span>
          <div>
            <strong>Hours</strong><br>
            Open 24 Hours, 7 Days a Week
          </div>
        </div>
        <div class="info-item">
          <span>💰</span>
          <div>
            <strong>Price Range</strong><br>
            ₦1–10,000 per person
          </div>
        </div>
        <div class="info-item">
          <span>🍽️</span>
          <div>
            <strong>Services</strong><br>
            Dine-in, Drive-through, Delivery
          </div>
        </div>
      </div>
    </section>

    <section>
      <h2>Photos</h2>
      <div class="gallery">
        <img src="https://via.placeholder.com/300x200/ff4d00/fff?text=Food+1" alt="Food photo">
        <img src="https://via.placeholder.com/300x200/ff8800/fff?text=Food+2" alt="Food photo">
        <img src="https://via.placeholder.com/300x200/ff4d00/fff?text=Food+3" alt="Food photo">
        <img src="https://via.placeholder.com/300x200/ff8800/fff?text=Food+4" alt="Food photo">
        <img src="https://via.placeholder.com/300x200/ff4d00/fff?text=Food+5" alt="Food photo">
        <img src="https://via.placeholder.com/300x200/ff8800/fff?text=Food+6" alt="Food photo">
      </div>
      <p style="text-align:center; margin-top:12px; color:#888;">Replace these with your real photos</p>
    </section>

    <section>
      <h2>Contact</h2>
      <div class="info-grid">
        <div class="info-item">
          <span>📞</span>
          <div>
            <strong>Phone</strong><br>
            <a href="tel:09133632817" style="color:#ff8800;">0913 363 2817</a>
          </div>
        </div>
        <div class="info-item">
          <span>🛵</span>
          <div>
            <strong>Order Online</strong><br>
            <a href="https://glovoapp.com" target="_blank" style="color:#ff8800;">Order on Glovo</a>
          </div>
        </div>
      </div>
    </section>

    <footer>
      <p>© 2026 Take Food Restaurant Lagos Island. Built to attract more customers.</p>
    </footer>
  </div>
</body>
</html>
