# Análisis Dinámico de un Robot de \( n \) Eslabones usando el Método de Lagrange-Euler

Este repositorio contiene un Live Script de MATLAB que realiza el cálculo de la energía cinética, energía potencial y torques de un robot de \( n \) eslabones usando el método de Lagrange-Euler. Es adaptable para robots de diferentes configuraciones y se basa en los parámetros de Denavit-Hartenberg (D-H).

## Contenido

- **`Lagrange_Euler_Para_N_Eslabones.mlx`**: Live Script de MATLAB que ejecuta el cálculo simbólico de la dinámica para un robot de \( n \) eslabones, incluyendo energía cinética, energía potencial, y torques necesarios en cada articulación.
- **`README.md`**: Archivo que contiene una descripción del proyecto y las instrucciones de uso.

## Características

- **Cálculo de Energía Cinética**: Calcula la energía cinética para cada eslabón usando la matriz de inercia y las velocidades de los centros de masa.
- **Cálculo de Energía Potencial**: Determina la energía potencial considerando la gravedad en el eje vertical.
- **Ecuaciones de Lagrange-Euler**: Aplica el método de Lagrange para obtener los torques requeridos en cada articulación.
- **Configuración Flexible**: Permite el análisis para cualquier número de eslabones, definido por el usuario.

## Requisitos

- **MATLAB** (preferentemente versión R2021a o posterior) con soporte para Live Scripts (`.mlx`).
- **Symbolic Math Toolbox**: Necesario para realizar cálculos simbólicos.

## Instrucciones de Uso

1. Clona este repositorio o descarga el archivo `Lagrange_Euler_Para_N_Eslabones.mlx` directamente desde GitHub:
   
   ```bash
   git clone https://github.com/rgcb01/robotica_n_eslabones.git
