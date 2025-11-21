🌊 AUV Depth Measurement System — Pressure Sensor SEN0257
<h1 align="center"> Sistem Pembacaan Kedalaman AUV — Sensor Tekanan SEN0257 </h1> <h3 align="center">Filtering — Zero Calibration — Hydrostatic Depth — Linear Regression Correction</h3> <p align="center"> 🤖 Firmware STM32/Arduino untuk Depth Control AUV <br> 🎯 Menggunakan Kalman Filter, Moving Average, dan Kalibrasi Zero <br> 📏 Dilengkapi Koreksi Regresi (m, c) dari Kalibrasi Offline </p>
🧠 Deskripsi Singkat

Sistem ini dirancang untuk membaca kedalaman AUV secara real-time menggunakan sensor tekanan SEN0257. Pembacaan sensor diproses melalui:

ADC Averaging (noise reduction)

Kalman Filter (filtering adaptif)

Moving Average (smoothing tambahan)

Zero Offset Calibration ('z')

Konversi Tegangan → Tekanan → Kedalaman

Koreksi Linear Regression (y = m·x + c) hasil kalibrasi offline

Output akhir berupa kedalaman dalam cm, stabil dan siap digunakan untuk kontrol PID depth-hold.
