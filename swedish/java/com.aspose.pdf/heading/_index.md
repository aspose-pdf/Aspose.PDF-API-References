---
title: "Rubrik"
linktitle: "Rubrik"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar rubrik."
type: docs
weight: 1890
url: /sv/java/com.aspose.pdf/heading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.TextFragment, com.aspose.pdf.Heading

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Heading extends TextFragment
```

Representerar rubrik.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Heading](#Heading--) | Endast för internt bruk |
| [Heading](#Heading-int-) | Initierar en ny instans av Cell-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | Klona rubriken med alla segment. |
| [deepClone](#deepClone--) | Klona rubriken. |
| [getDestinationPage](#getDestinationPage--) | Hämtar destinationssidan. |
| [getLevel](#getLevel--) | Hämtar nivån. |
| [getStartNumber](#getStartNumber--) | Hämtar rubrikens startnummer. |
| [getStyle](#getStyle--) | Hämtar eller anger stil. |
| [getTocPage](#getTocPage--) | Hämtar sidan som innehåller denna rubrik. |
| [getTop](#getTop--) | Hämtar den övre Y för dessa rubriker (för internt bruk). |
| [getUserLabel](#getUserLabel--) | Hämtar eller anger användarens etikett. |
| [isAutoSequence](#isAutoSequence--) | Hämtar om rubriken ska numreras automatiskt. |
| [isInList](#isInList--) | Hämtar om rubriken ska finnas i innehållsförteckningslistan. |
| [setAutoSequence](#setAutoSequence-boolean-) | Anger att rubriken ska numreras automatiskt. |
| [setDestinationPage](#setDestinationPage-com.aspose.pdf.Page-) | Anger destinationssidan. |
| [setInList](#setInList-boolean-) | Anger att rubriken ska finnas i innehållsförteckningslistan. |
| [setLevel](#setLevel-int-) | Anger nivån. |
| [setStartNumber](#setStartNumber-int-) | Hämtar rubrikens startnummer. Värde: startNumber. |
| [setStyle](#setStyle-com.aspose.pdf.NumberingStyle-) | anger eller anger stil. |
| [setTocPage](#setTocPage-com.aspose.pdf.Page-) | Anger sidan som innehåller denna rubrik. |
| [setTop](#setTop-double-) | Anger den övre Y för dessa rubriker (för internt bruk). |
| [setUserLabel](#setUserLabel-com.aspose.pdf.TextSegment-) | Hämtar eller anger användarens etikett. |

### Heading {#Heading--}
```
public Heading()
```

Endast för internt bruk

### Heading {#Heading-int-}
```
public Heading(int level)
```

Initierar en ny instans av Cell-klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nivå |  | Rubrikens nivå. |

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

Klona rubriken med alla segment.

**Returns:**
Det klonade objektet

### deepClone {#deepClone--}
```
public Object deepClone()
```

Klona rubriken.

**Returns:**
Det klonade objektet

### getDestinationPage {#getDestinationPage--}
```
public Page getDestinationPage()
```

Hämtar destinationssidan.

**Returns:**
Destinationssidan.

### getLevel {#getLevel--}
```
public int getLevel()
```

Hämtar nivån.

**Returns:**
Rubriknivå.

### getStartNumber {#getStartNumber--}
```
public int getStartNumber()
```

Hämtar rubrikens startnummer.

**Returns:**
Värde: startNumber.

### getStyle {#getStyle--}
```
public NumberingStyle getStyle()
```

Hämtar eller anger stil.

**Returns:**
Rubrikstilen.

### getTocPage {#getTocPage--}
```
public Page getTocPage()
```

Hämtar sidan som innehåller denna rubrik.

**Returns:**
Sidan.

### getTop {#getTop--}
```
public double getTop()
```

Hämtar den övre Y för dessa rubriker (för internt bruk).

**Returns:**
Det övre Y-värdet

### getUserLabel {#getUserLabel--}
```
public TextSegment getUserLabel()
```

Hämtar eller anger användarens etikett.

**Returns:**
TextSegment-objekt

### isAutoSequence {#isAutoSequence--}
```
public boolean isAutoSequence()
```

Hämtar om rubriken ska numreras automatiskt.

**Returns:**
IsAutoSequens.

### isInList {#isInList--}
```
public boolean isInList()
```

Hämtar om rubriken ska finnas i innehållsförteckningslistan.

**Returns:**
IsInList.

### setAutoSequence {#setAutoSequence-boolean-}
```
public void setAutoSequence(boolean value)
```

Anger att rubriken ska numreras automatiskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | IsAutoSequens. |

### setDestinationPage {#setDestinationPage-com.aspose.pdf.Page-}
Anger destinationssidan.

### setInList {#setInList-boolean-}
```
public void setInList(boolean value)
```

Anger att rubriken ska finnas i innehållsförteckningslistan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | IsInList. |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

Anger nivån.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | Rubriknivå. |

### setStartNumber {#setStartNumber-int-}
```
public void setStartNumber(int value)
```

Hämtar rubrikens startnummer. Värde: startNumber.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | startNumber. |

### setStyle {#setStyle-com.aspose.pdf.NumberingStyle-}
anger eller anger stil.

### setTocPage {#setTocPage-com.aspose.pdf.Page-}
Anger sidan som innehåller denna rubrik.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Anger den övre Y för dessa rubriker (för internt bruk).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | Det övre Y-värdet |

### setUserLabel {#setUserLabel-com.aspose.pdf.TextSegment-}
Hämtar eller anger användarens etikett.
