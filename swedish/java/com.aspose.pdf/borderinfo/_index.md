---
title: "BorderInfo"
linktitle: "BorderInfo"
second_title: "Aspose.PDF för Java API-referens"
description: "Denna klass representerar ram för grafikelement."
type: docs
weight: 370
url: /sv/java/com.aspose.pdf/borderinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BorderInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class BorderInfo extends Object implements com.aspose.ms.System.ICloneable
```

Denna klass representerar ram för grafikelement.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [BorderInfo](#BorderInfo--) | Initierar en ny instans av klassen {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-) | Initierar en ny instans av klassen {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.Color-) | Initierar en ny instans av klassen {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-float-) | Initierar en ny instans av klassen {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-float-com.aspose.pdf.Color-) | Initierar en ny instans av klassen {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.GraphInfo-) | Initierar en ny instans av klassen {@code BorderInfo}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone](#deepClone--) | Klonar ett nytt BorderInfo-objekt. |
| [getBottom](#getBottom--) | Hämtar objekt som anger kantens botten. |
| [getLeft](#getLeft--) | Hämtar {@code GraphInfo} objekt som anger kantens vänstra sida. |
| [getRight](#getRight--) | Hämtar {@code GraphInfo} objekt som anger kantens högra sida. |
| [getRoundedBorderRadius](#getRoundedBorderRadius--) | Hämtar rundad kantradie. |
| [getTop](#getTop--) | Hämtar {@code GraphInfo} objekt som anger den övre kanten. |
| [setBottom](#setBottom-com.aspose.pdf.GraphInfo-) | Anger objekt som anger kantens botten. |
| [setLeft](#setLeft-com.aspose.pdf.GraphInfo-) | Anger {@code GraphInfo} objekt som anger kantens vänstra sida. |
| [setRight](#setRight-com.aspose.pdf.GraphInfo-) | Anger {@code GraphInfo} objekt som anger kantens högra sida. |
| [setRoundedBorderRadius](#setRoundedBorderRadius-double-) | Anger rundad kantradie. |
| [setTop](#setTop-com.aspose.pdf.GraphInfo-) | Anger {@code GraphInfo} objekt som anger den övre kanten. |

### BorderInfo {#BorderInfo--}
```
public BorderInfo()
```

Initierar en ny instans av klassen {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-}
```
public BorderInfo(int borderSide)
```

Initierar en ny instans av klassen {@code BorderInfo}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| borderSide |  | Anger information om kantens sidor. Till exempel: (BorderSide.Left \ | BorderSide.Top). |

### BorderInfo {#BorderInfo-int-com.aspose.pdf.Color-}
Initierar en ny instans av klassen {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-float-}
```
public BorderInfo(int borderSide, float borderWidth)
```

Initierar en ny instans av klassen {@code BorderInfo}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| borderSide |  | Anger information om kantens sidor. Till exempel: (BorderSide.Left \ | BorderSide.Top). |
| borderWidth |  | Kantens bredd. |

### BorderInfo {#BorderInfo-int-float-com.aspose.pdf.Color-}
Initierar en ny instans av klassen {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-com.aspose.pdf.GraphInfo-}
Initierar en ny instans av klassen {@code BorderInfo}.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Klonar ett nytt BorderInfo-objekt.

**Returns:**
Det nya BorderInfo-objektet.

### getBottom {#getBottom--}
```
public GraphInfo getBottom()
```

Hämtar objekt som anger kantens botten.

**Returns:**
nedre

### getLeft {#getLeft--}
```
public GraphInfo getLeft()
```

Hämtar {@code GraphInfo} objekt som anger kantens vänstra sida.

**Returns:**
objekt som indikerar vänster om kanten.

### getRight {#getRight--}
```
public GraphInfo getRight()
```

Hämtar {@code GraphInfo} objekt som anger kantens högra sida.

**Returns:**
objekt som indikerar höger om kanten.

### getRoundedBorderRadius {#getRoundedBorderRadius--}
```
public double getRoundedBorderRadius()
```

Hämtar rundad kantradie.

**Returns:**
värde

### getTop {#getTop--}
```
public GraphInfo getTop()
```

Hämtar {@code GraphInfo} objekt som anger den övre kanten.

**Returns:**
objekt som indikerar den övre kanten

### setBottom {#setBottom-com.aspose.pdf.GraphInfo-}
Anger objekt som anger kantens botten.

### setLeft {#setLeft-com.aspose.pdf.GraphInfo-}
Anger {@code GraphInfo} objekt som anger kantens vänstra sida.

### setRight {#setRight-com.aspose.pdf.GraphInfo-}
Anger {@code GraphInfo} objekt som anger kantens högra sida.

### setRoundedBorderRadius {#setRoundedBorderRadius-double-}
```
public void setRoundedBorderRadius(double value)
```

Anger rundad kantradie.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setTop {#setTop-com.aspose.pdf.GraphInfo-}
Anger {@code GraphInfo} objekt som anger den övre kanten.
