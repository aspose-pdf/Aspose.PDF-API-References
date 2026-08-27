---
title: "GraphicElementCollection"
linktitle: "GraphicElementCollection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt die {@link GraphicElement}-Sammlung bereit."
type: docs
weight: 20
url: /de/java/com.aspose.pdf.vector/graphicelementcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElementCollection

**All Implemented Interfaces:**
Iterable < GraphicElement >

```
public final class GraphicElementCollection extends Object implements Iterable < GraphicElement >
```

Stellt die {@link GraphicElement}-Sammlung bereit.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GraphicElementCollection](#GraphicElementCollection--) | Initialisiert die neue Sammlung. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.vector.GraphicElement-) | Fügt ein neues {@link GraphicElement} zur Sammlung hinzu. Alle Elemente in der Sammlung müssen denselben {@code GraphicElement.Parent}({@link GraphicElement#getParent}) haben. |
| [clear](#clear--) | Leert die Sammlung. |
| [contains](#contains-com.aspose.pdf.vector.GraphicElement-) | Bestimmt, ob ein Element in der Sammlung ist. |
| [copyTo](#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-) | Kopiert die gesamte Sammlung in ein kompatibles eindimensionales Array, beginnend beim angegebenen Index des Zielarrays. |
| [get_Item](#get_Item-int-) | Gibt das {@link GraphicElement}-Element am angegebenen Index zurück. |
| [isReadOnly](#isReadOnly--) | Gibt einen Wert zurück, der angibt, ob die Sammlung schreibgeschützt ist. Gibt immer false zurück. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Gibt einen Enumerator für die gesamte Sammlung zurück. |
| [iterator](#iterator--) | Gibt einen Enumerator für die gesamte Sammlung zurück. |
| [remove](#remove-com.aspose.pdf.vector.GraphicElement-) | Löscht das {@link GraphicElement}-Element. |
| [size](#size--) | Gibt die Anzahl der tatsächlich in der Sammlung enthaltenen {@link GraphicElement}-Objektelemente zurück. |
| [toList](#toList--) | Gibt die innere Sammlung für uneingeschränkte Aufzählung zurück. |
| [toString](#toString--) | Gibt eine Zeichenkettenrepräsentation dieser Sammlung zurück. |

### GraphicElementCollection {#GraphicElementCollection--}
```
public GraphicElementCollection()
```

Initialisiert die neue Sammlung.

### add {#add-com.aspose.pdf.vector.GraphicElement-}
Fügt ein neues {@link GraphicElement} zur Sammlung hinzu. Alle Elemente in der Sammlung müssen denselben {@code GraphicElement.Parent}({@link GraphicElement#getParent}) haben.

### clear {#clear--}
```
public final void clear()
```

Leert die Sammlung.

### contains {#contains-com.aspose.pdf.vector.GraphicElement-}
Bestimmt, ob ein Element in der Sammlung ist.

### copyTo {#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-}
Kopiert die gesamte Sammlung in ein kompatibles eindimensionales Array, beginnend beim angegebenen Index des Zielarrays.

### get_Item {#get_Item-int-}
```
public final GraphicElement get_Item(int index)
```

Gibt das {@link GraphicElement}-Element am angegebenen Index zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index innerhalb der Sammlung. |

**Returns:**
{@link GraphicElement}.

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Gibt einen Wert zurück, der angibt, ob die Sammlung schreibgeschützt ist. Gibt immer false zurück.

**Returns:**
boolescher Wert

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public final com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Gibt einen Enumerator für die gesamte Sammlung zurück.

**Returns:**
Enumerator-Objekt.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< GraphicElement > iterator()
```

Gibt einen Enumerator für die gesamte Sammlung zurück.

**Returns:**
Enumerator-Objekt.

### remove {#remove-com.aspose.pdf.vector.GraphicElement-}
Löscht das {@link GraphicElement}-Element.

### size {#size--}
```
public final int size()
```

Gibt die Anzahl der tatsächlich in der Sammlung enthaltenen {@link GraphicElement}-Objektelemente zurück.

**Returns:**
int-Wert

### toList {#toList--}
```
public final com.aspose.ms.System.Collections.Generic.List< GraphicElement > toList()
```

Gibt die innere Sammlung für uneingeschränkte Aufzählung zurück.

**Returns:**
Innere Liste

### toString {#toString--}
```
public String toString()
```

Gibt eine Zeichenkettenrepräsentation dieser Sammlung zurück.

**Returns:**
Die Zeichenkette.
