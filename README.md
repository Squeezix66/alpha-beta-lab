# Laboratorio: Minimax y Poda Alfa-Beta

## Descripción
Proyecto de inteligencia artificial que implementa y compara los algoritmos Minimax y Poda Alfa-Beta sobre árboles de decisión de juegos adversariales.

## Instalación y Ejecución
```bash
# Activar entorno virtual
source .venv/Scripts/activate

# Instalar dependencias
pip install -r requirements.txt

# Ejecutar comparación de algoritmos
python -m src.main

# Ejecutar pruebas con reporte de cobertura
pytest --cov=src --cov-report=term-missing --cov-report=xml