# IoT Security Lab

Build a small IoT device, look at what it sends over the network, then secure it.

**Status:** 🚧 Planning — buying parts in Nov 2026, first build planned for Dec 2026

## The device

An ESP32 DevKit with an SHT31 temperature and humidity sensor and a 1.3-inch OLED screen. It sends its readings over MQTT to a broker on my laptop.

## Plan

1. **Build** — read the sensor, show the values on the OLED, publish them over MQTT
2. **Observe** — capture the MQTT traffic in Wireshark and check what can be read in plain text
3. **Review** — look for secrets stored in my own firmware, such as the Wi-Fi password or broker credentials
4. **Secure** — MQTT over TLS, broker authentication, secrets moved out of the source code
5. **Write up** — before and after captures, and what changed

## Log

| Date | What I did |
|---|---|
| May 2026 | Learned MQTT basics on TryHackMe |
| Nov 2026 | Chose the parts: ESP32, SHT31, 1.3-inch OLED |
