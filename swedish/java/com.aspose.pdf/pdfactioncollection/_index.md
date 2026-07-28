---
title: "PdfActionCollection"
linktitle: "PdfActionCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen beskriver en lista med åtgärder."
type: docs
weight: 3680
url: /sv/java/com.aspose.pdf/pdfactioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfActionCollection

**All Implemented Interfaces:**
Iterable < PdfAction >

```
public class PdfActionCollection extends Object implements Iterable < PdfAction >
```

Klassen beskriver en lista med åtgärder.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.PdfAction-) | Lägg till åtgärd i åtgärdslistan. |
| [delete](#delete-int-) | Ta bort åtgärd efter index. |
| [get_Item](#get_Item-int-) | Hämtar åtgärd efter dess index. |
| [getCount](#getCount--) | Hämtar antal åtgärder. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Intern metod |
| [iterator](#iterator--) | Hämtar enumerator. |

### add {#add-com.aspose.pdf.PdfAction-}
Lägg till åtgärd i åtgärdslistan.

### delete {#delete-int-}
```
public void delete(int index)
```

Ta bort åtgärd efter index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index för åtgärd att ta bort. |

### get_Item {#get_Item-int-}
```
public PdfAction get_Item(int index)
```

Hämtar åtgärd efter dess index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Åtgärdsindexvärde. |

**Returns:**
PdfAction-index om hittad; annars kastas @throws IndexOutOfRangeException IndexOutOfRangeException

### getCount {#getCount--}
```
public int getCount()
```

Hämtar antal åtgärder.

**Returns:**
int‑värde

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator< PdfAction > iterator_Rename_Namesake()
```

Intern metod

**Returns:**
internt objekt.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< PdfAction > iterator()
```

Hämtar enumerator.

**Returns:**
PDfAction-enumerator.
