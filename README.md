# 🌱 Proyecto GreenHouse – Agente Inteligente para Monitoreo de Invernaderos

Este proyecto fue desarrollado como parte de un trabajo académico para simular e implementar un sistema inteligente capaz de monitorear y controlar la temperatura de un invernadero. El sistema combina análisis de datos, simulación electrónica y automatización basada en reglas.

##  Objetivo General
Diseñar un agente inteligente que detecte valores anómalos en la temperatura del invernadero y active alertas o sistemas de control térmico de forma automatizada.

##  Tecnologías y Herramientas Utilizadas
- Python y Jupyter Notebook: Análisis de datos, gráficos y lógica de monitoreo.
- Node-RED: Desarrollo del agente inteligente y sistema de alertas.
- Arduino ATmega328P (simulado en Proteus): Simulación del sistema físico de monitoreo.

## Estructura del Proyecto
El proyecto cuenta con la siguiente estructura:
- Circuito.png: Diagrama del sistema electrónico simulado en Proteus.
- Codigo1.png y Codigo2.png: Capturas del código de control para Arduino.
- 01.csv a 05.csv: Datos por segmentos o sesiones.
- DatasetInvernadero.csv: Conjunto de datos completos simulados con los registros de temperaturas.
- Node-RED: Flujo de automatización para monitoreo y alertas (no incluido como archivo, pero se puede exportar desde Node-RED en JSON).
- Analisis.ipynb: Análisis de los datos y visualización de la temperatura en Python.

## Funcionamiento General
### Simulación en Proteus:
- Se utilizó un microcontrolador ATmega328P para simular el control de temperatura.
- El circuito se conecta virtualmente a sensores y actuadores.
### Monitoreo en Node-RED:
- Node-RED recibe los datos simulados y evalúa condiciones predefinidas.
- Si los valores exceden los rangos normales, se envía una alerta por via Whatsapp al propietario del invernadero.
### Análisis con Python:
- Se limpian y analizan los datos históricos de temperatura.
- Se generan gráficos para evaluar la eficiencia del sistema y detectar patrones.

## Capturas del Proyecto
Dentro del proyecto se adjuntan imagenes del funcionamiento del sistema asi como la elaboracion del circuito con el arduino atmega328P, asi como su programacion del misma
