---
title: "EmbeddedFileCollection"
linktitle: "EmbeddedFileCollection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die die Sammlung eingebetteter Dateien darstellt."
type: docs
weight: 1200
url: /de/java/com.aspose.pdf/embeddedfilecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class EmbeddedFileCollection extends Object implements Iterable < FileSpecification >
```

Klasse, die die Sammlung eingebetteter Dateien darstellt.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.FileSpecification-) | Fügt eine eingebettete Dateispezifikation zur Sammlung hinzu. |
| [add](#add-java.lang.String-com.aspose.pdf.FileSpecification-) | Fügt eine Datei zu den eingebetteten Dateien mit dem angegebenen Schlüssel hinzu. |
| [clear](#clear--) | Entfernt alle eingebetteten Dateien aus dem Dokument. |
| [contains](#contains-com.aspose.pdf.FileSpecification-) | Bestimmt, ob die Sammlung die angegebene FileSpecification enthält. Nicht unterstützt. |
| [copyTo](#copyTo-com.aspose.pdf.FileSpecification:A-int-) | Kopiert ein Array von FileSpecification‑Objekten in die colleciton. |
| [delete](#delete--) | Entfernt alle eingebetteten Dateien aus dem Dokument. |
| [delete](#delete-java.lang.String-) | Entfernt alle eingebetteten Dateien aus dem Dokument. |
| [deleteByKey](#deleteByKey-java.lang.String-) | Löscht die Datei aus der Sammlung anhand ihres Schlüssels in der Sammlung. |
| [findByName](#findByName-java.lang.String-) | Gibt die eingebettete Datei anhand ihres Namens zurück. |
| [get_Item](#get_Item-int-) | Liest die eingebettete Datei anhand ihres Indexes zurück. |
| [get_Item](#get_Item-java.lang.String-) | Ermittelt die eingebettete Datei anhand ihres Namens. |
| [getKeys](#getKeys--) | Gibt eine Liste von Dateianhangsschlüsseln zurück. |
| [getSyncRoot](#getSyncRoot--) | Ruft ein Objekt ab, das verwendet werden kann, um den Zugriff auf diese Sammlung zu synchronisieren. |
| [isEmbeddedFilesExist](#isEmbeddedFilesExist--) | Prüft, ob die Struktur für eingebettete Dateien existiert. Gibt TRUE zurück, wenn die Struktur existiert, und FALSE, wenn nicht. Wenn das Dokument niemals eingebettete Dateien enthalten hat, wurde diese Struktur nicht erstellt und ist nicht vorhanden. |
| [isReadOnly](#isReadOnly--) | Bestimmt, ob die Sammlung schreibgeschützt ist. Gibt immer false zurück. |
| [isSynchronized](#isSynchronized--) | Ruft einen Wert ab, der angibt, ob der Zugriff auf diese Sammlung synchronisiert (thread‑sicher) ist. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Gibt den Aufzählungs‑Enumerator der Sammlung zurück. |
| [iterator](#iterator--) | Gibt den Aufzählungs‑Enumerator der Sammlung zurück. |
| [remove](#remove-com.aspose.pdf.FileSpecification-) | Entfernt die angegebene FileSpecification aus der Sammlung. Nicht unterstützt. |
| [size](#size--) | Ermittelt die Anzahl eingebetteter Dateien in der Sammlung. |

### add {#add-com.aspose.pdf.FileSpecification-}
Fügt eine eingebettete Dateispezifikation zur Sammlung hinzu.

### add {#add-java.lang.String-com.aspose.pdf.FileSpecification-}
Fügt eine Datei zu den eingebetteten Dateien mit dem angegebenen Schlüssel hinzu.

### clear {#clear--}
```
public void clear()
```

Entfernt alle eingebetteten Dateien aus dem Dokument.

### contains {#contains-com.aspose.pdf.FileSpecification-}
Bestimmt, ob die Sammlung die angegebene FileSpecification enthält. Nicht unterstützt.

### copyTo {#copyTo-com.aspose.pdf.FileSpecification:A-int-}
Kopiert ein Array von FileSpecification‑Objekten in die colleciton.

### delete {#delete--}
```
public void delete()
```

Entfernt alle eingebetteten Dateien aus dem Dokument.

### delete {#delete-java.lang.String-}
Entfernt alle eingebetteten Dateien aus dem Dokument.

### deleteByKey {#deleteByKey-java.lang.String-}
Löscht die Datei aus der Sammlung anhand ihres Schlüssels in der Sammlung.

### findByName {#findByName-java.lang.String-}
Gibt die eingebettete Datei anhand ihres Namens zurück.

### get_Item {#get_Item-int-}
```
public FileSpecification get_Item(int index)
```

Liest die eingebettete Datei anhand ihres Indexes zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index der eingebetteten Datei. Die Nummerierung beginnt bei 1. |

**Returns:**
Abgerufene Spezifikation der eingebetteten Datei

### get_Item {#get_Item-java.lang.String-}
Ermittelt die eingebettete Datei anhand ihres Namens.

### getKeys {#getKeys--}
```
public final List < String > getKeys()
```

Gibt eine Liste von Dateianhangsschlüsseln zurück.

**Returns:**
Liste von String-Werten

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Ruft ein Objekt ab, das verwendet werden kann, um den Zugriff auf diese Sammlung zu synchronisieren.

**Returns:**
Objekt für Synchronisation

### isEmbeddedFilesExist {#isEmbeddedFilesExist--}
```
public boolean isEmbeddedFilesExist()
```

Prüft, ob die Struktur für eingebettete Dateien existiert. Gibt TRUE zurück, wenn die Struktur existiert, und FALSE, wenn nicht. Wenn das Dokument niemals eingebettete Dateien enthalten hat, wurde diese Struktur nicht erstellt und ist nicht vorhanden.

**Returns:**
boolescher Wert

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Bestimmt, ob die Sammlung schreibgeschützt ist. Gibt immer false zurück.

**Returns:**
boolescher Wert

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Ruft einen Wert ab, der angibt, ob der Zugriff auf diese Sammlung synchronisiert (thread‑sicher) ist.

**Returns:**
boolescher Wert

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< FileSpecification > iterator_Rename_Namesake()
```

Gibt den Aufzählungs‑Enumerator der Sammlung zurück.

**Returns:**
Enumerator der Sammlung.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< FileSpecification > iterator()
```

Gibt den Aufzählungs‑Enumerator der Sammlung zurück.

**Returns:**
Enumerator der Sammlung.

### remove {#remove-com.aspose.pdf.FileSpecification-}
Entfernt die angegebene FileSpecification aus der Sammlung. Nicht unterstützt.

### size {#size--}
```
public int size()
```

Ermittelt die Anzahl eingebetteter Dateien in der Sammlung.

**Returns:**
int-Wert
