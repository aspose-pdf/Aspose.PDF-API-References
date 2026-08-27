---
title: "TextSegmentCollection"
linktitle: "TextSegmentCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en samling av textsegment"
type: docs
weight: 5310
url: /sv/java/com.aspose.pdf/textsegmentcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextSegmentCollection

**All Implemented Interfaces:**
Iterable < TextSegment >

```
public final class TextSegmentCollection extends Object implements Iterable < TextSegment >
```

Representerar en samling av textsegment

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.TextSegment-) | Lägger till textsegmentelementet på det angivna indexet. |
| [clear](#clear--) | Rensar alla objekt från samlingen. |
| [contains](#contains-com.aspose.pdf.TextSegment-) | Avgör om samlingen innehåller ett specifikt värde. |
| [copyTo](#copyTo-com.aspose.pdf.TextSegment:A-int-) | Kopierar hela samlingen till en kompatibel endimensionell Array, med start vid det angivna indexet i målarrayen. |
| [delete](#delete-int-) | Tar bort textsegmentelementet på det angivna indexet. |
| [get_Item](#get_Item-int-) | Hämtar textsegmentelementet på det angivna indexet. |
| [getSyncRoot](#getSyncRoot--) | Hämtar ett objekt som kan användas för att synkronisera åtkomst till samlingen. |
| [isReadOnly](#isReadOnly--) | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [isSynchronized](#isSynchronized--) | Hämtar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [iterator](#iterator--) | Returnerar en enumerator för hela samlingen. |
| [remove](#remove-com.aspose.pdf.TextSegment-) | Tar bort specificerat objekt från samlingen. |
| [size](#size--) | Hämtar antalet {@code TextSegment} objektselement som faktiskt finns i samlingen. |

### add {#add-com.aspose.pdf.TextSegment-}
Lägger till textsegmentelementet på det angivna indexet.

### clear {#clear--}
```
public void clear()
```

Rensar alla objekt från samlingen.

### contains {#contains-com.aspose.pdf.TextSegment-}
Avgör om samlingen innehåller ett specifikt värde.

### copyTo {#copyTo-com.aspose.pdf.TextSegment:A-int-}
Kopierar hela samlingen till en kompatibel endimensionell Array, med start vid det angivna indexet i målarrayen.

### delete {#delete-int-}
```
public void delete(int index)
```

Tar bort textsegmentelementet på det angivna indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | int‑värde |

### get_Item {#get_Item-int-}
```
public TextSegment get_Item(int index)
```

Hämtar textsegmentelementet på det angivna indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index inom samlingen. |

**Returns:**
TextSegment-objekt.

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
public Iterator < TextSegment > iterator()
```

Returnerar en enumerator för hela samlingen.

**Returns:**
Enumerator‑objekt.

### remove {#remove-com.aspose.pdf.TextSegment-}
Tar bort specificerat objekt från samlingen.

### size {#size--}
```
public int size()
```

Hämtar antalet {@code TextSegment} objektselement som faktiskt finns i samlingen.

**Returns:**
int‑värde
