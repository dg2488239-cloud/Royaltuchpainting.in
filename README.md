 https://github.com/dg2488239-cloud/Royaltuchpainting.in/blob/564cc0191bcd5448676ed0b76cca393f93ae0170/IMG_6962.png   index.html
<!DOCTYPE html>

<html>

<head>

<meta charset="UTF-8">

<title>Royal Tuch Painting</title>

</head>

<body>

<h1>Royal Tuch Painting</h1>

<p>Professional House Painting Service</p>

<h2>Services</h2>

<ul>

<li>Interior Painting</li>

<li>Exterior Painting</li>

<li>Wall Putty</li>

<li>Texture Painting</li>

<li>Royale Play</li>

<li>Waterproofing</li>

<li>Wood Polish</li>

<li>Metal Painting</li>

<li>Apartment Painting</li>

<li>Villa Painting</li>

</ul>

</body>

</html>
Updated website
<h2>Our Recent Projects</h2>
<h2>Contact Us</h2> 
src="GOOGLE_MAPS_LINK"
from pathlib import Path

html = r'''<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Royal Tuch Painting Services Bangalore - Interior, Exterior, Texture, Waterproofing and Premium Painting Solutions.">
  <meta name="keywords" content="painting services Bangalore, house painting Bangalore, interior painting, exterior painting, texture painting, waterproofing">
  <meta name="theme-color" content="#0b1f3a">
  <title>Royal Tuch Painting Services Bangalore</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>

  <header>
    <div class="container">
      <a href="#home" class="logo-link">
        <img src="logo.jpg" alt="Royal Tuch Painting logo">
      </a>

      <nav>
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#projects">Projects</a>
        <a href="#reviews">Reviews</a>
        <a href="#quote">Get Quote</a>
      </nav>
    </div>
  </header>

  <main>

    <section id="home" class="hero">
      <div class="container">
        <div class="hero-content">
          <p class="eyebrow">Bangalore Professional Painting Service</p>
          <h1>Professional House Painting Service</h1>
          <p>Interior, Exterior, Texture, Waterproofing &amp; Premium Painting Solutions.</p>

          <div class="hero-buttons">
            <a class="btn" href="#quote">Get Free Quote</a>
            <a class="btn" href="tel:8009503341">Call Now</a>
            <a class="btn" href="https://wa.me/919035376925" target="_blank" rel="noopener">WhatsApp</a>
          </div>

          <div class="hero-points">
            <span>500+ Projects</span>
            <span>10+ Years Experience</span>
            <span>Professional Focus</span>
          </div>
        </div>
      </div>
    </section>

    <section id="services" class="section">
      <div class="container">
        <h2>Our Painting Services</h2>
        <p class="section-intro">Complete painting solutions for homes, apartments, villas and commercial spaces in Bangalore.</p>

        <div class="cards">
          <article class="card">
            <h3>Interior Painting</h3>
            <p>Premium interior painting, repainting, putty, primer and washable emulsion finishes.</p>
          </article>

          <article class="card">
            <h3>Exterior Painting</h3>
            <p>Exterior wall preparation and durable weather-resistant painting solutions.</p>
          </article>

          <article class="card">
            <h3>Texture &amp; Designer Walls</h3>
            <p>Modern texture, feature walls, Royale Play and designer decorative finishes.</p>
          </article>

          <article class="card">
            <h3>Waterproofing</h3>
            <p>Terrace, wall and damp-area waterproofing solutions with proper surface preparation.</p>
          </article>

          <article class="card">
            <h3>Commercial Painting</h3>
            <p>Painting services for offices, shops, apartments and other commercial properties.</p>
          </article>

          <article class="card">
            <h3>House Repainting</h3>
            <p>Complete repainting with crack repair, masking, cleaning and professional finishing.</p>
          </article>
        </div>
      </div>
    </section>

    <section class="section calculator-section">
      <div class="container">
        <h2>Quick Painting Estimate</h2>
        <p class="section-intro">Enter your approximate area to get a quick labour-and-material estimate.</p>

        <div class="calculator">
          <label for="calcArea">Area in sq.ft.</label>
          <input id="calcArea" type="number" min="1" placeholder="Example: 1000">

          <label for="calcType">Painting type</label>
          <select id="calcType">
            <option value="12">Standard Interior - ₹12/sq.ft.</option>
            <option value="18">Premium Interior - ₹18/sq.ft.</option>
            <option value="22">Exterior Painting - ₹22/sq.ft.</option>
            <option value="30">Texture / Designer - ₹30/sq.ft.</option>
          </select>

          <div id="estimate">Estimated Amount: ₹0</div>
          <a class="btn" href="#quote">Get Exact Site Quote</a>
        </div>
      </div>
    </section>

    <section id="projects" class="section">
      <div class="container">
        <h2>Our Recent Projects</h2>
        <p class="section-intro">A few examples of our painting and decorative wall work.</p>

        <div class="gallery">
          <figure>
            <img src="project-geometric-wall.jpg" alt="Geometric feature wall painting project" loading="lazy">
            <figcaption>Geometric Feature Wall</figcaption>
          </figure>

          <figure>
            <img src="project-feature-wall.jpg" alt="Premium feature wall painting project" loading="lazy">
            <figcaption>Premium Feature Wall</figcaption>
          </figure>

          <figure>
            <img src="brand-original.jpg" alt="Royal Tuch Painting project" loading="lazy">
            <figcaption>Royal Tuch Painting Work</figcaption>
          </figure>
        </div>
      </div>
    </section>

    <section id="reviews" class="section">
      <div class="container">
        <h2>Customer Reviews</h2>

        <div class="review-grid">
          <article class="review-card">
            <img src="review-excellent-work.jpg" alt="Customer review proof" loading="lazy">
            <h3>Excellent Work</h3>
            <p>Professional finishing and good quality work.</p>
          </article>

          <article class="review-card">
            <img src="review-arvind.jpg" alt="Arvind customer review" loading="lazy">
            <h3>Arvind</h3>
            <p>Good service and professional painting work.</p>
          </article>

          <article class="review-card">
            <img src="review-ashish.jpg" alt="Ashish customer review" loading="lazy">
            <h3>Ashish</h3>
            <p>Very good painting work and finishing.</p>
          </article>
        </div>
      </div>
    </section>

    <section id="quote" class="section quote-section">
      <div class="container">
        <h2>Get a Free Painting Quote</h2>
        <p class="section-intro">Send your details on WhatsApp and we will contact you for a site visit and quotation.</p>

        <form id="quoteForm">
          <label for="name">Name</label>
          <input id="name" name="name" type="text" placeholder="Your name" required>

          <label for="phone">Mobile Number</label>
          <input id="phone" name="phone" type="tel" inputmode="numeric" maxlength="10" placeholder="10-digit mobile number" required>

          <label for="location">Location</label>
          <input id="location" name="location" type="text" placeholder="Your Bangalore location" required>

          <label for="service">Service Required</label>
          <select id="service" name="service" required>
            <option value="">Select service</option>
            <option>Interior Painting</option>
            <option>Exterior Painting</option>
            <option>House Repainting</option>
            <option>Texture / Designer Wall</option>
            <option>Waterproofing</option>
            <option>Commercial Painting</option>
          </select>

          <label for="area">Approx. Area (sq.ft.)</label>
          <input id="area" name="area" type="number" min="1" placeholder="Example: 1200">

          <button class="btn" type="submit">Send Quote Request on WhatsApp</button>
        </form>
      </div>
    </section>

    <section class="section faq-section">
      <div class="container">
        <h2>Frequently Asked Questions</h2>

        <details>
          <summary>Do you provide a site visit?</summary>
          <p>Yes. Contact us to discuss your requirement and arrange a site visit.</p>
        </details>

        <details>
          <summary>Do you provide labour and material?</summary>
          <p>Yes, quotation options can be provided according to your project requirement.</p>
        </details>

        <details>
          <summary>Do you work across Bangalore?</summary>
          <p>Yes, we provide painting services in Bangalore and nearby areas.</p>
        </details>
      </div>
    </section>

    <section class="cta">
      <div class="container">
        <h2>Need Professional Painting Work?</h2>
        <p>Call or WhatsApp Royal Tuch Painting Services Bangalore today.</p>
        <div class="hero-buttons">
          <a class="btn" href="tel:8009503341">8009503341</a>
          <a class="btn" href="https://wa.me/919035376925" target="_blank" rel="noopener">WhatsApp Us</a>
        </div>
      </div>
    </section>

  </main>

  <footer>
    <div class="container">
      <img src="logo.jpg" alt="Royal Tuch Painting logo" loading="lazy">
      <p>© 2026 Royal Tuch Painting Services Bangalore. All rights reserved.</p>
      <p>Interior • Exterior • Texture • Waterproofing • Premium Painting</p>
    </div>
  </footer>

  <script>
    // Quick estimate calculator
    const calcArea = document.getElementById("calcArea");
    const calcType = document.getElementById("calcType");
    const estimate = document.getElementById("estimate");

    function updateEstimate() {
      const area = Number(calcArea.value) || 0;
      const rate = Number(calcType.value) || 0;
      const total = area * rate;

      estimate.textContent =
        "Estimated Amount: ₹" + total.toLocaleString("en-IN");
    }

    calcArea.addEventListener("input", updateEstimate);
    calcType.addEventListener("change", updateEstimate);

    // WhatsApp quote form
    const quoteForm = document.getElementById("quoteForm");

    quoteForm.addEventListener("submit", function (event) {
      event.preventDefault();

      const name = document.getElementById("name").value.trim();
      const phone = document.getElementById("phone").value.trim();
      const location = document.getElementById("location").value.trim();
      const service = document.getElementById("service").value.trim();
      const area = document.getElementById("area").value.trim();

      if (!/^[0-9]{10}$/.test(phone)) {
        alert("Please enter a valid 10-digit mobile number.");
        return;
      }

      const text = [
        "Hi Royal Tuch Painting,",
        "",
        "I need a painting quotation.",
        "",
        "Name: " + name,
        "Mobile: " + phone,
        "Location: " + location,
        "Service: " + service,
        "Area: " + (area || "Not provided"),
        "",
        "Please contact me for a site visit and quotation."
      ].join("\n");

      const whatsappURL =
        "https://wa.me/919035376925?text=" + encodeURIComponent(text);

      window.open(whatsappURL, "_blank");
    });

    // Keep phone input numeric
    document.getElementById("phone").addEventListener("input", function () {
      this.value = this.value.replace(/\D/g, "").slice(0, 10);
    });
  </script>

</body>
</html>
'''

path = Path("/mnt/data/index.html")
path.write_text(html, encoding="utf-8")
print(f"Created: {path}")
print(f"Size: {path.stat().st_size} bytes")
