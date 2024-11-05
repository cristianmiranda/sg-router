![Pilar del Este Logo](https://i.imgur.com/PZrOpqH.png)

<br/>

[![PROD](https://img.shields.io/badge/Production-e8665d?logo=icloud&logoColor=fff)](https://app.sg-comollego.ar)
[![DEV](https://img.shields.io/badge/Development-3693F3?logo=icloud&logoColor=fff)](https://develop.sg-comollego.pages.dev)

# 🗺️ SG - Como Llego

Este proyecto es una aplicación web simple que permite a los usuarios ingresar el número de lote de una propiedad y obtener las coordenadas en Google Maps para navegar hacia dicha ubicación.

## Descripción

La aplicación permite ingresar el número de lote de Santa Guadalupe, y redirige al usuario a Google Maps con la ruta sugerida hacia ese lote. Los datos de coordenadas para cada lote se obtienen de un archivo JSON alojado en Cloudflare R2.

### Características

- **Interfaz**: Utiliza TailwindCSS para un diseño limpio y responsivo.
- **Redirección**: Al ingresar el número de lote y presionar "Ir", la aplicación busca las coordenadas en el archivo `coords.json`ubicado en R2 y redirige a Google Maps para la navegación.
- **Compatibilidad**: Funciona en dispositivos móviles y de escritorio.

## Tecnologías Utilizadas

[![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?logo=Cloudflare&logoColor=white)](#)
[![HTML](https://img.shields.io/badge/HTML-%23E34F26.svg?logo=html5&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000)](#)
[![TailwindCSS](https://img.shields.io/badge/Tailwind%20CSS-%2338B2AC.svg?logo=tailwind-css&logoColor=white)](#)
[![JSON](https://img.shields.io/badge/JSON-000?logo=json&logoColor=fff)](#)

- **HTML**: Estructura del documento.
- **Tailwind CSS**: Estilos y diseño responsivo.
- **JavaScript**: Lógica de redirección y manejo de eventos.
- **Cloudflare R2**: Almacenamiento del archivo `coords.json` con datos de coordenadas.
- **Google Maps**: Redirección a la aplicación de mapas para navegación.

## Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/pilardeleste/sg-comollego.git
   ```

## QR

<img src="assets/qr.png" width="300"/>

## Mapeo de Lotes

https://jsfiddle.net/cristianmiranda/tsuL9mrn/31/
