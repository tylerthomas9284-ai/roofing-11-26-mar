# Remaining Page Templates for RoofEdge Website

This document provides the HTML structure and content for the remaining pages. Simply copy these templates and save them as separate files.

---

## financing.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Flexible financing options for your roof replacement. 0% promotional rates available with fast approval.">
  <title>Roof Financing Options | RoofEdge</title>
  <link rel="icon" type="image/png" href="images/favicon.png">
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Copy header from any existing page -->
  <header class="header">
    <div class="header-container">
      <a href="index.html" class="logo">
        <img src="images/logo-icon.png" alt="RoofEdge Logo" width="32" height="32">
        <span>RoofEdge</span>
      </a>
      <nav class="nav-menu">
        <a href="index.html">Home</a>
        <a href="services.html">Services</a>
        <a href="projects.html">Projects</a>
        <a href="reviews.html">Reviews</a>
        <a href="financing.html">Financing</a>
        <a href="about.html">About</a>
        <a href="blog.html">Blog</a>
        <a href="contact.html">Contact</a>
      </nav>
      <div class="header-actions">
        <a href="tel:5550130ROOF" class="phone-link"><span>📞</span><span>(555) 013-ROOF</span></a>
        <a href="contact.html" class="btn btn-primary">Get Free Estimate</a>
        <a href="emergency-repair.html" class="btn btn-secondary btn-small">Emergency 24/7</a>
      </div>
      <button class="mobile-menu-toggle" aria-label="Toggle mobile menu">
        <span></span><span></span><span></span>
      </button>
    </div>
  </header>

  <section class="hero" style="background: var(--gradient-primary); color: white;">
    <div class="container">
      <div class="hero-content" style="max-width: 700px; text-align: center; margin: 0 auto;">
        <span class="badge badge-success">0% APR Available</span>
        <h1 style="color: white;">Roof Financing Made Easy</h1>
        <p class="hero-subtitle" style="color: rgba(255,255,255,0.9);">
          Get your new roof today with affordable monthly payments. Fast approval, flexible terms, and competitive rates.
        </p>
      </div>
    </div>
  </section>

  <section class="section">
    <div class="container">
      <div class="section-header">
        <h2 class="section-title">Flexible Payment Plans</h2>
        <p class="section-description">Choose a financing option that fits your budget</p>
      </div>

      <div class="grid grid-3">
        <div class="card text-center fade-in-on-scroll">
          <span class="badge badge-primary">Most Popular</span>
          <h3>12 Months</h3>
          <div style="font-size: 2.5rem; font-weight: bold; color: var(--color-primary); margin: 1rem 0;">0%</div>
          <p style="font-size: 0.875rem; color: var(--color-gray);">No interest if paid in full within 12 months</p>
          <ul style="margin: 2rem 0; padding-left: 0; text-align: left;">
            <li style="margin-bottom: 0.75rem;">✓ Example: $6,000 project = $500/month</li>
            <li style="margin-bottom: 0.75rem;">✓ No prepayment penalty</li>
            <li style="margin-bottom: 0.75rem;">✓ Same-day approval</li>
          </ul>
          <a href="#apply" class="btn btn-primary">Apply Now</a>
        </div>

        <div class="card text-center fade-in-on-scroll">
          <h3>24-36 Months</h3>
          <div style="font-size: 2.5rem; font-weight: bold; color: var(--color-primary); margin: 1rem 0;">Low APR</div>
          <p style="font-size: 0.875rem; color: var(--color-gray);">Competitive rates for mid-term financing</p>
          <ul style="margin: 2rem 0; padding-left: 0; text-align: left;">
            <li style="margin-bottom: 0.75rem;">✓ Example: $12,000 project = $350/month</li>
            <li style="margin-bottom: 0.75rem;">✓ Fixed monthly payment</li>
            <li style="margin-bottom: 0.75rem;">✓ Quick online application</li>
          </ul>
          <a href="#apply" class="btn btn-outline">Apply Now</a>
        </div>

        <div class="card text-center fade-in-on-scroll">
          <h3>48-60 Months</h3>
          <div style="font-size: 2.5rem; font-weight: bold; color: var(--color-primary); margin: 1rem 0;">Extended</div>
          <p style="font-size: 0.875rem; color: var(--color-gray);">Lower monthly payments for larger projects</p>
          <ul style="margin: 2rem 0; padding-left: 0; text-align: left;">
            <li style="margin-bottom: 0.75rem;">✓ Example: $18,000 project = $375/month</li>
            <li style="margin-bottom: 0.75rem;">✓ Maximum flexibility</li>
            <li style="margin-bottom: 0.75rem;">✓ Rates as low as 4.99%</li>
          </ul>
          <a href="#apply" class="btn btn-outline">Apply Now</a>
        </div>
      </div>
    </div>
  </section>

  <section class="section bg-light" id="apply">
    <div class="container-narrow">
      <div class="section-header">
        <h2 class="section-title">Check Your Eligibility</h2>
        <p class="section-description">Get pre-qualified in 60 seconds with no impact to your credit score</p>
      </div>

      <form class="card" style="max-width: 600px; margin: 0 auto;">
        <div class="form-group">
          <label for="full-name" class="form-label">Full Name *</label>
          <input type="text" id="full-name" class="form-input" required>
        </div>

        <div class="grid grid-2">
          <div class="form-group">
            <label for="email" class="form-label">Email *</label>
            <input type="email" id="email" class="form-input" required>
          </div>
          <div class="form-group">
            <label for="phone" class="form-label">Phone *</label>
            <input type="tel" id="phone" class="form-input" required>
          </div>
        </div>

        <div class="form-group">
          <label for="project-cost" class="form-label">Estimated Project Cost *</label>
          <select id="project-cost" class="form-select" required>
            <option value="">Select range</option>
            <option value="5000">$5,000 - $10,000</option>
            <option value="10000">$10,000 - $15,000</option>
            <option value="15000">$15,000 - $20,000</option>
            <option value="20000">$20,000+</option>
          </select>
        </div>

        <div class="form-group">
          <label for="income" class="form-label">Annual Household Income *</label>
          <select id="income" class="form-select" required>
            <option value="">Select range</option>
            <option value="40000">$40,000 - $60,000</option>
            <option value="60000">$60,000 - $80,000</option>
            <option value="80000">$80,000 - $100,000</option>
            <option value="100000">$100,000+</option>
          </select>
        </div>

        <button type="submit" class="btn btn-primary btn-large" style="width: 100%;">Check Eligibility</button>
        <p style="text-align: center; margin-top: 1rem; font-size: 0.875rem; color: var(--color-gray);">
          Soft credit check only. No impact to your credit score.
        </p>
      </form>
    </div>
  </section>

  <section class="section">
    <div class="container">
      <div class="section-header">
        <h2 class="section-title">Financing FAQ</h2>
      </div>

      <div class="faq-list">
        <div class="faq-item">
          <button class="faq-question">
            How do I apply for financing?
            <span class="faq-icon">▼</span>
          </button>
          <div class="faq-answer">
            <div class="faq-answer-content">
              Fill out the pre-qualification form above or apply during your free estimate appointment. Approval typically takes less than 24 hours.
            </div>
          </div>
        </div>

        <div class="faq-item">
          <button class="faq-question">
            What credit score do I need?
            <span class="faq-icon">▼</span>
          </button>
          <div class="faq-answer">
            <div class="faq-answer-content">
              We work with a range of credit profiles. Generally, a score of 600+ qualifies for our standard programs, but options are available for lower scores as well.
            </div>
          </div>
        </div>

        <div class="faq-item">
          <button class="faq-question">
            When do I start making payments?
            <span class="faq-icon">▼</span>
          </button>
          <div class="faq-answer">
            <div class="faq-answer-content">
              First payment is typically due 30-45 days after your roof installation is complete. Exact terms depend on your chosen financing plan.
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Copy footer from existing pages -->
  <footer class="footer">
    <!-- ... footer content ... -->
  </footer>

  <div class="mobile-sticky-bar">
    <a href="tel:5550130ROOF" class="btn btn-secondary" style="flex: 1;">Call Now</a>
    <a href="#apply" class="btn btn-primary" style="flex: 1;">Apply Now</a>
  </div>

  <script src="script.js"></script>
