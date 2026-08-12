---
title: "Método Aspose::Pdf::Document::get_EmbedStandardFonts"
linktitle: "get_EmbedStandardFonts"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Document::get_EmbedStandardFonts. Propiedad que indica que el documento debe incrustar todas las fuentes estándar Type1 cuyo indicador IsEmbedded esté establecido en verdadero. Todas las fuentes PDF pueden incrustarse en el documento simplemente estableciendo el indicador IsEmbedded en verdadero, pero las fuentes estándar Type1 de PDF son una excepción a esta regla. La incrustación de fuentes Type1 estándar requiere mucho tiempo, por lo que para incrustar estas fuentes es necesario no solo establecer el indicador IsEmbedded en verdadero para la fuente especificada, sino también establecer un indicador adicional a nivel del documento: EmbedStandardFonts = true; Esta propiedad solo puede establecerse una vez para todas las fuentes. Por defecto es false en C++."
type: docs
weight: 2700
url: /es/cpp/aspose.pdf/document/get_embedstandardfonts/
---
## Document::get_EmbedStandardFonts method


Propiedad que declara que el documento debe incrustar todas las fuentes estándar Type1 que tengan la bandera IsEmbedded establecida en true. Todas las fuentes PDF pueden incrustarse en el documento simplemente configurando la bandera IsEmbedded en true, pero las fuentes estándar Type1 del PDF son una excepción a esta regla. La incrustación de fuentes Type1 estándar requiere mucho tiempo, por lo que para incrustar estas fuentes es necesario no solo establecer la bandera IsEmbedded en true para la fuente especificada, sino también establecer una bandera adicional a nivel del documento: EmbedStandardFonts = true; Esta propiedad solo puede establecerse una vez para todas las fuentes. Por defecto, false.

```cpp
bool Aspose::Pdf::Document::get_EmbedStandardFonts() const
```

## Ver también

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
