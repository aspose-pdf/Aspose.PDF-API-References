---
title: "Aspose::Pdf::ImageStamp class"
linktitle: "ImageStamp"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::ImageStamp class. Representa un sello gráfico en C++."
type: docs
weight: 8300
url: /es/cpp/aspose.pdf/imagestamp/
---
## ImageStamp class


Representa un sello gráfico.

```cpp
class ImageStamp : public Aspose::Pdf::Stamp
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AlternativeText](./get_alternativetext/)() const | Obtiene el texto alternativo [Texto](../../aspose.pdf.text/) para el sello de imagen. |
| [get_Height](./get_height/)() override | Obtiene la altura de la imagen. Configurar esta imagen permite escalar la imagen verticalmente. |
| [get_Image](./get_image/)() const | Obtiene el flujo de imagen utilizado para el estampado. |
| [get_Quality](./get_quality/)() const | Obtiene la calidad del sello de imagen en porcentaje. Los valores válidos son 0..100%. |
| [get_Width](./get_width/)() override | Obtiene el ancho de la imagen. Configurar esta propiedad permite escalar la imagen horizontalmente. |
| [get_XIndent](./get_xindent/)() override | Obtiene y establece la coordenada horizontal del sello, comenzando desde la izquierda. |
| [get_YIndent](./get_yindent/)() override | Obtiene y establece la coordenada vertical del sello, comenzando desde la parte inferior. |
| [ImageStamp](./imagestamp/)(const System::SharedPtr\<System::IO::Stream\>\&) | Inicializa una nueva instancia de la clase [ImageStamp](./). |
| [ImageStamp](./imagestamp/)(const System::String\&) | Crea un sello de imagen a partir de una imagen en el archivo especificado. |
| [Put](./put/)(System::SharedPtr\<Page\>) override | Añade un sello gráfico en la página. |
| [set_AlternativeText](./set_alternativetext/)(const System::String\&) | Establece el [Texto](../../aspose.pdf.text/) alternativo para el sello de imagen. |
| [set_Height](./set_height/)(double) override | Establece la altura de la imagen. Configurar esta imagen permite escalar la imagen verticalmente. |
| [set_Quality](./set_quality/)(int32_t) | Establece la calidad del sello de imagen en porcentaje. Los valores válidos son 0..100%. |
| [set_Width](./set_width/)(double) override | Establece el ancho de la imagen. Configurar esta propiedad permite escalar la imagen horizontalmente. |
| [set_XIndent](./set_xindent/)(double) override | Obtiene y establece la coordenada horizontal del sello, comenzando desde la izquierda. |
| [set_YIndent](./set_yindent/)(double) override | Obtiene y establece la coordenada vertical del sello, comenzando desde la parte inferior. |
## Ver también

* Class [Stamp](../stamp/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
