# Repositorio de Robots Cartesiano de 4GDL y Robot de 6GDL

Este repositorio contiene la implementación en MATLAB de dos robots:
- **Robot cartesiano de 4 grados de libertad (4GDL)** con articulaciones prismáticas.
- **Robot de 6 grados de libertad (6GDL)** con articulaciones rotacionales.

## Descripción
Los códigos incluyen el cálculo de las matrices de transformación homogénea, jacobianos (diferencial y analítico), y velocidades lineales y angulares de los robots.

## Archivos incluidos
- `robot_4gdl.m`: Implementación del robot cartesiano de 4GDL.
- `robot_6gdl.m`: Implementación del robot de 6GDL.

## Características principales
### Robot Cartesiano de 4GDL
- Configuración de 4 articulaciones prismáticas.
- Cálculo de matrices de transformación homogénea.
- Obtención del Jacobiano de forma diferencial y analítica.
- Cálculo de velocidades lineales y angulares.

### Robot de 6GDL
- Configuración de 6 articulaciones rotacionales.
- Cálculo de matrices de transformación homogénea.
- Obtención del Jacobiano de forma diferencial y analítica.
- Cálculo de velocidades lineales y angulares.

## Requisitos
- MATLAB (cualquier versión compatible con `syms`, `diff`, `simplify` y operaciones matriciales)


