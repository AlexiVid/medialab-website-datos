# Ficha del Proyecto

**Título:** Website académico/Tech con dataset de titulares del Blog de Python

**Pregunta / Objetivo:** Demonstrar flujo reproducible de extracción y procesamiento de datos para comunicación digital.

**Fuente:** [Blog de Python](https://blog.python.org/) (consulta automatizada)

**Metodología:**  
1. Web scraping de los titulares del blog usando Python, BeautifulSoup y pandas.  
2. Procesamiento de datos: limpieza de títulos, tokenización, conteo de palabras.  
3. Generación de datasets finales con CSV.

**Outputs:**  
- `data/posts_python_blog.csv` → titulares + URLs  
- `data/posts_python_blog_procesado.csv` → + longitud de título  
- `data/top_palabras_titulos.csv` → top 20 palabras
