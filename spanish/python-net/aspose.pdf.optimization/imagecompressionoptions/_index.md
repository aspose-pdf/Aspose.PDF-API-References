---
title: "ImageCompressionOptions"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase que contiene un conjunto de opciones para la compresión de imágenes."
type: docs
weight: 10
url: /es/python-net/aspose.pdf.optimization/imagecompressionoptions/
---

## ImageCompressionOptions class

Clase que contiene un conjunto de opciones para la compresión de imágenes.

El tipo ImageCompressionOptions expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| ImageCompressionOptions() | Inicializa una nueva instancia de la clase ImageCompressionOptions |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| compress_images | Si esta bandera se establece en true, las imágenes serán comprimidas en el documento. El nivel de compresión se especifica con la propiedad ImageQuality. |
| resize_images | Si esta bandera se establece en true y CompressImages es true, las imágenes se redimensionarán si la resolución de la imagen es mayor que el parámetro MaxResolution especificado. |
| image_quality | Especifica el nivel de compresión de la imagen cuando se usa la bandera CompressIamges. |
| max_resolution | Especifica la resolución máxima de las imágenes. Si la imagen tiene una resolución más alta, será escalada. |
| version | Versión del algoritmo de compresión. Los valores posibles son: 1. compresión estándar, 2. fast (compresión mejorada que es más rápida que la estándar pero puede no ser aplicable a todas las imágenes), 3. mixed (la compresión estándar se aplica a las imágenes que no pueden ser comprimidas por el algoritmo más rápido, esto puede ofrecer la mejor compresión pero es más lenta que el algoritmo \"fast\". La versión \"Fast\" no es aplicable para redimensionar imágenes (se utilizará el método estándar). El valor predeterminado es \"Standard\"). |
| codificación | Obtiene o establece la codificación utilizada para almacenar imágenes. |

### Ver también

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

