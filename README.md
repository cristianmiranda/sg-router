# SG - Como Llego

Este proyecto es una aplicación web simple que permite a los usuarios ingresar el número de lote de una propiedad y obtener las coordenadas en Google Maps para navegar hacia dicha ubicación.

![Pilar del Este Logo](https://i.imgur.com/PZrOpqH.png)

## Descripción

La aplicación permite ingresar el número de lote de Santa Guadalupe, y redirige al usuario a Google Maps con la ruta sugerida hacia ese lote. Los datos de coordenadas para cada lote se obtienen de un archivo JSON alojado en Cloudflare R2.

### Características
- **Interfaz**: Utiliza TailwindCSS para un diseño limpio y responsivo.
- **Redirección**: Al ingresar el número de lote y presionar "Ir", la aplicación busca las coordenadas en el archivo `coords.json`ubicado en R2 y redirige a Google Maps para la navegación.
- **Compatibilidad**: Funciona en dispositivos móviles y de escritorio.

## Tecnologías Utilizadas

- **HTML**: Estructura del documento.
- **Tailwind CSS**: Estilos y diseño responsivo.
- **JavaScript**: Lógica de redirección y manejo de eventos.
- **Cloudflare R2**: Almacenamiento del archivo `coords.json` con datos de coordenadas.
- **Google Maps**: Redirección a la aplicación de mapas para navegación.

## Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/sg-como-llego.git
