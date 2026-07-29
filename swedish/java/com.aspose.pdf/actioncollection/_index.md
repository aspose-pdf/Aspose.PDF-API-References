---
title: "ActionCollection"
linktitle: "ActionCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "Samling av åtgärder"
type: docs
weight: 40
url: /sv/java/com.aspose.pdf/actioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ActionCollection

**All Implemented Interfaces:**
Iterable < PdfAction >

```
public final class ActionCollection extends Object implements Iterable < PdfAction >
```

Samling av åtgärder

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.PdfAction-) | Lägger till en ny åtgärd i samlingen. |
| [clear](#clear--) | Rensa samling. |
| [contains](#contains-com.aspose.pdf.PdfAction-) | Stöds ännu inte. Returnerar true om angivet objekt finns i samlingen. |
| [copyTo](#copyTo-com.aspose.pdf.PdfAction:A-int-) | Kopierar åtgärdsarray till samlingen. |
| [delete](#delete--) | Ta bort alla åtgärder. |
| [delete](#delete-int-) | Tar bort åtgärd från samlingen efter index. |
| [get_Item](#get_Item-int-) | Hämtar åtgärd efter dess index. |
| [getSyncRoot](#getSyncRoot--) | Hämtar synkroniseringsobjekt. |
| [isReadOnly](#isReadOnly--) | Returnerar true om samlingen är skrivskyddad. |
| [isSynchronized](#isSynchronized--) | Returnerar true om objektet är synkroniserat. |
| [iterator](#iterator--) | / * / * Returnerar enumerator för samlingen. / * / * / * |
| [remove](#remove-com.aspose.pdf.PdfAction-) | * Stöds ännu inte. Tar bort objekt från samlingen. |
| [size](#size--) | Antal åtgärder på samlingen. |

### add {#add-com.aspose.pdf.PdfAction-}
Lägger till en ny åtgärd i samlingen.

### clear {#clear--}
```
public void clear()
```

Rensa samling.

### contains {#contains-com.aspose.pdf.PdfAction-}
Stöds ännu inte. Returnerar true om angivet objekt finns i samlingen.

### copyTo {#copyTo-com.aspose.pdf.PdfAction:A-int-}
Kopierar åtgärdsarray till samlingen.

### delete {#delete--}
```
public void delete()
```

Ta bort alla åtgärder.

### delete {#delete-int-}
```
public void delete(int index)
```

Tar bort åtgärd från samlingen efter index.

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
| index |  | Index för åtgärd. |

**Returns:**
Hämtad åtgärd.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Hämtar synkroniseringsobjekt.

**Returns:**
Objektvärde

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Returnerar true om samlingen är skrivskyddad.

**Returns:**
booleskt värde

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Returnerar true om objektet är synkroniserat.

**Returns:**
booleskt värde

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< PdfAction > iterator()
```

/ * / * Returnerar enumerator för samlingen. / * / * / *

**Returns:**
Samlingsenumerator. /

### remove {#remove-com.aspose.pdf.PdfAction-}
* Not supported yet. Removes item from collection.

### size {#size--}
```
public int size()
```

Antal åtgärder på samlingen.

**Returns:**
int‑värde
