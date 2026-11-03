# Control PID de Alabeo — Banco de Pruebas

Página web del TP final de **Sistemas de Control (2026)**.

## Descripción

Banco de pruebas de un avión de telgopor montado sobre una varilla, con un ventilador generando viento relativo y un lazo de control PID que corrige el alabeo (roll) automáticamente usando un servo que mueve ambos alerones en sentido opuesto (varillaje en Y).

## Hardware

- **ESP32** — microcontrolador principal, WiFi AP, loop de control a 100 Hz
- **MPU6050 (GY-521)** — acelerómetro + giróscopo, filtro complementario α=0.98
- **Servo** — controla ambos alerones, varillaje en Y, rango 60°–120°
- **Joystick** — modo manual / alternancia manual↔automático

## Uso

Abrir `index.html` en un navegador moderno (Chrome, Firefox, Edge).

No requiere servidor HTTP — funciona con `file://`.

## Integrantes

- Abel Locatelli
- Cristian Lopez
- Ezequiel Muntaneer
- Hugo Cordoba
- Joaquin De La Corte
- Gustavo Ciafroni

## Stack

- HTML5 + CSS3 + Vanilla JS
- Three.js r128 (CDN — sin bundler)
- Sin dependencias de build
