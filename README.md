# Análisis Dinámico de un Robot de \( n \) Eslabones usando el Método de Lagrange

Este repositorio contiene un script de MATLAB para calcular la energía cinética, energía potencial y los torques necesarios en cada articulación de un robot de \( n \) eslabones mediante el método de Lagrange. El script es adaptable para robots de cualquier número de eslabones y se basa en los parámetros de Denavit-Hartenberg (D-H).

## Contenido

- **`robotica_n_eslabones.mlx`**: Live Script de MATLAB que realiza el cálculo simbólico para un robot de \( n \) eslabones.
- **`README.md`**: Descripción general del proyecto, instrucciones de uso y requisitos.

## Características

- **Cálculo de Energía Cinética**: Calcula la energía cinética para cada eslabón usando la matriz de inercia y las velocidades.
- **Cálculo de Energía Potencial**: Determina la energía potencial considerando la gravedad en el eje vertical.
- **Ecuaciones de Lagrange**: Aplica el método de Lagrange para obtener los torques requeridos en cada articulación.
- **Configuración Flexible**: Permite análisis para cualquier número de eslabones.

## Requisitos

- **MATLAB** (preferentemente versión R2021a o posterior) con soporte para Live Scripts (`.mlx`).
- **Symbolic Math Toolbox**: Necesario para cálculos simbólicos.

## Instrucciones de Uso

1. Clona este repositorio o descarga el archivo `robotica_n_eslabones.mlx`:
   
   ```bash
   git clone https://github.com/TuNombreDeUsuario/robotica_n_eslabones.git
