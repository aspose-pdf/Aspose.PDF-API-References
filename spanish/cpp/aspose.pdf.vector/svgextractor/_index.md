---
title: "Aspose::Pdf::Vector::SvgExtractor clase"
linktitle: "SvgExtractor"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Vector::SvgExtractor clase. Representa una clase para la extracción de imágenes SVG de la página en C++."
type: docs
weight: 800
url: /es/cpp/aspose.pdf.vector/svgextractor/
---
## SvgExtractor class


Representa una clase para la extracción de imágenes SVG de la página.

```cpp
class SvgExtractor : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Extract](./extract/)(const System::SharedPtr\<GraphicsAbsorber\>\&, System::Predicate\<System::SharedPtr\<GraphicElement\>\>, const System::SharedPtr\<Page\>\&) | Extrae la imagen SVG a una cadena desde elementos gráficos representados por [absorber](../) con un filtro de predicado. |
| [Extract](./extract/)(const System::SharedPtr\<GraphicsAbsorber\>\&, System::Predicate\<System::SharedPtr\<GraphicElement\>\>, const System::SharedPtr\<Page\>\&, const System::String\&) | Extrae una imagen svg a un archivo a partir de elementos gráficos representados por [absorber](../) con un filtro de predicado. |
| [Extract](./extract/)(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>\&, const System::SharedPtr\<Page\>\&) | Extrae elementos gráficos a una cadena SVG. Opciones ignoradas: agrupación, extracción desde rectángulo. |
| [Extract](./extract/)(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>\&, const System::SharedPtr\<Page\>\&, const System::String\&) | Extrae elementos gráficos a un único archivo SVG. Opciones ignoradas: agrupación, extracción desde rectángulo. |
| [Extract](./extract/)(const System::SharedPtr\<Page\>\&) | Extrae imágenes Svg de una página a cadenas. |
| [Extract](./extract/)(const System::SharedPtr\<Page\>\&, const System::String\&) | Extrae imágenes Svg de una página a archivos. |
| [SvgExtractor](./svgextractor/)() | Representa una clase para extraer imágenes SVG de una página. |
| [SvgExtractor](./svgextractor/)(const System::SharedPtr\<SvgExtractionOptions\>\&) | Representa una clase para extraer imágenes SVG de una página. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
