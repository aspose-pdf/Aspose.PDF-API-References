---
title: "SaveOptions.MarginPartStyle"
linktitle: "SaveOptions.MarginPartStyle"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar information om en del av marginalen (övre, nedre, vänstra eller högra sidan)."
type: docs
weight: 4420
url: /sv/java/com.aspose.pdf/saveoptions.marginpartstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.MarginPartStyle

```
public static class SaveOptions.MarginPartStyle extends Object
```

Representerar information om en del av marginalen (övre, nedre, vänstra eller högra sidan).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [MarginPartStyle](#MarginPartStyle-boolean-) | Skapar en instans av klassen MarginPartStyle och initierar dess värde i punkter. |
| [MarginPartStyle](#MarginPartStyle-int-) | Skapar en instans av klassen MarginPartStyle och sätter dess värde i punkter. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getValueInPoints](#getValueInPoints--) | Representerar marginal i punkter. Måste vara ett tal större än noll. |
| [isAuto](#isAuto--) | Hämtar eller anger ett värde som indikerar om denna instans är automatisk. Värde: {@code true} om denna instans är automatisk; annars {@code false}. |
| [setAuto](#setAuto-boolean-) | Hämtar eller anger ett värde som indikerar om denna instans är automatisk. Värde: {@code true} om denna instans är automatisk; annars {@code false}. |
| [setValueInPoints](#setValueInPoints-int-) | Representerar marginal i punkter. Måste vara ett tal större än noll. |

### MarginPartStyle {#MarginPartStyle-boolean-}
```
public MarginPartStyle(boolean isAuto)
```

Skapar en instans av klassen MarginPartStyle och initierar dess värde i punkter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isAuto |  | Markera marginal automatiskt |

### MarginPartStyle {#MarginPartStyle-int-}
```
public MarginPartStyle(int valueInPoints)
```

Skapar en instans av klassen MarginPartStyle och sätter dess värde i punkter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| valueInPoints |  | Heltalsvärde i punkter |

### getValueInPoints {#getValueInPoints--}
```
public final int getValueInPoints()
```

Representerar marginal i punkter. Måste vara ett tal större än noll.

**Returns:**
int‑värde

### isAuto {#isAuto--}
```
public final boolean isAuto()
```

Hämtar eller anger ett värde som indikerar om denna instans är automatisk. Värde: {@code true} om denna instans är automatisk; annars {@code false}.

**Returns:**
booleskt värde

### setAuto {#setAuto-boolean-}
```
public final void setAuto(boolean value)
```

Hämtar eller anger ett värde som indikerar om denna instans är automatisk. Värde: {@code true} om denna instans är automatisk; annars {@code false}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setValueInPoints {#setValueInPoints-int-}
```
public final void setValueInPoints(int value)
```

Representerar marginal i punkter. Måste vara ett tal större än noll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |
