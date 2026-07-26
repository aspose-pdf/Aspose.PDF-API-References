---
title: "PdfActionCollection"
linktitle: "PdfActionCollection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse beschreibt eine Liste von Aktionen."
type: docs
weight: 3680
url: /de/java/com.aspose.pdf/pdfactioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfActionCollection

**All Implemented Interfaces:**
Iterable < PdfAction >

```
public class PdfActionCollection extends Object implements Iterable < PdfAction >
```

Klasse beschreibt eine Liste von Aktionen.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.PdfAction-) | Fügt eine Aktion zur Aktionsliste hinzu. |
| [delete](#delete-int-) | Entfernt die Aktion nach Index. |
| [get_Item](#get_Item-int-) | Gibt die Aktion nach ihrem Index zurück. |
| [getCount](#getCount--) | Ermittelt die Anzahl der Aktionen. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Interne Methode |
| [iterator](#iterator--) | Ermittelt den Enumerator. |

### add {#add-com.aspose.pdf.PdfAction-}
Fügt eine Aktion zur Aktionsliste hinzu.

### delete {#delete-int-}
```
public void delete(int index)
```

Entfernt die Aktion nach Index.

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
| index |  | Wert des Aktionsindex. |

**Returns:**
PdfAction-Index, falls gefunden; andernfalls wird @throws IndexOutOfRangeException IndexOutOfRangeException ausgelöst.

### getCount {#getCount--}
```
public int getCount()
```

Ermittelt die Anzahl der Aktionen.

**Returns:**
int-Wert

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator< PdfAction > iterator_Rename_Namesake()
```

Interne Methode

**Returns:**
internes Objekt.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< PdfAction > iterator()
```

Ermittelt den Enumerator.

**Returns:**
PDfAction-Enumerator.
