# Configuraciones Personales para WSL - Arch

Este repositorio contiene las configuraciones y pasos básicos que utilizo en mi entorno de trabajo en **Arch Linux en WSL** (Windows Subsystem for Linux). Aquí encontrarás una colección de configuraciones, herramientas y scripts que me ayudan a personalizar y optimizar mi experiencia de desarrollo.

## Contenido del Repositorio

### 1. **first_pack.txt**  
Este archivo contiene una lista de los paquetes esenciales que suelo instalar en mi entorno Arch para tener un setup inicial básico. Incluye herramientas como **git**, **zsh**, **vim**, **micro**, y muchas más.

### 2. **zshrc_config.txt**  
Archivo de configuración de **Zsh**, que incluye ajustes personalizados como temas, alias, y otras configuraciones útiles para mejorar la productividad en la terminal.

## ¿Cómo Configurarlo?

### 1. Instalar los paquetes básicos  
Para instalar todos los paquetes listados en el archivo **`first_pack.txt`**, simplemente ejecuta el siguiente comando:

```bash
# Instalar paquetes desde el archivo first_pack.txt
sudo pacman -S $(cat first_pack.txt)
