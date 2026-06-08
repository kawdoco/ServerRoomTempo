<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Server Room Temperature Management Unit</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        body {
            font-family: 'Segoe UI', system-ui, sans-serif;
        }
        .hero-bg {
            background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 100%);
        }
        .card {
            transition: all 0.3s ease;
        }
        .card:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);
        }
        .temp-gauge {
            background: conic-gradient(#22c55e 0deg 180deg, #eab308 180deg 270deg, #ef4444 270deg 360deg);
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">
    <!-- Header -->
    <header class="hero-bg text-white py-16">
        <div class="max-w-6xl mx-auto px-6">
            <div class="flex items-center gap-4 mb-6">
                <i class="fas fa-temperature-high text-5xl"></i>
                <h1 class="text-5xl font-bold">Server Room<br>Temperature Management Unit</h1>
            </div>
            <p class="text-xl max-w-2xl opacity-90">
                Real-time temperature monitoring and intelligent management system based on ESP32 with WiFi connectivity.
            </p>
            <div class="mt-8 flex gap-4">
                <a href="#features" 
                   class="bg-white text-blue-700 px-8 py-3 rounded-xl font-semibold hover:bg-gray-100 transition">
                    Explore Features
                </a>
                <a href="#hardware" 
                   class="border border-white px-8 py-3 rounded-xl font-semibold hover:bg-white/10 transition">
                    View Hardware
                </a>
            </div>
        </div>
    </header>

    <!-- Navigation -->
    <nav class="sticky top-0 bg-white border-b shadow-sm z-50">
        <div class="max-w-6xl mx-auto px-6">
            <div class="flex items-center justify-between py-5">
                <div class="flex items-center gap-8">
                    <a href="#" class="font-semibold text-xl flex items-center gap-2">
                        <i class="fas fa-server"></i>
                        SRTMU
                    </a>
                    <div class="hidden md:flex gap-8">
                        <a href="#aim" class="hover:text-blue-600 transition">Aim</a>
                        <a href="#features" class="hover:text-blue-600 transition">Features</a>
                        <a href="#hardware" class="hover:text-blue-600 transition">Hardware</a>
                        <a href="#how-it-works" class="hover:text-blue-600 transition">How it Works</a>
                    </div>
                </div>
                <div class="flex items-center gap-3">
                    <span class="px-4 py-2 bg-green-100 text-green-700 rounded-full text-sm font-medium flex items-center gap-2">
                        <div class="w-2 h-2 bg-green-500 rounded-full animate-pulse"></div>
                        Online
                    </span>
                </div>
            </div>
        </div>
    </nav>

    <div class="max-w-6xl mx-auto px-6 py-12">

        <!-- Aim Section -->
        <section id="aim" class="mb-20">
            <h2 class="text-3xl font-bold mb-8 flex items-center gap-3">
                <i class="fas fa-bullseye text-blue-600"></i>
                Project Aim
            </h2>
            <div class="grid md:grid-cols-2 gap-10">
                <div class="bg-white p-8 rounded-2xl shadow">
                    <p class="text-lg leading-relaxed text-gray-700">
                        To design and develop a reliable, cost-effective, and real-time <strong>Server Room Temperature Management Unit</strong> 
                        that continuously monitors temperature and humidity, provides instant alerts, and helps maintain optimal environmental 
                        conditions to prevent hardware damage, downtime, and data loss.
                    </p>
                </div>
                <div class="bg-blue-50 border border-blue-100 p-8 rounded-2xl">
                    <h3 class="font-semibold text-xl mb-4">Why This Project Matters</h3>
                    <ul class="space-y-4">
                        <li class="flex gap-3">
                            <i class="fas fa-check text-green-500 mt-1"></i>
                            <span>Server rooms generate significant heat and require strict temperature control (18–27°C)</span>
                        </li>
                        <li class="flex gap-3">
                            <i class="fas fa-check text-green-500 mt-1"></i>
                            <span>Early detection of temperature spikes prevents costly hardware failures</span>
                        </li>
                        <li class="flex gap-3">
                            <i class="fas fa-check text-green-500 mt-1"></i>
                            <span>Remote monitoring via WiFi enables 24/7 oversight from anywhere</span>
                        </li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Features -->
        <section id="features" class="mb-20">
            <h2 class="text-3xl font-bold mb-8">Key Features</h2>
            <div class="grid md:grid-cols-3 gap-6">
                <div class="card bg-white p-8 rounded-2xl shadow">
                    <div class="w-14 h-14 bg-blue-100 text-blue-600 rounded-2xl flex items-center justify-center text-3xl mb-6">
                        <i class="fas fa-thermometer-half"></i>
                    </div>
                    <h3 class="text-2xl font-semibold mb-2">Real-time Monitoring</h3>
                    <p class="text-gray-600">Continuous temperature and humidity tracking using high-precision sensors.</p>
                </div>
                <div class="card bg-white p-8 rounded-2xl shadow">
                    <div class="w-14 h-14 bg-amber-100 text-amber-600 rounded-2xl flex items-center justify-center text-3xl mb-6">
                        <i class="fas fa-wifi"></i>
                    </div>
                    <h3 class="text-2xl font-semibold mb-2">WiFi Connectivity</h3>
                    <p class="text-gray-600">ESP32-based wireless data transmission to cloud dashboard or mobile app.</p>
                </div>
                <div class="card bg-white p-8 rounded-2xl shadow">
                    <div class="w-14 h-14 bg-red-100 text-red-600 rounded-2xl flex items-center justify-center text-3xl mb-6">
                        <i class="fas fa-bell"></i>
                    </div>
                    <h3 class="text-2xl font-semibold mb-2">Smart Alerts</h3>
                    <p class="text-gray-600">Email/SMS/Push notifications when temperature exceeds safe thresholds.</p>
                </div>
            </div>
        </section>

        <!-- Hardware & Resources -->
        <section id="hardware" class="mb-20">
            <h2 class="text-3xl font-bold mb-8">Hardware Resources</h2>
            <div class="bg-white rounded-3xl p-10 shadow">
                <div class="grid md:grid-cols-2 gap-12">
                    <div>
                        <h3 class="text-2xl font-semibold mb-6 flex items-center gap-3">
                            <i class="fas fa-microchip text-blue-600"></i>
                            Core Components
                        </h3>
                        <ul class="space-y-6">
                            <li class="flex items-start gap-4">
                                <span class="bg-blue-100 text-blue-700 w-8 h-8 rounded-xl flex items-center justify-center font-mono font-bold">1</span>
                                <div>
                                    <strong>ESP32 DevKit</strong>
                                    <p class="text-gray-600 text-sm">Main microcontroller with built-in WiFi &amp; Bluetooth</p>
                                </div>
                            </li>
                            <li class="flex items-start gap-4">
                                <span class="bg-blue-100 text-blue-700 w-8 h-8 rounded-xl flex items-center justify-center font-mono font-bold">2</span>
                                <div>
                                    <strong>DHT22 / DS18B20 Sensor</strong>
                                    <p class="text-gray-600 text-sm">Temperature &amp; Humidity (DHT22) or Waterproof Temperature (DS18B20)</p>
                                </div>
                            </li>
                            <li class="flex items-start gap-4">
                                <span class="bg-blue-100 text-blue-700 w-8 h-8 rounded-xl flex items-center justify-center font-mono font-bold">3</span>
                                <div>
                                    <strong>Buzzer / Relay Module</strong>
                                    <p class="text-gray-600 text-sm">Local alarm and cooling system control</p>
                                </div>
                            </li>
                            <li class="flex items-start gap-4">
                                <span class="bg-blue-100 text-blue-700 w-8 h-8 rounded-xl flex items-center justify-center font-mono font-bold">4</span>
                                <div>
                                    <strong>Power Supply</strong>
                                    <p class="text-gray-600 text-sm">5V USB or 12V adapter with backup battery option</p>
                                </div>
                            </li>
                        </ul>
                    </div>

                    <div>
                        <h3 class="text-2xl font-semibold mb-6">Software &amp; Tools</h3>
                        <div class="grid grid-cols-2 gap-4">
                            <div class="bg-gray-50 p-5 rounded-2xl">
                                <p class="font-medium">Programming</p>
                                <p class="text-sm text-gray-600">Arduino IDE / ESP-IDF</p>
                            </div>
                            <div class="bg-gray-50 p-5 rounded-2xl">
                                <p class="font-medium">Web Dashboard</p>
                                <p class="text-sm text-gray-600">HTML + JavaScript (or Blynk / ThingSpeak)</p>
                            </div>
                            <div class="bg-gray-50 p-5 rounded-2
