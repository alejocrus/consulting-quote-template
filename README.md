# Generador de Presupuestos en Python 💼

Proyecto introductorio desarrollado en Jupyter Notebook que combina conceptos
básicos de Python para construir una herramienta que genera presupuestos de
consultoría en formato PDF.

## ¿Qué hace?

El notebook está estructurado de forma progresiva:

1. **Conceptos básicos** — uso de `print()` e `input()` para mostrar y recibir información
2. **Variables** — almacenamiento de texto y números
3. **Integración** — combinación de todos los conceptos para recopilar los datos del presupuesto
4. **Generación de PDF** — uso de la librería `fpdf` para producir un archivo PDF con plantilla visual

Los datos que solicita al usuario son:
- Nombre del proyecto
- Horas estimadas de trabajo
- Valor de la hora trabajada
- Plazo estimado de entrega

Con esa información calcula el costo total (`horas × valor_hora`) y genera
automáticamente un archivo `Presupuesto.pdf` con los datos sobre una plantilla diseñada en Canva.

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
2. Asegúrate de tener el archivo `Template.png` en la misma carpeta
3. Abre `generador_presupuesto.ipynb` en Jupyter Notebook o VS Code
4. Ejecuta las celdas en orden

## Autor
Alejandro Cruz Castañeda
Estudiante de Ingenieria de Sistemas — Minuto de Dios