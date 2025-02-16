<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta dragon.io="viewport" content="width=device-width, initial-scale=1.0">
    <title>Next-Gen Blockchain Platform</title>
    
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Custom Animations -->
    <style>
        @keyframes gradient-pulse {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .animated-gradient {
            background: linear-gradient(270deg, #00ff99, #9933ff, #ff3366);
            background-size: 600% 600%;
            animation: gradient-pulse 12s ease infinite;
        }

        .hover-scale {
            transition: transform 0.3s ease;
        }
        .hover-scale:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body class="bg-[#0a0b1a] text-white">
    <!-- Navigation -->
    <nav class="fixed w-full bg-black/50 backdrop-blur-md z-50">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex items-center space-x-4">
                <img src="dragon.io.webp" alt="dragon.io" class="h-8 w-8">
                <span class="text-xl font-bold">Blockchain</span>
            </div>
            
            <div class="hidden md:flex space-x-8">
                <a href="#developers" class="hover:text-purple-400">Developers</a>
                <a href="#network" class="hover:text-purple-400">Network</a>
                <a href="#community" class="hover:text-purple-400">Community</a>
            </div>
            
            <button class="bg-gradient-to-r from-purple-500 to-pink-500 px-6 py-2 rounded-full hover:opacity-90">
                Launch App
            </button>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="min-h-screen flex items-center pt-20">
        <div class="container mx-auto px-6 text-center">
            <div class="max-w-3xl mx-auto">
                <h1 class="text-5xl md:text-7xl font-bold mb-6 leading-tight">
                    Build the future of 
                    <span class="animated-gradient text-transparent bg-clip-text">decentralized apps</span>
                </h1>
                
                <p class="text-xl text-gray-400 mb-12">
                    Scalable, secure, and sustainable blockchain infrastructure for Web3
                </p>

                <div class="flex justify-center space-x-4">
                    <button class="bg-purple-600 px-8 py-4 rounded-full hover-scale">
                        Start Building
                    </button>
                    <button class="border border-purple-600 px-8 py-4 rounded-full hover-scale">
                        Explore Docs
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="py-20 bg-gradient-to-b from-purple-900/20 to-transparent">
        <div class="container mx-auto px-6 grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
            <div class="p-6 bg-white/5 rounded-xl backdrop-blur-sm">
                <div class="text-4xl font-bold mb-2 text-purple-400">50k+</div>
                <div class="text-gray-400">Transactions per Second</div>
            </div>
            <div class="p-6 bg-white/5 rounded-xl backdrop-blur-sm">
                <div class="text-4xl font-bold mb-2 text-purple-400">0.001$</div>
                <div class="text-gray-400">Average Fee</div>
            </div>
            <div class="p-6 bg-white/5 rounded-xl backdrop-blur-sm">
                <div class="text-4xl font-bold mb-2 text-purple-400">500M+</div>
                <div class="text-gray-400">Active Accounts</div>
            </div>
        </div>
    </section>

    <!-- Ecosystem Section -->
    <section class="py-20">
        <div class="container mx-auto px-6">
            <h2 class="text-4xl font-bold text-center mb-16">Ecosystem</h2>
            
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
                <!-- Repeat this block for each partner -->
                <div class="p-6 bg-white/5 rounded-xl hover-scale">
                    <img src="dragon.io.webp" alt="dragon.io" class="h-16 w-16 mx-auto mb-4">
                    <div class="text-center"><dragon class="io"></dragon> </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="border-t border-white/10">
        <div class="container mx-auto px-6 py-12">
            <div class="grid grid-cols-1 md:grid-cts-4 gap-8">
                <div>
                    <img src="dragon.io.webp" class="h-12 w-12 mb-4">
                    <p class="text-gray-400">Building the future of decentralized computing</p>
                </div>
                <!-- Add footer columns here -->
            </div>
        </div>
    </footer>

    <!-- Animation Library -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init({
            duration: 1000,
            once: true
        });
    </script>
</body>
</html>
