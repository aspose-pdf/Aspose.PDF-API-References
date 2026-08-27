---
title: "PageCollection"
linktitle: "PageCollection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Sammlung von PDF-Dokumentseiten."
type: docs
weight: 3340
url: /de/java/com.aspose.pdf/pagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageCollection

**All Implemented Interfaces:**
Iterable < Page >

```
public final class PageCollection extends Object implements Iterable < Page >
```

Sammlung von PDF-Dokumentseiten.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Akzeptiert {@code AnnotationSelector} Besucherobjekt, das Funktionalität zum Arbeiten mit Anmerkungen bereitstellt. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Akzeptiert {@code ImagePlacementAbsorber} Besucherobjekt, das Funktionalität zum Arbeiten mit Bildplatzierungsobjekten bereitstellt. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | Akzeptiert {@code TextAbsorber} Besucherobjekt, das Funktionalität zum Arbeiten mit Textobjekten bereitstellt. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Akzeptiert {@code TextFragmentAbsorber} Besucherobjekt, das Funktionalität zum Arbeiten mit Textobjekten bereitstellt. |
| [add_Rename_Namesake](#add_Rename_Namesake-com.aspose.pdf.Page-) | Fügt Seite zur Sammlung hinzu. |
| [add](#add--) | Fügt eine leere Seite hinzu. Wenn das Dokument bereits Seiten mit unterschiedlichen Größen enthält, wird die Größe der am häufigsten vorkommenden Seite ausgewählt. Falls es nur zwei verschiedene Seiten gibt, wird die Größe der ersten Seite verwendet. |
| [add](#add-java.lang.Iterable-) | Fügt eine leere Seite hinzu. Wenn das Dokument bereits Seiten mit unterschiedlichen Größen enthält, wird die Größe der am häufigsten vorkommenden Seite ausgewählt. Falls es nur zwei verschiedene Seiten gibt, wird die Größe der ersten Seite verwendet. |
| [add](#add-java.util.List-) | Fügt eine leere Seite hinzu. Wenn das Dokument bereits Seiten mit unterschiedlichen Größen enthält, wird die Größe der am häufigsten vorkommenden Seite ausgewählt. Falls es nur zwei verschiedene Seiten gibt, wird die Größe der ersten Seite verwendet. |
| [add](#add-com.aspose.pdf.Page-) | Fügt eine leere Seite hinzu. Wenn das Dokument bereits Seiten mit unterschiedlichen Größen enthält, wird die Größe der am häufigsten vorkommenden Seite ausgewählt. Falls es nur zwei verschiedene Seiten gibt, wird die Größe der ersten Seite verwendet. |
| [add](#add-com.aspose.pdf.Page:A-) | Fügt eine leere Seite hinzu. Wenn das Dokument bereits Seiten mit unterschiedlichen Größen enthält, wird die Größe der am häufigsten vorkommenden Seite ausgewählt. Falls es nur zwei verschiedene Seiten gibt, wird die Größe der ersten Seite verwendet. |
| [beginUpdate](#beginUpdate--) | Aktualisiert, wenn Gruppenänderungen beginnen. |
| [clear](#clear--) | Seitenkollektion leeren. |
| [contains](#contains-com.aspose.pdf.Page-) | Bestimmt, ob diese Instanz das Objekt enthält. |
| [copyTo](#copyTo-com.aspose.pdf.Page:A-int-) | Kopiert Seiten in das Dokument. |
| [delete](#delete--) | Löscht alle Seiten aus der Sammlung. |
| [delete](#delete-int-) | Lösche die angegebene Seite. |
| [delete](#delete-java.lang.Integer:A-) | Löscht alle Seiten aus der Sammlung. |
| [endUpdate](#endUpdate--) | Aktualisiert, wenn Gruppenänderungen abgeschlossen sind. |
| [findByPdfObject](#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-) |  |
| [flatten](#flatten--) | Entfernt alle Felder, die sich auf den Seiten befinden, und legt stattdessen deren Werte ab. |
| [freeMemory](#freeMemory--) | Löscht zwischengespeicherte Daten |
| [get_Item](#get_Item-int-) | Liefert Seite nach Index. |
| [getSyncRoot](#getSyncRoot--) | Liefert das Synchronisationsobjekt der Sammlung. |
| [getUnrestricted](#getUnrestricted-int-) | Gibt Seite nach ihrem Index zurück. {@code Page} |
| [indexOf](#indexOf-com.aspose.pdf.Page-) | <p> Gibt den Index der angegebenen Seite zurück. </p> |
| [insert](#insert-int-) | Füge eine leere Seite an der angegebenen Position in die Sammlung ein. Wenn das Dokument bereits Seiten mit unterschiedlichen Größen enthält, wird die Größe der am häufigsten vorkommenden Seite ausgewählt. Falls es nur zwei verschiedene Seiten gibt, wird die Größe der ersten Seite verwendet. |
| [insert](#insert-int-java.lang.Iterable-) | Fügt Seiten aus der Sammlung in das Dokument ein. |
| [insert](#insert-int-java.util.List-) | Fügt Seiten aus der Sammlung in das Dokument ein. |
| [insert](#insert-int-com.aspose.pdf.Page-) | Fügt eine Seite an der angegebenen Stelle in die Seitensammlung ein. |
| [insert](#insert-int-com.aspose.pdf.Page:A-) | Fügt die Seiten des Arrays in das Dokument ein. |
| [isEmpty](#isEmpty--) | Gibt TRUE zurück, wenn die Sammlung leer ist. |
| [isReadOnly](#isReadOnly--) | Liefert den Wert, der angibt, ob die Sammlung schreibgeschützt ist. Gibt immer false zurück. |
| [isSynchronized](#isSynchronized--) | Gibt true zurück, wenn das Objekt synchronisiert ist. |
| [iterator](#iterator--) | Gibt den Enumerator der Seiten zurück. |
| [remove](#remove-com.aspose.pdf.Page-) | Entfernt das angegebene Element, wirft eine Ausnahme. |
| [size](#size--) | Liefert die Anzahl der Seiten im Dokument. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Akzeptiert {@code AnnotationSelector} Besucherobjekt, das Funktionalität zum Arbeiten mit Anmerkungen bereitstellt.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
Akzeptiert {@code ImagePlacementAbsorber} Besucherobjekt, das Funktionalität zum Arbeiten mit Bildplatzierungsobjekten bereitstellt.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
Akzeptiert {@code TextAbsorber} Besucherobjekt, das Funktionalität zum Arbeiten mit Textobjekten bereitstellt.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
Akzeptiert {@code TextFragmentAbsorber} Besucherobjekt, das Funktionalität zum Arbeiten mit Textobjekten bereitstellt.

### add_Rename_Namesake {#add_Rename_Namesake-com.aspose.pdf.Page-}
Fügt Seite zur Sammlung hinzu.

### add {#add--}
```
public Page add()
```

Fügt eine leere Seite hinzu. Wenn das Dokument bereits Seiten mit unterschiedlichen Größen enthält, wird die Größe der am häufigsten vorkommenden Seite ausgewählt. Falls es nur zwei verschiedene Seiten gibt, wird die Größe der ersten Seite verwendet.

**Returns:**
Seite hinzugefügt.

### add {#add-java.lang.Iterable-}
Fügt eine leere Seite hinzu. Wenn das Dokument bereits Seiten mit unterschiedlichen Größen enthält, wird die Größe der am häufigsten vorkommenden Seite ausgewählt. Falls es nur zwei verschiedene Seiten gibt, wird die Größe der ersten Seite verwendet.

**Returns:**
Seite hinzugefügt.

### add {#add-java.util.List-}
Fügt eine leere Seite hinzu. Wenn das Dokument bereits Seiten mit unterschiedlichen Größen enthält, wird die Größe der am häufigsten vorkommenden Seite ausgewählt. Falls es nur zwei verschiedene Seiten gibt, wird die Größe der ersten Seite verwendet.

**Returns:**
Seite hinzugefügt.

### add {#add-com.aspose.pdf.Page-}
Fügt eine leere Seite hinzu. Wenn das Dokument bereits Seiten mit unterschiedlichen Größen enthält, wird die Größe der am häufigsten vorkommenden Seite ausgewählt. Falls es nur zwei verschiedene Seiten gibt, wird die Größe der ersten Seite verwendet.

**Returns:**
Seite hinzugefügt.

### add {#add-com.aspose.pdf.Page:A-}
Fügt eine leere Seite hinzu. Wenn das Dokument bereits Seiten mit unterschiedlichen Größen enthält, wird die Größe der am häufigsten vorkommenden Seite ausgewählt. Falls es nur zwei verschiedene Seiten gibt, wird die Größe der ersten Seite verwendet.

**Returns:**
Seite hinzugefügt.

### beginUpdate {#beginUpdate--}
```
public final void beginUpdate()
```

Aktualisiert, wenn Gruppenänderungen beginnen.

### clear {#clear--}
```
public void clear()
```

Seitenkollektion leeren.

### contains {#contains-com.aspose.pdf.Page-}
Bestimmt, ob diese Instanz das Objekt enthält.

### copyTo {#copyTo-com.aspose.pdf.Page:A-int-}
Kopiert Seiten in das Dokument.

### delete {#delete--}
```
public void delete()
```

Löscht alle Seiten aus der Sammlung.

### delete {#delete-int-}
```
public void delete(int index)
```

Lösche die angegebene Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Nummer der zu löschenden Seite. Seitennummern beginnen bei 1. |

### delete {#delete-java.lang.Integer:A-}
Löscht alle Seiten aus der Sammlung.

### endUpdate {#endUpdate--}
```
public final void endUpdate()
```

Aktualisiert, wenn Gruppenänderungen abgeschlossen sind.

### findByPdfObject {#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-}


### flatten {#flatten--}
```
public void flatten()
```

Entfernt alle Felder, die sich auf den Seiten befinden, und legt stattdessen deren Werte ab.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Löscht zwischengespeicherte Daten

### get_Item {#get_Item-int-}
```
public Page get_Item(int index)
```

Liefert Seite nach Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index der Seite. |

**Returns:**
Abgerufene Seite.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Liefert das Synchronisationsobjekt der Sammlung.

**Returns:**
Objekt für Synchronisation

### getUnrestricted {#getUnrestricted-int-}
```
public Page getUnrestricted(int index)
```

Gibt Seite nach ihrem Index zurück. {@code Page}

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index der angeforderten Seite. Seiten werden ab 1 nummeriert. |

**Returns:**
Angeforderte Seite

### indexOf {#indexOf-com.aspose.pdf.Page-}
<p> Gibt den Index der angegebenen Seite zurück. </p>

### insert {#insert-int-}
```
public Page insert(int pageNumber)
```

Füge eine leere Seite an der angegebenen Position in die Sammlung ein. Wenn das Dokument bereits Seiten mit unterschiedlichen Größen enthält, wird die Größe der am häufigsten vorkommenden Seite ausgewählt. Falls es nur zwei verschiedene Seiten gibt, wird die Größe der ersten Seite verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber |  | Position der neuen Seite. |

**Returns:**
Eingefügte Seite.

### insert {#insert-int-java.lang.Iterable-}
Fügt Seiten aus der Sammlung in das Dokument ein.

### insert {#insert-int-java.util.List-}
Fügt Seiten aus der Sammlung in das Dokument ein.

### insert {#insert-int-com.aspose.pdf.Page-}
Fügt eine Seite an der angegebenen Stelle in die Seitensammlung ein.

### insert {#insert-int-com.aspose.pdf.Page:A-}
Fügt die Seiten des Arrays in das Dokument ein.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Gibt TRUE zurück, wenn die Sammlung leer ist.

**Returns:**
boolescher Wert

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Liefert den Wert, der angibt, ob die Sammlung schreibgeschützt ist. Gibt immer false zurück.

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
public Iterator < Page > iterator()
```

Gibt den Enumerator der Seiten zurück.

**Returns:**
Aufzählung der Seiten

### remove {#remove-com.aspose.pdf.Page-}
Entfernt das angegebene Element, wirft eine Ausnahme.

### size {#size--}
```
public int size()
```

Liefert die Anzahl der Seiten im Dokument.

**Returns:**
int-Wert
