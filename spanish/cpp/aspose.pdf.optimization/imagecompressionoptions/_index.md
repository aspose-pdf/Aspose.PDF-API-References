---
title: "Aspose::Pdf::Optimization::ImageCompressionOptions clase"
linktitle: "ImageCompressionOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Optimization::ImageCompressionOptions clase. La clase contiene opciones establecidas para la compresión de imágenes en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions class


La clase contiene un conjunto de opciones para la compresión de imágenes.

```cpp
class ImageCompressionOptions : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_CompressImages](./get_compressimages/)() const | Si esta bandera se establece en true, las imágenes se comprimirán en el documento. El nivel de compresión se especifica con la propiedad ImageQuality. |
| [get_Encoding](./get_encoding/)() const | Obtiene la codificación utilizada para almacenar imágenes. |
| [get_ImageQuality](./get_imagequality/)() const | Especifica el nivel de compresión de imágenes cuando se usa la bandera CompressImages. |
| [get_MaxResolution](./get_maxresolution/)() const | Especifica la resolución máxima de las imágenes. Si una imagen tiene una resolución mayor, será escalada. |
| [get_ResizeImages](./get_resizeimages/)() const | Si esta bandera se establece en true y CompressImages es true, las imágenes se redimensionarán si la resolución de la imagen es mayor que el parámetro MaxResolution especificado. |
| [get_Version](./get_version/)() const | Versión del algoritmo de compresión. Los valores posibles son: 1. compresión estándar, 2. fast (compresión mejorada que es más rápida que la estándar pero puede no ser aplicable a todas las imágenes), 3. mixed (la compresión estándar se aplica a las imágenes que no pueden ser comprimidas por el algoritmo más rápido, lo que puede ofrecer la mejor compresión pero es más lenta que el algoritmo \"fast\". La versión \"Fast\" no es aplicable al redimensionamiento de imágenes (se utilizará el método estándar). El valor predeterminado es \"Standard\"). |
| [ImageCompressionOptions](./imagecompressionoptions/)() |  |
| [set_CompressImages](./set_compressimages/)(bool) | Si esta bandera se establece en true, las imágenes se comprimirán en el documento. El nivel de compresión se especifica con la propiedad ImageQuality. |
| [set_Encoding](./set_encoding/)(ImageEncoding) | Establece la codificación utilizada para almacenar imágenes. |
| [set_ImageQuality](./set_imagequality/)(int32_t) | Especifica el nivel de compresión de imágenes cuando se usa la bandera CompressImages. |
| [set_MaxResolution](./set_maxresolution/)(int32_t) | Especifica la resolución máxima de las imágenes. Si una imagen tiene una resolución mayor, será escalada. |
| [set_ResizeImages](./set_resizeimages/)(bool) | Si esta bandera se establece en true y CompressImages es true, las imágenes se redimensionarán si la resolución de la imagen es mayor que el parámetro MaxResolution especificado. |
| [set_Version](./set_version/)(ImageCompressionVersion) | Versión del algoritmo de compresión. Los valores posibles son: 1. compresión estándar, 2. fast (compresión mejorada que es más rápida que la estándar pero puede no ser aplicable a todas las imágenes), 3. mixed (la compresión estándar se aplica a las imágenes que no pueden ser comprimidas por el algoritmo más rápido, lo que puede ofrecer la mejor compresión pero es más lenta que el algoritmo \"fast\". La versión \"Fast\" no es aplicable al redimensionamiento de imágenes (se utilizará el método estándar). El valor predeterminado es \"Standard\"). |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Optimization](../)
* Library [Aspose.PDF for C++](../../)
