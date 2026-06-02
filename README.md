# Simulación de sistema de parqueaderos - Modelo M/M/1

Este repositorio contiene el desarrollo técnico del laboratorio final de simulación, basado en el sistema de pago de parqueaderos del centro comercial Supercentro.

## Objetivo

Simular el comportamiento de tres cajeros independientes mediante modelos M/M/1 para analizar si la cantidad actual de cajeros es suficiente o si se requiere una estrategia de mejora.

## Herramientas utilizadas

- Python
- NumPy
- Pandas
- Matplotlib
- SciPy
- Jupyter Notebook / Google Colab

## Descripción del modelo

El sistema cuenta con tres cajeros independientes. Los usuarios se clasifican en cuatro tipos:

- Rápido: 25%
- Normal: 20%
- Lento: 27.5%
- Muy lento: 27.5%

Cada tipo de usuario tiene un tiempo promedio de llegada y un tiempo promedio de servicio diferente. Los tiempos se simulan mediante distribuciones exponenciales, de acuerdo con el modelo M/M/1.

## Contenido del repositorio

- `simulacion_parqueaderos.ipynb`: notebook principal con el desarrollo del modelo.
- `resultados_parqueadero/`: carpeta con tablas y gráficas exportadas.
- `README.md`: descripción general del proyecto.

## Resultados principales

La simulación muestra que los tres cajeros permiten operar el sistema con un tiempo promedio de espera aceptable. Sin embargo, el tiempo promedio total en el sistema queda ligeramente por encima del criterio aceptable, por lo que se recomienda una mejora preventiva para reducir los tiempos asociados a usuarios lentos y muy lentos.

## Link colab

https://colab.research.google.com/drive/1pFqa_2Ok-_Sb2l3tvfsAj-i6Y5lnnoi5?usp=sharing

## Autores

- Camilo Londoño
- Miguel Morales
