<html lang="en" id="html-tag">
<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title data-translate="pageTitle">KazTech - Securing Digital Growth</title>
    <meta name="description" content="KazTech is a Sweden-based IT company specializing in Digital Marketing, SEO, and Cybersecurity Services. We help businesses strengthen their online presence and protect their digital assets.">
    <meta name="keywords" content="IT company Sweden, Digital Marketing Malmö, SEO Sweden, Cybersecurity Sweden, KazTech, Online Presence, Digital Assets, Malmö IT">

    <link rel="icon" href="favicon.ico" type="image/x-icon">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&family=Roboto:wght@400;700&family=Montserrat:wght@500;700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Noto+Kufi+Arabic:wght@400;700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+SC:wght@400;700&display=swap" rel="stylesheet">


    <script src="https://cdn.tailwindcss.com"></script>

    <script>
      tailwind.config = {
        theme: {
          extend: {
            fontFamily: {
              sans: ['Inter', 'sans-serif'],
              roboto: ['Roboto', 'sans-serif'],
              montserrat: ['Montserrat', 'sans-serif'],
              arabic: ['Noto Kufi Arabic', 'sans-serif'], // Added Arabic font
              chinese: ['Noto Sans SC', 'sans-serif'], // Added Chinese font
            },
            colors: {
              primary: '#007bff',
              secondary: '#6c757d',
              light: '#f8f9fa',
              dark: '#343a40',
            }
          }
        }
      }
    </script>

    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        /* Apply specific fonts for different languages */
        html[lang="ar"] body { font-family: 'Noto Kufi Arabic', sans-serif; }
        html[lang="zh"] body { font-family: 'Noto Sans SC', sans-serif; }
        html[lang="sv"] body { font-family: 'Inter', sans-serif; } /* Or specific Swedish font */
        html[lang="en"] body { font-family: 'Inter', sans-serif; }


        .hero-section {
             background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://placehold.co/1920x1080/cccccc/666666?text=Hero+Background') no-repeat center center;
             background-size: cover;
        }
        .nav-links {
            transition: max-height 0.3s ease-out;
        }
        /* Updated style for active language link */
        .language-switcher a.active {
            font-weight: 700; /* Bolder */
            color: #007bff; /* Primary color */
            text-decoration: none; /* No underline */
        }
        /* Basic RTL adjustments */
        html[dir="rtl"] .logo { /* Example: Adjust logo position if needed */
            /* margin-left: auto; */
            /* margin-right: 0; */
        }
         html[dir="rtl"] .language-switcher {
             /* Adjust spacing if needed */
             margin-left: 0;
             margin-right: auto; /* Push to the left in RTL */
             padding-left: 0;
             padding-right: 1rem; /* Add padding to the right */
             border-left: none;
             border-right: 1px solid #e5e7eb; /* Add border to the right */
         }
         html[dir="rtl"] .mobile-menu-toggle {
             /* Adjust if needed */
         }
          html[dir="rtl"] .language-switcher span {
              margin-left: 0.5rem; /* Add space after label in RTL */
              margin-right: 0;
          }

    </style>

