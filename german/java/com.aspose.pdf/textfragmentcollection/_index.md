---
title: "TextFragmentCollection"
linktitle: "TextFragmentCollection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Sammlung von Textfragmenten dar"
type: docs
weight: 5130
url: /de/java/com.aspose.pdf/textfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextFragmentCollection

**All Implemented Interfaces:**
Iterable < TextFragment >

```
public final class TextFragmentCollection extends Object implements Iterable < TextFragment >
```

Stellt eine Sammlung von Textfragmenten dar

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.TextFragment-) | Fügt das Textfragment-Element an der angegebenen Position ein. |
| [clear](#clear--) | Löscht alle Elemente aus der Sammlung. |
| [contains](#contains-com.aspose.pdf.TextFragment-) | Bestimmt, ob die Sammlung einen bestimmten Wert enthält. |
| [copyTo](#copyTo-com.aspose.pdf.TextFragment:A-int-) | / * / * Gibt einen Enumerator für die gesamte Sammlung zurück. / * / * |
| [get_Item](#get_Item-int-) | Liefert das Textfragment-Element am angegebenen Index. Der Index sollte im Bereich [1..n] liegen, wobei n der Anzahl der Textfragmente entspricht. |
| [getSyncRoot](#getSyncRoot--) | Liefert ein Objekt, das zur Synchronisation des Zugriffs auf die Sammlung verwendet werden kann. |
| [isReadOnly](#isReadOnly--) | Liefert einen Wert, der angibt, ob die Sammlung schreibgeschützt ist |
| [isSynchronized](#isSynchronized--) | Liefert einen Wert, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread‑sicher) ist. |
| [iterator](#iterator--) | Gibt einen Enumerator für die gesamte Sammlung zurück. |
| [remove](#remove-com.aspose.pdf.TextFragment-) | Löscht das angegebene Element aus der Sammlung. |
| [size](#size--) | Liefert die Anzahl der {@code TextFragment}-Objektelemente, die tatsächlich in der Sammlung enthalten sind. |

### add {#add-com.aspose.pdf.TextFragment-}
Fügt das Textfragment-Element an der angegebenen Position ein.

### clear {#clear--}
```
public void clear()
```

Löscht alle Elemente aus der Sammlung.

### contains {#contains-com.aspose.pdf.TextFragment-}
Bestimmt, ob die Sammlung einen bestimmten Wert enthält.

### copyTo {#copyTo-com.aspose.pdf.TextFragment:A-int-}
/ * / * Gibt einen Enumerator für die gesamte Sammlung zurück. / * / *

### get_Item {#get_Item-int-}
```
public TextFragment get_Item(int index)
```

Liefert das Textfragment-Element am angegebenen Index. Der Index sollte im Bereich [1..n] liegen, wobei n der Anzahl der Textfragmente entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index innerhalb der Sammlung. |

**Returns:**
TextFragment-Objekt.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Liefert ein Objekt, das zur Synchronisation des Zugriffs auf die Sammlung verwendet werden kann.

**Returns:**
Objektelement

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Liefert einen Wert, der angibt, ob die Sammlung schreibgeschützt ist

**Returns:**
boolescher Wert

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Liefert einen Wert, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread‑sicher) ist.

**Returns:**
boolescher Wert

### iterator {#iterator--}
```
public Iterator < TextFragment > iterator()
```

Gibt einen Enumerator für die gesamte Sammlung zurück.

**Returns:**
Enumerator-Objekt.

### remove {#remove-com.aspose.pdf.TextFragment-}
Löscht das angegebene Element aus der Sammlung.

### size {#size--}
```
public int size()
```

Liefert die Anzahl der {@code TextFragment}-Objektelemente, die tatsächlich in der Sammlung enthalten sind.

**Returns:**
int-Wert
