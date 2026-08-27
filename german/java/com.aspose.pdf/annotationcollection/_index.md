---
title: "AnnotationCollection"
linktitle: "AnnotationCollection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die eine Annotationssammlung darstellt."
type: docs
weight: 80
url: /de/java/com.aspose.pdf/annotationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationCollection

**All Implemented Interfaces:**
Iterable < Annotation >

```
public final class AnnotationCollection extends Object implements Iterable < Annotation >
```

Klasse, die eine Annotationssammlung darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [AnnotationCollection](#AnnotationCollection-com.aspose.pdf.Page-) | Konstruktor von AnnotationCollection. Erstellt eine Annotationssammlung für Anmerkungen auf der angegebenen Seite. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Akzeptiert Besucher, um die Annotation zu verarbeiten. |
| [add](#add-com.aspose.pdf.Annotation-) | Fügt der Sammlung eine Annotation hinzu. |
| [add](#add-com.aspose.pdf.Annotation-boolean-) | Fügt der Sammlung eine Annotation hinzu. Wenn die Seite gedreht ist, wird das Annotationsrechteck entsprechend neu berechnet. |
| [clear](#clear--) | Löscht alle Anmerkungen aus der Sammlung. |
| [contains](#contains-com.aspose.pdf.Annotation-) | Prüft, ob die angegebene Annotation zur Sammlung gehört. |
| [copyTo](#copyTo-com.aspose.pdf.Annotation:A-int-) | Kopiert ein Array von Anmerkungen in die Sammlung. |
| [delete](#delete--) | Löscht alle Anmerkungen aus der Sammlung. |
| [delete](#delete-com.aspose.pdf.Annotation-) | Löscht alle Anmerkungen aus der Sammlung. |
| [delete](#delete-int-) | Löscht die Annotation aus der Sammlung anhand des Index. |
| [findByName](#findByName-java.lang.String-) | Gibt die Annotation anhand ihres Namens zurück. |
| [get_Item](#get_Item-int-) | Der Index des abzurufenden Elements. |
| [getSyncRoot](#getSyncRoot--) | Liefert ein Objekt, das zur Synchronisation des Zugriffs auf com.aspose.pdf.AnnotationCollection verwendet werden kann. |
| [isReadOnly](#isReadOnly--) | Liefert einen Wert, der angibt, ob die Sammlung schreibgeschützt ist. |
| [isSynchronized](#isSynchronized--) | Liefert einen Wert, der angibt, ob der Zugriff auf com.aspose.pdf.AnnotationCollection synchronisiert (thread‑sicher) ist. |
| [iterator](#iterator--) | Gibt den Sammlungsenumerator zurück. |
| [remove](#remove-com.aspose.pdf.Annotation-) | Löscht die angegebene Annotation aus der Sammlung. |
| [size](#size--) | Liefert die Anzahl der Anmerkungen in der Sammlung. |

### AnnotationCollection {#AnnotationCollection-com.aspose.pdf.Page-}
Konstruktor von AnnotationCollection. Erstellt eine Annotationssammlung für Anmerkungen auf der angegebenen Seite.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Akzeptiert Besucher, um die Annotation zu verarbeiten.

### add {#add-com.aspose.pdf.Annotation-}
Fügt der Sammlung eine Annotation hinzu.

### add {#add-com.aspose.pdf.Annotation-boolean-}
Fügt der Sammlung eine Annotation hinzu. Wenn die Seite gedreht ist, wird das Annotationsrechteck entsprechend neu berechnet.

### clear {#clear--}
```
public void clear()
```

Löscht alle Anmerkungen aus der Sammlung.

### contains {#contains-com.aspose.pdf.Annotation-}
Prüft, ob die angegebene Annotation zur Sammlung gehört.

### copyTo {#copyTo-com.aspose.pdf.Annotation:A-int-}
Kopiert ein Array von Anmerkungen in die Sammlung.

### delete {#delete--}
```
public void delete()
```

Löscht alle Anmerkungen aus der Sammlung.

### delete {#delete-com.aspose.pdf.Annotation-}
Löscht alle Anmerkungen aus der Sammlung.

### delete {#delete-int-}
```
public void delete(int index)
```

Löscht die Annotation aus der Sammlung anhand des Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index der zu löschenden Annotation. |

### findByName {#findByName-java.lang.String-}
Gibt die Annotation anhand ihres Namens zurück.

### get_Item {#get_Item-int-}
```
public Annotation get_Item(int index)
```

Der Index des abzurufenden Elements.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Der Indexwert beginnt bei eins. |

**Returns:**
Annotationsobjekt

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Liefert ein Objekt, das zur Synchronisation des Zugriffs auf com.aspose.pdf.AnnotationCollection verwendet werden kann.

**Returns:**
Objekt zur Synchronisation

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Liefert einen Wert, der angibt, ob die Sammlung schreibgeschützt ist.

**Returns:**
boolescher Wert

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Liefert einen Wert, der angibt, ob der Zugriff auf com.aspose.pdf.AnnotationCollection synchronisiert (thread‑sicher) ist.

**Returns:**
boolescher Wert

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< Annotation > iterator()
```

Gibt den Sammlungsenumerator zurück.

**Returns:**
Enumerator-Objekt

### remove {#remove-com.aspose.pdf.Annotation-}
Löscht die angegebene Annotation aus der Sammlung.

### size {#size--}
```
public int size()
```

Liefert die Anzahl der Anmerkungen in der Sammlung.

**Returns:**
int-Wert
