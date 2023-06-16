---
title: LineJoin
second_title: Aspose.PDF for Java API Reference
description: The line join style shall specify the shape to be used at the corners of paths that are stroked.
type: docs
weight: 45
url: /java/com.aspose.pdf.operators/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LineJoin extends System.Enum
```

The line join style shall specify the shape to be used at the corners of paths that are stroked.
## Fields

| Field | Description |
| --- | --- |
| [MiterJoin](#MiterJoin) | Miter join. |
| [RoundJoin](#RoundJoin) | Round join. |
| [BevelJoin](#BevelJoin) | Bevel join. |
### MiterJoin {#MiterJoin}
```
public static final int MiterJoin
```


Miter join. The outer edges of the strokes for the two segments shall be extended until they meet at an angle, as in a picture frame. If the segments meet at too sharp an angle as defined by the miter limit parameter (see 8.4.3.5, "Miter Limit"), a bevel join shall be used instead.

### RoundJoin {#RoundJoin}
```
public static final int RoundJoin
```


Round join. An arc of a circle with a diameter equal to the line width shall be drawn around the point where the two segments meet, connecting the outer edges of the strokes for the two segments. This pieslice-shaped figure shall be filled in, producing a rounded corner.

### BevelJoin {#BevelJoin}
```
public static final int BevelJoin
```


Bevel join. The two segments shall be finished with butt caps (see 8.4.3.3, "Line Cap Style") and the resulting notch beyond the ends of the segments shall be filled with a triangle.

