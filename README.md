# ESP32-Power-Monitor-IoT
Sistema de monitoreo de energía eléctrica basado en ESP32 y MicroPython. Calcula voltaje RMS, corriente y potencia, enviando los datos en tiempo real a la nube mediante Google Apps Script.
Este proyecto utiliza un microcontrolador ESP32 con MicroPython para medir parámetros eléctricos básicos (Voltaje, Corriente y Potencia) y transmitirlos de forma inalámbrica a una hoja de cálculo de Google o un servidor externo mediante peticiones HTTP POST.

Características
Cálculo de Voltaje RMS: Realiza muestreo estadístico para estimar el voltaje de corriente alterna (AC).

Medición de Corriente: Implementa lógica para sensores de corriente analógicos con divisor de voltaje.

Cálculo de Potencia: Determina la potencia real en vatios (W).

Conectividad WiFi: Conexión automática a redes locales.

Integración Cloud: Envía datos en formato JSON a un endpoint de Google Apps Script.
