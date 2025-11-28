# Análisis del Comportamiento de Navegación en un E-Commerce

Este proyecto tiene como objetivo analizar el comportamiento de navegación de los usuarios en un sitio de comercio electrónico y estudiar su relación con la probabilidad de que una sesión finalice o no en una compra. El trabajo sigue el ciclo completo del análisis de datos, desde la comprensión del contexto hasta la obtención de conclusiones.

---

## Estructura del Proyecto

```
proyecto_aula/
│
└── entrega final/
    ├── 01 - contexto.ipynb
    ├── 02 - análisis exploratorio inicial.ipynb
    ├── 03 - análisis exploratorio (EDA).ipynb
    ├── 04 - detección de atípicos.ipynb
    ├── 05 - transformación.ipynb
    ├── 06 - conclusiones.ipynb
    └── README.md
│
└── entregas parciales/
    ├── sc_1_sebastian_florez_jaramillo.ipynb
    └── sc_5_sebastian_florez_jaramillo.ipynb
```

Los notebooks deben ejecutarse en orden, ya que cada uno continúa el procesamiento realizado en el anterior.

---

## Objetivo del Proyecto

Analizar cómo navegan los usuarios dentro del e-commerce y determinar qué patrones, características o comportamientos pueden estar asociados a que una sesión termine en compra. Se busca explorar, limpiar, transformar y preparar los datos para comprender estas relaciones.

---

## Descripción del Dataset

- **Registros iniciales:** 12 330 sesiones  
- **Columnas iniciales:** 18 variables  
- **Tipos de variables:**
  - 10 numéricas  
  - 8 categóricas (algunas representadas mediante números que corresponden a categorías)

El dataset contiene información como duración de páginas, tipo de visitante, comportamiento de navegación, día de la semana, si la sesión ocurrió en fin de semana, entre otras.

---

## Metodología

El proyecto sigue las etapas fundamentales del ciclo de vida del análisis de datos:

### 1. Contexto y comprensión del problema  
Notebook: **01 - contexto.ipynb**  
Se establece el objetivo del proyecto, el contexto y las preguntas principales.

### 2. Análisis exploratorio inicial  
Notebooks:  
- **02 - análisis exploratorio inicial.ipynb**  
- **03 - análisis exploratorio (EDA).ipynb**

Se revisan distribuciones, relaciones entre variables, estadísticas descriptivas, tipos de datos y primeras conclusiones.

### 3. Detección de valores atípicos  
Notebook: **04 - detección de atípicos.ipynb**  
Se identifican registros inusuales y se analizan sus posibles efectos sobre el análisis.

### 4. Transformación y escalamiento  
Notebook: **05 - transformación.ipynb**  
Incluye codificación de variables categóricas, estandarización de variables numéricas y preparación final del dataset.

### 5. Conclusiones  
Notebook: **06 - conclusiones.ipynb**  
Se presenta un resumen de los hallazgos y del estado final del dataset después del procesamiento.

---

## Ejecución del Proyecto

Para ejecutar el proyecto:

1. Abrir los notebooks en VSCode, Jupyter Notebook o un entorno equivalente.  
2. Ejecutarlos **en el orden indicado**, del 01 al 06.  
3. Verificar que el dataset original esté ubicado correctamente en el repositorio.

No se requiere un script principal; todo el análisis está documentado dentro de los notebooks.

---

## Autor

**Sebastián Flórez Jaramillo**
