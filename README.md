<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ClickMaster Pro | Advanced Clicking Engine</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Segoe+UI:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #0f0f13;
            color: #e2e2e2;
        }
        .luxury-gradient {
            background: linear-gradient(135deg, #bd93f9 0%, #ff79c6 100%);
        }
        .luxury-card {
            background: rgba(40, 42, 54, 0.6);
            border: 1px solid rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            transition: transform 0.3s ease, border-color 0.3s ease;
        }
        .luxury-card:hover {
            transform: translateY(-5px);
            border-color: rgba(189, 147, 249, 0.3);
        }
        .glow-text {
            text-shadow: 0 0 15px rgba(189, 147, 249, 0.5);
        }
    </style>
</head>
<body class="selection:bg-purple-500 selection:text-white">

    <!-- Hero Section -->
    <header class="relative py-24 px-6 overflow-hidden">
        <div class="absolute top-0 left-1/2 -translate-x-1/2 w-full h-full opacity-10 pointer-events-none">
            <div class="absolute top-0 left-1/2 -translate-x-1/2 w-[800px] h-[800px] bg-purple-600 rounded-full blur-[120px]"></div>
        </div>
        
        <div class="max-w-5xl mx-auto text-center relative z-10">
            <h1 class="text-5xl md:text-7xl font-bold mb-4 glow-text tracking-tight">
                CLICKMASTER <span class="text-transparent bg-clip-text luxury-gradient">PRO</span>
            </h1>
            <p class="text-xl md:text-2xl text-gray-400 font-medium mb-8">
                Advanced Automation & High-Performance Clicking Engine
            </p>
            <p class="max-w-2xl mx-auto text-gray-500 leading-relaxed">
                Java tabanlı mimarisi ve optimize edilmiş JRE yapısı ile sistem kaynaklarını minimum düzeyde kullanarak maksimum verimlilik sağlar. Düşük gecikme süreli ve profesyonel otomasyon çözümü.
            </p>
        </div>
    </header>

    <!-- Features Section -->
    <section class="py-20 px-6 bg-[#14141e]/50">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-3xl font-bold mb-12 text-center">TEMEL ÖZELLİKLER</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Feature 1 -->
                <div class="luxury-card p-8 rounded-2xl">
                    <div class="w-12 h-12 luxury-gradient rounded-lg mb-6 flex items-center justify-center text-white font-bold">01</div>
                    <h3 class="text-xl font-bold mb-4 text-purple-400">Tıklama Motoru</h3>
                    <ul class="text-sm text-gray-400 space-y-2">
                        <li>• Sol ve Sağ Bağımsız Motor</li>
                        <li>• 1 - 20 CPS Hassas Ayar</li>
                        <li>• Hold & Toggle Modları</li>
                    </ul>
                </div>

                <!-- Feature 2 -->
                <div class="luxury-card p-8 rounded-2xl">
                    <div class="w-12 h-12 luxury-gradient rounded-lg mb-6 flex items-center justify-center text-white font-bold">02</div>
                    <h3 class="text-xl font-bold mb-4 text-green-400">Legit & Güvenlik</h3>
                    <ul class="text-sm text-gray-400 space-y-2">
                        <li>• Humanized Timing</li>
                        <li>• Gaussian Variation</li>
                        <li>• HWID Doğrulama Sistemi</li>
                    </ul>
                </div>

                <!-- Feature 3 -->
                <div class="luxury-card p-8 rounded-2xl">
                    <div class="w-12 h-12 luxury-gradient rounded-lg mb-6 flex items-center justify-center text-white font-bold">03</div>
                    <h3 class="text-xl font-bold mb-4 text-blue-400">Rod Macro</h3>
                    <ul class="text-sm text-gray-400 space-y-2">
                        <li>• Instant Swap Sistemi</li>
                        <li>• Custom Sequence</li>
                        <li>• Old School Speed</li>
                    </ul>
                </div>

                <!-- Feature 4 -->
                <div class="luxury-card p-8 rounded-2xl">
                    <div class="w-12 h-12 luxury-gradient rounded-lg mb-6 flex items-center justify-center text-white font-bold">04</div>
                    <h3 class="text-xl font-bold mb-4 text-yellow-400">Görsel Panel</h3>
                    <ul class="text-sm text-gray-400 space-y-2">
                        <li>• Aircraft Radar Sistemi</li>
                        <li>• Performance Monitor</li>
                        <li>• Luxury UI Tasarımı</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Technical Section -->
    <section class="py-20 px-6">
        <div class="max-w-4xl mx-auto luxury-card p-10 rounded-3xl border-purple-500/20">
            <h2 class="text-2xl font-bold mb-8 flex items-center">
                <span class="w-2 h-8 luxury-gradient rounded-full mr-4"></span>
                TEKNİK DETAYLAR
            </h2>
            <div class="grid grid-cols-1 sm:grid-cols-3 gap-8 text-center">
                <div>
                    <p class="text-gray-500 text-xs uppercase tracking-widest mb-2">Mimari</p>
                    <p class="text-lg font-bold">JavaFX 21</p>
                </div>
                <div>
                    <p class="text-gray-500 text-xs uppercase tracking-widest mb-2">Kütüphane</p>
                    <p class="text-lg font-bold">JNativeHook</p>
                </div>
                <div>
                    <p class="text-gray-500 text-xs uppercase tracking-widest mb-2">Grafik</p>
                    <p class="text-lg font-bold">Prism D3D</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Installation -->
    <section class="py-20 px-6 bg-black/20">
        <div class="max-w-4xl mx-auto">
            <h2 class="text-3xl font-bold mb-12 text-center">KURULUM VE KULLANIM</h2>
            <div class="space-y-4">
                <div class="flex items-start p-6 bg-[#1a1a24] rounded-xl border border-white/5">
                    <span class="bg-purple-500/10 text-purple-400 w-8 h-8 rounded-full flex items-center justify-center mr-4 shrink-0 font-bold">1</span>
                    <p class="text-gray-300">ClickMaster Pro yükleyici dosyasını indirin ve kurulumu tamamlayın.</p>
                </div>
                <div class="flex items-start p-6 bg-[#1a1a24] rounded-xl border border-white/5">
                    <span class="bg-purple-500/10 text-purple-400 w-8 h-8 rounded-full flex items-center justify-center mr-4 shrink-0 font-bold">2</span>
                    <p class="text-gray-300">Uygulamayı yönetici olarak çalıştırın ve HWID kaydınızı kontrol edin.</p>
                </div>
                <div class="flex items-start p-6 bg-[#1a1a24] rounded-xl border border-white/5">
                    <span class="bg-purple-500/10 text-purple-400 w-8 h-8 rounded-full flex items-center justify-center mr-4 shrink-0 font-bold">3</span>
                    <p class="text-gray-300">Ayarlar sekmesinden Primary, Secondary ve Rod kısayol tuşlarınızı atayın.</p>
                </div>
                <div class="flex items-start p-6 bg-[#1a1a24] rounded-xl border border-white/5">
                    <span class="bg-purple-500/10 text-purple-400 w-8 h-8 rounded-full flex items-center justify-center mr-4 shrink-0 font-bold">4</span>
                    <p class="text-gray-300">Dashboard üzerinden hedef CPS değerinizi belirleyin ve makroyu aktif edin.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer / Contact -->
    <footer class="py-20 px-6 border-t border-white/5 text-center">
        <div class="max-w-4xl mx-auto">
            <h2 class="text-2xl font-bold mb-8">İLETİŞİM VE TOPLULUK</h2>
            <div class="flex flex-col md:flex-row justify-center items-center gap-6">
                <div class="px-8 py-4 bg-white/5 rounded-full border border-white/10 w-full md:w-auto">
                    <span class="text-gray-500 mr-2">Discord:</span>
                    <span class="font-bold text-purple-400">untilshurawin</span>
                </div>
                <a href="https://discord.gg/arjantin" class="px-8 py-4 luxury-gradient rounded-full font-bold shadow-lg shadow-purple-500/20 hover:scale-105 transition-transform w-full md:w-auto">
                    discord.gg/arjantin
                </a>
            </div>
            <p class="mt-16 text-gray-600 text-sm">
                Copyright 2025 ClickMaster Pro. All rights reserved.
            </p>
        </div>
    </footer>

</body>
</html>
