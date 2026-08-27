---
title: "ActionCollection"
linktitle: "ActionCollection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Sammlung von Aktionen"
type: docs
weight: 40
url: /de/java/com.aspose.pdf/actioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ActionCollection

**All Implemented Interfaces:**
Iterable < PdfAction >

```
public final class ActionCollection extends Object implements Iterable < PdfAction >
```

Sammlung von Aktionen

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.PdfAction-) | Fügt eine neue Aktion zur Sammlung hinzu. |
| [clear](#clear--) | Sammlung leeren. |
| [contains](#contains-com.aspose.pdf.PdfAction-) | Noch nicht unterstützt. Gibt true zurück, wenn das angegebene Element in der Sammlung vorhanden ist. |
| [copyTo](#copyTo-com.aspose.pdf.PdfAction:A-int-) | Kopiert das Aktions-Array in die Sammlung. |
| [delete](#delete--) | Alle Aktionen löschen. |
| [delete](#delete-int-) | Entfernt eine Aktion aus der Sammlung nach Index. |
| [get_Item](#get_Item-int-) | Gibt die Aktion nach ihrem Index zurück. |
| [getSyncRoot](#getSyncRoot--) | Liefert das Synchronisationsobjekt. |
| [isReadOnly](#isReadOnly--) | Gibt true zurück, wenn die Sammlung schreibgeschützt ist. |
| [isSynchronized](#isSynchronized--) | Gibt true zurück, wenn das Objekt synchronisiert ist. |
| [iterator](#iterator--) | / * / * Gibt Enumerator für die Sammlung zurück. / * / * / * |
| [remove](#remove-com.aspose.pdf.PdfAction-) | * Noch nicht unterstützt. Entfernt Element aus der Sammlung. |
| [size](#size--) | Anzahl der Aktionen in der Sammlung. |

### add {#add-com.aspose.pdf.PdfAction-}
Fügt eine neue Aktion zur Sammlung hinzu.

### clear {#clear--}
```
public void clear()
```

Sammlung leeren.

### contains {#contains-com.aspose.pdf.PdfAction-}
Noch nicht unterstützt. Gibt true zurück, wenn das angegebene Element in der Sammlung vorhanden ist.

### copyTo {#copyTo-com.aspose.pdf.PdfAction:A-int-}
Kopiert das Aktions-Array in die Sammlung.

### delete {#delete--}
```
public void delete()
```

Alle Aktionen löschen.

### delete {#delete-int-}
```
public void delete(int index)
```

Entfernt eine Aktion aus der Sammlung nach Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index der zu entfernenden Aktion. |

### get_Item {#get_Item-int-}
```
public PdfAction get_Item(int index)
```

Gibt die Aktion nach ihrem Index zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index der Aktion. |

**Returns:**
Abgerufene Aktion.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Liefert das Synchronisationsobjekt.

**Returns:**
Objektwert

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Gibt true zurück, wenn die Sammlung schreibgeschützt ist.

**Returns:**
boolescher Wert

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Gibt true zurück, wenn das Objekt synchronisiert ist.

**Returns:**
boolescher Wert

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< PdfAction > iterator()
```

/ * / * Gibt Enumerator für die Sammlung zurück. / * / * / *

**Returns:**
Sammlungs-Enumerator. /

### remove {#remove-com.aspose.pdf.PdfAction-}
* Not supported yet. Removes item from collection.

### size {#size--}
```
public int size()
```

Anzahl der Aktionen in der Sammlung.

**Returns:**
int-Wert
