# Generador de Presupuestos en Python 💼

Proyecto introductorio desarrollado en Jupyter Notebook que permite calcular y generar
un presupuesto en PDF para proyectos de desarrollo de software.

## ¿Qué hace?

El programa solicita al usuario cuatro datos:
- Nombre del proyecto
- Horas estimadas de trabajo
- Valor de la hora trabajada
- Plazo estimado de entrega

Con esa información calcula el costo total (`horas × valor_hora`) y genera
automáticamente un archivo `Presupuesto.pdf` con los datos ingresados.

## Tecnologías usadas

- Python 3
- Jupyter Notebook
- [fpdf](https://pypi.org/project/fpdf/) — generación de archivos PDF

## Requisitos
```bash
pip install fpdf
```

## Cómo ejecutarlo

1. Clona el repositorio
2. Coloca el archivo `Template.png` en la misma carpeta (plantilla visual del presupuesto)
3. Abre `proyecto.ipynb` en Jupyter Notebook o VS Code
4. Ejecuta las celdas en orden

## Aprendizajes aplicados

- Entrada y salida de datos con `input()` y `print()`
- Almacenamiento en variables y conversión de tipos (`int()`, `str()`)
- Uso de librerías externas (`fpdf`)
- Generación de archivos PDF desde Python

## Autor
Alejandro Cruz Castañeda
Estudiante de Ingenieria de Sistemas — Minuto de Dios