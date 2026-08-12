---
title: "Aspose::Pdf::Document::set_EmbedStandardFonts method"
linktitle: "set_EmbedStandardFonts"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Document::set_EmbedStandardFonts method. Propiedad que declara que el documento debe incrustar todas las fuentes Type1 estándar que tienen la bandera IsEmbedded establecida en true. Todas las fuentes PDF pueden incrustarse en el documento simplemente configurando la bandera IsEmbedded en true, pero las fuentes PDF Type1 estándar son una excepción a esta regla. La incrustación de fuentes Type1 estándar requiere mucho tiempo, por lo que para incrustar estas fuentes es necesario no solo establecer la bandera IsEmbedded en true para la fuente especificada, sino también establecer una bandera adicional a nivel del documento - EmbedStandardFonts = true; Esta propiedad solo puede establecerse una vez para todas las fuentes. Por defecto false en C++."
type: docs
weight: 9400
url: /es/cpp/aspose.pdf/document/set_embedstandardfonts/
---
## Document::set_EmbedStandardFonts method


Propiedad que declara que el documento debe incrustar todas las fuentes estándar Type1 que tengan la bandera IsEmbedded establecida en true. Todas las fuentes PDF pueden incrustarse en el documento simplemente configurando la bandera IsEmbedded en true, pero las fuentes estándar Type1 del PDF son una excepción a esta regla. La incrustación de fuentes Type1 estándar requiere mucho tiempo, por lo que para incrustar estas fuentes es necesario no solo establecer la bandera IsEmbedded en true para la fuente especificada, sino también establecer una bandera adicional a nivel del documento: EmbedStandardFonts = true; Esta propiedad solo puede establecerse una vez para todas las fuentes. Por defecto, false.

```cpp
void Aspose::Pdf::Document::set_EmbedStandardFonts(bool value)
```

## Ver también

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
