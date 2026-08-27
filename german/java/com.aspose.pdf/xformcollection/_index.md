---
title: "XFormCollection"
linktitle: "XFormCollection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse stellt eine Sammlung von XFormCollection dar."
type: docs
weight: 5600
url: /de/java/com.aspose.pdf/xformcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFormCollection

**All Implemented Interfaces:**
Iterable < XForm >

```
public final class XFormCollection extends Object implements Iterable < XForm >
```

Klasse stellt eine Sammlung von XFormCollection dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.XForm-) | Fügt ein neues XForm zur Sammlung hinzu. |
| [clear](#clear--) | Löscht alle Elemente aus der Sammlung. |
| [contains](#contains-com.aspose.pdf.XForm-) | Bestimmt, ob die Sammlung einen bestimmten Wert enthält. |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | Kopiert XFormCollection in die Sammlung. |
| [delete](#delete--) | Löscht alle XForms aus der Sammlung. |
| [delete](#delete-int-) | Lösche XForm aus der Sammlung |
| [delete](#delete-java.lang.String-) | Löscht alle XForms aus der Sammlung. |
| [freeMemory](#freeMemory--) | Löscht zwischengespeicherte Daten, gibt Speicher frei usw. |
| [get_Item](#get_Item-int-) | Gibt XForm nach Index zurück. |
| [get_Item](#get_Item-java.lang.String-) | Gibt XForm nach seinem Namen zurück. Eine Ausnahme wird ausgelöst, wenn kein XForm mit dem angegebenen Namen gefunden wird. |
| [getFormName](#getFormName-com.aspose.pdf.XForm-) | Gibt den Namen des Formulars in dieser Formsammlung zurück |
| [getSyncRoot](#getSyncRoot--) | Synchronisationsobjekt. |
| [hasForm](#hasForm-java.lang.String-) |  |
| [isReadOnly](#isReadOnly--) | Ermittelt einen Wert, der angibt, ob die Sammlung schreibgeschützt ist. |
| [isSynchronized](#isSynchronized--) | Gibt true zurück, wenn das Objekt synchronisiert ist. |
| [iterator](#iterator--) | Gibt den Sammlungsenumerator zurück. |
| [remove](#remove-com.aspose.pdf.XForm-) | Löscht das angegebene Element aus der Sammlung. |
| [size](#size--) | Ermittelt die Anzahl der XForms in der Sammlung. |

### add {#add-com.aspose.pdf.XForm-}
Fügt ein neues XForm zur Sammlung hinzu.

### clear {#clear--}
```
public void clear()
```

Löscht alle Elemente aus der Sammlung.

### contains {#contains-com.aspose.pdf.XForm-}
Bestimmt, ob die Sammlung einen bestimmten Wert enthält.

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
Kopiert XFormCollection in die Sammlung.

### delete {#delete--}
```
public void delete()
```

Löscht alle XForms aus der Sammlung.

### delete {#delete-int-}
```
public void delete(int index)
```

Lösche XForm aus der Sammlung

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index des zu löschenden XForm |

### delete {#delete-java.lang.String-}
Löscht alle XForms aus der Sammlung.

### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

Löscht zwischengespeicherte Daten, gibt Speicher frei usw.

### get_Item {#get_Item-int-}
```
public XForm get_Item(int index)
```

Gibt XForm nach Index zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index der XFormCollection. Die Nummerierung der XForms beginnt bei 1 |

**Returns:**
Abgerufenes XForm

### get_Item {#get_Item-java.lang.String-}
Gibt XForm nach seinem Namen zurück. Eine Ausnahme wird ausgelöst, wenn kein XForm mit dem angegebenen Namen gefunden wird.

### getFormName {#getFormName-com.aspose.pdf.XForm-}
Gibt den Namen des Formulars in dieser Formsammlung zurück

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Synchronisationsobjekt.

**Returns:**
Object

### hasForm {#hasForm-java.lang.String-}


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

Gibt true zurück, wenn das Objekt synchronisiert ist.

**Returns:**
boolean

### iterator {#iterator--}
```
public Iterator < XForm > iterator()
```

Gibt den Sammlungsenumerator zurück.

**Returns:**
Enumerator für die Sammlung

### remove {#remove-com.aspose.pdf.XForm-}
Löscht das angegebene Element aus der Sammlung.

### size {#size--}
```
public int size()
```

Ermittelt die Anzahl der XForms in der Sammlung.

**Returns:**
int-Wert
