
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
