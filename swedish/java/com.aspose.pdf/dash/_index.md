---
title: "Dash"
linktitle: "Dash"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar linjestreckmönster."
type: docs
weight: 910
url: /sv/java/com.aspose.pdf/dash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Dash

```
public final class Dash extends Object
```

Klass som representerar linjestreckmönster.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Dash](#Dash-int:A-) | Konstruktor för Dash. Definierar ett mönster av streck och mellanrum som ska användas vid ritning av en streckad ram. |
| [Dash](#Dash-int-int-) | Konstruktor för Dash. Definierar en streckad ram med specificerade streck och mellanrum, som förblir oförändrade för hela den streckade ramen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getOff](#getOff--) | Hämtar eller anger längden på det första gapet mellan strecken. |
| [getOn](#getOn--) | Hämtar eller anger längden på det första strecket. |
| [getPattern](#getPattern--) | Hämtar dash-array som definierar ett mönster av streck och mellanrum som ska användas vid ritning av en streckad ram. |
| [setOff](#setOff-int-) | Hämtar eller anger längden på det första gapet mellan strecken. |
| [setOn](#setOn-int-) | Hämtar eller anger längden på det första strecket. |

### Dash {#Dash-int:A-}
```
public Dash(int[] pattern)
```

Konstruktor för Dash. Definierar ett mönster av streck och mellanrum som ska användas vid ritning av en streckad ram.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mönster |  | En dash-array (minst två värden) som definierar ett mönster av streck och mellanrum som ska användas vid ritning av en streckad ram. |

### Dash {#Dash-int-int-}
```
public Dash(int on, int off)
```

Konstruktor för Dash. Definierar en streckad ram med specificerade streck och mellanrum, som förblir oförändrade för hela den streckade ramen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| på |  | Längd på strecket. |
| av |  | Längd på mellanrummet. |

### getOff {#getOff--}
```
public final int getOff()
```

Hämtar eller anger längden på det första gapet mellan strecken.

**Returns:**
int‑värde

### getOn {#getOn--}
```
public final int getOn()
```

Hämtar eller anger längden på det första strecket.

**Returns:**
int‑värde

### getPattern {#getPattern--}
```
public final int[] getPattern()
```

Hämtar dash-array som definierar ett mönster av streck och mellanrum som ska användas vid ritning av en streckad ram.

**Returns:**
int-array

### setOff {#setOff-int-}
```
public final void setOff(int value)
```

Hämtar eller anger längden på det första gapet mellan strecken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setOn {#setOn-int-}
```
public final void setOn(int value)
```

Hämtar eller anger längden på det första strecket.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |
