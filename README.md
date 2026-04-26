# Práctica Final — Deep Learning & Computer Vision

Clasificación multiclase de lesiones cutáneas con el dataset **HAM10000** usando 4 estrategias:
1. Modelo 1D (datos tabulares)
2. Modelo 2D (CNN sobre imágenes)
3. Late-Fusion (combinación de predicciones)
4. Early-Fusion (combinación de características)

## Cómo ejecutar el notebook

El notebook está pensado para ejecutarse en **Google Colab**.

### Pasos

1. Abre `Practica_deep_learning.ipynb` en Google Colab.
2. En el panel izquierdo de Colab, haz clic en el icono de **carpeta** 📁 (sección **Archivos**).
3. Sube los dos archivos CSV del dataset:
   - `HAM10000_metadata.csv`
   - `hmnist_28_28_RGB.csv`
5. Ejecuta cada celda en orden, de arriba hacia abajo (`Shift + Enter` en cada una, o `Runtime > Run all`).

## Archivos del proyecto

| Archivo | Descripción |
|---------|-------------|
| `Practica_deep_learning.ipynb` | Notebook con la solución completa de los 4 hitos |
| `enunciado.md` | Enunciado oficial de la práctica |
| `HAM10000_metadata.csv` | Metadatos de los pacientes (edad, sexo, localización) |
| `hmnist_28_28_RGB.csv` | Imágenes 28×28 RGB en formato array |