</body>
</html>
```

---

## projects.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Browse our portfolio of completed roofing projects. Residential and commercial roof installations across Texas.">
  <title>Our Projects | RoofEdge</title>
  <link rel="icon" type="image/png" href="images/favicon.png">
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Copy header -->
  <header class="header">
    <!-- ... header content ... -->
  </header>

  <section class="hero" style="background: var(--gradient-primary); color: white;">
    <div class="container">
      <div class="hero-content" style="max-width: 700px; text-align: center; margin: 0 auto;">
        <h1 style="color: white;">Our Recent Projects</h1>
        <p class="hero-subtitle" style="color: rgba(255,255,255,0.9);">
          Over 2,000 roofs completed across Texas. See our work and read what customers are saying.
        </p>
      </div>
    </div>
  </section>

  <section class="section">
    <div class="container">
      <div class="gallery-filters">
        <button class="filter-btn active" data-filter="all">All Projects</button>
        <button class="filter-btn" data-filter="residential">Residential</button>
        <button class="filter-btn" data-filter="commercial">Commercial</button>
      </div>

      <div class="gallery-grid">
        <!-- Project 1 -->
        <div class="project-card fade-in-on-scroll" data-category="residential" data-modal-target="project-1">
          <img src="images/project-1.jpg" alt="Residential roof replacement Austin" class="project-image" loading="lazy">
          <!-- Image: Beautiful modern home with new roof -->
          <div class="project-overlay">
            <h3 class="project-title">Modern Shingle Replacement</h3>
            <p class="project-details">Austin, TX • Residential • 3 Days</p>
          </div>
        </div>

        <!-- Project 2 -->
        <div class="project-card fade-in-on-scroll" data-category="commercial" data-modal-target="project-2">
          <img src="images/project-2.jpg" alt="Commercial TPO roof installation" class="project-image" loading="lazy">
          <!-- Image: Commercial building with white TPO roof -->
          <div class="project-overlay">
            <h3 class="project-title">Office Building TPO System</h3>
            <p class="project-details">Dallas, TX • Commercial • 5 Days</p>
          </div>
        </div>

        <!-- Project 3 -->
        <div class="project-card fade-in-on-scroll" data-category="residential" data-modal-target="project-3">
          <img src="images/project-3.jpg" alt="Metal roof installation" class="project-image" loading="lazy">
          <!-- Image: Standing seam metal roof -->
          <div class="project-overlay">
            <h3 class="project-title">Standing Seam Metal Roof</h3>
            <p class="project-details">Houston, TX • Residential • 4 Days</p>
          </div>
        </div>

        <!-- Project 4 -->
        <div class="project-card fade-in-on-scroll" data-category="residential" data-modal-target="project-4">
          <img src="images/project-4.jpg" alt="Storm damage repair" class="project-image" loading="lazy">
          <div class="project-overlay">
            <h3 class="project-title">Storm Damage Restoration</h3>
            <p class="project-details">San Antonio, TX • Residential • 2 Days</p>
          </div>
        </div>

        <!-- Project 5 -->
        <div class="project-card fade-in-on-scroll" data-category="commercial" data-modal-target="project-5">
          <img src="images/project-5.jpg" alt="Multi-family complex roofing" class="project-image" loading="lazy">
          <div class="project-overlay">
            <h3 class="project-title">Apartment Complex Re-Roof</h3>
            <p class="project-details">Fort Worth, TX • Commercial • 10 Days</p>
          </div>
        </div>

        <!-- Project 6 -->
        <div class="project-card fade-in-on-scroll" data-category="residential" data-modal-target="project-6">
          <img src="images/project-6.jpg" alt="Tile roof replacement" class="project-image" loading="lazy">
          <div class="project-overlay">
            <h3 class="project-title">Spanish Tile Roof</h3>
            <p class="project-details">Austin, TX • Residential • 5 Days</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Project Detail Modal Example -->
  <div id="project-1" class="modal">
    <div class="modal-content">
      <div class="modal-header">
        <h2>Modern Shingle Replacement - Austin, TX</h2>
        <div class="modal-close">✕</div>
      </div>
      <div class="modal-body">
        <img src="images/project-1-detail.jpg" alt="Project detail" style="width: 100%; border-radius: var(--radius-md); margin-bottom: 2rem;">
        <div class="grid grid-2">
          <div>
            <h4>Project Details</h4>
            <p><strong>Location:</strong> Austin, TX</p>
            <p><strong>Type:</strong> Residential Replacement</p>
            <p><strong>Timeline:</strong> 3 Days</p>
            <p><strong>Materials:</strong> GAF Timberline HDZ Shingles</p>
          </div>
          <div>
            <h4>Customer Review</h4>
            <div class="stars">★★★★★</div>
            <p>"Exceptional work from start to finish. The crew was professional, the cleanup was thorough, and our new roof looks amazing!"</p>
            <p style="font-weight: bold;">- Sarah M.</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Copy footer -->
  <footer class="footer">
    <!-- ... -->
  </footer>

  <script src="script.js"></script>
</body>
</html>
```

