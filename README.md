# P7-Explorando-drivers-de-comportamiento-en-NovaRetail-

## 🎯 Objetivos de aprendizaje del proyecto
Al finalizar este proyecto, podrás:

1. Integrar múltiples técnicas de correlación en un solo análisis.
2. Identificar relaciones significativas entre variables mediante el uso de scatterplots y heatmaps.
3. Detectar correlaciones engañosas.
4. Documentar supuestos y limitaciones.
5. Convertir hallazgos en recomendaciones de negocio.
6. Escribir un reporte profesional.

## 🛠️ Herramientas de la lección
- Jupyter Notebook
- Python: pandas, numpy, seaborn, matplotlib


## Dataset del proyecto
Nombre: '/datasets/novaretail_comportamiento_clientes_2024.csv'

- Link de descarga aquí. *
    **Dataset:** 📥 [Descargar novaretail_comportamiento_clientes_2024.csv](https://drive.google.com/uc?export=download&id=1-eHDkD0ZapRUKZ2zoWojNzT-Ufy_nqX9)
- 📏 Tamaño: 15,000 filas

## Columnas 

| Columna | Tipo de dato (ejemplo) | Descripción |
| :--- | :--- | :--- |
| `id_cliente` | string (ej.) | Identificador único |
| `edad` | num | Edad del cliente |
| `nivel_ingreso` | num | Ingreso anual estimado |
| `visitas_mes` | num | Número de visitas a la app/web en el mes |
| `compras_mes` | num | Compras realizadas en el mes |
| `gasto_publicidad_dirigida` | num | Gasto en anuncios asignado al usuario |
| `satisfaccion` | num 1–5 | Calificación de satisfacción |
| `miembro_premium` | 0/1 | Suscripción mensual (premium o no) |
| `abandono` | 0/1 | Si el cliente abandonó la plataforma |
| `tipo_dispositivo` | categórica | móvil / escritorio / tablet |
| `region` | categórica | norte / sur / oeste / este |
| `ingreso_anual` | num | Ingreso anual del cliente a la empresa |

Nota: Esta variable (ingreso_anual) es el foco principal del análisis.


## 📝 Plan de acción
Contexto del negocio
Tu misión será construir un análisis correlacional estructurado que combine variables de comportamiento del cliente, segmentación y valor económico para usuarios de NovaRetail+ durante 2024.

El objetivo es generar un reporte de análisis de correlación claro, responsable y accionable, que permita entender qué comportamientos del cliente están más fuertemente asociados con el ingreso generado, sin caer en interpretaciones causales incorrectas.

Tu trabajo culminará con:

- Un Jupyter Notebook completamente documentado, que muestre el análisis paso a paso.
- Un reporte ejecutivo dentro del Jupyter Notebook con hallazgos, implicaciones y límites claros.
- Conclusiones respaldadas por el análisis para futuras decisiones de crecimiento, retención o experimentación.

# 🔄 Flujo general del proyecto

