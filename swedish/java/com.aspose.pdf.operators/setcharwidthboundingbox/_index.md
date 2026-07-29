---
title: "SetCharWidthBoundingBox"
linktitle: "SetCharWidthBoundingBox"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar d1-operatorn (ställer in glyf och omgivningsruta)."
type: docs
weight: 520
url: /sv/java/com.aspose.pdf.operators/setcharwidthboundingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidthBoundingBox, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidthBoundingBox

```
public class SetCharWidthBoundingBox extends Operator
```

Klass som representerar d1-operatorn (ställer in glyf och omgivningsruta).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-double-double-double-double-double-double-) | Initierar SetCharWidthBoundingBox-operatorn. |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-) | Konstruktor för operator-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getLlx](#getLlx--) | Vänster nedre horisontella koordinat för avgränsningsrektangeln. |
| [getLly](#getLly--) | Vänster nedre vertikala koordinat för avgränsningsrektangeln. |
| [getUrx](#getUrx--) | Högra övre horisontella koordinat för avgränsningsrektangeln. |
| [getUry](#getUry--) | Högra övre vertikala koordinat för avgränsningsrektangeln. |
| [getWx](#getWx--) | Horisontell förskjutning av tecknet. |
| [getWy](#getWy--) | Vertikal förskjutning av tecknet. |
| [toCommand](#toCommand--) | Endast för internt bruk! |
| [toString](#toString--) | Returnerar textrepresentation av operatorn. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-double-double-double-double-double-double-}
```
public SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury)
```

Initierar SetCharWidthBoundingBox-operatorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| wx |  | Anger den horisontella förskjutningen i tecknets koordinatsystem. |
| wy |  | Anger den vertikala förskjutningen i tecknets koordinatsystem. Ska vara 0. |
| llx |  | Anger X-koordinaten för det vänstra nedre hörnet. |
| lly |  | Anger Y-koordinaten för det nedre vänstra hörnet. |
| urx |  | Anger X-koordinaten för det övre högra hörnet. |
| ury |  | Anger Y-koordinaten för det övre högra hörnet. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-}
Konstruktor för operator-klassen.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### getLlx {#getLlx--}
```
public double getLlx()
```

Vänster nedre horisontella koordinat för avgränsningsrektangeln.

**Returns:**
double-värde

### getLly {#getLly--}
```
public double getLly()
```

Vänster nedre vertikala koordinat för avgränsningsrektangeln.

**Returns:**
double-värde

### getUrx {#getUrx--}
```
public double getUrx()
```

Högra övre horisontella koordinat för avgränsningsrektangeln.

**Returns:**
double-värde

### getUry {#getUry--}
```
public double getUry()
```

Högra övre vertikala koordinat för avgränsningsrektangeln.

**Returns:**
double-värde

### getWx {#getWx--}
```
public double getWx()
```

Horisontell förskjutning av tecknet.

**Returns:**
double-värde

### getWy {#getWy--}
```
public double getWy()
```

Vertikal förskjutning av tecknet.

**Returns:**
double-värde

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Endast för internt bruk!

**Returns:**
ICommand värde ICommand objekt

### toString {#toString--}
```
public String toString()
```

Returnerar textrepresentation av operatorn.

**Returns:**
Textrepresentation av representation
