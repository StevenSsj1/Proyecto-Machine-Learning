# Proyecto de Machine Learning

## Descripción
Este proyecto utiliza técnicas de Machine Learning.
Este proyecto tiene como objetivo extraer y procesar información estructurada de documentos PDF, identificando bloques de texto relevantes y analizando su similitud. 
Utiliza técnicas de procesamiento de lenguaje natural (NLP) y aprendizaje automático para organizar, limpiar y comparar contenidos textuales de los PDFs.

Está orientado a aplicaciones donde es necesario analizar grandes volúmenes de información documental. Se realizaron procesos de limpieza de datos, entrenamiento de modelos y evaluación de resultados.

✅ Resumen del proyecto:

Extraes texto desde archivos PDF usando PyPDF2.

- Procesas el texto: eliminas fechas, números, símbolos raros, haces limpieza del lenguaje natural.
- Encuentras títulos dentro del texto que siguen un patrón de fecha, hora y nombre en mayúsculas (por ejemplo: 23/04/2024 15:00 JUAN PEREZ).
- Usas técnicas de procesamiento de lenguaje natural (NLP) como:
- Tokenización (dividir palabras)
- Stopwords removal (quitar palabras comunes como "el", "la", "de", etc.)
- Stemming (reducir palabras a su raíz).
- Calculas similitud de textos usando TF-IDF y coseno de similitud.

## Requisitos
- **Python** 3.8 o superior
- **Jupyter Notebook**
- **Bibliotecas** necesarias:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

Instalación rápida de bibliotecas:
```bash
pip install -r requirements.txt
```

(Instalación rápida: pip install -r requirements.txt)

Instalación
Clona el repositorio:

```bash
git clone https://github.com/tu_usuario/tu_proyecto.git
cd tu_proyecto
```
Crea un entorno virtual (opcional pero recomendado):

```
bash
python -m venv venv
source venv/bin/activate  # En Linux/Mac
venv\Scripts\activate     # En Windows
```
Instala las dependencias:
```
bash
pip install -r requirements.txt
```
Uso
Abre el notebook en Jupyter:

bash
jupyter notebook ProyectoMl_Limpio.ipynb
Sigue las instrucciones en las celdas para entrenar y evaluar los modelos.

Estructura del proyecto
```bash
ProyectoMl/
│
├── ProyectoMl_Limpio.ipynb   # Notebook principal
├── data/                     # Carpeta opcional para los datos
└── README.md                 # Este archivo
```
