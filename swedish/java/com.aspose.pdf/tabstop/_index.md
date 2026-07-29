---
title: "TabStop"
linktitle: "TabStop"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en anpassad tabbposition i ett stycke."
type: docs
weight: 4840
url: /sv/java/com.aspose.pdf/tabstop/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TabStop

```
public class TabStop extends Object
```

Representerar en anpassad tabbposition i ett stycke.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TabStop](#TabStop--) | Initierar en ny instans av {@code TabStop}-klassen. |
| [TabStop](#TabStop-float-) | Initierar en ny instans av {@code TabStop}-klassen med angiven position. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAlignmentType](#getAlignmentType--) | Hämtar eller anger ett {@code AlignmentType} enum som indikerar tabbens justeringstyp. |
| [getLeaderType](#getLeaderType--) | Hämtar eller anger ett {@code TabLeaderType} enum som indikerar tabbens ledartyp. |
| [getPosition](#getPosition--) | Hämtar eller anger ett float‑värde som indikerar tabbpositionen. |
| [isReadOnly](#isReadOnly--) | Hämtar värde som indikerar att denna {@code TabStop}-instans redan är bifogad till {@code TextFragment} och har blivit skrivskyddad. |
| [setAlignmentType](#setAlignmentType-int-) | Hämtar eller anger ett {@code AlignmentType} enum som indikerar tabbens justeringstyp. |
| [setLeaderType](#setLeaderType-int-) | Hämtar eller anger ett {@code TabLeaderType} enum som indikerar tabbens ledartyp. |
| [setPosition](#setPosition-float-) | Anger ett float‑värde som indikerar tabbpositionen. |

### TabStop {#TabStop--}
```
public TabStop()
```

Initierar en ny instans av {@code TabStop}-klassen.

### TabStop {#TabStop-float-}
```
public TabStop(float position)
```

Initierar en ny instans av {@code TabStop}-klassen med angiven position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position |  | Positionen för tabbstoppet. |

### getAlignmentType {#getAlignmentType--}
```
public int getAlignmentType()
```

Hämtar eller anger ett {@code AlignmentType} enum som indikerar tabbens justeringstyp.

**Returns:**
TabAlignmentType‑element @see TabAlignmentType

### getLeaderType {#getLeaderType--}
```
public int getLeaderType()
```

Hämtar eller anger ett {@code TabLeaderType} enum som indikerar tabbens ledartyp.

**Returns:**
TabLeaderType element @see TabLeaderType

### getPosition {#getPosition--}
```
public float getPosition()
```

Hämtar eller anger ett float‑värde som indikerar tabbpositionen.

**Returns:**
flyttalsvärde

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Hämtar värde som indikerar att denna {@code TabStop}-instans redan är bifogad till {@code TextFragment} och har blivit skrivskyddad.

**Returns:**
booleskt värde

### setAlignmentType {#setAlignmentType-int-}
```
public void setAlignmentType(int value)
```

Hämtar eller anger ett {@code AlignmentType} enum som indikerar tabbens justeringstyp.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | TabAlignmentType‑element @see TabAlignmentType |

### setLeaderType {#setLeaderType-int-}
```
public void setLeaderType(int value)
```

Hämtar eller anger ett {@code TabLeaderType} enum som indikerar tabbens ledartyp.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | TabLeaderType element @see TabLeaderType |

### setPosition {#setPosition-float-}
```
public void setPosition(float value)
```

Anger ett float‑värde som indikerar tabbpositionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |
