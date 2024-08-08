<div align="center">
    <h1>T5 | LLMs</h1>
    <p align="center">
        proyecto de bootcamp IA generativa con pythoon.
    </p>
</div>

# MODELO DE LENGUAJE ELEGIDO DE HUGGINFACE: 
T5 = https://huggingface.co/distilbert/distilbert-base-multilingual-cased

Elegí este modelo ya que es un modelo más versatil y es posible utilizarlo para varias actividades como el resumen, traducción y tareas de múltiples pasos.

# Justificación clara de la Elección del Modelo Encoder
Ventajas: El modelo encoder T5 esmuy versatil y se puede aplicar a una amplia variedad de tareas, en este caso he aplicado dos tareas, las cuales son: traducción y resumen.
Puedes realizar peticiones en varios idiomas, yo he realizado peticiones en ingles y español y ha funcionado perfectamente.
Por ultimo lo he utilizado ya que no requiere un alto costo computacional y quería experimentar más actividades que solo la generación de texto.

# COMPARACIÓN CON OTROS MODELOS: 

# GPT (Generative Pre-trained Transformer)
- Características:
  - Unidireccional: Procesa el texto de izquierda a derecha.
  - Pre-entrenado: Pre-entrenado en grandes cantidades de texto, luego afinado para tareas específicas.
  - Aplicaciones: Generación de texto, resumen, chatbots.
- Ventajas:
  - Excelente capacidad para generar texto coherente y de alta calidad.
  - Gran flexibilidad para diferentes tareas de generación de texto.
- Desventajas:
  - Gran tamaño del modelo puede ser costoso en términos de recursos computacionales

# BART (Bidirectional and Auto-Regressive Transformers)

- Características:
  - Híbrido: Combina características de los modelos bidireccionales y auto-regresivos.
  - Pre-entrenamiento: Pre-entrenado en tareas de corrección de ruido, lo que lo hace robusto para generación de texto.
  - Aplicaciones: Generación de texto, traducción, resumen.
- Ventajas:
  - Equilibrio entre generación de alta calidad y capacidad de manejo de texto corrupto.
  - Versátil en diversas tareas de generación de texto.
- Desventajas:
  - Puede ser menos eficiente que modelos especializados en tareas muy específicas.

# Tecnologías
Este proyecto utiliza las siguientes tecnologías:
- Python 3.10.0 importante tener esta version
- https://www.python.org/downloads/release/python-3100/

## Cómo levantar el proyecto

1. Clona el repositorio.

```bash
git clone https://github.com/CarlosRaul04/LLMs.git
```

```bash
cd LLMs
```
1. Crea y activa el entorno virtual con `python -m venv myvenv`

```bash
python -m venv myvenv
```

- Para Windows:

```bash
myvenv\Scripts\Activate
```

- Para Linux/macOS
  
```bash
source myvenv/bin/activate
```

3. Instala las dependencias con `pip install -r requirements.txt`.

```bash
pip install -r requirements.txt
```

4. Luego de eso eliges el entorno dentro del archivo jupiter y corres el proyecto.
