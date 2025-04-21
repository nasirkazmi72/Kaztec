7AC59586-66A8-4771-94E3-67C8A48B240C.png  C5517338-4D58-42AF-8F7B-F8950AF444DB.png   please add these two images in this html code this company name and logo <!DOCTYPE html>

<html lang="en" id="html-tag"> <head>

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

                         <img src="https://placehold.co/300x200/e2e8f0/cbd5e0?text=Blog+Image+2" alt="Blog Post Title 2" class="w-full md:w-1/3 h-48 md:h-auto object-cover">

                         <div class="p-6 flex flex-col justify-between">

                             <div>

                                <h3 class="text-xl font-bold mb-2 font-montserrat"><a href="#" class="hover:text-primary">Top 5 Cybersecurity Threats in 2025</a></h3>

                                <p class="post-meta text-sm text-gray-500 mb-3">Posted on April 10, 2025</p>

                                <p class="text-gray-600 mb-4">Understand the evolving threat landscape and how to protect your digital assets...</p>

                             </div>

                            <a href="#" class="text-primary hover:underline font-semibold mt-auto">Read Article</a>

                        </div>

                    </article>

                 </div>

                 <div class="text-center mt-12">

                     <a href="#" class="cta-button bg-secondary hover:bg-gray-700 text-white font-bold py-3 px-8 rounded-full text-lg transition duration-300" data-translate="blogViewAll">View All Posts</a>

                 </div>

            </div>

        </section>



        <section id="contact" class="section py-16 md:py-24">

            <div class="container mx-auto px-4">

                <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 font-montserrat" data-translate="contactTitle">Contact Us</h2>

                <p class="text-center text-gray-600 mb-12 max-w-2xl mx-auto" data-translate="contactSubTitle">Ready to secure your digital growth? Get in touch with us for a consultation.</p>



                <div class="flex flex-wrap -mx-4">

                    <div class="w-full lg:w-1/2 px-4 mb-12 lg:mb-0">

                        <div class="contact-details mb-8 bg-light p-6 rounded-lg shadow">

                            <h3 class="text-xl font-semibold mb-4" data-translate="contactInfoTitle">Our Information</h3>

                            <p class="mb-2"><strong data-translate="contactAddrLabel">Address:</strong> Professorsgatan 8, 215 33 Malmö, Sweden</p>

                            <p class="mb-2"><strong data-translate="contactPhoneLabel">Phone:</strong> <a href="tel:+46793305758" class="text-primary hover:underline">+46 793305758</a></p>

                            <p><strong data-translate="contactEmailLabel">Email:</strong> <a href="mailto:info@kaztech.com" class="text-primary hover:underline">info@kaztech.com</a></p>

                        </div>



                        <div class="contact-form bg-light p-6 rounded-lg shadow">

                             <h3 class="text-xl font-semibold mb-4" data-translate="contactFormTitle">Send Us a Message</h3>

                            <form action="#" method="post">

                                <div class="form-group mb-4">

                                    <label for="name" class="block text-gray-700 font-semibold mb-2" data-translate="contactFormName">Name:</label>

                                    <input type="text" id="name" name="name" required class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-primary">

                                </div>

                                <div class="form-group mb-4">

                                    <label for="email" class="block text-gray-700 font-semibold mb-2" data-translate="contactFormEmail">Email:</label>

                                    <input type="email" id="email" name="email" required class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-primary">

                                </div>

                                <div class="form-group mb-4">

                                    <label for="subject" class="block text-gray-700 font-semibold mb-2" data-translate="contactFormSubject">Subject:</label>

                                    <input type="text" id="subject" name="subject" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-primary">

                                </div>

                                <div class="form-group mb-6">

                                    <label for="message" class="block text-gray-700 font-semibold mb-2" data-translate="contactFormMessage">Message:</label>

                                    <textarea id="message" name="message" rows="5" required class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-primary"></textarea>

                                </div>

                                <button type="submit" class="cta-button w-full bg-primary hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-lg transition duration-300" data-translate="contactFormSend">Send Message</button>

                            </form>

                        </div>

                    </div>



                    <div class="w-full lg:w-1/2 px-4">

                        <div class="google-map h-full rounded-lg shadow overflow-hidden">

                            <iframe

                                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2255.840786611101!2d12.98806861592298!3d55.58436398050919!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4653a15f4f8e9d6b%3A0x7a8a8b8c1d8e8f9a!2sProfessorsgatan%208%2C%20215%2033%20Malm%C3%B6%2C%20Sweden!5e0!3m2!1sen!2sus!4v1678886400000!5m2!1sen!2sus"

                                width="100%"

                                height="100%"

                                style="border:0; min-height: 450px;"

                                allowfullscreen=""

                                loading="lazy"

                                referrerpolicy="no-referrer-when-downgrade">

                            </iframe>

                        </div>

                    </div>

                </div>

            </div>

        </section>



    </main>



    <footer class="bg-dark text-gray-300 py-12">

        <div class="container mx-auto px-4">

            <div class="footer-content grid grid-cols-1 md:grid-cols-4 gap-8 mb-8">

                <div class="footer-logo mb-6 md:mb-0">

                     <img src="https://placehold.co/150x50/ffffff/343a40?text=KazTech+Footer" alt="KazTech Logo Footer" class="h-10 mb-4">

                     <p class="text-sm" data-translate="footerSlogan">Securing your digital future.</p>

                </div>

                <div class="footer-nav">

                    <h4 class="font-semibold text-white mb-3" data-translate="footerLinksTitle">Quick Links</h4>

                    <ul class="space-y-2">

                         <li><a href="#home" class="hover:text-primary hover:underline" data-translate="footerHome">Home</a></li>

                        <li><a href="#about" class="hover:text-primary hover:underline" data-translate="footerAbout">About Us</a></li>

                        <li><a href="#services" class="hover:text-primary hover:underline" data-translate="footerServices">Services</a></li>

                        <li><a href="#portfolio" class="hover:text-primary hover:underline" data-translate="footerPortfolio">Portfolio</a></li>

                        <li><a href="#blog" class="hover:text-primary hover:underline" data-translate="footerBlog">Blog</a></li>

                        <li><a href="#contact" class="hover:text-primary hover:underline" data-translate="footerContact">Contact</a></li>

                    </ul>

                </div>

                <div class="footer-contact">

                     <h4 class="font-semibold text-white mb-3" data-translate="footerContactTitle">Contact Info</h4>

                     <p class="mb-2">Professorsgatan 8, 215 33 Malmö, Sweden</p>

                     <p class="mb-2">P: <a href="tel:+46793305758" class="hover:text-primary hover:underline">+46 793305758</a></p>

                     <p>E: <a href="mailto:info@kaztech.com" class="hover:text-primary hover:underline">info@kaztech.com</a></p>

                </div>

                <div class="social-media">

                    <h4 class="font-semibold text-white mb-3" data-translate="footerSocialTitle">Follow Us</h4>

                    <div class="flex space-x-4">

                        <a href="#" aria-label="Facebook" class="text-gray-400 hover:text-primary">

                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.772-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"></path></svg>

                        </a>

                        <a href="#" aria-label="LinkedIn" class="text-gray-400 hover:text-primary">

                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"></path></svg>

                        </a>

                    </div>

                </div>

            </div>

            <div class="copyright border-t border-gray-700 pt-8 text-center text-sm">

                <p data-translate="footerCopyright">© 2025 KazTech. All rights reserved.</p>

            </div>

        </div>

    </footer>



    <script>

        // --- Translations Object ---

        // Add all text content that needs translation here, keyed by the 'data-translate' attribute value.

        const translations = {

            pageTitle: {

                en: "KazTech - Securing Digital Growth",

                sv: "KazTech - Säkrar Digital Tillväxt",

                zh: "KazTech - 保障数字增长",

                ar: "كازتيك - تأمين النمو الرقمي"

            },

            navHome: { en: "Home", sv: "Hem", zh: "首页", ar: "الرئيسية" },

            navAbout: { en: "About Us", sv: "Om Oss", zh: "关于我们", ar: "من نحن" },

            navServices: { en: "Services", sv: "Tjänster", zh: "服务", ar: "خدماتنا" },

            navPortfolio: { en: "Portfolio", sv: "Portfölj", zh: "作品集", ar: "أعمالنا" },

            navBlog: { en: "Blog", sv: "Blogg", zh: "博客", ar: "المدونة" },

            navContact: { en: "Contact", sv: "Kontakt", zh: "联系", ar: "اتصل بنا" },

            navHomeMobile: { en: "Home", sv: "Hem", zh: "首页", ar: "الرئيسية" },

            navAboutMobile: { en: "About Us", sv: "Om Oss", zh: "关于我们", ar: "من نحن" },

            navServicesMobile: { en: "Services", sv: "Tjänster", zh: "服务", ar: "خدماتنا" },

            navPortfolioMobile: { en: "Portfolio", sv: "Portfölj", zh: "作品集", ar: "أعمالنا" },

            navBlogMobile: { en: "Blog", sv: "Blogg", zh: "博客", ar: "المدونة" },

            navContactMobile: { en: "Contact", sv: "Kontakt", zh: "联系", ar: "اتصل بنا" },

            navLanguageMobile: { en: "Language:", sv: "Språk:", zh: "语言:", ar: "اللغة:" },

            heroHeadline: {

                en: "Securing Digital Growth",

                sv: "Säkrar Digital Tillväxt",

                zh: "保障数字增长",

                ar: "تأمين النمو الرقمي"

            },

            heroSubheadline: {

                en: "Empowering businesses in Sweden and beyond with expert Digital Marketing, robust SEO, and essential Cybersecurity solutions.",

                sv: "Stärker företag i Sverige och utomlands med expertis inom Digital Marknadsföring, robust SEO och grundläggande Cybersäkerhetslösningar.",

                zh: "为瑞典及其他地区的企业提供专业的数字营销、强大的搜索引擎优化和必要的网络安全解决方案。",

                ar: "تمكين الشركات في السويد وخارجها من خلال التسويق الرقمي المتخصص، وتحسين محركات البحث القوي، وحلول الأمن السيبراني الأساسية."

            },

            heroCTA: {

                en: "Request a Consultation",

                sv: "Begär en Konsultation",

                zh: "请求咨询",

                ar: "اطلب استشارة"

            },

            aboutTitle: {

                en: "About KazTech",

                sv: "Om KazTech",

                zh: "关于 KazTech",

                ar: "عن كازتيك"

            },

            aboutPara1: {

                 en: "KazTech was founded in Sweden with a mission to bridge the gap between business ambitions and digital success. We are a team of dedicated professionals with deep expertise in navigating the complexities of the digital landscape.",

                 sv: "KazTech grundades i Sverige med uppdraget att överbrygga klyftan mellan affärsambitioner och digital framgång. Vi är ett team av engagerade proffs med djup expertis i att navigera komplexiteten i det digitala landskapet.",

                 zh: "KazTech 在瑞典成立，其使命是弥合商业雄心与数字成功之间的差距。我们是一支由敬业的专业人士组成的团队，在驾驭复杂的数字环境方面拥有深厚的专业知识。",

                 ar: "تأسست كازتيك في السويد بهدف سد الفجوة بين طموحات الأعمال والنجاح الرقمي. نحن فريق من المهنيين المتخصصين ذوي الخبرة العميقة في التعامل مع تعقيدات المشهد الرقمي."

             },

             aboutPara2: {

                 en: "Our commitment is to deliver innovative, results-driven solutions that not only enhance your online presence but also safeguard your valuable digital assets. We believe in building long-term partnerships based on trust, transparency, and measurable results.",

                 sv: "Vårt åtagande är att leverera innovativa, resultatdrivna lösningar som inte bara förbättrar din online-närvaro utan också skyddar dina värdefulla digitala tillgångar. Vi tror på att bygga långsiktiga partnerskap baserade på förtroende, transparens och mätbara resultat.",

                 zh: "我们的承诺是提供创新的、以结果为导向的解决方案，不仅能提升您的在线形象，还能保护您宝贵的数字资产。我们相信在信任、透明和可衡量结果的基础上建立长期合作伙伴关系。",

                 ar: "التزامنا هو تقديم حلول مبتكرة قائمة على النتائج لا تعزز وجودك عبر الإنترنت فحسب، بل تحمي أيضًا أصولك الرقمية القيمة. نؤمن ببناء شراكات طويلة الأمد قائمة على الثقة والشفافية والنتائج القابلة للقياس."

             },

            servicesTitle: {

                en: "Our Services",

                sv: "Våra Tjänster",

                zh: "我们的服务",

                ar: "خدماتنا"

            },

             servicesSubTitle: {

                 en: "We offer a comprehensive suite of IT services designed to propel your business forward digitally and ensure its security.",

                 sv: "Vi 
