---
title: "Aspose::Pdf::Text::Font class"
linktitle: "Fuente"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Text::Font class. Representa un objeto de fuente en C++."
type: docs
weight: 900
url: /es/cpp/aspose.pdf.text/font/
---
## Font class


Representa un objeto de fuente.

```cpp
class Font : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [CppIsSetTrailerable](./cppissettrailerable/)() |  |
| [get_BaseFont](./get_basefont/)() | Obtiene el valor BaseFont del objeto de fuente PDF. También conocido como el nombre PostScript de la fuente. |
| [get_DecodedFontName](./get_decodedfontname/)() | A veces las fuentes PDF (generalmente fuentes chinas/japonesas/coreanas) pueden tener un nombre de fuente específico. Este nombre es el valor de la propiedad "BaseFont" de la fuente PDF y a veces esta propiedad puede representarse en forma hexadecimal. Si se lee este nombre directamente, podría aparecer en un formato no legible. Para obtener un formato legible es necesario decodificar el nombre de la fuente mediante reglas específicas para esa fuente. Esta propiedad devuelve el nombre de fuente decodificado, por lo que debe usarse en casos en los que se encuentre con un [FontName](../) no legible. Si la propiedad [FontName](../) tiene un formato legible, esta propiedad será la misma que [FontName](../), por lo que puede usar esta propiedad en cualquier caso en que necesite obtener el nombre de la fuente en un formato legible. |
| [get_FontName](./get_fontname/)() const | Obtiene el nombre de la fuente del objeto [Font](./). |
| [get_FontOptions](./get_fontoptions/)() | Propiedades útiles para ajustar el comportamiento de [Font](./). |
| [get_IsAccessible](./get_isaccessible/)() const | Obtiene que indica si la fuente está presente (instalada) en el sistema. |
| [get_IsEmbedded](./get_isembedded/)() const | Obtiene un valor que indica si la fuente está incrustada. [Font](./) basado en IFont se subestablecerá y se incrustará automáticamente. |
| [get_IsSubset](./get_issubset/)() | Obtiene un valor que indica si la fuente es un subconjunto. [Font](./) basado en IFont se subestablecerá y se incrustará automáticamente. |
| [GetLastFontEmbeddingError](./getlastfontembeddingerror/)() | El objetivo de este método es devolver la descripción del error si un intento de incrustar la fuente falló. Si no hay casos de error, devuelve una cadena vacía. |
| [MeasureString](./measurestring/)(const System::String\&, float) | Mide la cadena. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&) | Guarda la fuente en el flujo. [Note](../../aspose.pdf/note/) que la fuente se guarda en formato TTF intermedio destinado a usarse solo en una copia convertida del documento original. El archivo de fuente no está destinado a usarse fuera del contexto del documento original. |
| [set_IsEmbedded](./set_isembedded/)(bool) | Establece un valor que indica si la fuente está incrustada. [Font](./) basado en IFont se subestablecerá y se incrustará automáticamente. |
| [set_IsSubset](./set_issubset/)(bool) | Establece un valor que indica si la fuente es un subconjunto. [Font](./) basado en IFont se subestablecerá y se incrustará automáticamente. |



## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
