---
title: "TabStop"
linktitle: "TabStop"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine benutzerdefinierte Tab‑Stopp‑Position in einem Absatz dar."
type: docs
weight: 4840
url: /de/java/com.aspose.pdf/tabstop/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TabStop

```
public class TabStop extends Object
```

Stellt eine benutzerdefinierte Tab‑Stopp‑Position in einem Absatz dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TabStop](#TabStop--) | Initialisiert eine neue Instanz der {@code TabStop}-Klasse. |
| [TabStop](#TabStop-float-) | Initialisiert eine neue Instanz der {@code TabStop}-Klasse mit angegebener Position. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAlignmentType](#getAlignmentType--) | Liest oder setzt ein {@code AlignmentType}-Enum, das den Tab-Ausrichtungstyp angibt. |
| [getLeaderType](#getLeaderType--) | Liest oder setzt ein {@code TabLeaderType}-Enum, das den Tab-Leader-Typ angibt. |
| [getPosition](#getPosition--) | Liest oder setzt einen Float-Wert, der die Position des Tab-Stops angibt. |
| [isReadOnly](#isReadOnly--) | Liest den Wert, der anzeigt, dass diese {@code TabStop}-Instanz bereits an {@code TextFragment} angehängt ist und schreibgeschützt wurde. |
| [setAlignmentType](#setAlignmentType-int-) | Liest oder setzt ein {@code AlignmentType}-Enum, das den Tab-Ausrichtungstyp angibt. |
| [setLeaderType](#setLeaderType-int-) | Liest oder setzt ein {@code TabLeaderType}-Enum, das den Tab-Leader-Typ angibt. |
| [setPosition](#setPosition-float-) | Setzt einen Float-Wert, der die Position des Tab-Stops angibt. |

### TabStop {#TabStop--}
```
public TabStop()
```

Initialisiert eine neue Instanz der {@code TabStop}-Klasse.

### TabStop {#TabStop-float-}
```
public TabStop(float position)
```

Initialisiert eine neue Instanz der {@code TabStop}-Klasse mit angegebener Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Position |  | Die Position des Tabstopps. |

### getAlignmentType {#getAlignmentType--}
```
public int getAlignmentType()
```

Liest oder setzt ein {@code AlignmentType}-Enum, das den Tab-Ausrichtungstyp angibt.

**Returns:**
TabAlignmentType-Element @see TabAlignmentType

### getLeaderType {#getLeaderType--}
```
public int getLeaderType()
```

Liest oder setzt ein {@code TabLeaderType}-Enum, das den Tab-Leader-Typ angibt.

**Returns:**
TabLeaderType Element @see TabLeaderType

### getPosition {#getPosition--}
```
public float getPosition()
```

Liest oder setzt einen Float-Wert, der die Position des Tab-Stops angibt.

**Returns:**
float-Wert

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Liest den Wert, der anzeigt, dass diese {@code TabStop}-Instanz bereits an {@code TextFragment} angehängt ist und schreibgeschützt wurde.

**Returns:**
boolescher Wert

### setAlignmentType {#setAlignmentType-int-}
```
public void setAlignmentType(int value)
```

Liest oder setzt ein {@code AlignmentType}-Enum, das den Tab-Ausrichtungstyp angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | TabAlignmentType-Element @see TabAlignmentType |

### setLeaderType {#setLeaderType-int-}
```
public void setLeaderType(int value)
```

Liest oder setzt ein {@code TabLeaderType}-Enum, das den Tab-Leader-Typ angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | TabLeaderType Element @see TabLeaderType |

### setPosition {#setPosition-float-}
```
public void setPosition(float value)
```

Setzt einen Float-Wert, der die Position des Tab-Stops angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |
