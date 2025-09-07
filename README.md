# 🧪 Muestreo Digital con Raspberry Pi Pico 2W

Este repositorio contiene los y archivos .txt de análisis utilizados en el laboratorio. El objetivo principal es realizar muestreo de señales analógicas utilizando el Raspberry Pi Pico 2W y analizar los datos en el dominio del tiempo y la frecuencia.

## 📂 Contenido

- `ADC_testing.py`: Script base para adquisición de datos desde el ADC del Pico 2W.
- `muestras.txt` y `fft.txt`: Archivos generados con datos muestreados y transformada rápida de Fourier.
- `análisis_fft.m`: Script en MATLAB para visualizar los datos y evaluar la resolución espectral.
- `muestreo_estable.py`: Alternativa al script original con control preciso del tiempo de muestreo y cálculo de jitter.

## ⚙️ Requisitos

- Raspberry Pi Pico 2W
- Generador de señales (200 Hz, 1.2 Vpp, 1.6 V DC)
- Conexión a MATLAB Online o local

## 📊 Actividades principales

- Muestreo de señal senoidal con componente DC
- Análisis de la tasa de muestreo y efecto del número de puntos en la FFT
- Evaluación del jitter y su impacto en la codificación de fuente
- Visualización de datos con MATLAB usando `plot` y `stem`