---

## reviews.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Read customer reviews and testimonials from RoofEdge clients. 4.9/5 rating from over 500 reviews.">
  <title>Customer Reviews | RoofEdge</title>
  <link rel="icon" type="image/png" href="images/favicon.png">
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Copy header -->
  <header class="header">
    <!-- ... -->
  </header>

  <section class="hero" style="background: var(--gradient-primary); color: white;">
    <div class="container">
      <div class="hero-content" style="max-width: 700px; text-align: center; margin: 0 auto;">
        <div style="font-size: 4rem; margin-bottom: 1rem;">⭐ 4.9/5</div>
        <h1 style="color: white;">What Our Customers Say</h1>
        <p class="hero-subtitle" style="color: rgba(255,255,255,0.9);">
          Over 500 five-star reviews from satisfied customers across Texas.
        </p>
      </div>
    </div>
  </section>

  <section class="section">
    <div class="container">
      <div class="gallery-filters">
        <button class="filter-btn active" data-filter="all">All Reviews</button>
        <button class="filter-btn" data-filter="google">Google</button>
        <button class="filter-btn" data-filter="yelp">Yelp</button>
        <button class="filter-btn" data-filter="facebook">Facebook</button>
      </div>

      <div class="grid grid-3">
        <div class="review-card fade-in-on-scroll" data-category="google">
          <div class="stars">★★★★★</div>
          <p class="review-text">"RoofEdge replaced our entire roof in just two days. The crew was professional, clean, and the quality is outstanding. Highly recommend!"</p>
          <div class="review-header">
            <div class="review-avatar">SM</div>
            <div class="review-info">
              <h4>Sarah Miller</h4>
              <div class="review-location">Austin, TX • Google</div>
            </div>
          </div>
        </div>

        <div class="review-card fade-in-on-scroll" data-category="google">
          <div class="stars">★★★★★</div>
          <p class="review-text">"After storm damage, RoofEdge responded within hours. They worked with our insurance and handled everything. True professionals."</p>
          <div class="review-header">
            <div class="review-avatar">JD</div>
            <div class="review-info">
              <h4>James Davidson</h4>
              <div class="review-location">Dallas, TX • Google</div>
            </div>
          </div>
        </div>

        <!-- Add 10-15 more review cards... -->

      </div>

      <div style="text-align: center; margin-top: 3rem;">
        <a href="https://google.com/reviews" class="btn btn-primary btn-large" target="_blank">Leave a Review</a>
      </div>
    </div>
  </section>

  <!-- Copy footer -->
  <footer class="footer">
    <!-- ... -->
  </footer>

  <script src="script.js"></script>
