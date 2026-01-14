# Phytonunir2026
curso Phyton
# Calculadora de Promedios

Archivos incluidos:
- `main.py`: script interactivo con funciones testables.
- `test_main.py`: pruebas unitarias usando `pytest`.

Requisitos:
- Python 3.8+

Ejecutar:
```bash
python main.py
```

Probar (pytest):
```bash
pip install pytest
pytest -q
```

Notas:
- `calcular_promedio` lanza `ValueError` si la lista de notas está vacía.
- Las entradas interactivas validan que la cantidad de materias y notas sean enteros positivos,
  y que las notas estén entre 0.0 y 5.0.
