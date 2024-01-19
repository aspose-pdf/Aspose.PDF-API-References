---
title: Enum LineJoin
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.LineJoin enum. The line join style shall specify the shape to be used at the corners of paths that are stroked
type: docs
weight: 5350
url: /net/aspose.pdf.operators/linejoin/
---
## LineJoin enumeration

The line join style shall specify the shape to be used at the corners of paths that are stroked.

```csharp
public enum LineJoin
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| MiterJoin | `0` | Miter join. The outer edges of the strokes for the two segments shall be extended until they meet at an angle, as in a picture frame. If the segments meet at too sharp an angle as defined by the miter limit parameter (see 8.4.3.5, "Miter Limit"), a bevel join shall be used instead. |
| RoundJoin | `1` | Round join. An arc of a circle with a diameter equal to the line width shall be drawn around the point where the two segments meet, connecting the outer edges of the strokes for the two segments. This pieslice-shaped figure shall be filled in, producing a rounded corner. |
| BevelJoin | `2` | Bevel join. The two segments shall be finished with butt caps (see 8.4.3.3, "Line Cap Style") and the resulting notch beyond the ends of the segments shall be filled with a triangle. |

### See Also

* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