</body>
</html>
```

---

## about.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Learn about RoofEdge - Texas's premier roofing company. Licensed, insured, and certified by major manufacturers.">
  <title>About RoofEdge | Our Story</title>
  <link rel="icon" type="image/png" href="images/favicon.png">
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Copy header -->
  <header class="header">
    <!-- ... -->
  </header>

  <section class="hero" style="background: var(--gradient-primary); color: white;">
    <div class="container">
      <div class="hero-content" style="max-width: 700px; text-align: center; margin: 0 auto;">
        <h1 style="color: white;">About RoofEdge</h1>
        <p class="hero-subtitle" style="color: rgba(255,255,255,0.9);">
          Texas's premier roofing company. Built on trust, quality, and customer satisfaction since 2010.
        </p>
      </div>
    </div>
  </section>

  <section class="section">
    <div class="container">
      <div class="grid grid-2">
        <div class="fade-in-on-scroll">
          <h2>Our Story</h2>
          <p>Founded in 2010, RoofEdge began with a simple mission: deliver premium roofing services with transparency, integrity, and craftsmanship.</p>
          <p>Today, we're one of Texas's most trusted roofing companies, with over 2,000 completed projects and a team of certified professionals dedicated to excellence.</p>
          <p>We combine modern technology (drone inspections, digital estimates) with old-school values (honest pricing, clean job sites, and warranty-backed work).</p>
        </div>
        <div class="fade-in-on-scroll">
          <img src="images/about-team.jpg" alt="RoofEdge team photo" loading="lazy" style="border-radius: var(--radius-lg); box-shadow: var(--shadow-lg);">
          <!-- Image: Team photo of RoofEdge crew in front of truck -->
        </div>
      </div>
    </div>
  </section>

  <section class="section bg-light">
    <div class="container">
      <div class="section-header">
        <h2 class="section-title">Our Values</h2>
      </div>

      <div class="grid grid-3">
        <div class="card text-center fade-in-on-scroll">
          <h3>Quality First</h3>
          <p>Every roof is installed to manufacturer specifications using premium materials and certified techniques.</p>
        </div>
        <div class="card text-center fade-in-on-scroll">
          <h3>Transparent Pricing</h3>
          <p>No hidden fees, no surprise charges. Your quote is your final price, guaranteed.</p>
        </div>
        <div class="card text-center fade-in-on-scroll">
          <h3>Safety & Compliance</h3>
          <p>Fully licensed, insured, and OSHA-compliant. Your property and our crew are protected.</p>
        </div>
      </div>
    </div>
  </section>

  <section class="section">
    <div class="container">
      <div class="section-header">
        <h2 class="section-title">Meet Our Team</h2>
      </div>

      <div class="grid grid-4">
        <div class="card text-center fade-in-on-scroll">
          <img src="images/team-1.jpg" alt="Michael Rodriguez" style="width: 150px; height: 150px; border-radius: 50%; margin: 0 auto 1rem; object-fit: cover;">
          <!-- Image: Professional headshot -->
          <h4>Michael Rodriguez</h4>
          <p style="color: var(--color-gray); font-size: 0.875rem;">Founder & CEO</p>
        </div>
        <!-- Add 3-6 more team members... -->
      </div>
    </div>
  </section>

  <section class="cta-section">
    <div class="container">
      <h2>Join Our Growing Team</h2>
      <p>We're always looking for skilled roofers and project managers to join the RoofEdge family.</p>
      <div style="display: flex; gap: 1rem; justify-content: center; flex-wrap: wrap; margin-top: 2rem;">
        <a href="mailto:careers@roofedge.com" class="btn btn-white btn-large">View Open Positions</a>
      </div>
    </div>
  </section>

  <!-- Copy footer -->
  <footer class="footer">
    <!-- ... -->
  </footer>

  <script src="script.js"></script>
</body>
</html>
```

