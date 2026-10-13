# bubblehound.vip
Bubble Hound Website
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bubble Hound | Discover & Track Rare Bubbles</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['"Plus Jakarta Sans"', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            50: '#f0f7ff',
                            100: '#e0effe',
                            500: '#3b82f6',
                            600: '#2563eb',
                            700: '#1d4ed8',
                        }
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-slate-50 text-slate-800 antialiased font-sans">

    <!-- Navigation -->
    <nav class="fixed top-0 left-0 right-0 z-50 bg-white/80 backdrop-blur-md border-b border-slate-200/80">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
            <div class="flex items-center space-x-3">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-blue-600 to-cyan-400 flex items-center justify-center text-white shadow-md shadow-blue-500/20">
                    <i class="fa-solid fa-dog text-lg"></i>
                </div>
                <span class="text-xl font-bold bg-gradient-to-r from-blue-600 to-cyan-600 bg-clip-text text-transparent">Bubble Hound</span>
            </div>
            
            <div class="hidden md:flex items-center space-x-8 text-sm font-semibold text-slate-600">
                <a href="#features" class="hover:text-blue-600 transition-colors">Features</a>
                <a href="#support" class="hover:text-blue-600 transition-colors">Support</a>
                <a href="#privacy" class="hover:text-blue-600 transition-colors">Privacy Policy</a>
            </div>

            <a href="#download" class="inline-flex items-center justify-center px-4 py-2 text-sm font-semibold text-white bg-blue-600 hover:bg-blue-700 rounded-xl shadow-sm transition-all">
                Get App
            </a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="pt-32 pb-20 md:pt-40 md:pb-28 overflow-hidden">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                
                <div class="lg:col-span-7 text-center lg:text-left space-y-6">
                    <div class="inline-flex items-center space-x-2 px-3 py-1 rounded-full bg-blue-100/80 text-blue-700 text-xs font-bold uppercase tracking-wider">
                        <i class="fa-solid fa-sparkles"></i>
                        <span>Now in Beta Testing</span>
                    </div>
                    
                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold text-slate-900 tracking-tight leading-none">
                        Sniff out the best <span class="bg-gradient-to-r from-blue-600 to-cyan-500 bg-clip-text text-transparent">Bubble Deals</span> instantly.
                    </h1>
                    
                    <p class="text-lg text-slate-600 max-w-xl mx-auto lg:mx-0 font-medium">
                        Bubble Hound makes tracking, analyzing, and discovering special listings effortless. Get real-time alerts right on your phone.
                    </p>

                    <!-- App Download Buttons -->
                    <div id="download" class="pt-4 flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4">
                        <a href="#" class="w-full sm:w-auto inline-flex items-center justify-center space-x-3 bg-slate-900 hover:bg-slate-800 text-white px-6 py-3.5 rounded-2xl shadow-lg transition-all hover:-translate-y-0.5">
                            <i class="fa-brands fa-apple text-2xl"></i>
                            <div class="text-left">
                                <p class="text-[10px] uppercase font-semibold text-slate-400 leading-tight">Download on the</p>
                                <p class="text-sm font-bold text-white leading-tight">App Store</p>
                            </div>
                        </a>

                        <a href="#" class="w-full sm:w-auto inline-flex items-center justify-center space-x-3 bg-slate-900 hover:bg-slate-800 text-white px-6 py-3.5 rounded-2xl shadow-lg transition-all hover:-translate-y-0.5">
                            <i class="fa-brands fa-google-play text-xl"></i>
                            <div class="text-left">
                                <p class="text-[10px] uppercase font-semibold text-slate-400 leading-tight">Get it on</p>
                                <p class="text-sm font-bold text-white leading-tight">Google Play</p>
                            </div>
                        </a>
                    </div>
                </div>

                <!-- Hero Phone Showcase Mockup -->
                <div class="lg:col-span-5 flex justify-center">
                    <div class="relative w-64 h-[500px] bg-slate-900 rounded-[45px] p-3 shadow-2xl ring-1 ring-slate-900/10">
                        <div class="absolute top-0 left-1/2 -translate-x-1/2 w-32 h-5 bg-slate-900 rounded-b-2xl z-20"></div>
                        <div class="w-full h-full bg-slate-100 rounded-[35px] overflow-hidden flex flex-col pt-8 px-4 space-y-4">
                            <!-- Mock UI Card 1 -->
                            <div class="bg-white p-3.5 rounded-2xl shadow-sm border border-slate-200/60 flex items-center space-x-3">
                                <div class="w-10 h-10 rounded-xl bg-blue-100 text-blue-600 flex items-center justify-center font-bold">
                                    <i class="fa-solid fa-bell"></i>
                                </div>
                                <div>
                                    <p class="text-xs font-bold text-slate-800">Alert Triggered!</p>
                                    <p class="text-[10px] text-slate-500">New bubble found near you</p>
                                </div>
                            </div>

                            <!-- Mock UI Card 2 -->
                            <div class="bg-gradient-to-br from-blue-600 to-indigo-600 p-4 rounded-2xl text-white shadow-md">
                                <p class="text-[11px] font-semibold text-blue-100">Live Status</p>
                                <p class="text-xl font-extrabold mt-1">Hound Active</p>
                                <p class="text-[10px] text-blue-200 mt-2">Scanning 24/7 for updates</p>
                            </div>

                            <!-- Mock UI Card 3 -->
                            <div class="bg-white p-3 rounded-2xl shadow-sm border border-slate-200/60 flex-1 space-y-2">
                                <div class="h-2 bg-slate-200 rounded-full w-3/4"></div>
                                <div class="h-2 bg-slate-100 rounded-full w-1/2"></div>
                                <div class="h-2 bg-slate-100 rounded-full w-full"></div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="py-20 bg-white border-y border-slate-200/80">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <h2 class="text-3xl font-bold text-slate-900">Designed for Speed and Simplicity</h2>
                <p class="text-slate-600 mt-3 font-medium">Everything you need to track and manage notifications easily.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="p-6 rounded-2xl bg-slate-50 border border-slate-200/60">
                    <div class="w-12 h-12 rounded-xl bg-blue-100 text-blue-600 flex items-center justify-center text-xl font-bold mb-4">
                        <i class="fa-solid fa-bolt"></i>
                    </div>
                    <h3 class="text-lg font-bold text-slate-900">Instant Alerts</h3>
                    <p class="text-slate-600 text-sm mt-2">Get notified the moment matching listings or updates appear.</p>
                </div>

                <div class="p-6 rounded-2xl bg-slate-50 border border-slate-200/60">
                    <div class="w-12 h-12 rounded-xl bg-cyan-100 text-cyan-600 flex items-center justify-center text-xl font-bold mb-4">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <h3 class="text-lg font-bold text-slate-900">Secure Account Access</h3>
                    <p class="text-slate-600 text-sm mt-2">Quick OTP phone verification gets you in securely without complex passwords.</p>
                </div>

                <div class="p-6 rounded-2xl bg-slate-50 border border-slate-200/60">
                    <div class="w-12 h-12 rounded-xl bg-indigo-100 text-indigo-600 flex items-center justify-center text-xl font-bold mb-4">
                        <i class="fa-solid fa-sliders"></i>
                    </div>
                    <h3 class="text-lg font-bold text-slate-900">Custom Filters</h3>
                    <p class="text-slate-600 text-sm mt-2">Tailor your search preferences to only get alerts for what matters to you.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- App Support / Contact Section -->
    <section id="support" class="py-20 bg-slate-50">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-white rounded-3xl p-8 md:p-12 shadow-sm border border-slate-200/80">
                <div class="max-w-xl mx-auto text-center mb-10">
                    <h2 class="text-3xl font-bold text-slate-900">App Support</h2>
                    <p class="text-slate-600 mt-2 text-sm font-medium">Have questions or need help with Bubble Hound? Send us a message and our team will respond shortly.</p>
                    <p class="text-xs font-semibold text-blue-600 mt-2">Direct Email: support@bubblehound.vip</p>
                </div>

                <form id="contact-form" onsubmit="handleSupportSubmit(event)" class="space-y-4 max-w-lg mx-auto">
                    <div>
                        <label class="block text-xs font-bold uppercase text-slate-500 mb-1">Your Name</label>
                        <input type="text" required class="w-full px-4 py-3 rounded-xl bg-slate-50 border border-slate-200 focus:outline-none focus:ring-2 focus:ring-blue-500 text-sm" placeholder="John Doe">
                    </div>
                    <div>
                        <label class="block text-xs font-bold uppercase text-slate-500 mb-1">Email Address / Phone</label>
                        <input type="text" required class="w-full px-4 py-3 rounded-xl bg-slate-50 border border-slate-200 focus:outline-none focus:ring-2 focus:ring-blue-500 text-sm" placeholder="you@example.com">
                    </div>
                    <div>
                        <label class="block text-xs font-bold uppercase text-slate-500 mb-1">How can we help?</label>
                        <textarea rows="4" required class="w-full px-4 py-3 rounded-xl bg-slate-50 border border-slate-200 focus:outline-none focus:ring-2 focus:ring-blue-500 text-sm" placeholder="Describe your question or issue..."></textarea>
                    </div>
                    <button type="submit" class="w-full py-3.5 bg-blue-600 hover:bg-blue-700 text-white font-bold rounded-xl shadow-md transition-all text-sm">
                        Send Message
                    </button>
                    <div id="form-response" class="hidden text-center text-xs font-bold text-emerald-600 mt-2">
                        Thank you! Your message has been sent to our support team.
                    </div>
                </form>
            </div>
        </div>
    </section>

    <!-- Privacy Policy Section -->
    <section id="privacy" class="py-20 bg-white border-t border-slate-200/80">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="prose prose-slate max-w-none">
                <h2 class="text-3xl font-bold text-slate-900 mb-6">Privacy Policy</h2>
                <p class="text-sm text-slate-500 mb-6">Last updated: October 2026</p>
                
                <div class="space-y-6 text-sm text-slate-600 leading-relaxed">
                    <p>At <strong>Bubble Hound</strong>, we take your privacy seriously. This policy outlines how we handle data when you use our mobile application and website.</p>
                    
                    <h3 class="text-base font-bold text-slate-800">1. Information We Collect</h3>
                    <p>We collect phone numbers and email addresses strictly for authentication purposes (such as sending OTP verification codes). We do not sell or share your personal contact details with third-party marketers.</p>

                    <h3 class="text-base font-bold text-slate-800">2. How Data is Used</h3>
                    <p>Data collected is used exclusively to maintain your account access, deliver real-time notifications configured by you, and ensure app security.</p>

                    <h3 class="text-base font-bold text-slate-800">3. Contact Us</h3>
                    <p>If you have any questions regarding your account data or wish to request data deletion, please contact us at <strong>support@bubblehound.vip</strong>.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-900 text-slate-400 py-12 border-t border-slate-800">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col sm:flex-row items-center justify-between gap-6">
            <div class="flex items-center space-x-3">
                <div class="w-8 h-8 rounded-lg bg-blue-600 flex items-center justify-center text-white font-bold">
                    <i class="fa-solid fa-dog text-xs"></i>
                </div>
                <span class="text-white font-bold text-base">Bubble Hound</span>
            </div>
            
            <p class="text-xs text-slate-500">© 2026 Bubble Hound. All rights reserved.</p>
        </div>
    </footer>

    <script>
        function handleSupportSubmit(e) {
            e.preventDefault();
            const responseDiv = document.getElementById('form-response');
            responseDiv.classList.remove('hidden');
            e.target.reset();
            setTimeout(() => {
                responseDiv.classList.add('hidden');
            }, 5000);
        }
    </script>
</body>
</html>
