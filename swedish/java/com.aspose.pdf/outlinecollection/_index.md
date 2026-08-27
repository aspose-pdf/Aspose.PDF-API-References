---
title: "OutlineCollection"
linktitle: "OutlineCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar dokumentets dispositionshierarki."
type: docs
weight: 3260
url: /sv/java/com.aspose.pdf/outlinecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineCollection extends Outlines
```

Representerar dokumentets dispositionshierarki.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | Lägger till ett outline-objekt i samlingen. |
| [clear](#clear--) | Rensar alla objekt från samlingen. |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | Stöds ännu inte. Kontrollerar om samlingen innehåller det angivna objektet. |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | Kopierar outline-objekten till en System.Array, med start vid ett specifikt System.Array-index. |
| [delete](#delete--) | Tar bort alla outline-objekt från dokumentets kontur. |
| [delete](#delete-java.lang.String-) | Tar bort alla outline-objekt från dokumentets kontur. |
| [get_Item](#get_Item-int-) | Hämtar outline-objekt från samlingen efter index. |
| [getFirst](#getFirst--) | Hämtar ett outline-objekt som representerar det första top-nivåobjektet i konturen. |
| [getLast](#getLast--) | Hämtar ett konturobjekt som representerar det sista top‑nivåobjektet i konturen. |
| [getSyncRoot](#getSyncRoot--) | Hämtar ett objekt som kan användas för att synkronisera åtkomst till denna samling. |
| [getVisibleCount](#getVisibleCount--) | Count är summan av antalet synliga underordnade konturposter på alla nivåer. Obs: förväxla inte med Count som är antalet objekt i samlingen. |
| [hasNext](#hasNext--) |  |
| [isReadOnly](#isReadOnly--) | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [isSynchronized](#isSynchronized--) | Hämtar ett värde som indikerar om åtkomst till denna samling är synkroniserad (trådsäker). |
| [iterator](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [next](#next--) |  |
| [remove](#remove-int-) | Ta bort objekt efter index. |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | Stöds ännu inte. Kastar alltid ett undantag. |
| [size](#size--) | Hämtar det totala antalet konturposter (bokmärken) på alla nivåer i dokumentets kontur. |

### add {#add-com.aspose.pdf.OutlineItemCollection-}
Lägger till ett outline-objekt i samlingen.

### clear {#clear--}
```
public void clear()
```

Rensar alla objekt från samlingen.

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
Stöds ännu inte. Kontrollerar om samlingen innehåller det angivna objektet.

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
Kopierar outline-objekten till en System.Array, med start vid ett specifikt System.Array-index.

### delete {#delete--}
```
public void delete()
```

Tar bort alla outline-objekt från dokumentets kontur.

### delete {#delete-java.lang.String-}
Tar bort alla outline-objekt från dokumentets kontur.

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

Hämtar outline-objekt från samlingen efter index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index för begärt objekt. |

**Returns:**
OutlineItemCollection‑objekt

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

Hämtar ett outline-objekt som representerar det första top-nivåobjektet i konturen.

**Returns:**
OutlineItemCollection‑objekt

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

Hämtar ett konturobjekt som representerar det sista top‑nivåobjektet i konturen.

**Returns:**
OutlineItemCollection‑objekt

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Hämtar ett objekt som kan användas för att synkronisera åtkomst till denna samling.

**Returns:**
Objekt för synkronisering

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

Count är summan av antalet synliga underordnade konturposter på alla nivåer. Obs: förväxla inte med Count som är antalet objekt i samlingen.

**Returns:**
int‑värde

### hasNext {#hasNext--}
```
public boolean hasNext()
```



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

Hämtar ett värde som indikerar om åtkomst till denna samling är synkroniserad (trådsäker).

**Returns:**
booleskt värde

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returns:**
Ett System.Collections.IEnumerator‑objekt som kan användas för att iterera genom samlingen.

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

Ta bort objekt efter index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index för objektet som ska tas bort. |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
Stöds ännu inte. Kastar alltid ett undantag.

### size {#size--}
```
public int size()
```

Hämtar det totala antalet konturposter (bokmärken) på alla nivåer i dokumentets kontur.

**Returns:**
int‑värde
