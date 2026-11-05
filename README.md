# smart-room-dashboard
About the Project
​What it is
​A self-hosted, headless environmental monitoring system built around an ESP32 microcontroller and a DHT temperature/humidity sensor.
​What it does
​Instead of using a physical screen, the ESP32 acts as an independent local web server. It connects to your Wi-Fi, broadcasts a custom local domain via mDNS ([http://room-monitor.local](http://room-monitor.local)), and serves a responsive dark-mode web dashboard that updates temperature and humidity metrics in real-time using asynchronous AJAX polling.
​Why it's useful
​Cloud-Free & Private: Operates 100% locally on your network with zero external APIs, cloud servers, or internet dependencies.
​Headless Design: Saves hardware costs and complexity by turning any phone, tablet, or PC browser into your live display.
​Practical & Versatile: Ideal for monitoring room climate, workbench conditions, or closed environments like greenhouses without needing a dedicated physical LCD display.
