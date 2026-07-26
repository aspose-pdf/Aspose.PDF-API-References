---
title: "FontCollection"
linktitle: "FontCollection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt eine Schriftartensammlung dar. </p> <hr> <pre> Das Beispiel zeigt, wie alle auf der Seite deklarierten Schriftarten eingebettet werden können. // Open document Document doc = new.</pre>"
type: docs
weight: 1670
url: /de/java/com.aspose.pdf/fontcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontCollection

**All Implemented Interfaces:**
Iterable < Font >

```
public final class FontCollection extends Object implements Iterable < Font >
```

<p> Stellt eine Schriftartensammlung dar. </p> <hr> <pre> Das Beispiel zeigt, wie alle auf der Seite deklarierten Schriftarten eingebettet werden können. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // ensure all fonts declared on page resources are embedded // note that if fonts are declared on form resources they are not accessible from page resources for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save("D:\\Tests\\input.pdf"); </pre> <hr> <p> Schriftartensammlungen, die durch die Klasse {@code FontCollection} repräsentiert werden, werden in mehreren Szenarien verwendet. Zum Beispiel in Ressourcen mit der Eigenschaft {@code Resources.Fonts}. </p>

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.Font-) | Fügt eine Schriftart zur Sammlung hinzu. |
| [add](#add-com.aspose.pdf.Font-java.lang.String:A-) | Fügt eine neue Schriftart zu den Schriftartressourcen hinzu und gibt den automatisch zugewiesenen Namen der Schriftartressource zurück. |
| [add](#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-) | Neue Schriftart zur Schriftartensammlung hinzufügen. |
| [add](#add-java.lang.String-java.lang.String-) | Fügt den Schriftressourcen einen neuen Schriftart-Eintrag mit dem angegebenen Basis-Schriftartnamen hinzu. |
| [clear_Rename_Namesake](#clear_Rename_Namesake--) | / * / * Fügt Schriftart in die Sammlung ein. / * / * |
| [contains](#contains-com.aspose.pdf.Font-) | Bestimmt, ob die Sammlung einen bestimmten Wert enthält. |
| [contains](#contains-java.lang.String-) | Überprüft, ob die Schriftart in der Schriftartsammlung existiert. |
| [copyTo](#copyTo-com.aspose.pdf.Font:A-int-) | Kopiert die gesamte Sammlung in ein kompatibles eindimensionales Array, beginnend beim angegebenen Index des Zielarrays. |
| [delete](#delete-java.lang.String-) | Löscht die Schriftart mit dem angegebenen Ressourcennamen. |
| [get_Item](#get_Item-int-) | Ruft das Schriftartelement am angegebenen Index ab. |
| [get_Item](#get_Item-java.lang.String-) | Ruft die Schriftart aus der Sammlung anhand des Schriftartnamens ab. Eine Ausnahme wird ausgelöst, wenn die Schriftart nicht gefunden wurde. |
| [getFontsDictionary](#getFontsDictionary--) | Hole IPdfDictionary-Objekt |
| [getHash](#getHash--) |  |
| [getSyncRoot](#getSyncRoot--) | Liefert ein Objekt, das zur Synchronisation des Zugriffs auf die Sammlung verwendet werden kann. |
| [isReadOnly](#isReadOnly--) | Liefert einen Wert, der angibt, ob die Sammlung schreibgeschützt ist |
| [isSynchronized](#isSynchronized--) | Liefert einen Wert, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread‑sicher) ist. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Gibt einen Enumerator für die gesamte Sammlung zurück. |
| [iterator](#iterator--) | Gibt einen Enumerator für die gesamte Sammlung zurück. |
| [remove](#remove-com.aspose.pdf.Font-) | Löscht das angegebene Element aus der Sammlung. |
| [size](#size--) | Gibt die Anzahl der {@code Font}-Objektelemente zurück, die tatsächlich in der Sammlung enthalten sind. |

### add {#add-com.aspose.pdf.Font-}
Fügt eine Schriftart zur Sammlung hinzu.

### add {#add-com.aspose.pdf.Font-java.lang.String:A-}
Fügt eine neue Schriftart zu den Schriftartressourcen hinzu und gibt den automatisch zugewiesenen Namen der Schriftartressource zurück.

### add {#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-}
Neue Schriftart zur Schriftartensammlung hinzufügen.

### add {#add-java.lang.String-java.lang.String-}
Fügt den Schriftressourcen einen neuen Schriftart-Eintrag mit dem angegebenen Basis-Schriftartnamen hinzu.

### clear_Rename_Namesake {#clear_Rename_Namesake--}
```
public void clear_Rename_Namesake()
```

/ * / * Fügt Schriftart in die Sammlung ein. / * / *

### contains {#contains-com.aspose.pdf.Font-}
Bestimmt, ob die Sammlung einen bestimmten Wert enthält.

### contains {#contains-java.lang.String-}
Überprüft, ob die Schriftart in der Schriftartsammlung existiert.

### copyTo {#copyTo-com.aspose.pdf.Font:A-int-}
Kopiert die gesamte Sammlung in ein kompatibles eindimensionales Array, beginnend beim angegebenen Index des Zielarrays.

### delete {#delete-java.lang.String-}
Löscht die Schriftart mit dem angegebenen Ressourcennamen.

### get_Item {#get_Item-int-}
```
public Font get_Item(int index)
```

Ruft das Schriftartelement am angegebenen Index ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index innerhalb der Sammlung. |

**Returns:**
Schriftart-Objekt.

### get_Item {#get_Item-java.lang.String-}
Ruft die Schriftart aus der Sammlung anhand des Schriftartnamens ab. Eine Ausnahme wird ausgelöst, wenn die Schriftart nicht gefunden wurde.

### getFontsDictionary {#getFontsDictionary--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getFontsDictionary()
```

Hole IPdfDictionary-Objekt

**Returns:**
IPdfDictionary-Objekt

### getHash {#getHash--}
```
public com.aspose.pdf.engine.collections.HashDictionary< String , Font > getHash()
```



### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Liefert ein Objekt, das zur Synchronisation des Zugriffs auf die Sammlung verwendet werden kann.

**Returns:**
Objekt für Synchronisation

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

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Gibt einen Enumerator für die gesamte Sammlung zurück.

**Returns:**
Enumerator-Objekt.

### iterator {#iterator--}
```
public Iterator < Font > iterator()
```

Gibt einen Enumerator für die gesamte Sammlung zurück.

**Returns:**
Enumerator-Objekt.

### remove {#remove-com.aspose.pdf.Font-}
Löscht das angegebene Element aus der Sammlung.

### size {#size--}
```
public int size()
```

Gibt die Anzahl der {@code Font}-Objektelemente zurück, die tatsächlich in der Sammlung enthalten sind.

**Returns:**
int-Wert
