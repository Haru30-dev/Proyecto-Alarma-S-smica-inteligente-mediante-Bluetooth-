# 🚨 Alarma Sísmica Inteligente

## 📌 Descripción

La **Alarma Sísmica Inteligente** es un prototipo desarrollado como proyecto de investigación escolar con el objetivo de contribuir a mejorar la respuesta de las personas ante una situación de emergencia sísmica.

El sistema utiliza un **ESP32** como unidad principal y se comunica mediante **Bluetooth** con una aplicación móvil desarrollada en **MIT App Inventor**.

Desde la aplicación se puede controlar el estado de la alarma. Cuando se activa el modo **ALERTA**, el ESP32 enciende los LEDs rojos y activa los buzzers para generar una señal visual y sonora. En el modo **NORMAL**, la alarma permanece apagada y el LED verde indica que el sistema está listo.

---

## 🎯 Objetivo

Diseñar e implementar un sistema de alerta basado en ESP32 y Bluetooth que permita activar una señal sonora y visual de manera rápida durante una situación de emergencia.

---

## ⚙️ ¿Cómo funciona?

El funcionamiento básico del sistema es:

**📱 Aplicación móvil → 📡 Bluetooth → ESP32 → 🚨 LEDs + Buzzers**

1. El usuario abre la aplicación.
2. Se conecta al ESP32 mediante Bluetooth.
3. Al seleccionar **ALERTA**, la aplicación envía el comando correspondiente.
4. El ESP32 recibe el comando.
5. Los LEDs rojos y los buzzers se activan simultáneamente.
6. Al seleccionar **NORMAL**, la alarma se desactiva y el sistema vuelve a su estado inicial.

---

## 🔧 Componentes

- ESP32
- Protoboard
- LEDs
- Resistencias de 220 Ω
- 2 buzzers
- Cables jumper
- Power Bank de 5 V
- Teléfono Android
- Aplicación desarrollada en MIT App Inventor

---

## 📱 Aplicación móvil

La aplicación fue desarrollada utilizando **MIT App Inventor**.

Sus funciones principales son:

- 🔵 Conexión con el ESP32 mediante Bluetooth.
- 🟢 Activación del modo NORMAL.
- 🔴 Activación del modo ALERTA.
- 📊 Visualización del estado de conexión.
- 🚨 Control de la alarma.

---

## 🔋 Alimentación

El prototipo utiliza una **Power Bank de 5 V** como fuente de alimentación mediante USB.

Durante el desarrollo se realizaron pruebas con diferentes fuentes de energía y finalmente se seleccionó la Power Bank debido a su facilidad de uso y estabilidad para alimentar el sistema durante las pruebas y demostraciones.

---

## 💻 Programación

El ESP32 fue programado utilizando **Arduino IDE**.

La comunicación Bluetooth utiliza el nombre:

`Alarma_Sismica`

Los comandos principales utilizados por la aplicación son:

`ALERTA`

`NORMAL`

---

## 🚀 Instalación de la aplicación

Para instalar la aplicación en un dispositivo Android:

1. Descargar el archivo `.apk` desde la sección **Releases**.
2. Abrir el archivo descargado.
3. Permitir la instalación de aplicaciones desde esta fuente si Android lo solicita.
4. Instalar la aplicación.
5. Activar Bluetooth.
6. Emparejar el ESP32.
7. Abrir la aplicación y seleccionar el dispositivo `Alarma_Sismica`.

> **Nota:** La aplicación está desarrollada como parte de un prototipo escolar y está diseñada para controlar el sistema electrónico mediante Bluetooth.

---

## 📥 Descargar aplicación

### [⬇️ Descargar Alarma Sísmica](../../releases/latest)

---

## 🔮 Mejoras futuras

Como futuras mejoras del proyecto se propone:

- Incorporar un sensor sísmico o acelerómetro para detectar movimientos automáticamente.
- Implementar conexión Wi-Fi para enviar alertas a varios dispositivos.
- Utilizar una sirena de mayor potencia.
- Incorporar una batería de respaldo.
- Mejorar la carcasa y protección del circuito.
- Registrar datos de las activaciones del sistema.

---

## 👨‍🔬 Proyecto de investigación

**Proyecto:** Alarma Sísmica Inteligente  
**Plataforma:** ESP32  
**Comunicación:** Bluetooth  
**Aplicación:** MIT App Inventor  
**Año:** 2026

---

## ⚠️ Importante

Este proyecto es un **prototipo educativo** desarrollado para demostrar el funcionamiento de un sistema de alerta. No debe considerarse un sistema profesional certificado de detección o alerta sísmica.
