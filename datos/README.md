# Datos: MAGFiLO 1.0 (versión Kaggle 2026)

Copia del conjunto de datos publicado en la competencia [Solar Filament Segmentation Challenge 2026](https://www.kaggle.com/competitions/filament-segmentation-2026), incluida para que el proyecto pueda reproducirse sin pasos adicionales.

| | |
|---|---|
| **Fuente** | Kaggle, pestaña *Data* de la competencia (descargado el 29/10/2026) |
| **Autores del conjunto** | Ahmadzadeh, A. et al. (2024), *Scientific Data*, 11, 1031. https://doi.org/10.1038/s41597-024-03876-y |
| **Licencia** | [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/): uso no comercial y con atribución |
| **Imágenes** | Observaciones H-alfa de la red GONG, JPEG en escala de grises, 2048 por 2048 píxeles |

## Contenido

```
MAGFiLO_1.0_Kaggle_2026/
├── train/
│   ├── train_images/                                 707 imágenes
│   └── MAGFiLO_1.0_Annotations_kaggle2026_train.json anotaciones en formato COCO
└── test/
    └── test_images/                                  180 imágenes sin etiquetas
```

| Elemento | Cantidad |
|---|---|
| Imágenes de entrenamiento | 707 |
| Pares (anotador, imagen) en el JSON | 1 154 |
| Filamentos anotados | 8 199 |
| Imágenes con 1, 2 y 3 anotadores | 411, 145 y 151 |
| Imágenes de prueba | 180 |

Cada filamento está anotado con un polígono de segmentación, una caja delimitadora, una línea central (*spine*) y una clase: Left, Right, Unidentifiable o Ambiguous.

Los archivos no fueron modificados respecto de la descarga original.
