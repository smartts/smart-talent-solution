<!DOCTYPE html>
<html lang="en" class="scroll-smooth">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smart Talent Solution (PVT) LTD - Manpower & Recruitment Experts</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;500;600;700;800&display=swap');

        body {
            font-family: 'Outfit', sans-serif;
        }

        .hero-pattern {
            background-image: linear-gradient(to right, rgba(15, 23, 42, 0.9), rgba(15, 23, 42, 0.7)), url('https://images.unsplash.com/photo-1600880292203-757bb62b4baf?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }

        .blob {
            border-radius: 40% 60% 70% 30% / 40% 50% 60% 50%;
            animation: morph 8s ease-in-out infinite;
        }

        @keyframes morph {

            0%,
            100% {
                border-radius: 40% 60% 70% 30% / 40% 50% 60% 50%;
            }

            34% {
                border-radius: 70% 30% 50% 50% / 30% 30% 70% 70%;
            }

            67% {
                border-radius: 100% 60% 60% 100% / 100% 100% 60% 60%;
            }
        }
    </style>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#1d4ed8', // blue-700
                        secondary: '#eab308', // yellow-500
                        dark: '#0f172a',
                        light: '#f8fafc'
                    }
                }
            }
        }
    </script>
</head>

<body class="bg-gray-50 text-gray-800 antialiased overflow-x-hidden">

    <!-- Navbar -->
    <nav class="fixed w-full z-50 transition-all duration-300 bg-white shadow-md" id="navbar">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <div class="flex-shrink-0 flex items-center">
                    <a href="index.html" class="flex items-center gap-3">
                        <svg class="h-10 w-10 text-primary" viewBox="0 0 100 100" fill="none"
                            xmlns="http://www.w3.org/2000/svg">
                            <path
                                d="M50 10C27.9 10 10 27.9 10 50C10 72.1 27.9 90 50 90C72.1 90 90 72.1 90 50C90 27.9 72.1 10 50 10ZM50 85C30.7 85 15 69.3 15 50C15 30.7 30.7 15 50 15C69.3 15 85 30.7 85 50C85 69.3 69.3 85 50 85Z"
                                fill="#1d4ed8" />
                            <path d="M70 20C55 10 35 15 25 30C15 45 20 65 35 75" stroke="#eab308" stroke-width="6"
                                stroke-linecap="round" />
                            <path
                                d="M45 40C45 37.2 47.2 35 50 35C52.8 35 55 37.2 55 40C55 42.8 52.8 45 50 45C47.2 45 45 42.8 45 40ZM48 48H52V65H48V48ZM40 68H60V72H40V68Z"
                                fill="#eab308" />
                            <path
                                d="M50 30C44.5 30 40 34.5 40 40C40 43.1 41.4 45.8 43.7 47.6V55H56.3V47.6C58.6 45.8 60 43.1 60 40C60 34.5 55.5 30 50 30ZM53.6 44.9C52.1 46.1 51 47.8 50.8 49.7H49.2C49 47.8 47.9 46.1 46.4 44.9C44.7 43.6 43.6 41.5 43.8 39.2C44 36.3 46.6 34 49.5 33.8C52.7 33.6 55.4 36 55.8 39.1C56 41.4 55.1 43.5 53.6 44.9Z"
                                fill="#1d4ed8" />
                        </svg>
                        <span class="font-bold text-xl md:text-2xl text-dark tracking-tight leading-tight">Smart
                            Talent<br><span class="text-primary">Solution</span></span>
                    </a>
                </div>
                <div class="hidden md:flex space-x-8 items-center">
                    <a href="index.html"
                        class="text-primary font-semibold hover:text-secondary transition-colors">Home</a>
                    <a href="about.html" class="text-gray-600 font-medium hover:text-primary transition-colors">About
                        Us</a>
                    <a href="services.html"
                        class="text-gray-600 font-medium hover:text-primary transition-colors">Services</a>
                    <a href="contact.html"
                        class="text-gray-600 font-medium hover:text-primary transition-colors">Contact</a>
                    <a href="contact.html"
                        class="bg-primary hover:bg-blue-800 text-white px-6 py-2.5 rounded-full font-medium transition-all shadow-lg shadow-blue-500/30 hover:shadow-blue-500/50 transform hover:-translate-y-0.5">Get
                        a Quote</a>
                </div>
                <!-- Mobile menu button -->
                <div class="md:hidden flex items-center">
                    <button class="mobile-menu-button text-gray-600 hover:text-primary focus:outline-none">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile Menu -->
        <div class="hidden mobile-menu md:hidden bg-white border-t border-gray-100">
            <a href="index.html" class="block py-3 px-6 text-sm bg-blue-50 text-primary font-semibold">Home</a>
            <a href="about.html" class="block py-3 px-6 text-sm text-gray-600 hover:bg-gray-50">About Us</a>
            <a href="services.html" class="block py-3 px-6 text-sm text-gray-600 hover:bg-gray-50">Services</a>
            <a href="contact.html" class="block py-3 px-6 text-sm text-gray-600 hover:bg-gray-50">Contact</a>
            <div class="px-6 py-4">
                <a href="contact.html"
                    class="block w-full text-center bg-primary text-white px-4 py-2 rounded-lg font-medium">Get a
                    Quote</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="relative h-screen min-h-[600px] flex items-center hero-pattern pt-20">
        <div class="absolute inset-0 bg-gradient-to-r from-dark/90 to-dark/40 z-0"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 w-full">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div class="text-white space-y-8 animate-[fadeInUp_1s_ease-out]">
                    <div
                        class="inline-block px-4 py-1.5 rounded-full bg-white/10 backdrop-blur-sm border border-white/20 text-secondary font-medium text-sm mb-2">
                        <i class="fas fa-star mr-2"></i> Leading Manpower Agency in Sri Lanka
                    </div>
                    <h1 class="text-4xl md:text-5xl lg:text-6xl font-extrabold leading-tight">
                        Connecting Elite Talent With <span class="text-secondary">Great Companies</span>
                    </h1>
                    <p class="text-lg md:text-xl text-gray-300 font-light max-w-xl">
                        Smart Talent Solution (PVT) LTD specializes in providing high-quality workforce solutions. We
                        bridge the gap between skilled professionals and businesses seeking excellence.
                    </p>
                    <div class="flex flex-col sm:flex-row gap-4 pt-4">
                        <a href="services.html"
                            class="bg-secondary hover:bg-yellow-400 text-dark font-bold px-8 py-4 rounded-full text-center transition-all transform hover:-translate-y-1 shadow-lg shadow-yellow-500/30 flex items-center justify-center group">
                            Our Services <i
                                class="fas fa-arrow-right ml-2 group-hover:translate-x-1 transition-transform"></i>
                        </a>
                        <a href="contact.html"
                            class="border border-white/30 hover:border-white hover:bg-white/10 text-white font-medium px-8 py-4 rounded-full text-center transition-all backdrop-blur-sm shadow-lg">
                            Hire Staff Now
                        </a>
                    </div>
                    <div class="flex items-center gap-6 pt-8 border-t border-white/10 mt-8">
                        <div>
                            <p class="text-3xl font-bold text-white">500+</p>
                            <p class="text-gray-400 text-sm">Positions Filled</p>
                        </div>
                        <div class="h-10 w-px bg-white/20"></div>
                        <div>
                            <p class="text-3xl font-bold text-white">50+</p>
                            <p class="text-gray-400 text-sm">Corporate Clients</p>
                        </div>
                        <div class="h-10 w-px bg-white/20"></div>
                        <div>
                            <p class="text-3xl font-bold text-white">99%</p>
                            <p class="text-gray-400 text-sm">Success Rate</p>
                        </div>
                    </div>
                </div>

                <div class="hidden lg:block relative">
                    <div class="absolute -inset-4 bg-primary/20 blob blur-xl z-0"></div>
                    <img src="https://images.unsplash.com/photo-1573164713988-8665fc963095?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80"
                        alt="Professional meeting"
                        class="relative z-10 w-full rounded-2xl shadow-2xl border-4 border-white/10 object-cover h-[500px]">

                    <!-- Floating card -->
                    <div
                        class="absolute -bottom-10 -left-10 bg-white p-6 rounded-2xl shadow-2xl z-20 flex items-center gap-4 animate-[bounce_3s_infinite_alternate]">
                        <div class="bg-green-100 text-green-600 p-4 rounded-full">
                            <i class="fas fa-check-circle text-2xl"></i>
                        </div>
                        <div>
                            <p class="text-dark font-bold text-lg">Verified Candidates</p>
                            <p class="text-gray-500 text-sm">100% Background Checked</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Partners / Trusted By -->
    <section class="py-10 border-b border-gray-200 bg-white relative z-20">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <p class="text-gray-500 text-sm font-semibold uppercase tracking-wider mb-6">Trusted by leading companies
                nationwide</p>
            <div
                class="flex flex-wrap justify-center gap-8 md:gap-16 opacity-60 grayscale hover:grayscale-0 transition-all duration-500 child-hover:opacity-100">
                <i class="fab fa-aws text-4xl"></i>
                <i class="fab fa-microsoft text-4xl"></i>
                <i class="fab fa-google text-4xl"></i>
                <i class="fab fa-accusoft text-4xl"></i>
                <i class="fab fa-atlassian text-4xl"></i>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section class="py-24 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-primary font-bold tracking-wide uppercase text-sm mb-2">What We Do</h2>
                <h3 class="text-3xl md:text-4xl font-extrabold text-dark mb-4">Comprehensive Manpower Solutions</h3>
                <p class="text-gray-600 text-lg">We offer end-to-end recruitment and staffing services tailored to meet
                    the unique needs of your organization.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div
                    class="bg-white rounded-2xl p-8 shadow-lg hover:shadow-xl transition-all duration-300 border border-gray-100 group">
                    <div
                        class="w-16 h-16 bg-blue-50 text-primary rounded-2xl flex items-center justify-center text-2xl mb-6 group-hover:bg-primary group-hover:text-white transition-colors duration-300">
                        <i class="fas fa-users-gear"></i>
                    </div>
                    <h4 class="text-xl font-bold text-dark mb-3">Temporary Staffing</h4>
                    <p class="text-gray-600 mb-6">Flexible workforce solutions for seasonal demands, special projects,
                        or employee absences without long-term commitment.</p>
                    <a href="services.html"
                        class="text-primary font-medium flex items-center group-hover:text-dark transition-colors">Learn
                        more <i class="fas fa-arrow-right ml-2 text-sm"></i></a>
                </div>

                <!-- Service 2 -->
                <div
                    class="bg-dark rounded-2xl p-8 shadow-xl hover:-translate-y-2 transition-transform duration-300 relative overflow-hidden group">
                    <div class="absolute top-0 right-0 w-32 h-32 bg-primary/20 rounded-full blur-2xl -mr-10 -mt-10">
                    </div>
                    <div
                        class="w-16 h-16 bg-white/10 text-secondary rounded-2xl flex items-center justify-center text-2xl mb-6">
                        <i class="fas fa-user-tie"></i>
                    </div>
                    <h4 class="text-xl font-bold text-white mb-3">Permanent Placement</h4>
                    <p class="text-gray-300 mb-6">Finding the perfect full-time employees who align with your company
                        culture and possess the exact skills you need.</p>
                    <a href="services.html"
                        class="text-secondary font-medium flex items-center hover:text-white transition-colors">Learn
                        more <i class="fas fa-arrow-right ml-2 text-sm"></i></a>
                </div>

                <!-- Service 3 -->
                <div
                    class="bg-white rounded-2xl p-8 shadow-lg hover:shadow-xl transition-all duration-300 border border-gray-100 group">
                    <div
                        class="w-16 h-16 bg-blue-50 text-primary rounded-2xl flex items-center justify-center text-2xl mb-6 group-hover:bg-primary group-hover:text-white transition-colors duration-300">
                        <i class="fas fa-magnifying-glass-chart"></i>
                    </div>
                    <h4 class="text-xl font-bold text-dark mb-3">Executive Search</h4>
                    <p class="text-gray-600 mb-6">Targeted headhunting for C-suite and senior management roles. We find
                        industry leaders who drive real business growth.</p>
                    <a href="services.html"
                        class="text-primary font-medium flex items-center group-hover:text-dark transition-colors">Learn
                        more <i class="fas fa-arrow-right ml-2 text-sm"></i></a>
                </div>
            </div>

            <div class="text-center mt-12">
                <a href="services.html"
                    class="inline-block bg-white border-2 border-primary text-primary hover:bg-primary hover:text-white font-semibold px-8 py-3 rounded-full transition-colors">View
                    All Services</a>
            </div>
        </div>
    </section>

    <!-- Why Choose Us / About snippet -->
    <section class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
                <div class="relative">
                    <img src="https://images.unsplash.com/photo-1522071820081-009f0129c71c?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80"
                        alt="Team collaborating" class="rounded-3xl shadow-xl w-full">
                    <div
                        class="absolute -bottom-8 -right-8 bg-primary text-white p-8 rounded-3xl shadow-2xl hidden md:block max-w-xs">
                        <h4 class="text-4xl font-extrabold mb-2">10+</h4>
                        <p class="text-blue-100 font-medium">Years of Excellence in HR & Recruitment</p>
                    </div>
                </div>

                <div class="space-y-6">
                    <h2 class="text-primary font-bold tracking-wide uppercase text-sm">Why Choose Us</h2>
                    <h3 class="text-3xl md:text-4xl font-extrabold text-dark leading-tight">We Are The Best Manpower
                        Agency For Your Business</h3>
                    <p class="text-gray-600 text-lg">At Smart Talent Solution (PVT) LTD, we don't just fill vacancies;
                        we build highly effective teams. Our rigorous screening process ensures you only meet candidates
                        who are truly exceptional fits for your roles.</p>

                    <ul class="space-y-4 mt-6">
                        <li class="flex items-start gap-4">
                            <div class="bg-green-100 text-green-600 p-2 rounded-full mt-1 shrink-0">
                                <i class="fas fa-check text-sm"></i>
                            </div>
                            <div>
                                <h5 class="font-bold text-dark text-lg">Extensive Talent Pool</h5>
                                <p class="text-gray-600">Access to thousands of pre-screened professionals across
                                    various industries.</p>
                            </div>
                        </li>
                        <li class="flex items-start gap-4">
                            <div class="bg-green-100 text-green-600 p-2 rounded-full mt-1 shrink-0">
                                <i class="fas fa-check text-sm"></i>
                            </div>
                            <div>
                                <h5 class="font-bold text-dark text-lg">Time & Cost Efficient</h5>
                                <p class="text-gray-600">We handle the entire process from sourcing to onboarding,
                                    saving you valuable resources.</p>
                            </div>
                        </li>
                        <li class="flex items-start gap-4">
                            <div class="bg-green-100 text-green-600 p-2 rounded-full mt-1 shrink-0">
                                <i class="fas fa-check text-sm"></i>
                            </div>
                            <div>
                                <h5 class="font-bold text-dark text-lg">Guaranteed Replacements</h5>
                                <p class="text-gray-600">Peace of mind with our replacement guarantee if a candidate
                                    doesn't work out.</p>
                            </div>
                        </li>
                    </ul>

                    <div class="pt-6">
                        <a href="about.html"
                            class="bg-primary hover:bg-blue-800 text-white font-semibold px-8 py-4 rounded-full transition-colors inline-block shadow-lg shadow-blue-500/30">Read
                            Our Story</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="py-20 bg-primary relative overflow-hidden">
        <div class="absolute inset-0 bg-[url('https://www.transparenttextures.com/patterns/cubes.png')] opacity-10">
        </div>
        <div class="absolute top-0 right-0 -mt-20 -mr-20 w-80 h-80 bg-blue-600 rounded-full blur-3xl opacity-50"></div>
        <div class="absolute bottom-0 left-0 -mb-20 -ml-20 w-80 h-80 bg-blue-800 rounded-full blur-3xl opacity-50">
        </div>

        <div class="max-w-4xl mx-auto px-4 relative z-10 text-center text-white">
            <h2 class="text-3xl md:text-5xl font-extrabold mb-6">Ready To Build Your Dream Team?</h2>
            <p class="text-blue-100 text-lg md:text-xl mb-10 max-w-2xl mx-auto">Contact us today to discuss your
                staffing requirements. Let our experts find the perfect talent for your business growth.</p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="contact.html"
                    class="bg-secondary hover:bg-yellow-400 text-dark font-bold px-10 py-4 rounded-full text-center transition-all shadow-xl inline-block text-lg">
                    Contact Us Now
                </a>
                <a href="tel:+94771234567"
                    class="bg-transparent border-2 border-white hover:bg-white hover:text-primary text-white font-bold px-10 py-4 rounded-full text-center transition-all inline-block text-lg">
                    <i class="fas fa-phone mr-2"></i> Call +94 77 123 4567
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-gray-300 pt-16 pb-8 border-t-4 border-secondary">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-12 mb-12">
                <div class="col-span-1 lg:col-span-1">
                    <div class="flex items-center gap-3 mb-6">
                        <svg class="h-8 w-8 text-secondary" viewBox="0 0 100 100" fill="none"
                            xmlns="http://www.w3.org/2000/svg">
                            <path
                                d="M50 10C27.9 10 10 27.9 10 50C10 72.1 27.9 90 50 90C72.1 90 90 72.1 90 50C90 27.9 72.1 10 50 10ZM50 85C30.7 85 15 69.3 15 50C15 30.7 30.7 15 50 15C69.3 15 85 30.7 85 50C85 69.3 69.3 85 50 85Z"
                                fill="#eab308" />
                            <path d="M70 20C55 10 35 15 25 30C15 45 20 65 35 75" stroke="#ffffff" stroke-width="6"
                                stroke-linecap="round" />
                            <path
                                d="M45 40C45 37.2 47.2 35 50 35C52.8 35 55 37.2 55 40C55 42.8 52.8 45 50 45C47.2 45 45 42.8 45 40ZM48 48H52V65H48V48ZM40 68H60V72H40V68Z"
                                fill="#ffffff" />
                        </svg>
                        <span class="font-bold text-xl text-white tracking-tight">Smart Talent</span>
                    </div>
                    <p class="text-sm text-gray-400 mb-6 leading-relaxed">Smart Talent Solution (PVT) LTD is your
                        trusted partner in manpower recruitment, connecting leading companies with exceptional talents.
                    </p>
                    <div class="flex space-x-4">
                        <a href="#"
                            class="w-10 h-10 rounded-full bg-gray-800 flex items-center justify-center hover:bg-primary hover:text-white transition-colors"><i
                                class="fab fa-facebook-f"></i></a>
                        <a href="#"
                            class="w-10 h-10 rounded-full bg-gray-800 flex items-center justify-center hover:bg-primary hover:text-white transition-colors"><i
                                class="fab fa-twitter"></i></a>
                        <a href="#"
                            class="w-10 h-10 rounded-full bg-gray-800 flex items-center justify-center hover:bg-primary hover:text-white transition-colors"><i
                                class="fab fa-linkedin-in"></i></a>
                        <a href="#"
                            class="w-10 h-10 rounded-full bg-gray-800 flex items-center justify-center hover:bg-primary hover:text-white transition-colors"><i
                                class="fab fa-instagram"></i></a>
                    </div>
                </div>

                <div>
                    <h4 class="text-white font-bold text-lg mb-6 relative inline-block">
                        Quick Links
                        <span class="absolute -bottom-2 left-0 w-1/2 h-1 bg-secondary rounded-full"></span>
                    </h4>
                    <ul class="space-y-3">
                        <li><a href="index.html" class="hover:text-secondary transition-colors flex items-center"><i
                                    class="fas fa-chevron-right text-xs mr-2 text-primary"></i> Home</a></li>
                        <li><a href="about.html" class="hover:text-secondary transition-colors flex items-center"><i
                                    class="fas fa-chevron-right text-xs mr-2 text-primary"></i> About Us</a></li>
                        <li><a href="services.html" class="hover:text-secondary transition-colors flex items-center"><i
                                    class="fas fa-chevron-right text-xs mr-2 text-primary"></i> Services</a></li>
                        <li><a href="contact.html" class="hover:text-secondary transition-colors flex items-center"><i
                                    class="fas fa-chevron-right text-xs mr-2 text-primary"></i> Contact</a></li>
                    </ul>
                </div>

                <div>
                    <h4 class="text-white font-bold text-lg mb-6 relative inline-block">
                        Services
                        <span class="absolute -bottom-2 left-0 w-1/2 h-1 bg-secondary rounded-full"></span>
                    </h4>
                    <ul class="space-y-3">
                        <li><a href="services.html" class="hover:text-secondary transition-colors flex items-center"><i
                                    class="fas fa-chevron-right text-xs mr-2 text-primary"></i> Temporary Staffing</a>
                        </li>
                        <li><a href="services.html" class="hover:text-secondary transition-colors flex items-center"><i
                                    class="fas fa-chevron-right text-xs mr-2 text-primary"></i> Permanent Placement</a>
                        </li>
                        <li><a href="services.html" class="hover:text-secondary transition-colors flex items-center"><i
                                    class="fas fa-chevron-right text-xs mr-2 text-primary"></i> Executive Search</a>
                        </li>
                        <li><a href="services.html" class="hover:text-secondary transition-colors flex items-center"><i
                                    class="fas fa-chevron-right text-xs mr-2 text-primary"></i> HR Consulting</a></li>
                    </ul>
                </div>

                <div>
                    <h4 class="text-white font-bold text-lg mb-6 relative inline-block">
                        Contact Info
                        <span class="absolute -bottom-2 left-0 w-1/2 h-1 bg-secondary rounded-full"></span>
                    </h4>
                    <ul class="space-y-4">
                        <li class="flex items-start gap-3">
                            <i class="fas fa-map-marker-alt text-primary mt-1"></i>
                            <span class="text-sm">123 Business Avenue, Colombo 03, Sri Lanka</span>
                        </li>
                        <li class="flex items-center gap-3">
                            <i class="fas fa-phone-alt text-primary"></i>
                            <span class="text-sm">+94 11 234 5678</span>
                        </li>
                        <li class="flex items-center gap-3">
                            <i class="fas fa-envelope text-primary"></i>
                            <span class="text-sm">info@smarttalentsolution.lk</span>
                        </li>
                    </ul>
                </div>
            </div>

            <div
                class="border-t border-gray-800 pt-8 flex flex-col md:flex-row justify-between items-center text-sm text-gray-500">
                <p>&copy; 2026 Smart Talent Solution (PVT) LTD. All Rights Reserved.</p>
                <div class="flex space-x-4 mt-4 md:mt-0">
                    <a href="#" class="hover:text-white transition-colors">Privacy Policy</a>
                    <a href="#" class="hover:text-white transition-colors">Terms of Service</a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Script to add background to navbar on scroll & Mobile Menu -->
    <script>
        document.addEventListener('DOMContentLoaded', function () {
            // Navbar scroll effect
            const navbar = document.getElementById('navbar');
            window.addEventListener('scroll', () => {
                if (window.scrollY > 10) {
                    navbar.classList.add('py-0');
                    navbar.classList.remove('py-2');
                } else {
                    navbar.classList.add('py-2');
                    navbar.classList.remove('py-0');
                }
            });

            // Mobile menu toggle
            const btn = document.querySelector("button.mobile-menu-button");
            const menu = document.querySelector(".mobile-menu");

            btn.addEventListener("click", () => {
                menu.classList.toggle("hidden");
            });

            // Add animation classes on intersection
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('animate-[fadeInUp_1s_ease-out]');
                    }
                });
            });
        });
    </script>
</body>

</html>
