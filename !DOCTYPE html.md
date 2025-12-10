**<!DOCTYPE html>**

**<html lang="en">**

**<head>**

  **<meta charset="UTF-8" />**

  **<title>Raxter Ltd – Home, Garden \& Lifestyle Store</title>**

  **<meta name="viewport" content="width=device-width, initial-scale=1.0" />**

  **<meta name="description" content="Raxter Ltd - Quality home, garden, camping, toys and lifestyle products. Shop Raxter on our website, Amazon and eBay." />**

  **<style>**

    **:root {**

      **--primary: #1c7ed6;**

      **--primary-dark: #1864ab;**

      **--accent: #ffa94d;**

      **--bg: #f5f5f7;**

      **--text: #222;**

      **--muted: #666;**

      **--radius: 12px;**

      **--shadow-soft: 0 10px 25px rgba(0, 0, 0, 0.06);**

    **}**



    **\* {**

      **box-sizing: border-box;**

      **margin: 0;**

      **padding: 0;**

    **}**



    **body {**

      **font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;**

      **background: var(--bg);**

      **color: var(--text);**

      **line-height: 1.6;**

    **}**



    **a {**

      **color: inherit;**

      **text-decoration: none;**

    **}**



    **img {**

      **max-width: 100%;**

      **display: block;**

    **}**



    **.container {**

      **width: 100%;**

      **max-width: 1200px;**

      **margin: 0 auto;**

      **padding: 0 1.2rem;**

    **}**



    **header {**

      **position: sticky;**

      **top: 0;**

      **z-index: 50;**

      **background: rgba(255, 255, 255, 0.96);**

      **backdrop-filter: blur(10px);**

      **box-shadow: 0 1px 3px rgba(0, 0, 0, 0.06);**

    **}**



    **.nav {**

      **display: flex;**

      **align-items: center;**

      **justify-content: space-between;**

      **padding: 0.8rem 0;**

    **}**



    **.logo {**

      **display: flex;**

      **align-items: center;**

      **gap: 0.5rem;**

      **font-weight: 700;**

      **font-size: 1.2rem;**

    **}**



    **.logo-mark {**

      **width: 32px;**

      **height: 32px;**

      **border-radius: 10px;**

      **background: linear-gradient(135deg, var(--primary), var(--accent));**

      **display: flex;**

      **align-items: center;**

      **justify-content: center;**

      **color: #fff;**

      **font-weight: 800;**

      **font-size: 1.1rem;**

      **box-shadow: var(--shadow-soft);**

    **}**



    **.nav-links {**

      **display: flex;**

      **gap: 1.3rem;**

      **align-items: center;**

      **font-size: 0.95rem;**

    **}**



    **.nav-links a {**

      **position: relative;**

      **padding-bottom: 0.15rem;**

    **}**



    **.nav-links a::after {**

      **content: "";**

      **position: absolute;**

      **left: 0;**

      **bottom: 0;**

      **width: 0;**

      **height: 2px;**

      **background: var(--primary);**

      **transition: width 0.2s ease;**

    **}**



    **.nav-links a:hover::after {**

      **width: 100%;**

    **}**



    **.nav-cta {**

      **border-radius: 999px;**

      **background: var(--primary);**

      **color: #fff;**

      **padding: 0.45rem 1rem;**

      **font-weight: 600;**

      **box-shadow: var(--shadow-soft);**

      **transition: background 0.2s ease, transform 0.1s ease;**

    **}**



    **.nav-cta:hover {**

      **background: var(--primary-dark);**

      **transform: translateY(-1px);**

    **}**



    **.nav-toggle {**

      **display: none;**

      **flex-direction: column;**

      **gap: 5px;**

      **cursor: pointer;**

    **}**



    **.nav-toggle span {**

      **width: 22px;**

      **height: 2px;**

      **background: #333;**

      **border-radius: 999px;**

    **}**



    **/\* Hero \*/**

    **.hero {**

      **padding: 3.5rem 0 2.5rem;**

    **}**



    **.hero-grid {**

      **display: grid;**

      **gap: 2rem;**

      **grid-template-columns: minmax(0, 1.3fr) minmax(0, 1fr);**

      **align-items: center;**

    **}**



    **.badge {**

      **display: inline-flex;**

      **align-items: center;**

      **gap: 0.4rem;**

      **border-radius: 999px;**

      **background: #e7f5ff;**

      **color: #1864ab;**

      **padding: 0.2rem 0.75rem;**

      **font-size: 0.8rem;**

      **font-weight: 600;**

      **margin-bottom: 0.8rem;**

    **}**



    **.badge-dot {**

      **width: 7px;**

      **height: 7px;**

      **border-radius: 999px;**

      **background: #51cf66;**

    **}**



    **.hero h1 {**

      **font-size: clamp(2.1rem, 3.4vw, 2.8rem);**

      **margin-bottom: 0.7rem;**

    **}**



    **.hero h1 span {**

      **color: var(--primary);**

    **}**



    **.hero-subtitle {**

      **font-size: 1rem;**

      **color: var(--muted);**

      **margin-bottom: 1.4rem;**

    **}**



    **.hero-actions {**

      **display: flex;**

      **flex-wrap: wrap;**

      **gap: 0.9rem;**

      **margin-bottom: 1.3rem;**

    **}**



    **.btn {**

      **border-radius: 999px;**

      **border: none;**

      **cursor: pointer;**

      **padding: 0.75rem 1.4rem;**

      **font-weight: 600;**

      **font-size: 0.95rem;**

      **display: inline-flex;**

      **align-items: center;**

      **gap: 0.45rem;**

      **text-decoration: none;**

    **}**



    **.btn-primary {**

      **background: var(--primary);**

      **color: #fff;**

      **box-shadow: var(--shadow-soft);**

    **}**



    **.btn-primary:hover {**

      **background: var(--primary-dark);**

    **}**



    **.btn-outline {**

      **border: 1px solid #ddd;**

      **background: #fff;**

      **color: #333;**

    **}**



    **.btn-outline:hover {**

      **border-color: var(--primary);**

    **}**



    **.hero-meta {**

      **display: flex;**

      **flex-wrap: wrap;**

      **gap: 1.5rem;**

      **font-size: 0.9rem;**

      **color: var(--muted);**

    **}**



    **.hero-meta span {**

      **display: flex;**

      **align-items: center;**

      **gap: 0.4rem;**

    **}**



    **.hero-meta span strong {**

      **color: #222;**

    **}**



    **.hero-card {**

      **border-radius: 18px;**

      **background: linear-gradient(145deg, #ffffff, #f1f3f5);**

      **padding: 1.4rem;**

      **box-shadow: var(--shadow-soft);**

    **}**



    **.hero-card-header {**

      **display: flex;**

      **justify-content: space-between;**

      **align-items: center;**

      **margin-bottom: 1rem;**

    **}**



    **.hero-card-title {**

      **font-weight: 600;**

      **font-size: 0.98rem;**

    **}**



    **.hero-tag {**

      **font-size: 0.75rem;**

      **padding: 0.15rem 0.5rem;**

      **border-radius: 999px;**

      **background: #e7f5ff;**

      **color: #1864ab;**

      **font-weight: 600;**

    **}**



    **.hero-card-grid {**

      **display: grid;**

      **gap: 0.7rem;**

      **grid-template-columns: repeat(2, minmax(0, 1fr));**

      **font-size: 0.8rem;**

    **}**



    **.hero-card-item {**

      **border-radius: 10px;**

      **background: #fff;**

      **padding: 0.7rem;**

      **border: 1px solid #f1f3f5;**

    **}**



    **.hero-card-item h4 {**

      **font-size: 0.8rem;**

      **margin-bottom: 0.25rem;**

    **}**



    **.hero-card-item p {**

      **color: var(--muted);**

      **font-size: 0.78rem;**

    **}**



    **/\* Section shared \*/**

    **section {**

      **padding: 2.5rem 0;**

    **}**



    **.section-header {**

      **text-align: center;**

      **margin-bottom: 1.8rem;**

    **}**



    **.section-eyebrow {**

      **font-size: 0.8rem;**

      **text-transform: uppercase;**

      **letter-spacing: 0.12em;**

      **color: var(--primary);**

      **font-weight: 700;**

      **margin-bottom: 0.2rem;**

    **}**



    **.section-title {**

      **font-size: 1.5rem;**

      **margin-bottom: 0.3rem;**

    **}**



    **.section-subtitle {**

      **max-width: 520px;**

      **margin: 0.2rem auto 0;**

      **font-size: 0.95rem;**

      **color: var(--muted);**

    **}**



    **/\* Categories \*/**

    **.grid {**

      **display: grid;**

      **gap: 1.3rem;**

    **}**



    **.grid-3 {**

      **grid-template-columns: repeat(3, minmax(0, 1fr));**

    **}**



    **.grid-4 {**

      **grid-template-columns: repeat(4, minmax(0, 1fr));**

    **}**



    **.category-card {**

      **border-radius: var(--radius);**

      **background: #fff;**

      **padding: 1rem;**

      **box-shadow: var(--shadow-soft);**

      **border: 1px solid #edf2ff;**

      **display: flex;**

      **flex-direction: column;**

      **gap: 0.4rem;**

      **font-size: 0.9rem;**

    **}**



    **.category-label {**

      **font-weight: 600;**

      **margin-bottom: 0.1rem;**

    **}**



    **.category-pill {**

      **display: inline-flex;**

      **align-items: center;**

      **padding: 0.15rem 0.6rem;**

      **font-size: 0.75rem;**

      **border-radius: 999px;**

      **background: #f1f3f5;**

      **color: var(--muted);**

      **margin-top: 0.2rem;**

    **}**



    **/\* Products \*/**

    **.filters {**

      **display: flex;**

      **flex-wrap: wrap;**

      **gap: 0.6rem;**

      **justify-content: center;**

      **margin-bottom: 1.5rem;**

    **}**



    **.filter-btn {**

      **border-radius: 999px;**

      **border: 1px solid #dee2e6;**

      **background: #fff;**

      **padding: 0.3rem 0.85rem;**

      **font-size: 0.82rem;**

      **cursor: pointer;**

      **transition: background 0.15s ease, border-color 0.15s ease;**

    **}**



    **.filter-btn.active {**

      **background: #e7f5ff;**

      **border-color: #74c0fc;**

      **color: #1864ab;**

      **font-weight: 600;**

    **}**



    **.product-card {**

      **border-radius: var(--radius);**

      **background: #fff;**

      **box-shadow: var(--shadow-soft);**

      **overflow: hidden;**

      **display: flex;**

      **flex-direction: column;**

      **border: 1px solid #edf2ff;**

    **}**



    **.product-img {**

      **background: #f1f3f5;**

      **height: 170px;**

      **display: flex;**

      **align-items: center;**

      **justify-content: center;**

      **font-size: 0.8rem;**

      **color: var(--muted);**

    **}**



    **.product-body {**

      **padding: 0.9rem 0.9rem 1rem;**

      **display: flex;**

      **flex-direction: column;**

      **gap: 0.4rem;**

      **flex: 1;**

    **}**



    **.product-title {**

      **font-size: 0.95rem;**

      **font-weight: 600;**

      **min-height: 2.3em;**

    **}**



    **.product-meta {**

      **display: flex;**

      **justify-content: space-between;**

      **align-items: baseline;**

      **font-size: 0.85rem;**

    **}**



    **.product-price {**

      **font-weight: 700;**

    **}**



    **.product-tag {**

      **font-size: 0.75rem;**

      **padding: 0.1rem 0.5rem;**

      **border-radius: 999px;**

      **background: #e9ecef;**

      **color: var(--muted);**

    **}**



    **.product-actions {**

      **margin-top: 0.6rem;**

      **display: flex;**

      **gap: 0.5rem;**

    **}**



    **.product-actions a {**

      **flex: 1;**

      **font-size: 0.8rem;**

      **justify-content: center;**

    **}**



    **/\* About / Stats \*/**

    **.about-grid {**

      **display: grid;**

      **gap: 2rem;**

      **grid-template-columns: minmax(0, 1.3fr) minmax(0, 1fr);**

      **align-items: flex-start;**

    **}**



    **.stat-grid {**

      **display: grid;**

      **gap: 1rem;**

      **grid-template-columns: repeat(2, minmax(0, 1fr));**

    **}**



    **.stat-card {**

      **border-radius: var(--radius);**

      **background: #fff;**

      **padding: 0.9rem;**

      **text-align: center;**

      **box-shadow: var(--shadow-soft);**

      **border: 1px solid #edf2ff;**

    **}**



    **.stat-number {**

      **font-size: 1.3rem;**

      **font-weight: 700;**

      **margin-bottom: 0.2rem;**

      **color: var(--primary-dark);**

    **}**



    **.stat-label {**

      **font-size: 0.8rem;**

      **color: var(--muted);**

    **}**



    **/\* How to shop \*/**

    **.steps {**

      **display: grid;**

      **gap: 1rem;**

      **grid-template-columns: repeat(3, minmax(0, 1fr));**

    **}**



    **.step-card {**

      **border-radius: var(--radius);**

      **background: #fff;**

      **padding: 1rem;**

      **box-shadow: var(--shadow-soft);**

      **border: 1px solid #edf2ff;**

      **font-size: 0.9rem;**

    **}**



    **.step-number {**

      **width: 26px;**

      **height: 26px;**

      **border-radius: 999px;**

      **background: #e7f5ff;**

      **color: #1864ab;**

      **display: flex;**

      **align-items: center;**

      **justify-content: center;**

      **font-weight: 700;**

      **font-size: 0.85rem;**

      **margin-bottom: 0.5rem;**

    **}**



    **/\* Contact \*/**

    **.contact-grid {**

      **display: grid;**

      **gap: 2rem;**

      **grid-template-columns: minmax(0, 1.1fr) minmax(0, 1fr);**

      **align-items: flex-start;**

    **}**



    **form {**

      **display: grid;**

      **gap: 0.8rem;**

    **}**



    **label {**

      **font-size: 0.85rem;**

      **font-weight: 600;**

    **}**



    **input,**

    **textarea {**

      **width: 100%;**

      **border-radius: 8px;**

      **border: 1px solid #dee2e6;**

      **padding: 0.6rem 0.7rem;**

      **font-size: 0.9rem;**

      **font-family: inherit;**

    **}**



    **textarea {**

      **min-height: 100px;**

      **resize: vertical;**

    **}**



    **.helper-text {**

      **font-size: 0.8rem;**

      **color: var(--muted);**

      **margin-top: 0.15rem;**

    **}**



    **.newsletter {**

      **border-radius: var(--radius);**

      **background: #fff;**

      **padding: 1rem;**

      **box-shadow: var(--shadow-soft);**

      **border: 1px solid #edf2ff;**

      **font-size: 0.9rem;**

    **}**



    **.newsletter input {**

      **margin-top: 0.4rem;**

    **}**



    **footer {**

      **margin-top: 2.5rem;**

      **padding: 1.5rem 0 2rem;**

      **border-top: 1px solid #dee2e6;**

      **font-size: 0.8rem;**

      **color: var(--muted);**

    **}**



    **.footer-inner {**

      **display: flex;**

      **flex-wrap: wrap;**

      **gap: 0.8rem;**

      **justify-content: space-between;**

      **align-items: center;**

    **}**



    **.footer-links {**

      **display: flex;**

      **flex-wrap: wrap;**

      **gap: 0.8rem;**

    **}**



    **.footer-links a {**

      **text-decoration: underline;**

      **text-decoration-style: dotted;**

    **}**



    **/\* Responsive \*/**

    **@media (max-width: 900px) {**

      **.hero-grid,**

      **.about-grid,**

      **.contact-grid {**

        **grid-template-columns: minmax(0, 1fr);**

      **}**



      **.hero {**

        **padding-top: 2.5rem;**

      **}**



      **.grid-3 {**

        **grid-template-columns: repeat(2, minmax(0, 1fr));**

      **}**



      **.grid-4 {**

        **grid-template-columns: repeat(2, minmax(0, 1fr));**

      **}**



      **.steps {**

        **grid-template-columns: repeat(2, minmax(0, 1fr));**

      **}**

    **}**



    **@media (max-width: 700px) {**

      **.nav-toggle {**

        **display: flex;**

      **}**



      **.nav-links {**

        **position: absolute;**

        **inset: auto 0 0 0;**

        **top: 56px;**

        **background: #fff;**

        **padding: 0.8rem 1.2rem 1.2rem;**

        **flex-direction: column;**

        **border-top: 1px solid #eee;**

        **transform: translateY(-130%);**

        **opacity: 0;**

        **pointer-events: none;**

        **transition: transform 0.15s ease, opacity 0.15s ease;**

      **}**



      **.nav-links.open {**

        **transform: translateY(0);**

        **opacity: 1;**

        **pointer-events: auto;**

      **}**



      **.hero-grid {**

        **gap: 1.5rem;**

      **}**



      **.grid-3,**

      **.grid-4,**

      **.steps {**

        **grid-template-columns: minmax(0, 1fr);**

      **}**

    **}**

  **</style>**

**</head>**

**<body>**

  **<!-- Header -->**

  **<header>**

    **<div class="container nav">**

      **<a href="#top" class="logo">**

        **<div class="logo-mark">R</div>**

        **<div>**

          **<div>Raxter Ltd</div>**

          **<div style="font-size: 0.75rem; color: #666;">Home • Garden • Lifestyle</div>**

        **</div>**

      **</a>**



      **<nav>**

        **<div class="nav-toggle" id="navToggle" aria-label="Toggle navigation">**

          **<span></span><span></span><span></span>**

        **</div>**

        **<div class="nav-links" id="navLinks">**

          **<a href="#categories">Categories</a>**

          **<a href="#products">Featured</a>**

          **<a href="#about">About</a>**

          **<a href="#how-to-shop">How to shop</a>**

          **<a href="#contact">Contact</a>**

          **<a href="#shop-online" class="nav-cta">Shop Online</a>**

        **</div>**

      **</nav>**

    **</div>**

  **</header>**



  **<main id="top">**

    **<!-- Hero -->**

    **<section class="hero">**

      **<div class="container hero-grid">**

        **<div>**

          **<div class="badge">**

            **<span class="badge-dot"></span>**

            **Trusted UK Seller • Raxter**

          **</div>**

          **<h1>**

            **Everyday essentials from <span>Raxter Ltd</span> – for home, garden \& beyond.**

          **</h1>**

          **<p class="hero-subtitle">**

            **Discover practical, great-value products for your home, garden, camping trips, pets, toys and more – from a seller trusted by thousands of customers.**

          **</p>**

          **<div class="hero-actions">**

            **<a href="#products" class="btn btn-primary">**

              **Browse featured products →**

            **</a>**

            **<a href="#shop-online" class="btn btn-outline">**

              **View Amazon \&amp; eBay stores**

            **</a>**

          **</div>**

          **<div class="hero-meta">**

            **<span><strong>Raxter</strong> • Brand by Raxter Ltd</span>**

            **<span>✔ Fast UK dispatch</span>**

            **<span>✔ Wide variety of products</span>**

          **</div>**

        **</div>**



        **<aside class="hero-card" aria-label="Store highlights">**

          **<div class="hero-card-header">**

            **<div>**

              **<div class="hero-card-title">Why shop with Raxter?</div>**

              **<div style="font-size: 0.78rem; color: var(--muted);">**

                **Multi-channel retailer across Website, Amazon \&amp; eBay.**

              **</div>**

            **</div>**

            **<div class="hero-tag">Raxter</div>**

          **</div>**

          **<div class="hero-card-grid">**

            **<div class="hero-card-item">**

              **<h4>Huge range</h4>**

              **<p>Homeware, garden, camping, toys, health \& beauty, pet supplies and more.</p>**

            **</div>**

            **<div class="hero-card-item">**

              **<h4>Great value</h4>**

              **<p>Competitive pricing with multi-buy deals and offers on many products.</p>**

            **</div>**

            **<div class="hero-card-item">**

              **<h4>Trusted seller</h4>**

              **<p>Years of online selling experience with strong customer feedback.</p>**

            **</div>**

            **<div class="hero-card-item">**

              **<h4>Fast shipping</h4>**

              **<p>UK-based stock with quick dispatch so you get your order sooner.</p>**

            **</div>**

          **</div>**

        **</aside>**

      **</div>**

    **</section>**



    **<!-- Categories -->**

    **<section id="categories">**

      **<div class="container">**

        **<div class="section-header">**

          **<div class="section-eyebrow">Shop by category</div>**

          **<h2 class="section-title">Everything you need in one place</h2>**

          **<p class="section-subtitle">**

            **Raxter covers a wide variety of everyday categories – from bathroom accessories to garden supplies, toys, tools and more.**

          **</p>**

        **</div>**



        **<div class="grid grid-4">**

          **<div class="category-card">**

            **<div class="category-label">Home \&amp; Kitchen</div>**

            **<p>Kitchenware, storage, home decor, cleaning essentials and more for your home.</p>**

            **<span class="category-pill">Examples: cookware, kettles, mats</span>**

          **</div>**

          **<div class="category-card">**

            **<div class="category-label">Garden \&amp; Outdoor</div>**

            **<p>Garden accessories, fire pits, parasol bases, outdoor furniture and lighting.</p>**

            **<span class="category-pill">Perfect for patios \&amp; BBQs</span>**

          **</div>**

          **<div class="category-card">**

            **<div class="category-label">Camping \&amp; Travel</div>**

            **<p>Tents, portable stoves, gas canisters and accessories for outdoor adventures.</p>**

            **<span class="category-pill">Camping \&amp; outdoor gear</span>**

          **</div>**

          **<div class="category-card">**

            **<div class="category-label">Toys \&amp; Games</div>**

            **<p>Fun and nostalgic toys including virtual pets and more for kids \&amp; adults.</p>**

            **<span class="category-pill">Great gift ideas</span>**

          **</div>**

          **<div class="category-card">**

            **<div class="category-label">Health \&amp; Beauty</div>**

            **<p>Everyday personal care and beauty accessories to keep you feeling fresh.</p>**

            **<span class="category-pill">Self-care essentials</span>**

          **</div>**

          **<div class="category-card">**

            **<div class="category-label">Pet Supplies</div>**

            **<p>Dog cages, pet ramps, grooming gloves and more for your furry friends.</p>**

            **<span class="category-pill">For happy pets</span>**

          **</div>**

          **<div class="category-card">**

            **<div class="category-label">Tools \&amp; DIY</div>**

            **<p>Blow torches, lighters and useful tools for DIY projects and repairs.</p>**

            **<span class="category-pill">Handy around the home</span>**

          **</div>**

          **<div class="category-card">**

            **<div class="category-label">Gifts \&amp; Seasonal</div>**

            **<p>Christmas trees, flags, photo frames, gifts and seasonal best-sellers.</p>**

            **<span class="category-pill">For every occasion</span>**

          **</div>**

        **</div>**

      **</div>**

    **</section>**



    **<!-- Featured Products -->**

    **<section id="products">**

      **<div class="container">**

        **<div class="section-header">**

          **<div class="section-eyebrow">Featured products</div>**

          **<h2 class="section-title">A snapshot of what Raxter offers</h2>**

          **<p class="section-subtitle">**

            **Below are example products to show how your items can be displayed on your own website.**

            **Replace images, titles, prices and links with your real listings.**

          **</p>**

        **</div>**



        **<!-- Filters (optional JS) -->**

        **<div class="filters">**

          **<button class="filter-btn active" data-filter="all">All</button>**

          **<button class="filter-btn" data-filter="home">Home \&amp; Kitchen</button>**

          **<button class="filter-btn" data-filter="garden">Garden \&amp; Outdoor</button>**

          **<button class="filter-btn" data-filter="camping">Camping</button>**

          **<button class="filter-btn" data-filter="toys">Toys \&amp; Games</button>**

        **</div>**



        **<div class="grid grid-4" id="productGrid">**

          **<!-- Product 1 -->**

          **<article class="product-card" data-category="garden">**

            **<div class="product-img">**

              **Replace with product image (Fire Pit)**

            **</div>**

            **<div class="product-body">**

              **<div class="product-title">**

                **Cast Iron Effect Garden Fire Pit / Fire Bowl**

              **</div>**

              **<div class="product-meta">**

                **<span class="product-price">£XX.XX</span>**

                **<span class="product-tag">Garden \&amp; Outdoor</span>**

              **</div>**

              **<p style="font-size: 0.8rem; color: var(--muted);">**

                **Stylish fire pit – perfect for cosy evenings in the garden or on the patio.**

              **</p>**

              **<div class="product-actions">**

                **<a href="https://www.ebay.co.uk/str/stevesdiscountstores" target="\_blank" class="btn btn-outline">**

                  **View on eBay**

                **</a>**

                **<a href="https://www.amazon.co.uk/stores/Raxter/page/FB454EAF-767C-47EB-AE57-82276466425D" target="\_blank" class="btn btn-outline">**

                  **View on Amazon**

                **</a>**

              **</div>**

            **</div>**

          **</article>**



          **<!-- Product 2 -->**

          **<article class="product-card" data-category="camping">**

            **<div class="product-img">**

              **Replace with product image (Camping Stove)**

            **</div>**

            **<div class="product-body">**

              **<div class="product-title">**

                **Portable Camping Gas Cooker \&amp; Gas Canisters**

              **</div>**

              **<div class="product-meta">**

                **<span class="product-price">£XX.XX</span>**

                **<span class="product-tag">Camping</span>**

              **</div>**

              **<p style="font-size: 0.8rem; color: var(--muted);">**

                **Compact stove that’s ideal for festivals, camping trips and outdoor cooking.**

              **</p>**

              **<div class="product-actions">**

                **<a href="https://www.ebay.co.uk/str/stevesdiscountstores" target="\_blank" class="btn btn-outline">**

                  **View on eBay**

                **</a>**

                **<a href="https://www.amazon.co.uk/stores/Raxter/page/FB454EAF-767C-47EB-AE57-82276466425D" target="\_blank" class="btn btn-outline">**

                  **View on Amazon**

                **</a>**

              **</div>**

            **</div>**

          **</article>**



          **<!-- Product 3 -->**

          **<article class="product-card" data-category="home">**

            **<div class="product-img">**

              **Replace with product image (Yoga Mat)**

            **</div>**

            **<div class="product-body">**

              **<div class="product-title">**

                **Thick Non-Slip Yoga / Exercise Mat with Carry Strap**

              **</div>**

              **<div class="product-meta">**

                **<span class="product-price">£XX.XX</span>**

                **<span class="product-tag">Home \&amp; Fitness</span>**

              **</div>**

              **<p style="font-size: 0.8rem; color: var(--muted);">**

                **Comfortable mat for home workouts, pilates, yoga and stretching.**

              **</p>**

              **<div class="product-actions">**

                **<a href="https://www.ebay.co.uk/str/stevesdiscountstores" target="\_blank" class="btn btn-outline">**

                  **View on eBay**

                **</a>**

                **<a href="https://www.amazon.co.uk/stores/Raxter/page/FB454EAF-767C-47EB-AE57-82276466425D" target="\_blank" class="btn btn-outline">**

                  **View on Amazon**

                **</a>**

              **</div>**

            **</div>**

          **</article>**



          **<!-- Product 4 -->**

          **<article class="product-card" data-category="toys">**

            **<div class="product-img">**

              **Replace with product image (Virtual Pet)**

            **</div>**

            **<div class="product-body">**

              **<div class="product-title">**

                **Retro Virtual Pet / Tamagotchi-Style Toy**

              **</div>**

              **<div class="product-meta">**

                **<span class="product-price">£XX.XX</span>**

                **<span class="product-tag">Toys \&amp; Games</span>**

              **</div>**

              **<p style="font-size: 0.8rem; color: var(--muted);">**

                **Nostalgic digital pet toy – a fun gift for kids and 90s lovers.**

              **</p>**

              **<div class="product-actions">**

                **<a href="https://www.ebay.co.uk/str/stevesdiscountstores" target="\_blank" class="btn btn-outline">**

                  **View on eBay**

                **</a>**

                **<a href="https://www.amazon.co.uk/stores/Raxter/page/FB454EAF-767C-47EB-AE57-82276466425D" target="\_blank" class="btn btn-outline">**

                  **View on Amazon**

                **</a>**

              **</div>**

            **</div>**

          **</article>**

        **</div>**



        **<p style="text-align: center; margin-top: 1.4rem; font-size: 0.9rem; color: var(--muted);">**

          **Want to add more products? Simply copy one of the product cards above and update the details.**

        **</p>**

      **</div>**

    **</section>**



    **<!-- About -->**

    **<section id="about">**

      **<div class="container about-grid">**

        **<div>**

          **<div class="section-eyebrow">About Raxter Ltd</div>**

          **<h2 class="section-title">Your everyday essentials partner</h2>**

          **<p style="margin-top: 0.7rem; font-size: 0.95rem;">**

            **Raxter Ltd is a UK-based retailer offering a broad range of everyday products –**

            **from homeware and kitchen essentials to garden accessories, camping gear, toys,**

            **health \&amp; beauty, pet supplies and more.**

          **</p>**

          **<p style="margin-top: 0.6rem; font-size: 0.95rem;">**

            **We focus on practical items that deliver value for money and make life a little**

            **easier. Our products are available on our own website, as well as through our**

            **established Amazon and eBay stores.**

          **</p>**

          **<p style="margin-top: 0.6rem; font-size: 0.9rem; color: var(--muted);">**

            **If you’re interested in bulk or wholesale orders, please get in touch via the form**

            **below and the Raxter team will get back to you.**

          **</p>**

        **</div>**

        **<div>**

          **<div class="stat-grid">**

            **<div class="stat-card">**

              **<div class="stat-number">Multi-category</div>**

              **<div class="stat-label">Home, garden, camping, toys \&amp; more</div>**

            **</div>**

            **<div class="stat-card">**

              **<div class="stat-number">Online brand</div>**

              **<div class="stat-label">Raxter products available across channels</div>**

            **</div>**

            **<div class="stat-card">**

              **<div class="stat-number">UK-based</div>**

              **<div class="stat-label">Stock and customer service in the UK</div>**

            **</div>**

            **<div class="stat-card">**

              **<div class="stat-number">Customer-first</div>**

              **<div class="stat-label">Focused on value, reliability \&amp; service</div>**

            **</div>**

          **</div>**

        **</div>**

      **</div>**

    **</section>**



    **<!-- How to shop -->**

    **<section id="how-to-shop">**

      **<div class="container">**

        **<div class="section-header">**

          **<div class="section-eyebrow">How to shop</div>**

          **<h2 class="section-title">Three easy ways to buy from Raxter</h2>**

          **<p class="section-subtitle">**

            **You can purchase Raxter products directly through our marketplace listings, or contact us for**

            **wholesale or bulk enquiries.**

          **</p>**

        **</div>**



        **<div class="steps">**

          **<div class="step-card">**

            **<div class="step-number">1</div>**

            **<h3 style="font-size: 1rem; margin-bottom: 0.3rem;">Browse products</h3>**

            **<p>**

              **Use this website to explore example categories and featured items. Replace these with your full product**

              **range as your site grows.**

            **</p>**

          **</div>**

          **<div class="step-card">**

            **<div class="step-number">2</div>**

            **<h3 style="font-size: 1rem; margin-bottom: 0.3rem;">Buy via Amazon or eBay</h3>**

            **<p>**

              **Click through to our official Raxter stores on Amazon and eBay to complete your purchase with buyer**

              **protections and secure checkout.**

            **</p>**

          **</div>**

          **<div class="step-card">**

            **<div class="step-number">3</div>**

            **<h3 style="font-size: 1rem; margin-bottom: 0.3rem;">Contact us directly</h3>**

            **<p>**

              **For bulk orders, business enquiries or product questions, use the contact form below and our team will reply.**

            **</p>**

          **</div>**

        **</div>**

      **</div>**

    **</section>**



    **<!-- Shop online section (links to external stores) -->**

    **<section id="shop-online">**

      **<div class="container">**

        **<div class="section-header">**

          **<div class="section-eyebrow">Shop online</div>**

          **<h2 class="section-title">Find Raxter on Amazon \&amp; eBay</h2>**

          **<p class="section-subtitle">**

            **Prefer to shop on marketplaces you already know? Visit our official brand stores and keep an eye out for new arrivals and offers.**

          **</p>**

        **</div>**



        **<div class="grid grid-3">**

          **<div class="step-card">**

            **<h3 style="font-size: 1rem; margin-bottom: 0.4rem;">Raxter Amazon Store</h3>**

            **<p style="font-size: 0.9rem; margin-bottom: 0.7rem;">**

              **Explore Raxter products on Amazon UK with fast delivery options and familiar checkout.**

            **</p>**

            **<a href="https://www.amazon.co.uk/stores/Raxter/page/FB454EAF-767C-47EB-AE57-82276466425D" target="\_blank" class="btn btn-primary">**

              **Visit Amazon Store →**

            **</a>**

          **</div>**



          **<div class="step-card">**

            **<h3 style="font-size: 1rem; margin-bottom: 0.4rem;">Raxter eBay Store</h3>**

            **<p style="font-size: 0.9rem; margin-bottom: 0.7rem;">**

              **Shop our wide range of listings on eBay UK – including home, garden, camping, toys and more.**

            **</p>**

            **<a href="https://www.ebay.co.uk/str/stevesdiscountstores" target="\_blank" class="btn btn-primary">**

              **Visit eBay Store →**

            **</a>**

          **</div>**



          **<div class="step-card">**

            **<h3 style="font-size: 1rem; margin-bottom: 0.4rem;">This website (coming soon)</h3>**

            **<p style="font-size: 0.9rem; margin-bottom: 0.7rem;">**

              **As your site develops, you can integrate direct checkout (e.g. Stripe, PayPal or ecommerce platform)**

              **so customers can buy straight from raxter.co.uk.**

            **</p>**

            **<span class="helper-text">**

              **For now, customers can browse here and purchase via Amazon/eBay.**

            **</span>**

          **</div>**

        **</div>**

      **</div>**

    **</section>**



    **<!-- Contact -->**

    **<section id="contact">**

      **<div class="container contact-grid">**

        **<div>**

          **<div class="section-eyebrow">Contact</div>**

          **<h2 class="section-title">Get in touch with Raxter Ltd</h2>**

          **<p style="margin: 0.6rem 0 1rem; font-size: 0.95rem;">**

            **Have a question about a product, an order, or a wholesale enquiry? Send us a message using the form below.**

          **</p>**



          **<!-- NOTE: Update the email address in the "action" below -->**

          **<form action="mailto:info@yourdomain.co.uk" method="post" enctype="text/plain">**

            **<div>**

              **<label for="name">Name</label>**

              **<input id="name" name="name" type="text" placeholder="Your name" required />**

            **</div>**

            **<div>**

              **<label for="email">Email</label>**

              **<input id="email" name="email" type="email" placeholder="you@example.com" required />**

            **</div>**

            **<div>**

              **<label for="subject">Subject</label>**

              **<input id="subject" name="subject" type="text" placeholder="Order enquiry, product question, etc." />**

            **</div>**

            **<div>**

              **<label for="message">Message</label>**

              **<textarea id="message" name="message" placeholder="How can we help?"></textarea>**

            **</div>**

            **<button type="submit" class="btn btn-primary">**

              **Send message**

            **</button>**

            **<p class="helper-text">**

              **Tip: once you set up proper hosting, you can replace this with a contact form service or CRM.**

            **</p>**

          **</form>**

        **</div>**



        **<aside class="newsletter">**

          **<h3 style="font-size: 1rem; margin-bottom: 0.4rem;">Stay updated</h3>**

          **<p style="font-size: 0.9rem; margin-bottom: 0.6rem;">**

            **Add a simple newsletter or offers signup here – perfect for announcing new product lines, seasonal deals or**

            **clearance offers.**

          **</p>**

          **<label for="newsletter-email">Email address</label>**

          **<input id="newsletter-email" type="email" placeholder="you@example.com" />**

          **<button class="btn btn-outline" style="margin-top: 0.6rem; width: 100%; justify-content: center;">**

            **Join mailing list**

          **</button>**

          **<p class="helper-text">**

            **You can connect this to a free email marketing tool (e.g. Mailchimp) once your site is live.**

          **</p>**



          **<hr style="margin: 1rem 0; border: none; border-top: 1px solid #eee;" />**



          **<h4 style="font-size: 0.95rem; margin-bottom: 0.3rem;">Business details</h4>**

          **<p style="font-size: 0.85rem; color: var(--muted);">**

            **Raxter Ltd<br />**

            **<!-- Replace with your registered office / trading address if you want it public -->**

            **United Kingdom**

          **</p>**

        **</aside>**

      **</div>**

    **</section>**

  **</main>**



  **<!-- Footer -->**

  **<footer>**

    **<div class="container footer-inner">**

      **<div>**

        **© <span id="year"></span> Raxter Ltd. All rights reserved.**

      **</div>**

      **<div class="footer-links">**

        **<a href="#">Privacy Policy</a>**

        **<a href="#">Returns \&amp; Refunds</a>**

        **<a href="#">Terms \&amp; Conditions</a>**

      **</div>**

    **</div>**

  **</footer>**



  **<script>**

    **// Mobile nav toggle**

    **const navToggle = document.getElementById("navToggle");**

    **const navLinks = document.getElementById("navLinks");**



    **navToggle.addEventListener("click", () => {**

      **navLinks.classList.toggle("open");**

    **});**



    **// Close nav on link click (mobile)**

    **navLinks.querySelectorAll("a").forEach((link) => {**

      **link.addEventListener("click", () => {**

        **navLinks.classList.remove("open");**

      **});**

    **});**



    **// Simple product filter**

    **const filterButtons = document.querySelectorAll(".filter-btn");**

    **const productCards = document.querySelectorAll(".product-card");**



    **filterButtons.forEach((btn) => {**

      **btn.addEventListener("click", () => {**

        **const filter = btn.getAttribute("data-filter");**



        **filterButtons.forEach((b) => b.classList.remove("active"));**

        **btn.classList.add("active");**



        **productCards.forEach((card) => {**

          **const category = card.getAttribute("data-category");**

          **if (filter === "all" || category === filter) {**

            **card.style.display = "flex";**

          **} else {**

            **card.style.display = "none";**

          **}**

        **});**

      **});**

    **});**



    **// Current year in footer**

    **document.getElementById("year").textContent = new Date().getFullYear();**

  **</script>**

**</body>**

**</html>**



