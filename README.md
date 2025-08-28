- Este proyecto hace parte de una prueba práctica de postulación al IETS (Colombia)

# Modelo de Decisión para Manejo Sintomático de Condición Terminal

Este proyecto desarrolla un **simulador/modelador en Python** para evaluar diferentes tratamientos en pacientes con una condición terminal, comparando su impacto en mortalidad y calidad de vida.

## Descripción del Proyecto

El modelo considera tres escenarios:

- **Sin tratamiento**
- **Tratamiento 1**
- **Tratamiento 2**

Cada uno se evalúa en términos de:
- Mortalidad durante la crisis.
- Calidad de vida durante la crisis.
- Secuelas en la calidad de vida post-crisis.

Además, se incluye un análisis de sensibilidad (+/- 10% en secuelas) y un escenario extendido con expectativa de vida de 10 años posteriores a la crisis.

## Archivos del Repositorio

- `Prueba_Practica_Simulador_Modelador_Alexander_Marin.ipynb`  
  Contiene el código en Python para la simulación y el análisis de los escenarios.

- `Prueba_Práctica_Alexander_Marín.docx`  
  Documento explicativo del desarrollo del modelo, parámetros y resultados.

- `Presentación_Prueba_Practica_Alexander_Marin.pptx`  
  Presentación en PowerPoint con el resumen del proyecto y hallazgos clave.

## Metodología

- Se utiliza un grafo de estados (Salud → Fase Leve → Crisis → Muerte/Secuelas).
- Se calculan los valores de calidad de vida multiplicando supervivencia por los factores de reducción de calidad de vida durante crisis y secuelas.
- Se comparan resultados entre escenarios para identificar la mejor opción terapéutica.

## Resultados Principales

- El **Tratamiento 1** presenta los mejores resultados en reducción de mortalidad y mejora de la calidad de vida.
- Incluso en el análisis de sensibilidad y escenario extendido, sigue siendo la opción óptima.

