---
title: "Aspose::Pdf::Text::Font::get_DecodedFontName método"
linktitle: "get_DecodedFontName"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::Font::get_DecodedFontName método. A veces las fuentes PDF (generalmente fuentes chinas/japonesas/coreanas) pueden tener un nombre de fuente específico. Este nombre es el valor de la propiedad de fuente PDF \\\"BaseFont\\\" y a veces esta propiedad puede representarse en forma hexadecimal. Si se lee este nombre directamente, podría aparecer en una forma no legible. Para obtener una forma legible es necesario decodificar el nombre de la fuente mediante reglas específicas para esa fuente. Esta propiedad devuelve el nombre de fuente decodificado, por lo que debe usarse en casos en los que se encuentre con un FontName no legible. Si la propiedad FontName tiene una forma legible, esta propiedad será la misma que FontName, por lo que puede usar esta propiedad en cualquier caso en que necesite obtener el nombre de la fuente en una forma legible en C++."
type: docs
weight: 300
url: /es/cpp/aspose.pdf.text/font/get_decodedfontname/
---
## Font::get_DecodedFontName method


A veces las fuentes PDF (generalmente fuentes chinas/japonesas/coreanas) pueden tener un nombre de fuente específico. Este nombre es el valor de la propiedad "BaseFont" de la fuente PDF y a veces esta propiedad puede representarse en forma hexadecimal. Si se lee este nombre directamente, podría aparecer en un formato no legible. Para obtener un formato legible es necesario decodificar el nombre de la fuente mediante reglas específicas para esa fuente. Esta propiedad devuelve el nombre de fuente decodificado, por lo que debe usarse en casos en los que se encuentre con un [FontName](../) no legible. Si la propiedad [FontName](../) tiene un formato legible, esta propiedad será la misma que [FontName](../), por lo que puede usar esta propiedad en cualquier caso en que necesite obtener el nombre de la fuente en un formato legible.

```cpp
System::String Aspose::Pdf::Text::Font::get_DecodedFontName()
```

## Ver también

* Class [String](../../../system/string/)
* Class [Font](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
