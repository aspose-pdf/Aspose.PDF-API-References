---
title: Aspose::Pdf::Text::TextRenderingMode enum
linktitle: TextRenderingMode
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextRenderingMode enum. The text rendering mode, Tmode, determines whether showing text shall cause glyph outlines to be stroked, filled, used as a clipping boundary, or some combination of the three in C++.'
type: docs
weight: 6300
url: /cpp/aspose.pdf.text/textrenderingmode/
---
## TextRenderingMode enum


The text rendering mode, Tmode, determines whether showing text shall cause glyph outlines to be stroked, filled, used as a clipping boundary, or some combination of the three.

```cpp
enum class TextRenderingMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| FillText | 0 | Fill text. |
| StrokeText | 1 | Stroke text. |
| FillThenStrokeText | 2 | Fill, then stroke text. |
| Invisible | 3 | Neither fill nor stroke text (invisible). |
| FillTextAndAddPathToClipping | 4 | Fill text and add to path for clipping (see 9.3.6, "Text Rendering Mode,"). |
| StrokeTextAndAddPathToClipping | 5 | Stroke text and add to path for clipping. |
| FillThenStrokeTextAndAddPathToClipping | 6 | Fill, then stroke text and add to path for clipping. |
| AddPathToClipping | 7 | Add text to path for clipping. |

## See Also

* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
