# Orbitra '26 — Pre-Flight Launch Checklist

### 1. Power Subsystem (EPS)
- [ ] 2S Li-Ion cells fully charged (>7.8V combined).
- [ ] LM2596 output measured with multimeter and calibrated to exactly 5.0V before plugging in ESP32.
- [ ] Common ground connected between battery, buck converter, and ESP32.

### 2. Sensors & Hardware Check
- [ ] I2C lines (GPIO 21 SDA, GPIO 22 SCL) firmly seated.
- [ ] DHT11 data pin on GPIO 4.
- [ ] GPS TX/RX wired to GPIO 16/17 (TX->RX cross connection).
- [ ] GPS ceramic antenna facing skyward with outdoor satellite lock (PPS LED blinking).

### 3. Telemetry Ground Station Link
- [ ] Ground Base ESP32 plugged into laptop via USB-C.
- [ ] Dashboard opened on Chrome/Edge: [https://<username>.github.io/orbitra26/](https://minercrat.github.io/orbitra26/)
- [ ] Clicked `CONNECT USB` and verified live telemetry packets arriving.
- [ ] Clicked `TARE ALT` to zero the BMP280 altimeter to local pad ground level.
- [ ] Started CSV blackbox recording (`REC CSV`).
