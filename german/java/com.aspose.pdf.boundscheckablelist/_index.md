---
title: "com.aspose.pdf.boundscheckablelist"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt BoundsCheckableList – Wrapper um System.Collections.Generic.List dar."
type: docs
weight: 10
url: /de/java/com.aspose.pdf.boundscheckablelist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.boundscheckablelist.BoundsCheckableList<T>

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<T>, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<T>, com.aspose.ms.System.Collections.Generic.IGenericList<T>, com.aspose.ms.System.Collections.IEnumerable<T>, Iterable <T>

```
public class BoundsCheckableList<T extends IBoundsCheckableItem > extends Object implements com.aspose.ms.System.Collections.Generic.IGenericList<T>
```

Stellt BoundsCheckableList – Wrapper um System.Collections.Generic.List dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BoundsCheckableList](#BoundsCheckableList--) | Initialisiert eine neue Instanz der BoundsCheckableList-Klasse. |
| [BoundsCheckableList](#BoundsCheckableList-int-double-double-) | Initialisiert eine neue Instanz der BoundsCheckableList-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addItem](#addItem-T-) | Fügt ein Objekt am Ende der System.Collections.Generic.List hinzu, abhängig vom Parameter "boundsCheckMode". |
| [clear](#clear--) | Entfernt alle Elemente aus der System.Collections.Generic.List. |
| [containsItem](#containsItem-T-) | Bestimmt, ob ein Element in der System.Collections.Generic.List ist. |
| [copyToTArray](#copyToTArray-T:A-int-) | Kopiert die gesamte System.Collections.Generic.List in ein kompatibles eindimensionales Array, beginnend beim angegebenen Index des Zielarrays. |
| [get_Item](#get_Item-int-) | Liest oder setzt einen Absatz aus bzw. in die Sammlung. |
| [indexOfItem](#indexOfItem-T-) | Durchsucht das angegebene Objekt und gibt den nullbasierten Index des ersten Vorkommens in der gesamten System.Collections.Generic.List zurück. |
| [insertItem](#insertItem-int-T-) | Fügt ein Element in die System.Collections.Generic.List an dem angegebenen Index ein. |
| [isReadOnly](#isReadOnly--) | Liest den Wert, der angibt, ob die Sammlung schreibgeschützt ist. |
| [iterator](#iterator--) | Gibt einen Enumerator zurück, der durch die System.Collections.Generic.List iteriert. |
| [removeAt](#removeAt-int-) | Entfernt das Element am angegebenen Index der System.Collections.Generic.List. |
| [removeItem](#removeItem-T-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der System.Collections.Generic.List. |
| [set_Item](#set_Item-int-T-) | Liest oder setzt einen Absatz aus bzw. in die Sammlung. |
| [size](#size--) | Liest die Anzahl der in der System.Collections.Generic.List enthaltenen Elemente. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-) | Aktualisiert den Parameter boundsCheckMode für die initialisierte Sammlung. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-double-double-) | Aktualisiert den Parameter boundsCheckMode für die initialisierte Sammlung. |

### BoundsCheckableList {#BoundsCheckableList--}
```
public BoundsCheckableList()
```

Initialisiert eine neue Instanz der BoundsCheckableList-Klasse.

### BoundsCheckableList {#BoundsCheckableList-int-double-double-}
```
public BoundsCheckableList(int boundsCheckMode, double containerWidth, double containerHeight)
```

Initialisiert eine neue Instanz der BoundsCheckableList-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| boundsCheckMode |  | Der bounds cCheck-Modus. |
| containerWidth |  | Die Containerbreite. |
| containerHeight |  | Die Containerhöhe. |

### addItem {#addItem-T-}
```
public final void addItem( T item)
```

Fügt ein Objekt am Ende der System.Collections.Generic.List hinzu, abhängig vom Parameter "boundsCheckMode".

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Element |  | Das Objekt, das am Ende der System.Collections.Generic.List hinzugefügt werden soll. Der Wert kann für Referenztypen "null" sein. |

### clear {#clear--}
```
public final void clear()
```

Entfernt alle Elemente aus der System.Collections.Generic.List.

### containsItem {#containsItem-T-}
```
public final boolean containsItem( T item)
```

Bestimmt, ob ein Element in der System.Collections.Generic.List ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Element |  | Das Objekt, das in der System.Collections.Generic.List gesucht werden soll. Der Wert kann für Referenztypen null sein. |

**Returns:**
true, wenn itemitem in der System.Collections.Generic.List gefunden wird; andernfalls false.

### copyToTArray {#copyToTArray-T:A-int-}
```
public final void copyToTArray( T [] array, int arrayIndex)
```

Kopiert die gesamte System.Collections.Generic.List in ein kompatibles eindimensionales Array, beginnend beim angegebenen Index des Zielarrays.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Array |  | Das eindimensionale System.Array, das das Ziel der aus der System.Collections.Generic.List kopierten Elemente ist. Das System.Array muss nullbasierte Indizierung haben. |
| arrayIndex |  | Der nullbasierte Index im array, an dem das Kopieren beginnt. |

### get_Item {#get_Item-int-}
```
public final T get_Item(int index)
```

Liest oder setzt einen Absatz aus bzw. in die Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Der Absatzindex. |

**Returns:**
das Element am angegebenen Index.

### indexOfItem {#indexOfItem-T-}
```
public final int indexOfItem( T item)
```

Durchsucht das angegebene Objekt und gibt den nullbasierten Index des ersten Vorkommens in der gesamten System.Collections.Generic.List zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Element |  | Das Objekt, das in der System.Collections.Generic.List gesucht werden soll. Der Wert kann für Referenztypen null sein. |

**Returns:**
Der nullbasierte Index des ersten Vorkommens von itemitem innerhalb der gesamten System.Collections.Generic.List, falls gefunden; andernfalls –1.

### insertItem {#insertItem-int-T-}
```
public final void insertItem(int index, T item)
```

Fügt ein Element in die System.Collections.Generic.List an dem angegebenen Index ein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Der nullbasierte Index, an dem item eingefügt werden soll. |
| Element |  | Das einzufügende Objekt. Der Wert kann für Referenztypen null sein. |

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Liest den Wert, der angibt, ob die Sammlung schreibgeschützt ist.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< T > iterator()
```

Gibt einen Enumerator zurück, der durch die System.Collections.Generic.List iteriert.

**Returns:**
Ein Enumerator für die System.Collections.Generic.List.

### removeAt {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt das Element am angegebenen Index der System.Collections.Generic.List.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Der nullbasierte Index des zu entfernenden Elements. |

### removeItem {#removeItem-T-}
```
public final boolean removeItem( T item)
```

Entfernt das erste Vorkommen eines bestimmten Objekts aus der System.Collections.Generic.List.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Element |  | Das zu entfernende Objekt aus der System.Collections.Generic.List. Der Wert kann für Referenztypen null sein. |

**Returns:**
true, wenn itemitem erfolgreich entfernt wurde; andernfalls false. Diese Methode gibt ebenfalls false zurück, wenn itemitem in der System.Collections.Generic.List nicht gefunden wurde.

### set_Item {#set_Item-int-T-}
```
public final void set_Item(int index, T value)
```

Liest oder setzt einen Absatz aus bzw. in die Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Der Absatzindex. |

### size {#size--}
```
public final int size()
```

Liest die Anzahl der in der System.Collections.Generic.List enthaltenen Elemente.

**Returns:**
Die Anzahl der im System.Collections.Generic.List enthaltenen Elemente.

### updateBoundsCheckMode {#updateBoundsCheckMode-int-}
```
public final void updateBoundsCheckMode(int boundsCheckMode)
```

Aktualisiert den Parameter boundsCheckMode für die initialisierte Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| boundsCheckMode |  | Der Grenzprüfungsmodus. |

### updateBoundsCheckMode {#updateBoundsCheckMode-int-double-double-}
```
public final void updateBoundsCheckMode(int boundsCheckMode, double containerWidth, double containerHeight)
```

Aktualisiert den Parameter boundsCheckMode für die initialisierte Sammlung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| boundsCheckMode |  | Der Grenzprüfungsmodus. |
| containerWidth |  | Die Containerbreite. |
| containerHeight |  | Die Containerhöhe. |