</head>
<body class="bg-white text-gray-800">

    <header class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <div class="logo">
                <a href="#home">
                    <img src="https://placehold.co/150x50/007bff/ffffff?text=KazTech" alt="KazTech Logo" class="h-10">
                </a>
            </div>

            <nav class="hidden md:flex items-center space-x-4">
                <ul class="flex space-x-4">
                    <li><a href="#home" class="text-gray-600 hover:text-primary rounded px-3 py-2" data-translate="navHome">Home</a></li>
                    <li><a href="#about" class="text-gray-600 hover:text-primary rounded px-3 py-2" data-translate="navAbout">About Us</a></li>
                    <li><a href="#services" class="text-gray-600 hover:text-primary rounded px-3 py-2" data-translate="navServices">Services</a></li>
                    <li><a href="#portfolio" class="text-gray-600 hover:text-primary rounded px-3 py-2" data-translate="navPortfolio">Portfolio</a></li>
                    <li><a href="#blog" class="text-gray-600 hover:text-primary rounded px-3 py-2" data-translate="navBlog">Blog</a></li>
                    <li><a href="#contact" class="text-gray-600 hover:text-primary rounded px-3 py-2" data-translate="navContact">Contact</a></li>
                </ul>
                <div class="language-switcher text-sm ml-4 border-l pl-4">
                    <a href="#" data-lang="en" class="text-gray-500 hover:text-primary px-1 active">EN</a> |
                    <a href="#" data-lang="sv" class="text-gray-500 hover:text-primary px-1">SV</a> |
                    <a href="#" data-lang="zh" class="text-gray-500 hover:text-primary px-1">ZH</a> |
                    <a href="#" data-lang="ar" class="text-gray-500 hover:text-primary px-1">AR</a>
                </div>
            </nav>

            <div class="md:hidden">
                <button id="mobile-menu-button" class="text-gray-600 hover:text-primary focus:outline-none">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
                    </svg>
                </button>
            </div>
        </div>

        <div id="mobile-menu" class="md:hidden hidden bg-white border-t">
             <ul class="nav-links flex flex-col px-4 py-2">
                 <li><a href="#home" class="block text-gray-600 hover:text-primary rounded px-3 py-2" data-translate="navHomeMobile">Home</a></li>
                 <li><a href="#about" class="block text-gray-600 hover:text-primary rounded px-3 py-2" data-translate="navAboutMobile">About Us</a></li>
                 <li><a href="#services" class="block text-gray-600 hover:text-primary rounded px-3 py-2" data-translate="navServicesMobile">Services</a></li>
                 <li><a href="#portfolio" class="block text-gray-600 hover:text-primary rounded px-3 py-2" data-translate="navPortfolioMobile">Portfolio</a></li>
                 <li><a href="#blog" class="block text-gray-600 hover:text-primary rounded px-3 py-2" data-translate="navBlogMobile">Blog</a></li>
                 <li><a href="#contact" class="block text-gray-600 hover:text-primary rounded px-3 py-2" data-translate="navContactMobile">Contact</a></li>
            </ul>
             <div class="language-switcher text-sm px-4 pb-4 pt-2 border-t mt-2">
                 <span class="font-semibold mr-2" data-translate="navLanguageMobile">Language:</span>
                 <a href="#" data-lang="en" class="text-gray-500 hover:text-primary px-1 active">EN</a> |
                 <a href="#" data-lang="sv" class="text-gray-500 hover:text-primary px-1">SV</a> |
                 <a href="#" data-lang="zh" class="text-gray-500 hover:text-primary px-1">ZH</a> |
                 <a href="#" data-lang="ar" class="text-gray-500 hover:text-primary px-1">AR</a>
             </div>
        </div>
    </header>

    <main>

        <section id="home" class="hero-section text-white py-20 md:py-32">
            <div class="container mx-auto px-4 text-center">
                <div class="hero-content">
                    <h1 class="text-4xl md:text-6xl font-bold mb-4 font-montserrat" data-translate="heroHeadline">Securing Digital Growth</h1>
                    <p class="text-lg md:text-xl mb-8 max-w-3xl mx-auto" data-translate="heroSubheadline">Empowering businesses in Sweden and beyond with expert Digital Marketing, robust SEO, and essential Cybersecurity solutions.</p>
                    <a href="#contact" class="cta-button bg-primary hover:bg-blue-700 text-white font-bold py-3 px-8 rounded-full text-lg transition duration-300" data-translate="heroCTA">Request a Consultation</a>
                </div>
            </div>
        </section>

        <section id="about" class="section py-16 md:py-24">
            <div class="container mx-auto px-4 text-center">
                 <h2 class="text-3xl md:text-4xl font-bold mb-6 font-montserrat" data-translate="aboutTitle">About KazTech</h2>
                <div class="max-w-3xl mx-auto text-gray-600 space-y-4">
                     <p data-translate="aboutPara1">KazTech was founded in Sweden with a mission to bridge the gap between business ambitions and digital success. We are a team of dedicated professionals with deep expertise in navigating the complexities of the digital landscape.</p>
                    <p data-translate="aboutPara2">Our commitment is to deliver innovative, results-driven solutions that not only enhance your online presence but also safeguard your valuable digital assets. We believe in building long-term partnerships based on trust, transparency, and measurable results.</p>
                </div>
            </div>
        </section>

        <section id="services" class="section py-16 md:py-24 bg-light">
            <div class="container mx-auto px-4">
                 <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 font-montserrat" data-translate="servicesTitle">Our Services</h2>
                 <p class="text-center text-gray-600 mb-12 max-w-2xl mx-auto" data-translate="servicesSubTitle">We offer a comprehensive suite of IT services designed to propel your business forward digitally and ensure its security.</p>

                <div class="services-grid grid md:grid-cols-3 gap-8">
                    <div class="service-item bg-white p-8 rounded-lg shadow-md text-center hover:shadow-lg transition duration-300">
                        <div class="mb-4 text-primary">
                            <svg class="w-12 h-12 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                        </div>
                         <h3 class="text-xl font-bold mb-3 font-montserrat" data-translate="service1Title">Digital Marketing</h3>
                        <p class="text-gray-600" data-translate="service1Desc">Crafting tailored digital marketing plans to reach your target audience, build brand awareness, and drive conversions across various online channels.</p>
                    </div>
                     <div class="service-item bg-white p-8 rounded-lg shadow-md text-center hover:shadow-lg transition duration-300">
                         <div class="mb-4 text-primary">
                            <svg class="w-12 h-12 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path></svg>
                         </div>
                         <h3 class="text-xl font-bold mb-3 font-montserrat" data-translate="service2Title">Search Engine Optimization (SEO)</h3>
                        <p class="text-gray-600" data-translate="service2Desc">Optimizing your website and online content to rank higher in search engine results, increasing organic traffic and visibility.</p>
                    </div>
                     <div class="service-item bg-white p-8 rounded-lg shadow-md text-center hover:shadow-lg transition duration-300">
                         <div class="mb-4 text-primary">
                            <svg class="w-12 h-12 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z"></path></svg>
                         </div>
                         <h3 class="text-xl font-bold mb-3 font-montserrat" data-translate="service3Title">Cybersecurity Solutions</h3>
                        <p class="text-gray-600" data-translate="service3Desc">Protecting your business from digital threats with robust security measures, risk assessments, and proactive defense strategies.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="portfolio" class="section py-16 md:py-24">
            <div class="container mx-auto px-4">
                 <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 font-montserrat" data-translate="portfolioTitle">Portfolio & Case Studies</h2>
                <p class="text-center text-gray-600 mb-12 max-w-2xl mx-auto" data-translate="portfolioSubTitle">Discover how we've helped businesses achieve significant digital growth and enhance their security posture.</p>
                <div class="portfolio-grid grid md:grid-cols-2 gap-8">
                    <div class="case-study-item bg-white rounded-lg shadow-md overflow-hidden hover:shadow-lg transition duration-300">
                        <img src="https://placehold.co/600x400/e2e8f0/cbd5e0?text=Case+Study+1" alt="Case Study 1" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <h3 class="text-xl font-bold mb-2 font-montserrat">Case Study: E-commerce SEO Boost</h3>
                            <p class="text-gray-600 mb-4">Challenge: Declining organic traffic. Solution: Comprehensive SEO audit and on-page optimization. Result: 40% increase in organic traffic.</p>
                            <a href="#" class="text-primary hover:underline font-semibold">Read More</a>
                        </div>
                    </div>
                    <div class="case-study-item bg-white rounded-lg shadow-md overflow-hidden hover:shadow-lg transition duration-300">
                         <img src="https://placehold.co/600x400/e2e8f0/cbd5e0?text=Case+Study+2" alt="Case Study 2" class="w-full h-48 object-cover">
                         <div class="p-6">
                            <h3 class="text-xl font-bold mb-2 font-montserrat">Case Study: Cybersecurity Audit</h3>
                            <p class="text-gray-600 mb-4">Challenge: Concerns over data breaches. Solution: Full security assessment and vulnerability patching. Result: Strengthened security posture, no incidents reported.</p>
                            <a href="#" class="text-primary hover:underline font-semibold">Read More</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="blog" class="section py-16 md:py-24 bg-light">
            <div class="container mx-auto px-4">
                 <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 font-montserrat" data-translate="blogTitle">Blog & Insights</h2>
                <p class="text-center text-gray-600 mb-12 max-w-2xl mx-auto" data-translate="blogSubTitle">Stay updated with the latest trends, tips, and strategies in digital marketing, SEO, and cybersecurity.</p>
                <div class="blog-grid grid md:grid-cols-2 gap-8">
                    <article class="blog-post-item bg-white rounded-lg shadow-md overflow-hidden hover:shadow-lg transition duration-300 flex flex-col md:flex-row">
                         <img src="https://placehold.co/300x200/e2e8f0/cbd5e0?text=Blog+Image+1" alt="Blog Post Title 1" class="w-full md:w-1/3 h-48 md:h-auto object-cover">
                         <div class="p-6 flex flex-col justify-between">
                            <div>
                                <h3 class="text-xl font-bold mb-2 font-montserrat"><a href="#" class="hover:text-primary">The Importance of Local SEO for Swedish Businesses</a></h3>
                                <p class="post-meta text-sm text-gray-500 mb-3">Posted on April 15, 2025</p>
                                <p class="text-gray-600 mb-4">Why focusing on local search is crucial for attracting customers in Malmö and beyond...</p>
                            </div>
                            <a href="#" class="text-primary hover:underline font-semibold mt-auto">Read Article</a>
                        </div>
                    </article>
                     <article class="blog-post-item bg-white rounded-lg shadow-md overflow-hidden hover:shadow-lg transition duration-300 flex flex-col md:flex-row">
                         <img src="https://placehold.co/300x200/e2e8f0/cbd5e0?text=Blog+Image+2" alt="Blog Post Title 2" class="w-full md:w-1/3
