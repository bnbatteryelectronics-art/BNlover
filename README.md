
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BN BATTERY - Durga Puja Special Scratch & Win</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts: Poppins & Cinzel -->
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600;800&family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <!-- Canvas Confetti Library for reveal effects -->
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        festiveRed: '#8B0000',
                        festiveDarkRed: '#5A0000',
                        festiveGold: '#FFD700',
                        festiveAmber: '#FFBF00',
                        festiveNavy: '#0F172A',
                    },
                    fontFamily: {
                        cinzel: ['Cinzel', 'serif'],
                        poppins: ['Poppins', 'sans-serif'],
                    }
                }
            }
        }
    </script>

    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background: radial-gradient(circle at top, #3A0007 0%, #1A0003 50%, #0A0002 100%);
            color: #F8FAFC;
            min-height: 100vh;
        }

        .gold-border {
            border: 2px solid #FFD700;
            box-shadow: 0 0 15px rgba(255, 215, 0, 0.3);
        }

        .gold-text-glow {
            text-shadow: 0 0 12px rgba(255, 215, 0, 0.6);
        }

        .glass-card {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 215, 0, 0.2);
        }

        .glass-card-dark {
            background: rgba(15, 23, 42, 0.85);
            backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 215, 0, 0.3);
        }

        /* Diya Glow Effect */
        .diya-glow {
            filter: drop-shadow(0 -5px 10px rgba(255, 191, 0, 0.8));
            animation: pulseGlow 2s infinite alternate;
        }

        @keyframes pulseGlow {
            0% { filter: drop-shadow(0 -4px 8px rgba(255, 191, 0, 0.7)); transform: scale(1); }
            100% { filter: drop-shadow(0 -8px 16px rgba(255, 215, 0, 1)); transform: scale(1.03); }
        }

        /* Phone mockup styling */
        .phone-mockup {
            border: 10px solid #1e293b;
            border-radius: 36px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.8), 0 0 20px rgba(255, 215, 0, 0.2);
        }

        /* Canvas cursor style */
        #scratchCanvas {
            touch-action: none;
            cursor: pointer;
        }
    </style>
