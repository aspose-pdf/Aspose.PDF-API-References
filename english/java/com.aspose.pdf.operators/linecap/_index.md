---
title: LineCap
second_title: Aspose.PDF for Java API Reference
description: The line cap style shall specify the shape that shall be used at the ends of open subpaths and dashes if any when they are stroked.
type: docs
weight: 44
url: /java/com.aspose.pdf.operators/linecap/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LineCap extends System.Enum
```

The line cap style shall specify the shape that shall be used at the ends of open subpaths (and dashes, if any) when they are stroked.
## Fields

| Field | Description |
| --- | --- |
| [ButtCap](#ButtCap) | Butt cap. |
| [RoundCap](#RoundCap) | Round cap. |
| [SquareCap](#SquareCap) | Projecting square cap. |
### ButtCap {#ButtCap}
```
public static final int ButtCap
```


Butt cap. The stroke shall be squared off at the endpoint of the path. There shall be no projection beyond the end of the path.

### RoundCap {#RoundCap}
```
public static final int RoundCap
```


Round cap. A semicircular arc with a diameter equal to the line width shall be drawn around the endpoint and shall be filled in.

### SquareCap {#SquareCap}
```
public static final int SquareCap
```


Projecting square cap. The stroke shall continue beyond the endpoint of the path for a distance equal to half the line width and shall besquared off.

