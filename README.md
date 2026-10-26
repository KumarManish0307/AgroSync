🌾 AgroSync: Cloud IoT Smart Irrigation System

AgroSync is a full-stack IoT & Cloud-based Precision Agriculture system built using the ESP32 microcontroller and Google Firebase Realtime Database. Designed specifically for rice paddies and multi-crop fields, it automates irrigation with a mandatory 90% soil moisture shutoff and dry-run tank protection, accessible via a responsive glassmorphic web dashboard.

✨ Key Features

🤖 Automated 90% Cutoff Logic: Automatically turns the water pump ON when soil moisture drops below the user-defined threshold and keeps it running until moisture reaches 90%, preventing waterlogging and wastage.

☁️ Real-Time Cloud Sync (2s Latency): Bidirectional JSON telemetry sync between the ESP32 hardware and the web portal via Firebase REST APIs.

🔐 Mandatory SMS OTP Authentication: Secure operator login on every session with a 4-digit OTP verification workflow.

🛡️ Dry-Run Pump Protection: Uses an HC-SR04 ultrasonic sensor to monitor water storage and automatically cuts off the motor if the tank level drops below 10%.

🌱 One-Click Crop Presets: Instant moisture threshold configuration for Rice/Paddy (55%), Tomato (40%), Wheat (30%), and Mustard (28%).

📊 Live Canvas Telemetry & CSV Audit Logs: Real-time moisture vs. 90% cutoff plotting and one-click CSV report downloads for agricultural analysis.
