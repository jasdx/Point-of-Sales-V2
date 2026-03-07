<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JazzPOS - Retail Pro V2.0 README</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            line-height: 1.6;
        }

        .hero-gradient {
            background: linear-gradient(135deg, #7c3aed 0%, #4f46e5 100%);
        }

        .glass-card {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 24px;
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.05);
        }

        .feature-icon {
            background: #f1f5f9;
            width: 48px;
            height: 48px;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 12px;
            font-size: 24px;
            margin-bottom: 1rem;
        }

        .screenshot-container {
            border-radius: 20px;
            overflow: hidden;
            border: 4px solid white;
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .screenshot-container:hover {
            transform: translateY(-5px);
        }

        code {
            background: #1e293b;
            color: #f8fafc;
            padding: 0.2rem 0.5rem;
            border-radius: 6px;
            font-size: 0.9em;
        }

        .pre-block {
            background: #1e293b;
            color: #e2e8f0;
            padding: 1.5rem;
            border-radius: 16px;
            font-family: 'Courier New', Courier, monospace;
            overflow-x: auto;
            margin: 1rem 0;
        }
    </style>
</head>
<body class="p-4 md:p-8 lg:p-12">

    <div class="max-w-6xl mx-auto">
        
        <!-- Header Section -->
        <header class="hero-gradient text-white p-12 rounded-[40px] mb-12 shadow-2xl relative overflow-hidden">
            <div class="relative z-10">
                <h1 class="text-5xl md:text-7xl font-bold mb-6 italic tracking-tight">⚡ JazzPOS</h1>
                <p class="text-xl md:text-2xl font-light max-w-2xl opacity-90 leading-relaxed">
                    Retail Pro V2.0: A modern, high-performance Point of Sale system designed for retail excellence.
                </p>
            </div>
            <!-- Decorative circle -->
            <div class="absolute -top-20 -right-20 w-64 h-64 bg-white opacity-10 rounded-full"></div>
        </header>

        <!-- Main Dashboard Image -->
        <section class="mb-16">
            <div class="screenshot-container">
                <img src="Dashboard.png" alt="JazzPOS Dashboard" class="w-full h-auto" onerror="this.src='https://via.placeholder.com/1200x600?text=Dashboard+Screenshot+Missing'">
            </div>
        </section>

        <!-- Intro Text -->
        <section class="mb-16 text-center max-w-3xl mx-auto">
            <h2 class="text-3xl font-bold mb-6 text-slate-800">Intuitive. Clean. Powerful.</h2>
            <p class="text-xl text-slate-600">
                Built with a focus on intuitive user experience and clean aesthetics, JazzPOS provides business owners with real-time insights, effortless inventory management, and a streamlined sales process.
            </p>
        </section>

        <!-- Features Grid -->
        <div class="grid md:grid-cols-2 gap-8 mb-20">
            <!-- Dashboard Feature -->
            <div class="glass-card p-8">
                <div class="feature-icon">📊</div>
                <h3 class="text-2xl font-bold mb-4">Comprehensive Dashboard</h3>
                <ul class="space-y-3 text-lg text-slate-600">
                    <li><strong>Real-time Metrics:</strong> Track Revenue, Sales, and Stock.</li>
                    <li><strong>Low Stock Alerts:</strong> Visual indicators for replenishment.</li>
                    <li><strong>History:</strong> Monitor recent sales activity instantly.</li>
                    <li><strong>Top Selling:</strong> Quick view of popular items.</li>
                </ul>
            </div>

            <!-- Inventory Feature -->
            <div class="glass-card p-8">
                <div class="feature-icon">📦</div>
                <h3 class="text-2xl font-bold mb-4">Robust Inventory</h3>
                <ul class="space-y-3 text-lg text-slate-600">
                    <li><strong>Tracking:</strong> Detailed views including SKU and Category.</li>
                    <li><strong>Visual Status:</strong> Color-coded stock levels (Red alerts).</li>
                    <li><strong>Full CRUD:</strong> Add, edit, or delete products with ease.</li>
                </ul>
            </div>

            <!-- Settings Feature -->
            <div class="glass-card p-8">
                <div class="feature-icon">⚙️</div>
                <h3 class="text-2xl font-bold mb-4">Personalized Settings</h3>
                <ul class="space-y-3 text-lg text-slate-600">
                    <li><strong>Store Identity:</strong> Custom business name and currency.</li>
                    <li><strong>Taxation:</strong> Global tax rates for accurate billing.</li>
                    <li><strong>Maintenance:</strong> Factory resets for data management.</li>
                    <li><strong>Theme:</strong> Native dark mode support.</li>
                </ul>
            </div>

            <!-- Design Feature -->
            <div class="glass-card p-8">
                <div class="feature-icon">🎨</div>
                <h3 class="text-2xl font-bold mb-4">Design Philosophy</h3>
                <p class="text-lg text-slate-600">
                    Utilizing a "Glassmorphism" language with soft UI elements, rounded corners, and high-contrast accents (vibrant purple) for premium accessibility and feel.
                </p>
            </div>
        </div>

        <!-- Screenshots Showcase -->
        <section class="mb-20">
            <h2 class="text-4xl font-bold mb-10 flex items-center gap-4">
                <span class="text-3xl">📸</span> Interface Gallery
            </h2>
            <div class="grid md:grid-cols-2 gap-12">
                   <div>
                    <h4 class="text-xl font-semibold mb-4 text-center">Dashboard</h4>
                    <div class="screenshot-container">
                        <img src="Dashboard.png" alt="dash" class="w-full" onerror="this.src='https://via.placeholder.com/600x400?text=Inventory+Missing'">
                    </div>
                </div>
                <div>
                    <h4 class="text-xl font-semibold mb-4 text-center">Product Management</h4>
                    <div class="screenshot-container">
                        <img src="Product-mgmt.png" alt="Inventory Management" class="w-full" onerror="this.src='https://via.placeholder.com/600x400?text=Inventory+Missing'">
                    </div>
                </div>
                <div>
                    <h4 class="text-xl font-semibold mb-4 text-center">System Settings</h4>
                    <div class="screenshot-container">
                        <img src="Settings.png" alt="Settings" class="w-full" onerror="this.src='https://via.placeholder.com/600x400?text=Settings+Missing'">
                    </div>
                </div>
            </div>
        </section>

        <!-- Getting Started -->
        <section class="glass-card p-10 mb-20 bg-slate-900 text-white">
            <h2 class="text-3xl font-bold mb-8">🚀 Getting Started</h2>
            
            <div class="mb-8">
                <h4 class="text-purple-400 font-bold mb-2 uppercase tracking-widest text-sm">Prerequisites</h4>
                <p class="text-lg opacity-80">Any modern web browser (Chrome, Firefox, Safari, Edge)</p>
            </div>

            <div>
                <h4 class="text-purple-400 font-bold mb-2 uppercase tracking-widest text-sm">Installation</h4>
                <div class="pre-block">
                    git clone https://github.com/yourusername/jazzpos.git
                </div>
                <p class="text-lg opacity-80 mt-4">Simply open <code>index.html</code> in your browser to launch the application.</p>
            </div>
        </section>

        <!-- Tech Stack -->
        <section class="mb-20">
            <h2 class="text-3xl font-bold mb-8 text-center">🛠️ Built With</h2>
            <div class="flex flex-wrap justify-center gap-4">
                <span class="px-6 py-2 bg-white rounded-full shadow-sm border border-slate-200 font-medium">HTML5</span>
                <span class="px-6 py-2 bg-white rounded-full shadow-sm border border-slate-200 font-medium">Tailwind CSS</span>
                <span class="px-6 py-2 bg-white rounded-full shadow-sm border border-slate-200 font-medium">Vanilla JS</span>
                <span class="px-6 py-2 bg-white rounded-full shadow-sm border border-slate-200 font-medium">Lucide Icons</span>
            </div>
        </section>

        <!-- Footer -->
        <footer class="text-center py-12 border-t border-slate-200">
            <p class="text-2xl font-medium text-slate-800">Created with ❤️ by Jasmine Karki</p>
            <p class="text-slate-400 mt-2">© 2026 JazzPOS Retail Pro</p>
        </footer>

    </div>

</body>
</html>
