---
title: "TabStops"
linktitle: "TabStops"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en samling av {@code TabStop}-objekt."
type: docs
weight: 4850
url: /sv/java/com.aspose.pdf/tabstops/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TabStops

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class TabStops extends Object implements com.aspose.ms.System.ICloneable
```

Representerar en samling av {@code TabStop}-objekt.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TabStops](#TabStops--) | Initierar en ny instans av klassen {@code TabStops}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add--) | Initierar en ny instans av klassen {@code TabStop} och lägger till den i TabStops-samlingen. |
| [add](#add-float-) | Initierar en ny instans av klassen {@code TabStop} med angiven position och lägger till den i TabStops-samlingen. |
| [add](#add-float-int-) | Initierar en ny instans av klassen {@code TabStop} med angiven position och ledartyp och lägger till den i TabStops-samlingen. |
| [add](#add-com.aspose.pdf.TabStop-) | Initierar en ny instans av klassen {@code TabStop} och lägger till den i TabStops-samlingen. |
| [deepClone](#deepClone--) | Klonar nya {@code TabStops}-objekt. |
| [get_Item](#get_Item-int-) | Hämtar ett {@code TabStop}-objekt från samlingen enligt TabStop-index. |
| [getCount](#getCount--) | Returnerar tabStops Count |
| [isReadOnly](#isReadOnly--) | Hämtar värde som indikerar att detta {@code TabStops} instans redan är bifogad till {@code TextFragment} och har blivit skrivskyddad. |
| [set_Item](#set_Item-int-com.aspose.pdf.TabStop-) | Ställer in ett {@code TabStop} objekt från samlingen enligt TabStop-index. |

### TabStops {#TabStops--}
```
public TabStops()
```

Initierar en ny instans av klassen {@code TabStops}.

### add {#add--}
```
public TabStop add()
```

Initierar en ny instans av klassen {@code TabStop} och lägger till den i TabStops-samlingen.

**Returns:**
Det nya {@code TabStop} objektet.

### add {#add-float-}
```
public TabStop add(float position)
```

Initierar en ny instans av klassen {@code TabStop} med angiven position och lägger till den i TabStops-samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position |  | Positionen för tabbstoppet. |

**Returns:**
Det nya {@code TabStop} objektet.

### add {#add-float-int-}
```
public TabStop add(float position, int leaderType)
```

Initierar en ny instans av klassen {@code TabStop} med angiven position och ledartyp och lägger till den i TabStops-samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position |  | Positionen för tabbstoppet. |
| leaderType |  | Ledartypen för tabbstoppet. |

**Returns:**
Det nya {@code TabStop} objektet.

### add {#add-com.aspose.pdf.TabStop-}
Initierar en ny instans av klassen {@code TabStop} och lägger till den i TabStops-samlingen.

**Returns:**
Det nya {@code TabStop} objektet.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Klonar nya {@code TabStops}-objekt.

**Returns:**
Det nya {@code TabStops} objektet.

### get_Item {#get_Item-int-}
```
public TabStop get_Item(int index)
```

Hämtar ett {@code TabStop}-objekt från samlingen enligt TabStop-index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Nollbaserat index för element i {@code TabStops} samlingen. |

**Returns:**
{@code TabStop} objekt.

### getCount {#getCount--}
```
public int getCount()
```

Returnerar tabStops Count

**Returns:**
int‑värde

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Hämtar värde som indikerar att detta {@code TabStops} instans redan är bifogad till {@code TextFragment} och har blivit skrivskyddad.

**Returns:**
booleskt värde

### set_Item {#set_Item-int-com.aspose.pdf.TabStop-}
Ställer in ett {@code TabStop} objekt från samlingen enligt TabStop-index.
