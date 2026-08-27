---
title: "SubPath"
linktitle: "SubPath"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar vektor grafikobjekt på sidan. I princip representeras vektorgrafikobjekt av två grupper av SubPaths. En av dem representeras av en uppsättning linjer och."
type: docs
weight: 60
url: /sv/java/com.aspose.pdf.vector/subpath/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.SubPath, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.SubPath

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class SubPath extends GraphicElement
```

Representerar ett vektorgrafikobjekt på sidan. I grund och botten representeras vektorgrafikobjekt av två grupper av SubPaths. En av dem representeras av en uppsättning linjer och kurvor. De andra presenteras som rektanglar och kan ibland förväxlas. Vanligtvis är det ett rektangulärt område som har en färg, men mycket ofta placeras denna rektangel i början av sidan och definierar hela sidans utrymme i vitt. Så du får SubPath, men visuellt ser du bara texten på sidan.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRectangle](#getRectangle--) | Hämtar den omgivande rektangeln för GraphicElement. |

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Hämtar den omgivande rektangeln för GraphicElement.

**Returns:**
Rektangelinstans