</head>
<body class="flex flex-col min-h-screen relative overflow-x-hidden selection:bg-festiveGold selection:text-black">

    <!-- Background Festival Decor -->
    <div class="fixed inset-0 pointer-events-none opacity-15 bg-[radial-gradient(#FFD700_1px,transparent_1px)] [background-size:24px_24px]"></div>

    <!-- MAIN CONTAINER -->
    <div class="container mx-auto px-4 py-6 max-w-4xl flex-grow relative z-10">

        <!-- HEADER / BRANDING -->
        <header class="text-center mb-8">
            <div class="flex items-center justify-center gap-3 mb-2">
                <i class="fa-solid fa-om text-3xl text-festiveGold diya-glow"></i>
                <h1 class="text-4xl sm:text-5xl font-extrabold font-cinzel text-transparent bg-clip-text bg-gradient-to-r from-yellow-300 via-amber-400 to-yellow-500 gold-text-glow">
                    BN BATTERY
                </h1>
                <i class="fa-solid fa-om text-3xl text-festiveGold diya-glow"></i>
            </div>
            
            <p class="text-amber-200 text-sm sm:text-base font-medium tracking-wide uppercase">
                <span class="inline-block border-b-2 border-festiveGold pb-1">Durga Puja Special Festival Offer</span>
            </p>

            <!-- Brand Badges -->
            <div class="flex flex-wrap justify-center items-center gap-2 sm:gap-4 mt-4 text-xs font-semibold">
                <span class="px-3 py-1 rounded-full bg-red-950/80 border border-amber-500/40 text-amber-300"><i class="fa-solid fa-car-battery text-amber-400 mr-1"></i> EXIDE</span>
                <span class="px-3 py-1 rounded-full bg-red-950/80 border border-amber-500/40 text-amber-300"><i class="fa-solid fa-bolt text-amber-400 mr-1"></i> AMARON</span>
                <span class="px-3 py-1 rounded-full bg-red-950/80 border border-amber-500/40 text-amber-300"><i class="fa-solid fa-plug text-amber-400 mr-1"></i> LUMINOUS</span>
                <span class="px-3 py-1 rounded-full bg-red-950/80 border border-amber-500/40 text-amber-300"><i class="fa-solid fa-shield-halved text-amber-400 mr-1"></i> LIVGUARD</span>
            </div>
        </header>

        <!-- CUSTOMER OFFER & SCRATCH CARD SECTION -->
        <main class="mb-12">
            <div class="glass-card rounded-3xl p-6 sm:p-8 gold-border text-center shadow-2xl relative overflow-hidden">
                <div class="absolute -top-12 -right-12 w-32 h-32 bg-amber-500/10 rounded-full blur-2xl"></div>
                
                <h2 class="text-2xl sm:text-3xl font-bold font-cinzel text-amber-300 mb-2">
                    Scratch & Win Festival Discount
                </h2>
                <p class="text-slate-300 text-xs sm:text-sm mb-6">
                    Enter the Master Code provided on your purchase memo to unlock your guaranteed instant cash discount card!
                </p>

                <!-- CODE SEARCH FORM -->
                <div class="max-w-md mx-auto mb-8">
                    <div class="flex flex-col sm:flex-row gap-3">
                        <div class="relative flex-grow">
                            <i class="fa-solid fa-key absolute left-4 top-1/2 -translate-y-1/2 text-amber-400"></i>
                            <input type="text" id="masterCodeInput" placeholder="Enter Master Code (e.g. BN0001)" 
                                class="w-full pl-11 pr-4 py-3 bg-slate-900/90 text-white rounded-xl border border-amber-500/40 focus:outline-none focus:border-amber-400 focus:ring-2 focus:ring-amber-400/30 font-mono tracking-wider placeholder-slate-500 text-center sm:text-left text-lg uppercase transition-all" />
                        </div>
                        <button onclick="searchMasterCode()" class="px-6 py-3 bg-gradient-to-r from-amber-500 to-yellow-600 hover:from-amber-400 hover:to-yellow-500 text-slate-950 font-bold rounded-xl shadow-lg hover:shadow-amber-500/20 active:scale-95 transition-all flex items-center justify-center gap-2 text-base">
                            <i class="fa-solid fa-magnifying-glass"></i>
                            <span>Search</span>
                        </button>
                    </div>
                    <p id="searchMessage" class="text-xs mt-3 hidden font-medium"></p>
                </div>

                <!-- PHONE MOCKUP / SCRATCH CARD CONTAINER -->
                <div id="scratchContainer" class="max-w-xs mx-auto phone-mockup bg-slate-900 p-4 hidden transition-all duration-500">
                    <!-- Phone Notch -->
                    <div class="w-24 h-4 bg-slate-800 mx-auto rounded-b-xl mb-4 flex items-center justify-center">
                        <div class="w-8 h-1 bg-slate-700 rounded-full"></div>
                    </div>

                    <div class="text-center mb-3">
                        <span id="cardCodeBadge" class="text-xs font-mono px-2 py-1 bg-amber-500/20 text-amber-300 rounded border border-amber-500/30">
                            CODE: BN0001
                        </span>
                    </div>

                    <!-- SCRATCH CARD FRAME -->
                    <div class="relative w-full aspect-[4/5] rounded-2xl overflow-hidden bg-gradient-to-br from-red-900 via-red-950 to-slate-950 border-2 border-amber-400/50 flex flex-col items-center justify-center p-4 shadow-inner">
                        
                        <!-- REVEALED PRIZE CONTENT (Underneath Canvas) -->
                        <div class="text-center flex flex-col items-center justify-center h-full w-full">
                            <div class="w-16 h-16 rounded-full bg-amber-500/20 border border-amber-400 flex items-center justify-center mb-3 text-amber-400 text-2xl animate-bounce">
                                <i class="fa-solid fa-gift"></i>
                            </div>
                            <h3 class="text-amber-200 text-xs uppercase tracking-widest font-bold mb-1">Durga Puja Special</h3>
                            <div id="revealedAmount" class="text-4xl font-extrabold font-cinzel text-transparent bg-clip-text bg-gradient-to-r from-yellow-300 via-amber-300 to-yellow-500 my-1">
                                ₹0 OFF
                            </div>
                            <p class="text-slate-300 text-xs font-medium mt-2">Congratulations!</p>
                            <p class="text-[10px] text-slate-400 mt-1">Show this screen at BN BATTERY store counter to claim discount.</p>
                        </div>

                        <!-- HTML5 SCRATCH CANVAS OVERLAY -->
                        <canvas id="scratchCanvas" class="absolute inset-0 w-full h-full z-10 transition-opacity duration-700"></canvas>
                    </div>

                    <p class="text-xs text-amber-300/80 mt-3 font-medium flex items-center justify-center gap-1">
                        <i class="fa-solid fa-hand-pointer animate-pulse"></i>
                        <span>Scratch the silver layer above</span>
                    </p>
                </div>
            </div>
        </main>

        <!-- BRANCH LOCATIONS & CONTACT SECTION -->
        <section class="mb-12">
            <h3 class="text-xl font-bold font-cinzel text-amber-300 text-center mb-6 flex items-center justify-center gap-2">
                <i class="fa-solid fa-store text-amber-400"></i>
                <span>BN BATTERY Stores & Contact</span>
            </h3>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <!-- Branch 1 -->
                <div class="glass-card rounded-2xl p-6 border border-amber-500/30 hover:border-amber-400/60 transition-all">
                    <div class="flex items-start gap-4">
                        <div class="w-12 h-12 rounded-xl bg-amber-500/20 border border-amber-400/40 flex items-center justify-center text-amber-400 text-xl shrink-0">
                            <i class="fa-solid fa-location-dot"></i>
                        </div>
                        <div>
                            <h4 class="text-lg font-bold text-amber-200">Berachampa Branch</h4>
                            <p class="text-slate-300 text-sm mt-1">Taki Road, Berachampa, North 24 Parganas</p>
                            <div class="mt-4 flex flex-wrap gap-2">
                                <a href="tel:8918018413" class="inline-flex items-center gap-2 px-3 py-1.5 rounded-lg bg-amber-500/20 border border-amber-500/30 text-amber-300 text-xs font-semibold hover:bg-amber-500/30 transition-all">
                                    <i class="fa-solid fa-phone"></i> 8918018413
                                </a>
                                <a href="tel:9851963857" class="inline-flex items-center gap-2 px-3 py-1.5 rounded-lg bg-amber-500/20 border border-amber-500/30 text-amber-300 text-xs font-semibold hover:bg-amber-500/30 transition-all">
                                    <i class="fa-solid fa-phone"></i> 9851963857
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Branch 2 -->
                <div class="glass-card rounded-2xl p-6 border border-amber-500/30 hover:border-amber-400/60 transition-all">
                    <div class="flex items-start gap-4">
                        <div class="w-12 h-12 rounded-xl bg-amber-500/20 border border-amber-400/40 flex items-center justify-center text-amber-400 text-xl shrink-0">
                            <i class="fa-solid fa-location-dot"></i>
                        </div>
                        <div>
                            <h4 class="text-lg font-bold text-amber-200">Baduria Branch</h4>
                            <p class="text-slate-300 text-sm mt-1">Lorry Stand, Baduria, North 24 Parganas</p>
                            <div class="mt-4 flex flex-wrap gap-2">
                                <a href="tel:6295574350" class="inline-flex items-center gap-2 px-3 py-1.5 rounded-lg bg-amber-500/20 border border-amber-500/30 text-amber-300 text-xs font-semibold hover:bg-amber-500/30 transition-all">
                                    <i class="fa-solid fa-phone"></i> 6295574350
                                </a>
                                <a href="tel:8918018413" class="inline-flex items-center gap-2 px-3 py-1.5 rounded-lg bg-amber-500/20 border border-amber-500/30 text-amber-300 text-xs font-semibold hover:bg-amber-500/30 transition-all">
                                    <i class="fa-solid fa-phone"></i> 8918018413
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </div>

    <!-- FOOTER & SECRET ADMIN ACCESS -->
    <footer class="border-t border-amber-500/20 py-6 bg-slate-950/80 text-center relative z-10">
        <div class="container mx-auto px-4">
            <p class="text-slate-400 text-xs mb-3">
                © 2026 BN BATTERY. All Rights Reserved. Durga Puja Offer Scheme.
            </p>
            
            <!-- Discrete Secret Admin Login Button -->
            <button onclick="openAdminModal()" class="text-xs text-amber-400/70 hover:text-amber-300 transition-all underline decoration-amber-500/30 underline-offset-4 flex items-center justify-center gap-1.5 mx-auto">
                <i class="fa-solid fa-user-shield"></i>
                <span>Shop Owner Admin Login</span>
            </button>
        </div>
    </footer>

    <!-- SECRET ADMIN MODAL -->
    <div id="adminModal" class="fixed inset-0 bg-slate-950/90 backdrop-blur-md z-50 flex items-center justify-center p-4 hidden">
        <div class="glass-card-dark rounded-3xl p-6 sm:p-8 max-w-lg w-full gold-border shadow-2xl relative max-h-[90vh] overflow-y-auto">
            <!-- Close Modal Button -->
            <button onclick="closeAdminModal()" class="absolute top-4 right-4 text-slate-400 hover:text-white text-xl p-2">
                <i class="fa-solid fa-xmark"></i>
            </button>

            <!-- LOGIN VIEW -->
            <div id="adminLoginSection">
                <div class="text-center mb-6">
                    <div class="w-16 h-16 bg-amber-500/20 border border-amber-400 rounded-full flex items-center justify-center mx-auto text-amber-400 text-2xl mb-3">
                        <i class="fa-solid fa-lock"></i>
                    </div>
                    <h3 class="text-2xl font-bold font-cinzel text-amber-300">Admin Authentication</h3>
                    <p class="text-slate-400 text-xs mt-1">Authorized Shop Owner Access Only</p>
                </div>

                <div class="space-y-4 max-w-xs mx-auto">
                    <div>
                        <label class="block text-slate-300 text-xs font-medium mb-1 text-left">Password</label>
                        <input type="password" id="adminPasswordInput" placeholder="Enter Security Password" 
                            class="w-full px-4 py-2.5 bg-slate-900 border border-amber-500/30 rounded-xl text-white text-sm focus:outline-none focus:border-amber-400" />
                    </div>
                    <p id="adminAuthMessage" class="text-xs text-red-400 hidden text-center"></p>
                    <button onclick="authenticateAdmin()" class="w-full py-3 bg-gradient-to-r from-amber-500 to-yellow-600 hover:from-amber-400 hover:to-yellow-500 text-slate-950 font-bold rounded-xl text-sm shadow-lg transition-all">
                        Login to Admin Portal
                    </button>
                </div>
            </div>

            <!-- LOGGED-IN ADMIN DASHBOARD VIEW -->
            <div id="adminDashboardSection" class="hidden">
                <div class="flex justify-between items-center pb-4 mb-6 border-b border-slate-700">
                    <div>
                        <h3 class="text-xl font-bold font-cinzel text-amber-300">Shop Admin Panel</h3>
                        <p class="text-slate-400 text-xs">Manage Master Scratch Codes</p>
                    </div>
                    <button onclick="logoutAdmin()" class="text-xs px-3 py-1.5 bg-red-950 border border-red-500/50 text-red-300 rounded-lg hover:bg-red-900">
                        Logout
                    </button>
                </div>

                <!-- GENERATE NEW CODE FORM -->
                <div class="bg-slate-900/80 p-4 rounded-2xl border border-amber-500/20 mb-6 space-y-4">
                    <h4 class="text-sm font-bold text-amber-200 uppercase tracking-wider">Generate New Master Code</h4>
                    
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                        <div>
                            <label class="block text-xs text-slate-400 mb-1">Select Discount Amount</label>
                            <select id="discountSelect" class="w-full px-3 py-2 bg-slate-800 border border-slate-700 rounded-xl text-amber-300 text-sm focus:outline-none focus:border-amber-400">
                                <option value="100">₹100 OFF</option>
                                <option value="150">₹150 OFF</option>
                                <option value="200">₹200 OFF</option>
                                <option value="250">₹250 OFF</option>
                                <option value="300" selected>₹300 OFF (Max)</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-xs text-slate-400 mb-1">Custom Code Prefix</label>
                            <input type="text" id="codePrefixInput" value="BN" class="w-full px-3 py-2 bg-slate-800 border border-slate-700 rounded-xl text-white text-sm font-mono uppercase focus:outline-none focus:border-amber-400" />
                        </div>
                    </div>

                    <button onclick="generateNewMasterCode()" class="w-full py-2.5 bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold rounded-xl text-sm transition-all flex items-center justify-center gap-2">
                        <i class="fa-solid fa-plus-circle"></i>
                        <span>Generate & Save Code</span>
                    </button>
                </div>

                <!-- ACTIVE CODES TABLE -->
                <div>
                    <h4 class="text-sm font-bold text-amber-200 uppercase tracking-wider mb-3">Active Master Codes List</h4>
                    <div class="overflow-x-auto">
                        <table class="w-full text-left text-xs border-collapse">
                            <thead>
                                <tr class="bg-slate-800 text-slate-300 border-b border-slate-700">
                                    <th class="p-2.5">Master Code</th>
                                    <th class="p-2.5">Discount Amount</th>
                                    <th class="p-2.5">Status</
