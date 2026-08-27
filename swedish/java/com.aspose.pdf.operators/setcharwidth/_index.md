---
title: "SetCharWidth"
linktitle: "SetCharWidth"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar d0-operatorn (ställer in glyfbredd)."
type: docs
weight: 510
url: /sv/java/com.aspose.pdf.operators/setcharwidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidth

```
public class SetCharWidth extends Operator
```

Klass som representerar d0-operatorn (ställer in glyfbredd).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SetCharWidth](#SetCharWidth-double-double-) | Konstruktor. |
| [SetCharWidth](#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Konstruktor för operator-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getWx](#getWx--) | Horisontell förskjutning av glyfkoordinat. |
| [getWy](#getWy--) | Vertikal förskjutning av glyfkoordinat. |
| [toCommand](#toCommand--) | Endast för internt bruk! |
| [toString](#toString--) | Returnerar textrepresentation av operatorn. |

### SetCharWidth {#SetCharWidth-double-double-}
```
public SetCharWidth(double wx, double wy)
```

Konstruktor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| wx |  | Horisontell förskjutning av tecknet. |
| wy |  | Vertikal förskjutning av tecknet. |

### SetCharWidth {#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Konstruktor för operator-klassen.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### getWx {#getWx--}
```
public double getWx()
```

Horisontell förskjutning av glyfkoordinat.

**Returns:**
double-värde

### getWy {#getWy--}
```
public double getWy()
```

Vertikal förskjutning av glyfkoordinat.

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
