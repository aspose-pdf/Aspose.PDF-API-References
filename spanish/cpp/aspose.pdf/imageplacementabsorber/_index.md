---
title: "Aspose::Pdf::ImagePlacementAbsorber class"
linktitle: "ImagePlacementAbsorber"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::ImagePlacementAbsorber class. Representa un objeto absorbente de objetos de colocación de imágenes. Realiza la búsqueda de usos de imágenes y proporciona acceso a los resultados de búsqueda a través de la colección ImagePlacementAbsorber::ImagePlacements en C++."
type: docs
weight: 8100
url: /es/cpp/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber class


Representa un objeto absorbente de objetos de colocación de imágenes. Realiza la búsqueda de usos de imágenes y proporciona acceso a los resultados de la búsqueda a través de la colección [ImagePlacementAbsorber::ImagePlacements](../).

```cpp
class ImagePlacementAbsorber : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_ImagePlacements](./get_imageplacements/)() const | Obtiene la colección de ocurrencias de colocación de imágenes que se presentan con objetos [ImagePlacement](../imageplacement/). |
| [get_IsReadOnlyMode](./get_isreadonlymode/)() const | Obtiene/establece el modo de solo lectura para la colección de operaciones de análisis. Puede ayudar a prevenir excepciones por falta de memoria. |
| [ImagePlacementAbsorber](./imageplacementabsorber/)() | Inicializa una nueva instancia del objeto [ImagePlacementAbsorber](./). |
| [set_IsReadOnlyMode](./set_isreadonlymode/)(bool) | Obtiene/establece el modo de solo lectura para la colección de operaciones de análisis. Puede ayudar a prevenir excepciones por falta de memoria. |
| [Visit](./visit/)(const System::SharedPtr\<Page\>\&) | Realiza la búsqueda en la página especificada. |
| [Visit](./visit/)(const System::SharedPtr\<Document\>\&) | Realiza la búsqueda en el documento especificado. |
## Observaciones


El objeto [ImagePlacementAbsorber](./) se utiliza básicamente en escenarios de búsqueda de imágenes. Cuando la búsqueda se completa, las ocurrencias se representan con objetos [ImagePlacement](../imageplacement/) que contiene la colección [ImagePlacementAbsorber::ImagePlacements](../). El objeto [ImagePlacement](../imageplacement/) proporciona acceso a las propiedades de colocación de la imagen: dimensiones, resolución, etc. La rotación positiva de [Image](../image/) es en sentido antihorario; para la página, es en sentido horario. Aquí, necesitamos representar el ángulo de rotación de la imagen, por lo que restamos el ángulo de la página del ángulo de la imagen.
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
