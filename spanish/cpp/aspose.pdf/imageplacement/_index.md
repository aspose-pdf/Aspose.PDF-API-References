---
title: "Clase Aspose::Pdf::ImagePlacement"
linktitle: "ImagePlacement"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::ImagePlacement. Representa las características de una imagen colocada en la página del documento Pdf en C++."
type: docs
weight: 8000
url: /es/cpp/aspose.pdf/imageplacement/
---
## ImagePlacement class


Representa las características de una imagen colocada en la página del documento [Pdf](../).

```cpp
class ImagePlacement : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_CompositingParameters](./get_compositingparameters/)() const | Obtiene los parámetros de composición del estado gráfico activo para la imagen colocada en la página. |
| [get_Image](./get_image/)() const | Obtiene el objeto de recurso [XImage](../ximage/) relacionado. |
| [get_Matrix](./get_matrix/)() const | Matriz de transformación actual para esta imagen. |
| [get_Operator](./get_operator/)() const | [Operator](../operator/) utilizado para mostrar la imagen. |
| [get_Page](./get_page/)() const | Obtiene la página que contiene la imagen. |
| [get_Rectangle](./get_rectangle/)() const | Obtiene el rectángulo de la [Image](../image/). |
| [get_Resolution](./get_resolution/)() const | Obtiene la resolución de la [Image](../image/). |
| [get_Rotation](./get_rotation/)() const | Obtiene el ángulo de rotación de la [Image](../image/). |
| [Hide](./hide/)() | Eliminar la imagen de la página. |
| [Replace](./replace/)(const System::SharedPtr\<System::IO::Stream\>\&) | Reemplazar la imagen en la colección con otra imagen. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&) | Guarda la imagen con las transformaciones correspondientes: escalado, rotación y resolución. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Guarda la imagen con las transformaciones correspondientes: escalado, rotación y resolución. |
## Observaciones


Cuando una imagen se coloca en una página, puede tener dimensiones diferentes a las dimensiones físicas definidas en [Resources](../resources/). El objeto [ImagePlacement](./) está destinado a proporcionar dicha información, como dimensiones, resolución, etc.
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
