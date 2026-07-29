---
title: "TextFragmentCollection"
linktitle: "TextFragmentCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en samling av textfragment"
type: docs
weight: 5130
url: /sv/java/com.aspose.pdf/textfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextFragmentCollection

**All Implemented Interfaces:**
Iterable < TextFragment >

```
public final class TextFragmentCollection extends Object implements Iterable < TextFragment >
```

Representerar en samling av textfragment

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.TextFragment-) | Lägger till textfragmentselementet på det angivna indexet. |
| [clear](#clear--) | Rensar alla objekt från samlingen. |
| [contains](#contains-com.aspose.pdf.TextFragment-) | Avgör om samlingen innehåller ett specifikt värde. |
| [copyTo](#copyTo-com.aspose.pdf.TextFragment:A-int-) | / * / * Returnerar en enumerator för hela samlingen. / * / * |
| [get_Item](#get_Item-int-) | Hämtar textfragmentselementet på det angivna indexet. Index bör vara i intervallet [1..n] där n är lika med antalet textfragment. |
| [getSyncRoot](#getSyncRoot--) | Hämtar ett objekt som kan användas för att synkronisera åtkomst till samlingen. |
| [isReadOnly](#isReadOnly--) | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [isSynchronized](#isSynchronized--) | Hämtar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [iterator](#iterator--) | Returnerar en enumerator för hela samlingen. |
| [remove](#remove-com.aspose.pdf.TextFragment-) | Tar bort specificerat objekt från samlingen. |
| [size](#size--) | Hämtar antalet {@code TextFragment} objekt‑element som faktiskt finns i samlingen. |

### add {#add-com.aspose.pdf.TextFragment-}
Lägger till textfragmentselementet på det angivna indexet.

### clear {#clear--}
```
public void clear()
```

Rensar alla objekt från samlingen.

### contains {#contains-com.aspose.pdf.TextFragment-}
Avgör om samlingen innehåller ett specifikt värde.

### copyTo {#copyTo-com.aspose.pdf.TextFragment:A-int-}
/ * / * Returnerar en enumerator för hela samlingen. / * / *

### get_Item {#get_Item-int-}
```
public TextFragment get_Item(int index)
```

Hämtar textfragmentselementet på det angivna indexet. Index bör vara i intervallet [1..n] där n är lika med antalet textfragment.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index inom samlingen. |

**Returns:**
TextFragment‑objekt.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Hämtar ett objekt som kan användas för att synkronisera åtkomst till samlingen.

**Returns:**
Objektelement

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Hämtar ett värde som indikerar om samlingen är skrivskyddad.

**Returns:**
booleskt värde

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Hämtar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker).

**Returns:**
booleskt värde

### iterator {#iterator--}
```
public Iterator < TextFragment > iterator()
```

Returnerar en enumerator för hela samlingen.

**Returns:**
Enumerator‑objekt.

### remove {#remove-com.aspose.pdf.TextFragment-}
Tar bort specificerat objekt från samlingen.

### size {#size--}
```
public int size()
```

Hämtar antalet {@code TextFragment} objekt‑element som faktiskt finns i samlingen.

**Returns:**
int‑värde
