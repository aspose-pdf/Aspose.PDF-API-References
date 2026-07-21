---
title: "System::Drawing::Graphics::MeasureCharacterRanges método"
linktitle: "MeasureCharacterRanges"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::Graphics::MeasureCharacterRanges método. Devuelve una matriz de regiones, cada una de las cuales delimita posiciones de caracteres en la cadena especificada en C++."
type: docs
weight: 6400
url: /es/cpp/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges method


Devuelve una matriz de regiones, cada una de las cuales delimita posiciones de caracteres en la cadena especificada.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | const System::String\& | La cadena a medir |
| font | const SharedPtr\<Font\>\& | La fuente utilizada durante la medición de la cadena |
| layoutRect | RectangleF | El rectángulo de diseño utilizado durante la medición de la cadena |
| stringFormat | const SharedPtr\<StringFormat\>\& | El formato de cadena, contiene los rangos de caracteres a medir |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../../region/)
* Class [String](../../../system/string/)
* Class [Font](../../font/)
* Class [RectangleF](../../rectanglef/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.PDF for C++](../../../)
