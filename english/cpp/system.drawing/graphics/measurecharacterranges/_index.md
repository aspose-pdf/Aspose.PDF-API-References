---
title: System::Drawing::Graphics::MeasureCharacterRanges method
linktitle: MeasureCharacterRanges
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Graphics::MeasureCharacterRanges method. Returns an array of regions each of which bounds character positions in the specified string in C++.'
type: docs
weight: 6400
url: /cpp/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges method


Returns an array of regions each of which bounds character positions in the specified string.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```


| Parameter | Type | Description |
| --- | --- | --- |
| text | const System::String\& | The string to measure |
| font | const SharedPtr\<Font\>\& | The font used during the measurement of the string |
| layoutRect | RectangleF | The layout rectangle used during the measurement of the string |
| stringFormat | const SharedPtr\<StringFormat\>\& | The string format, contaions the character ranges to measure |

## See Also

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