---

## blog.html & blog-article.html

See README.md for blog structure. Use similar card-based grid layout with featured article hero.

---

## Legal Pages (privacy-policy.html, terms-of-service.html, warranty-policy.html)

All three legal pages follow the same structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="RoofEdge Privacy Policy - How we collect, use, and protect your information.">
  <title>Privacy Policy | RoofEdge</title>
  <link rel="icon" type="image/png" href="images/favicon.png">
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Copy header -->
  <header class="header">
    <!-- ... -->
  </header>

  <section class="section">
    <div class="container-narrow">
      <div class="article-container">
        <div class="article-header">
          <h1 class="article-title">Privacy Policy</h1>
          <p class="article-meta">Last Updated: January 21, 2026</p>
        </div>

        <div class="article-content">
          <h2>1. Information We Collect</h2>
          <p>RoofEdge ("we," "our," or "us") collects information you provide directly to us when you request a quote, contact us, or use our services. This includes:</p>
          <ul>
            <li>Name, email address, phone number</li>
            <li>Property address and project details</li>
            <li>Photos you upload for estimates</li>
            <li>Payment and billing information</li>
          </ul>

          <h2>2. How We Use Your Information</h2>
          <p>We use the information we collect to:</p>
          <ul>
            <li>Provide roofing services and respond to your inquiries</li>
            <li>Send you project updates, estimates, and appointment reminders</li>
            <li>Process payments and maintain records</li>
            <li>Improve our website and services</li>
            <li>Comply with legal obligations</li>
          </ul>

          <h2>3. Information Sharing</h2>
          <p>We do not sell your personal information. We may share your information with:</p>
          <ul>
            <li>Service providers (payment processors, scheduling tools)</li>
            <li>Insurance companies (if you request assistance with claims)</li>
            <li>Legal authorities when required by law</li>
          </ul>

          <h2>4. Data Security</h2>
          <p>We implement reasonable security measures to protect your information from unauthorized access, disclosure, or destruction.</p>

          <h2>5. Your Rights</h2>
          <p>You have the right to:</p>
          <ul>
            <li>Access, correct, or delete your personal information</li>
            <li>Opt out of marketing communications</li>
            <li>Request a copy of your data</li>
          </ul>

          <h2>6. Cookies</h2>
          <p>We use cookies and similar technologies to improve your website experience, analyze traffic, and remember your preferences.</p>

          <h2>7. Contact Us</h2>
          <p>For privacy questions or to exercise your rights, contact us at:</p>
          <p>Email: privacy@roofedge.com<br>Phone: (555) 013-ROOF</p>

          <p style="margin-top: 3rem; font-size: 0.875rem; color: var(--color-gray);">
            <strong>Note:</strong> This privacy policy template is provided for demonstration purposes. Please consult with a legal professional to ensure compliance with applicable privacy laws (GDPR, CCPA, etc.).
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Copy footer -->
  <footer class="footer">
    <!-- ... -->
  </footer>

  <script src="script.js"></script>
</body>
</html>
```

**For Terms of Service:** Same structure, covering use of website, service agreements, limitations of liability, dispute resolution, etc.

**For Warranty Policy:** Same structure, detailing manufacturer warranties, workmanship guarantees, exclusions, claims process, and transferability.

---

## Notes

1. **All pages** should use the same header and footer from existing pages
2. **Image comments** describe what professional stock photos to use
3. **Form submissions** use JavaScript validation (already in script.js)
4. **Modals and interactions** are handled by existing script.js
5. **Responsive design** works automatically via style.css media queries

**Legal Disclaimer:** Legal page content is templated and should be reviewed by an attorney before use.

