---
title: Aspose::Pdf::Operators::LineJoin enum
linktitle: LineJoin
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Operators::LineJoin enum. The line join style shall specify the shape to be used at the corners of paths that are stroked in C++.'
type: docs
weight: 8400
url: /cpp/aspose.pdf.operators/linejoin/
---
## LineJoin enum


The line join style shall specify the shape to be used at the corners of paths that are stroked.

```cpp
enum class LineJoin
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| MiterJoin | 0 | Miter join. The outer edges of the strokes for the two segments shall be extended until they meet at an angle, as in a picture frame. If the segments meet at too sharp an angle as defined by the miter limit parameter (see 8.4.3.5, "Miter Limit"), a bevel join shall be used instead. |
| RoundJoin | 1 | Round join. An arc of a circle with a diameter equal to the line width shall be drawn around the point where the two segments meet, connecting the outer edges of the strokes for the two segments. This pieslice-shaped figure shall be filled in, producing a rounded corner. |
| BevelJoin | 2 | Bevel join. The two segments shall be finished with butt caps (see 8.4.3.3, "Line Cap Style") and the resulting notch beyond the ends of the segments shall be filled with a triangle. |

## See Also

* Namespace [Aspose::Pdf::Operators](../)
* Library [Aspose.PDF for C++](../../)
