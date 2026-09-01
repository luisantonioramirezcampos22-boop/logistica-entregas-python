# Sistema de Logística y Entrega de Paquetes

Este es un sistema modular desarrollado en Python diseñado para gestionar de manera óptima el flujo de logística de una empresa de reparto. El software procesa información de clientes, paquetes y repartidores, organizando y estructurando las rutas logísticas.

## Tecnologías y Conceptos Utilizados
*   **Lenguaje:** Python 3
*   **Paradigma:** Programación Orientada a Objetos (POO) mediante la separación de entidades en clases modulares.
*   **Formatos de Datos:** Parsing y manipulación de archivos estructurados en formato **CSV** y **JSON**.
*   **Arquitectura de Software:** Organización limpia de proyectos separando datos (`data/`), lógica del negocio (`src/modules/` y `src/objetos/`), y el punto de entrada principal (`app.py`).

## Estructura del Proyecto
*   `data/`: Contiene los archivos fuente de almacenamiento (`clientes.csv`, `paquetes.csv`, `repartidores.csv`, `rutas.json`).
*   `src/objetos/`: Clases base que modelan las entidades del negocio de forma aislada.
*   `src/modules/`: Lógica encargada de la lectura y procesamiento de los archivos de datos.
*   `app.py`: Archivo principal que arranca la aplicación y ejecuta la interfaz de usuario en consola.

## Instalación y Ejecución

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com
   ```

2. Navega al directorio del proyecto:
   ```bash
   cd logistica-entregas-python
   ```

3. Ejecuta la aplicación principal:
   ```bash
   python app.py
   ```
