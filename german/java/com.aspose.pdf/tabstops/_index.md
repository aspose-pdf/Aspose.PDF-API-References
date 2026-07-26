---
title: "TabStops"
linktitle: "TabStops"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Sammlung von {@code TabStop}-Objekten dar."
type: docs
weight: 4850
url: /de/java/com.aspose.pdf/tabstops/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TabStops

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class TabStops extends Object implements com.aspose.ms.System.ICloneable
```

Stellt eine Sammlung von {@code TabStop}-Objekten dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TabStops](#TabStops--) | Initialisiert eine neue Instanz der {@code TabStops} Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add--) | Initialisiert eine neue Instanz der {@code TabStop} Klasse und fügt sie zur TabStops-Sammlung hinzu. |
| [add](#add-float-) | Initialisiert eine neue Instanz der {@code TabStop} Klasse mit angegebener Position und fügt sie zur TabStops-Sammlung hinzu. |
| [add](#add-float-int-) | Initialisiert eine neue Instanz der {@code TabStop} Klasse mit angegebener Position und Führungszeichen und fügt sie zur TabStops-Sammlung hinzu. |
| [add](#add-com.aspose.pdf.TabStop-) | Initialisiert eine neue Instanz der {@code TabStop} Klasse und fügt sie zur TabStops-Sammlung hinzu. |
| [deepClone](#deepClone--) | Klont ein neues {@code TabStops} Objekt. |
| [get_Item](#get_Item-int-) | Ruft ein {@code TabStop} Objekt aus der Sammlung gemäß TabStop-Index ab. |
| [getCount](#getCount--) | Gibt die Anzahl der TabStops zurück |
| [isReadOnly](#isReadOnly--) | Ermittelt den Wert, der anzeigt, dass diese {@code TabStops}-Instanz bereits an {@code TextFragment} angehängt ist und schreibgeschützt wurde. |
| [set_Item](#set_Item-int-com.aspose.pdf.TabStop-) | Setzt ein {@code TabStop}-Objekt aus der Sammlung gemäß dem TabStop-Index. |

### TabStops {#TabStops--}
```
public TabStops()
```

Initialisiert eine neue Instanz der {@code TabStops} Klasse.

### add {#add--}
```
public TabStop add()
```

Initialisiert eine neue Instanz der {@code TabStop} Klasse und fügt sie zur TabStops-Sammlung hinzu.

**Returns:**
Das neue {@code TabStop}-Objekt.

### add {#add-float-}
```
public TabStop add(float position)
```

Initialisiert eine neue Instanz der {@code TabStop} Klasse mit angegebener Position und fügt sie zur TabStops-Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position |  | Die Position des Tabstopps. |

**Returns:**
Das neue {@code TabStop}-Objekt.

### add {#add-float-int-}
```
public TabStop add(float position, int leaderType)
```

Initialisiert eine neue Instanz der {@code TabStop} Klasse mit angegebener Position und Führungszeichen und fügt sie zur TabStops-Sammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position |  | Die Position des Tabstopps. |
| leaderType |  | Der Leader-Typ des Tabstopps. |

**Returns:**
Das neue {@code TabStop}-Objekt.

### add {#add-com.aspose.pdf.TabStop-}
Initialisiert eine neue Instanz der {@code TabStop} Klasse und fügt sie zur TabStops-Sammlung hinzu.

**Returns:**
Das neue {@code TabStop}-Objekt.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Klont ein neues {@code TabStops} Objekt.

**Returns:**
Das neue {@code TabStops}-Objekt.

### get_Item {#get_Item-int-}
```
public TabStop get_Item(int index)
```

Ruft ein {@code TabStop} Objekt aus der Sammlung gemäß TabStop-Index ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Nullbasierter Index des Elements in der {@code TabStops}-Sammlung. |

**Returns:**
{@code TabStop}-Objekt.

### getCount {#getCount--}
```
public int getCount()
```

Gibt die Anzahl der TabStops zurück

**Returns:**
int-Wert

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Ermittelt den Wert, der anzeigt, dass diese {@code TabStops}-Instanz bereits an {@code TextFragment} angehängt ist und schreibgeschützt wurde.

**Returns:**
boolescher Wert

### set_Item {#set_Item-int-com.aspose.pdf.TabStop-}
Setzt ein {@code TabStop}-Objekt aus der Sammlung gemäß dem TabStop-Index.
