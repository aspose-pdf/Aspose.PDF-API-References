---
title: "Метод System::Drawing::Graphics::MeasureCharacterRanges"
linktitle: "MeasureCharacterRanges"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Drawing::Graphics::MeasureCharacterRanges. Возвращает массив областей, каждая из которых ограничивает позиции символов в указанной строке, в C++."
type: docs
weight: 6400
url: /ru/cpp/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges method


Возвращает массив областей, каждая из которых ограничивает позиции символов в указанной строке.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| text | const System::String\& | Строка для измерения |
| шрифт | const SharedPtr\<Font\>\& | Шрифт, используемый при измерении строки |
| layoutRect | RectangleF | Прямоугольник размещения, используемый при измерении строки |
| stringFormat | const SharedPtr\<StringFormat\>\& | Формат строки, содержащий диапазоны символов для измерения |

## См. также

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
