# Hjmr-media.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="HJMR Media - Premium social media growth services and streaming accounts. Buy Instagram, YouTube, TikTok followers/likes and Netflix, Shahid VIP accounts.">
    <meta name="keywords" content="Instagram followers, YouTube subscribers, TikTok likes, Netflix VIP, Shahid VIP, social media growth">
    <title>HJMR Media | Premium Social Media Services</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #6c5ce7;
            --primary-dark: #5649c0;
            --secondary: #00cec9;
            --accent: #fd79a8;
            --dark: #2d3436;
            --light: #f5f6fa;
            --success: #00b894;
            --warning: #fdcb6e;
            --danger: #d63031;
            --gray: #636e72;
            --light-gray: #dfe6e9;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
            color: var(--dark);
            background-color: var(--light);
            overflow-x: hidden;
        }
        
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        section {
            padding: 80px 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 60px;
        }
        
        .section-title h2 {
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--primary);
            margin-bottom: 15px;
            position: relative;
            display: inline-block;
        }
        
        .section-title h2::after {
            content: '';
            position: absolute;
            width: 60px;
            height: 4px;
            background: var(--secondary);
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            border-radius: 2px;
        }
        
        .section-title p {
            color: var(--gray);
            max-width: 700px;
            margin: 0 auto;
            font-size: 1.1rem;
        }
        
        .btn {
            display: inline-block;
            padding: 12px 30px;
            border-radius: 50px;
            font-weight: 600;
            text-decoration: none;
            transition: all 0.3s ease;
            text-align: center;
            cursor: pointer;
            border: none;
            font-size: 1rem;
        }
        
        .btn-primary {
            background: var(--primary);
            color: white;
        }
        
        .btn-primary:hover {
            background: var(--primary-dark);
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(108, 92, 231, 0.2);
        }
        
        .btn-secondary {
            background: var(--secondary);
            color: white;
        }
        
        .btn-secondary:hover {
            background: #00b5b2;
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0, 206, 201, 0.2);
        }
        
        /* Header */
        header {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            z-index: 1000;
            transition: all 0.3s ease;
            background: rgba(255, 255, 255, 0.98);
            box-shadow: 0 2px 15px rgba(0, 0, 0, 0.1);
        }
        
        header.scrolled {
            background: rgba(255, 255, 255, 0.98);
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.1);
            padding: 10px 0;
        }
        
        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
        }
        
        .logo {
            display: flex;
            align-items: center;
            text-decoration: none;
        }
        
        .logo-icon {
            font-size: 2rem;
            color: var(--primary);
            margin-right: 10px;
        }
        
        .logo-text {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--dark);
        }
        
        .logo-text span {
            color: var(--primary);
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 30px;
        }
        
        nav ul li a {
            color: var(--dark);
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s ease;
            position: relative;
            font-size: 1rem;
        }
        
        nav ul li a::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            background: var(--primary);
            bottom: -5px;
            left: 0;
            transition: width 0.3s ease;
        }
        
        nav ul li a:hover::after {
            width: 100%;
        }
        
        nav ul li a:hover {
            color: var(--primary);
        }
        
        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            font-size: 1.5rem;
            color: var(--dark);
            cursor: pointer;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, rgba(108, 92, 231, 0.9), rgba(0, 206, 201, 0.9)), url('https://images.unsplash.com/photo-1611162616475-465a5daaf5e0?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;
            color: white;
            padding: 200px 0 150px;
            text-align: center;
            position: relative;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.3);
        }
        
        .hero-content {
            position: relative;
            z-index: 1;
            max-width: 800px;
            margin: 0 auto;
        }
        
        .hero h1 {
            font-size: 3.5rem;
            font-weight: 700;
            margin-bottom: 20px;
            line-height: 1.2;
        }
        
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 30px;
            opacity: 0.9;
        }
        
        .hero-btns {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        
        /* Services Section */
        .services {
            background: white;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 30px;
        }
        
        .service-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: all 0.3s ease;
            border: 1px solid var(--light-gray);
        }
        
        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
            border-color: var(--primary);
        }
        
        .service-badge {
            position: absolute;
            top: 15px;
            right: 15px;
            background: var(--accent);
            color: white;
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: 600;
        }
        
        .service-img {
            height: 180px;
            overflow: hidden;
            position: relative;
        }
        
        .service-img img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }
        
        .service-card:hover .service-img img {
            transform: scale(1.05);
        }
        
        .service-content {
            padding: 25px;
        }
        
        .service-content h3 {
            font-size: 1.3rem;
            margin-bottom: 10px;
            color: var(--primary);
        }
        
        .service-content p {
            color: var(--gray);
            margin-bottom: 20px;
            font-size: 0.95rem;
        }
        
        .service-meta {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
        }
        
        .price {
            font-size: 1.4rem;
            font-weight: 700;
            color: var(--primary);
        }
        
        .price span {
            font-size: 0.9rem;
            font-weight: 400;
            color: var(--gray);
        }
        
        .service-rating {
            color: var(--warning);
            font-size: 0.9rem;
        }
        
        /* Features Section */
        .features {
            background: var(--light);
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .feature-card {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            text-align: center;
            transition: all 0.3s ease;
        }
        
        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }
        
        .feature-icon {
            width: 70px;
            height: 70px;
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.8rem;
            margin: 0 auto 20px;
        }
        
        .feature-card h3 {
            font-size: 1.3rem;
            margin-bottom: 15px;
            color: var(--dark);
        }
        
        .feature-card p {
            color: var(--gray);
            font-size: 0.95rem;
        }
        
        /* Payment Methods */
        .payment-methods {
            background: white;
            text-align: center;
        }
        
        .payment-icons {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 30px;
            margin-top: 40px;
        }
        
        .payment-icon {
            background: white;
            width: 120px;
            height: 70px;
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: all 0.3s ease;
            border: 1px solid var(--light-gray);
            padding: 10px;
        }
        
        .payment-icon:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
            border-color: var(--primary);
        }
        
        .payment-icon img {
            max-width: 100%;
            max-height: 100%;
            filter: grayscale(100%);
            opacity: 0.7;
            transition: all 0.3s ease;
        }
        
        .payment-icon:hover img {
            filter: grayscale(0);
            opacity: 1;
        }
        
        /* Testimonials */
        .testimonials {
            background: linear-gradient(135deg, rgba(108, 92, 231, 0.03), rgba(0, 206, 201, 0.03)));
        }
        
        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .testimonial-card {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            position: relative;
        }
        
        .testimonial-card::before {
            content: '"';
            position: absolute;
            top: 20px;
            left: 20px;
            font-size: 4rem;
            color: var(--light-gray);
            font-family: serif;
            line-height: 1;
            z-index: 0;
        }
        
        .testimonial-content {
            position: relative;
            z-index: 1;
            margin-bottom: 20px;
            font-style: italic;
            color: var(--gray);
        }
        
        .testimonial-author {
            display: flex;
            align-items: center;
        }
        
        .author-avatar {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            overflow: hidden;
            margin-right: 15px;
        }
        
        .author-avatar img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .author-info h4 {
            font-size: 1rem;
            margin-bottom: 5px;
            color: var(--dark);
        }
        
        .author-info p {
            font-size: 0.8rem;
            color: var(--gray);
        }
        
        .testimonial-rating {
            color: var(--warning);
            margin-top: 5px;
        }
        
        /* Contact Section */
        .contact {
            background: white;
        }
        
        .contact-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
        }
        
        .contact-info {
            margin-bottom: 30px;
        }
        
        .contact-info h3 {
            font-size: 1.5rem;
            margin-bottom: 20px;
            color: var(--primary);
        }
        
        .contact-info p {
            color: var(--gray);
            margin-bottom: 30px;
        }
        
        .contact-method {
            display: flex;
            align-items: flex-start;
            margin-bottom: 20px;
        }
        
        .contact-icon {
            width: 50px;
            height: 50px;
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 15px;
            font-size: 1.2rem;
            flex-shrink: 0;
        }
        
        .contact-text h4 {
            font-size: 1.1rem;
            margin-bottom: 5px;
            color: var(--dark);
        }
        
        .contact-text a, .contact-text p {
            color: var(--gray);
            text-decoration: none;
            transition: all 0.3s ease;
            font-size: 0.95rem;
        }
        
        .contact-text a:hover {
            color: var(--primary);
        }
        
        .contact-form {
            background: var(--light);
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 500;
            color: var(--dark);
        }
        
        .form-control {
            width: 100%;
            padding: 12px 15px;
            border: 1px solid var(--light-gray);
            border-radius: 5px;
            font-family: 'Poppins', sans-serif;
            transition: all 0.3s ease;
        }
        
        .form-control:focus {
            outline: none;
            border-color: var(--primary);
            box-shadow: 0 0 0 3px rgba(108, 92, 231, 0.1);
        }
        
        textarea.form-control {
            min-height: 120px;
            resize: vertical;
        }
        
        /* FAQ Section */
        .faq {
            background: var(--light);
        }
        
        .accordion {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .accordion-item {
            margin-bottom: 15px;
            border-radius: 5px;
            overflow: hidden;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
            background: white;
        }
        
        .accordion-header {
            padding: 15px 20px;
            background: white;
            cursor: pointer;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-weight: 500;
            transition: all 0.3s ease;
        }
        
        .accordion-header:hover {
            background: var(--light);
        }
        
        .accordion-header::after {
            content: '+';
            font-size: 1.2rem;
            transition: all 0.3s ease;
        }
        
        .accordion-item.active .accordion-header::after {
            content: '-';
        }
        
        .accordion-content {
            padding: 0 20px;
            max-height: 0;
            overflow: hidden;
            transition: all 0.3s ease;
            border-top: 1px solid transparent;
        }
        
        .accordion-item.active .accordion-content {
            padding: 15px 20px;
            max-height: 500px;
            border-top: 1px solid var(--light-gray);
        }
        
        /* Footer */
        footer {
            background: var(--dark);
            color: white;
            padding: 60px 0 20px;
        }
        
        .footer-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 40px;
            margin-bottom: 40px;
        }
        
        .footer-col h3 {
            font-size: 1.2rem;
            margin-bottom: 20px;
            position: relative;
            padding-bottom: 10px;
        }
        
        .footer-col h3::after {
            content: '';
            position: absolute;
            width: 40px;
            height: 2px;
            background: var(--secondary);
            bottom: 0;
            left: 0;
        }
        
        .footer-col ul {
            list-style: none;
        }
        
        .footer-col ul li {
            margin-bottom: 10px;
        }
        
        .footer-col ul li a {
            color: #b2b2b2;
            text-decoration: none;
            transition: all 0.3s ease;
            font-size: 0.95rem;
        }
        
        .footer-col ul li a:hover {
            color: var(--secondary);
            padding-left: 5px;
        }
        
        .footer-about p {
            color: #b2b2b2;
            margin-bottom: 20px;
            font-size: 0.95rem;
        }
        
        .social-links {
            display: flex;
            gap: 15px;
        }
        
        .social-links a {
            width: 40px;
            height: 40px;
            background: rgba(255, 255, 255, 0.1);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s ease;
        }
        
        .social-links a:hover {
            background: var(--secondary);
            transform: translateY(-3px);
        }
        
        .footer-bottom {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: #b2b2b2;
            font-size: 0.9rem;
        }
        
        /* Responsive Styles */
        @media (max-width: 992px) {
            .header-container {
                padding: 15px 0;
            }
            
            .hero {
                padding: 180px 0 120px;
            }
            
            .hero h1 {
                font-size: 2.8rem;
            }
            
            section {
                padding: 60px 0;
            }
        }
        
        @media (max-width: 768px) {
            nav {
                position: fixed;
                top: 0;
                right: -100%;
                width: 280px;
                height: 100vh;
                background: white;
                box-shadow: -5px 0 15px rgba(0, 0, 0, 0.1);
                transition: all 0.3s ease;
                z-index: 1001;
                padding: 80px 30px 30px;
            }
            
            nav.active {
                right: 0;
            }
            
            nav ul {
                flex-direction: column;
            }
            
            nav ul li {
                margin: 0 0 20px 0;
            }
            
            nav ul li a {
                font-size: 1.1rem;
            }
            
            .mobile-menu-btn {
                display: block;
                z-index: 1002;
            }
            
            .mobile-menu-btn i {
                font-size: 1.8rem;
            }
            
            .hero h1 {
                font-size: 2.3rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
            
            .section-title h2 {
                font-size: 2rem;
            }
            
            .footer-container {
                grid-template-columns: 1fr;
                gap: 30px;
            }
        }
        
        @media (max-width: 576px) {
            .hero {
                padding: 150px 0 100px;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .hero-btns {
                flex-direction: column;
                gap: 15px;
            }
            
            .btn {
                width: 100%;
            }
            
            .section-title h2 {
                font-size: 1.8rem;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header id="header">
        <div class="container header-container">
            <a href="#" class="logo">
                <div class="logo-icon">
                    <i class="fas fa-rocket"></i>
                </div>
                <div class="logo-text">HJMR <span>Media</span></div>
            </a>
            
            <button class="mobile-menu-btn" id="mobileMenuBtn">
                <i class="fas fa-bars"></i>
            </button>
            
            <nav id="mainNav">
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#features">Why Choose Us</a></li>
                    <li><a href="#testimonials">Testimonials</a></li>
                    <li><a href="#payment">Payment</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <div class="hero-content">
                <h1>Premium Social Media Growth Services</h1>
                <p>Boost your online presence with real Instagram, YouTube, and TikTok followers and likes. Get authentic Netflix and Shahid VIP accounts at competitive prices.</p>
                <div class="hero-btns">
                    <a href="#services" class="btn btn-primary">Our Services</a>
                    <a href="#contact" class="btn btn-secondary">Contact Us</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="services" id="services">
        <div class="container">
            <div class="section-title">
                <h2>Our Services</h2>
                <p>We offer high-quality social media services to help you grow your online presence quickly and safely.</p>
            </div>
            
            <div class="services-grid">
                <!-- Instagram Followers -->
                <div class="service-card">
                    <div class="service-badge">Popular</div>
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1611162617213-7d7a39e9b1d7?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Instagram Followers">
                    </div>
                    <div class="service-content">
                        <h3>Instagram Followers</h3>
                        <p>High-quality, real Instagram followers to boost your credibility and visibility.</p>
                        <div class="service-meta">
                            <div class="price">$5.99 <span>/ 100 followers</span></div>
                            <div class="service-rating">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                        </div>
                        <a href="#contact" class="btn btn-primary" style="width: 100%;">Order Now</a>
                    </div>
                </div>
                
                <!-- Instagram Likes -->
                <div class="service-card">
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1611162616305-c69b3fa7fbe0?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Instagram Likes">
                    </div>
                    <div class="service-content">
                        <h3>Instagram Likes</h3>
                        <p>Increase engagement on your posts with our premium Instagram likes service.</p>
                        <div class="service-meta">
                            <div class="price">$3.99 <span>/ 100 likes</span></div>
                            <div class="service-rating">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="far fa-star"></i>
                            </div>
                        </div>
                        <a href="#contact" class="btn btn-primary" style="width: 100%;">Order Now</a>
                    </div>
                </div>
                
                <!-- YouTube Subscribers -->
                <div class="service-card">
                    <div class="service-badge">Best Value</div>
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1611162616475-465a5daaf5e0?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="YouTube Subscribers">
                    </div>
                    <div class="service-content">
                        <h3>YouTube Subscribers</h3>
                        <p>Grow your channel with real subscribers who engage with your content.</p>
                        <div class="service-meta">
                            <div class="price">$9.99 <span>/ 100 subs</span></div>
                            <div class="service-rating">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                        <a href="#contact" class="btn btn-primary" style="width: 100%;">Order Now</a>
                    </div>
                </div>
                
                <!-- YouTube Likes -->
                <div class="service-card">
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1611162617263-4ec306b1f4f0?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="YouTube Likes">
                    </div>
                    <div class="service-content">
                        <h3>YouTube Likes</h3>
                        <p>Boost your video's visibility with authentic YouTube likes from real users.</p>
                        <div class="service-meta">
                            <div class="price">$4.99 <span>/ 100 likes</span></div>
                            <div class="service-rating">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                        </div>
                        <a href="#contact" class="btn btn-primary" style="width: 100%;">Order Now</a>
                    </div>
                </div>
                
                <!-- TikTok Followers -->
                <div class="service-card">
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1611605698335-8b1569810432?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="TikTok Followers">
                    </div>
                    <div class="service-content">
                        <h3>TikTok Followers</h3>
                        <p>Increase your TikTok popularity with real, active followers.</p>
                        <div class="service-meta">
                            <div class="price">$7.99 <span>/ 100 followers</span></div>
                            <div class="service-rating">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="far fa-star"></i>
                            </div>
                        </div>
                        <a href="#contact" class="btn btn-primary" style="width: 100%;">Order Now</a>
                    </div>
                </div>
                
                <!-- TikTok Likes -->
                <div class="service-card">
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1611605698323-de90ad1a0b32?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="TikTok Likes">
                    </div>
                    <div class="service-content">
                        <h3>TikTok Likes</h3>
                        <p>Get more engagement on your TikTok videos with our premium like packages.</p>
                        <div class="service-meta">
                            <div class="price">$2.99 <span>/ 100 likes</span></div>
                            <div class="service-rating">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                        </div>
                        <a href="#contact" class="btn btn-primary" style="width: 100%;">Order Now</a>
                    </div>
                </div>
                
                <!-- Netflix VIP -->
                <div class="service-card">
                    <div class="service-badge">Limited</div>
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1611162617263-4ec306b1f4f0?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Netflix VIP">
                    </div>
                    <div class="service-content">
                        <h3>Netflix VIP Accounts</h3>
                        <p>Premium Netflix accounts with full access to all content worldwide.</p>
                        <div class="service-meta">
                            <div class="price">$14.99 <span>/ month</span></div>
                            <div class="service-rating">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                        <a href="#contact" class="btn btn-primary" style="width: 100%;">Order Now</a>
                    </div>
                </div>
                
                <!-- Shahid VIP -->
                <div class="service-card">
                    <div class="service-img">
                        <img src="https://images.unsplash.com/photo-1611162616475-465a5daaf5e0?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" alt="Shahid VIP">
                    </div>
                    <div class="service-content">
                        <h3>Shahid VIP Accounts</h3>
                        <p>Premium Shahid VIP accounts with access to all exclusive Arabic content.</p>
                        <div class="service-meta">
                            <div class="price">$12.99 <span>/ month</span></div>
                            <div class="service-rating">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                        </div>
                        <a href="#contact" class="btn btn-primary" style="width: 100%;">Order Now</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features" id="features">
        <div class="container">
            <div class="section-title">
                <h2>Why Choose HJMR Media</h2>
                <p>We provide the highest quality services with guaranteed results and excellent customer support.</p>
            </div>
            
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-check-circle"></i>
                    </div>
                    <h3>High Quality Services</h3>
                    <p>All our followers, likes, and subscribers are from real, active accounts to ensure authenticity.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-bolt"></i>
                    </div>
                    <h3>Fast Delivery</h3>
                    <p>Most orders start within minutes and complete within 24-48 hours depending on the size.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-lock"></i>
                    </div>
                    <h3>Secure Payments</h3>
                    <p>We use encrypted payment gateways to ensure your financial information is always protected.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-headset"></i>
                    </div>
                    <h3>24/7 Support</h3>
                    <p>Our customer support team is available around the clock to assist you with any questions.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-shield-alt"></i>
                    </div>
                    <h3>Privacy Guaranteed</h3>
                    <p>We never ask for your password or any sensitive account information. Your privacy is our priority.</p>
                </div>
                
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-percentage"></i>
                    </div>
                    <h3>Competitive Prices</h3>
                    <p>We offer the best prices in the market with regular discounts and special offers.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials" id="testimonials">
        <div class="container">
            <div class="section-title">
                <h2>What Our Clients Say</h2>
                <p>Don't just take our word for it. Here's what some of our satisfied customers have to say.</p>
            </div>
            
            <div class="testimonials-grid">
                <div class="testimonial-card">
                    <div class="testimonial-content">
                        <p>I was skeptical at first, but HJMR Media delivered exactly what they promised. My Instagram grew by 2,000 real followers in just 3 days. Highly recommended!</p>
                    </div>
                    <div class="testimonial-author">
                        <div class="author-avatar">
                            <img src="https://randomuser.me/api/portraits/women/32.jpg" alt="Sarah K.">
                        </div>
                        <div class="author-info">
                            <h4>Sarah K.</h4>
                            <p>Instagram Influencer</p>
                            <div class="testimonial-rating">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-content">
                        <p>The Netflix VIP account I purchased works perfectly. It's been 6 months and I still have full access to all regions. Great service and support!</p>
                    </div>
                    <div class="testimonial-author">
                        <div class="author-avatar">
                            <img src="https://randomuser.me/api/portraits/men/45.jpg" alt="Mohammed A.">
                        </div>
                        <div class="author-info">
                            <h4>Mohammed A.</h4>
                            <p>Regular Customer</p>
                            <div class="testimonial-rating">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-content">
                        <p>As a small business, growing our YouTube channel was challenging. HJMR Media helped us get our first 5,000 subscribers. The engagement is real!</p>
                    </div>
                    <div class="testimonial-author">
                        <div class="author-avatar">
                            <img src="https://randomuser.me/api/portraits/women/68.jpg" alt="Lisa M.">
                        </div>
                        <div class="author-info">
                            <h4>Lisa M.</h4>
                            <p>Small Business Owner</p>
                            <div class="testimonial-rating">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Payment Methods -->
    <section class="payment-methods" id="payment">
        <div class="container">
            <div class="section-title">
                <h2>Secure Payment Methods</h2>
                <p>We accept all major payment methods for your convenience and security.</p>
            </div>
            
            <div class="payment-icons">
                <div class="payment-icon">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/PayPal_Logo.png/640px-PayPal_Logo.png" alt="PayPal">
                </div>
                <div class="payment-icon">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/72/Logo_CIH_Bank.svg/1200px-Logo_CIH_Bank.svg.png" alt="CIH Bank">
                </div>
                <div class="payment-icon">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/Visa_Inc._logo.svg/2560px-Visa_Inc._logo.svg.png" alt="Visa">
                </div>
                <div class="payment-icon">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2a/Mastercard-logo.svg/1280px-Mastercard-logo.svg.png" alt="Mastercard">
                </div>
                <div class="payment-icon">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b7/Stripe_Logo%2C_revised_2016.svg/2560px-Stripe_Logo%2C_revised_2016.svg.png" alt="Stripe">
                </div>
                <div class="payment-icon">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/46/Bitcoin.svg/1200px-Bitcoin.svg.png" alt="Bitcoin">
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section class="faq" id="faq">
        <div class="container">
            <div class="section-title">
                <h2>Frequently Asked Questions</h2>
                <p>Find answers to common questions about our services and how they work.</p>
            </div>
            
            <div class="accordion">
                <div class="accordion-item">
                    <div class="accordion-header">
                        <span>Are your followers/likes real?</span>
                        <span></span>
                    </div>
                    <div class="accordion-content">
                        <p>Yes, all our followers and likes come from real, active accounts. We never use bots or fake accounts as they can harm your profile in the long run.</p>
                    </div>
                </div>
                
                <div class="accordion-item">
                    <div class="accordion-header">
                        <span>How long does delivery take?</span>
                        <span></span>
                    </div>
                    <div class="accordion-content">
                        <p>Delivery times vary depending on the service and order size. Most Instagram and TikTok services start within 30 minutes and complete within 24-48 hours. YouTube services may take 3-5 days for larger orders.</p>
                    </div>
                </div>
                
                <div class="accordion-item">
                    <div class="accordion-header">
                        <span>Is my account safe?</span>
                        <span></span>
                    </div>
                    <div class="accordion-content">
                        <p>Absolutely. We never ask for your password or any sensitive information. Our methods are completely safe and comply with all platform terms of service.</p>
                    </div>
                </div>
                
                <div class="accordion-item">
                    <div class="accordion-header">
                        <span>What if I'm not satisfied with the service?</span>
                        <span></span>
                    </div>
                    <div class="accordion-content">
                        <p>We offer a 100% satisfaction guarantee. If you're not happy with the results, contact our support team and we'll either fix the issue or provide a full refund.</p>
                    </div>
                </div>
                
                <div class="accordion-item">
                    <div class="accordion-header">
                        <span>How do the Netflix/Shahid VIP accounts work?</span>
                        <span></span>
                    </div>
                    <div class="accordion-content">
                        <p>We provide you with login credentials for premium accounts that you can use just like a regular subscription. These accounts are maintained by us and you'll receive automatic renewals.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="container">
            <div class="section-title">
                <h2>Contact Us</h2>
                <p>Have questions or ready to place an order? Get in touch with our team today.</p>
            </div>
            
            <div class="contact-container">
                <div class="contact-info">
                    <h3>Get In Touch</h3>
                    <p>Our customer support team is available 24/7 to answer your questions and help you place orders. Reach out through any of the following methods:</p>
                    
                    <div class="contact-method">
                        <div class="contact-icon">
                            <i class="fab fa-whatsapp"></i>
                        </div>
                        <div class="contact-text">
                            <h4>WhatsApp</h4>
                            <a href="https://wa.me/212776527414" target="_blank">+212 776-527414</a>
                            <p>Fastest response time - usually within minutes</p>
                        </div>
                    </div>
                    
                    <div class="contact-method">
                        <div class="contact-icon">
                            <i class="fab fa-instagram"></i>
                        </div>
                        <div class="contact-text">
                            <h4>Instagram</h4>
                            <a href="https://www.instagram.com/hjrm_media?igsh=MXAxMnlwZjVyZDhrZQ==" target="_blank">@hjrm_media</a>
                            <p>DM us for quick inquiries and updates</p>
                        </div>
                    </div>
                    
                    <div class="contact-method">
                        <div class="contact-icon">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <div class="contact-text">
                            <h4>Email</h4>
                            <a href="mailto:support@hjrmmedia.com">support@hjrmmedia.com</a>
                            <p>For detailed inquiries and support</p>
                        </div>
                    </div>
                    
                    <div class="contact-method">
                        <div class="contact-icon">
                            <i class="fas fa-clock"></i>
                        </div>
                        <div class="contact-text">
                            <h4>Working Hours</h4>
                            <p>24/7 Support</p>
                            <p>Orders processed around the clock</p>
                        </div>
                    </div>
                </div>
                
                <div class="contact-form">
                    <h3>Place Your Order</h3>
                    <form id="orderForm">
                        <div class="form-group">
                            <label for="name">Full Name</label>
                            <input type="text" id="name" name="name" class="form-control" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="email">Email Address</label>
                            <input type="email" id="email" name="email" class="form-control" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="service">Service</label>
                            <select id="service" name="service" class="form-control" required>
                                <option value="">Select a service</option>
                                <option value="instagram-followers">Instagram Followers</option>
                                <option value="instagram-likes">Instagram Likes</option>
                                <option value="youtube-subscribers">YouTube Subscribers</option>
                                <option value="youtube-likes">YouTube Likes</option>
                                <option value="tiktok-followers">TikTok Followers</option>
                                <option value="tiktok-likes">TikTok Likes</option>
                                <option value="netflix-vip">Netflix VIP</option>
                                <option value="shahid-vip">Shahid VIP</option>
                            </select>
                        </div>
                        
                        <div class="form-group">
                            <label for="package">Package/Quantity</label>
                            <input type="text" id="package" name="package" class="form-control" required placeholder="E.g., 1000 followers, 1 month, etc.">
                        </div>
                        
                        <div class="form-group">
                            <label for="username">Username/URL (if applicable)</label>
                            <input type="text" id="username" name="username" class="form-control" placeholder="Your Instagram/YouTube/TikTok username">
                        </div>
                        
                        <div class="form-group">
                            <label for="message">Additional Details</label>
                            <textarea id="message" name="message" class="form-control" rows="4"></textarea>
                        </div>
                        
                        <button type="submit" class="btn btn-primary" style="width: 100%;">Submit Order</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-container">
                <div class="footer-col footer-about">
                    <h3>About HJMR Media</h3>
                    <p>We are a premium social media growth service provider, helping individuals and businesses grow their online presence since 2020.</p>
                    <div class="social-links">
                        <a href="https://www.instagram.com/hjrm_media?igsh=MXAxMnlwZjVyZDhrZQ==" target="_blank"><i class="fab fa-instagram"></i></a>
                        <a href="https://wa.me/212776527414" target="_blank"><i class="fab fa-whatsapp"></i></a>
                        <a href="mailto:support@hjrmmedia.com"><i class="fas fa-envelope"></i></a>
                    </div>
                </div>
                
                <div class="footer-col">
                    <h3>Services</h3>
                    <ul>
                        <li><a href="#services">Instagram Growth</a></li>
                        <li><a href="#services">YouTube Growth</a></li>
                        <li><a href="#services">TikTok Growth</a></li>
                        <li><a href="#services">Netflix VIP</a></li>
                        <li><a href="#services">Shahid VIP</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h3>Company</h3>
                    <ul>
                        <li><a href="#about">About Us</a></li>
                        <li><a href="#testimonials">Testimonials</a></li>
                        <li><a href="#faq">FAQ</a></li>
                        <li><a href="#contact">Contact</a></li>
                        <li><a href="#">Privacy Policy</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h3>Support</h3>
                    <ul>
                        <li><a href="https://wa.me/212776527414" target="_blank">WhatsApp Support</a></li>
                        <li><a href="mailto:support@hjrmmedia.com">Email Support</a></li>
                        <li><a href="#faq">Help Center</a></li>
                        <li><a href="#">Payment Methods</a></li>
                        <li><a href="#">Refund Policy</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="footer-bottom">
                <p>&copy; 2023 HJMR Media. All Rights Reserved. | Designed with <i class="fas fa-heart" style="color: var(--accent);"></i> by HJMR Team</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile Menu Toggle
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const mainNav = document.getElementById('mainNav');
        
        mobileMenuBtn.addEventListener('click', function() {
            mainNav.classList.toggle('active');
            mobileMenuBtn.innerHTML = mainNav.classList.contains('active') ? 
                '<i class="fas fa-times"></i>' : '<i class="fas fa-bars"></i>';
        });
        
        // Close mobile menu when clicking on a link
        document.querySelectorAll('#mainNav a').forEach(link => {
            link.addEventListener('click', function() {
                if (mainNav.classList.contains('active')) {
                    mainNav.classList.remove('active');
                    mobileMenuBtn.innerHTML = '<i class="fas fa-bars"></i>';
                }
            });
        });
        
        // Header scroll effect
        const header = document.getElementById('header');
        window.addEventListener('scroll', function() {
            if (window.scrollY > 100) {
                header.classList.add('scrolled');
            } else {
                header.classList.remove('scrolled');
            }
        });
        
        // Accordion functionality
        const accordionItems = document.querySelectorAll('.accordion-item');
        accordionItems.forEach(item => {
            const header = item.querySelector('.accordion-header');
            
            header.addEventListener('click', function() {
                const currentlyActive = document.querySelector('.accordion-item.active');
                
                if (currentlyActive && currentlyActive !== item) {
                    currentlyActive.classList.remove('active');
                }
                
                item.classList.toggle('active');
            });
        });
        
        // Form submission
        const orderForm = document.getElementById('orderForm');
        orderForm.addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Get form values
            const formData = new FormData(orderForm);
            const data = Object.fromEntries(formData.entries());
            
            // Here you would typically send this data to your server
            // For this example, we'll show a confirmation message
            const confirmationMessage = `
                Thank you, ${data.name}!
                Your order for ${data.service} (${data.package}) has been received.
                We'll contact you at ${data.email} shortly with payment details.
            `;
            
            alert(confirmationMessage);
            
            // Reset the form
            orderForm.reset();
            
            // Scroll to top
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });
        
        // Smooth scrolling for all links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
</body>
</html>
