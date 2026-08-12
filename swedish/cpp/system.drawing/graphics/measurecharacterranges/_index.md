---
title: "System::Drawing::Graphics::MeasureCharacterRanges‑metod"
linktitle: "MeasureCharacterRanges"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Graphics::MeasureCharacterRanges‑metod. Returnerar en array av regioner där varje region avgränsar teckenpositioner i den angivna strängen i C++."
type: docs
weight: 6400
url: /sv/cpp/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges method


Returnerar en array av regioner som var och en begränsar teckenpositioner i den angivna strängen.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | const System::String\& | Strängen att mäta |
| teckensnitt | const SharedPtr\<Font\>\& | Teckensnittet som används under mätning av strängen |
| layoutRect | RectangleF | Layoutrektangeln som används under mätning av strängen |
| stringFormat | const SharedPtr\<StringFormat\>\& | Strängformatet, innehåller teckenintervallen som ska mätas |

## Se även

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
