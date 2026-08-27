---
title: "OutlineCollection"
linktitle: "OutlineCollection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt die Dokumenten-Gliederungshierarchie dar."
type: docs
weight: 3260
url: /de/java/com.aspose.pdf/outlinecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineCollection extends Outlines
```

Stellt die Dokumenten-Gliederungshierarchie dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | Fügt ein Gliederungselement zur Sammlung hinzu. |
| [clear](#clear--) | Löscht alle Elemente aus der Sammlung. |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | Noch nicht unterstützt. Prüft, ob die Sammlung das angegebene Element enthält. |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | Kopiert die Gliederungselemente in ein System.Array, beginnend bei einem bestimmten System.Array-Index. |
| [delete](#delete--) | Löscht alle Gliederungselemente aus der Dokumenten-Gliederung. |
| [delete](#delete-java.lang.String-) | Löscht alle Gliederungselemente aus der Dokumenten-Gliederung. |
| [get_Item](#get_Item-int-) | Ruft das Gliederungselement aus der Sammlung nach Index ab. |
| [getFirst](#getFirst--) | Ruft ein Gliederungselement ab, das das erste Element der obersten Ebene in der Gliederung darstellt. |
| [getLast](#getLast--) | Ruft ein Gliederungselement ab, das das letzte Element der obersten Ebene in der Gliederung darstellt. |
| [getSyncRoot](#getSyncRoot--) | Ruft ein Objekt ab, das verwendet werden kann, um den Zugriff auf diese Sammlung zu synchronisieren. |
| [getVisibleCount](#getVisibleCount--) | Count ist die Summe der Anzahl sichtbarer untergeordneter Gliederungselemente auf allen Ebenen. Hinweis: Bitte nicht mit Count verwechseln, das die Anzahl der Elemente in der Sammlung ist. |
| [hasNext](#hasNext--) |  |
| [isReadOnly](#isReadOnly--) | Ermittelt einen Wert, der angibt, ob die Sammlung schreibgeschützt ist. |
| [isSynchronized](#isSynchronized--) | Ruft einen Wert ab, der angibt, ob der Zugriff auf diese Sammlung synchronisiert (thread‑sicher) ist. |
| [iterator](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [next](#next--) |  |
| [remove](#remove-int-) | Entfernt ein Element nach Index. |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | Noch nicht unterstützt. Wirft immer eine Ausnahme. |
| [size](#size--) | Ruft die Gesamtzahl der Gliederungselemente (Lesezeichen) auf allen Ebenen der Dokumenten‑Gliederung ab. |

### add {#add-com.aspose.pdf.OutlineItemCollection-}
Fügt ein Gliederungselement zur Sammlung hinzu.

### clear {#clear--}
```
public void clear()
```

Löscht alle Elemente aus der Sammlung.

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
Noch nicht unterstützt. Prüft, ob die Sammlung das angegebene Element enthält.

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
Kopiert die Gliederungselemente in ein System.Array, beginnend bei einem bestimmten System.Array-Index.

### delete {#delete--}
```
public void delete()
```

Löscht alle Gliederungselemente aus der Dokumenten-Gliederung.

### delete {#delete-java.lang.String-}
Löscht alle Gliederungselemente aus der Dokumenten-Gliederung.

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

Ruft das Gliederungselement aus der Sammlung nach Index ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index des angeforderten Elements. |

**Returns:**
OutlineItemCollection-Objekt

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

Ruft ein Gliederungselement ab, das das erste Element der obersten Ebene in der Gliederung darstellt.

**Returns:**
OutlineItemCollection-Objekt

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

Ruft ein Gliederungselement ab, das das letzte Element der obersten Ebene in der Gliederung darstellt.

**Returns:**
OutlineItemCollection-Objekt

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Ruft ein Objekt ab, das verwendet werden kann, um den Zugriff auf diese Sammlung zu synchronisieren.

**Returns:**
Objekt für Synchronisation

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

Count ist die Summe der Anzahl sichtbarer untergeordneter Gliederungselemente auf allen Ebenen. Hinweis: Bitte nicht mit Count verwechseln, das die Anzahl der Elemente in der Sammlung ist.

**Returns:**
int-Wert

### hasNext {#hasNext--}
```
public boolean hasNext()
```



### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Ermittelt einen Wert, der angibt, ob die Sammlung schreibgeschützt ist.

**Returns:**
boolescher Wert

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Ruft einen Wert ab, der angibt, ob der Zugriff auf diese Sammlung synchronisiert (thread‑sicher) ist.

**Returns:**
boolescher Wert

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Returns:**
Ein System.Collections.IEnumerator-Objekt, das verwendet werden kann, um die Sammlung zu durchlaufen.

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

Entfernt ein Element nach Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index des zu entfernenden Elements. |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
Noch nicht unterstützt. Wirft immer eine Ausnahme.

### size {#size--}
```
public int size()
```

Ruft die Gesamtzahl der Gliederungselemente (Lesezeichen) auf allen Ebenen der Dokumenten‑Gliederung ab.

**Returns:**
int-Wert
