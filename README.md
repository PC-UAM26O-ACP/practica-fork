# Práctica: Uso de `fork()` en C

Este repositorio contiene una serie de ejercicios en C para comprender la creación y gestión de procesos hijo utilizando la llamada al sistema `fork()`.

## 📁 Archivos del Repositorio

* **`ejemplo1.c`**: Introducción básica a la llamada `fork()`.
* **`ejemplo2.c`**: Identificación de procesos (Padre e Hijo) mediante el valor devuelto por `fork()`.
* **`escalonado.c`**: Creación de procesos en cadena o estructura jerárquica.
* **`flor.c`**: Ejemplo donde un proceso padre genera múltiples procesos hijo a partir de un mismo punto.

## 🛠️ Requisitos e Instalación

Para compilar y ejecutar estos archivos necesitas un compilador de C (como `gcc`) en un entorno Unix/Linux.

### Compilar un archivo
bash
gcc -o ejemplo1 ejemplo1.c
