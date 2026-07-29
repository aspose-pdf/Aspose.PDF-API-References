---
title: "DestinationCollection"
linktitle: "DestinationCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen representerar samlingen av alla destinationer (ett namntre som mappar namnsträngar till destinationer (se 12.3.2.3, \"Named Destinations\") och (se 7.7.4, \"Name Dictionary\")) i."
type: docs
weight: 960
url: /sv/java/com.aspose.pdf/destinationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DestinationCollection

**All Implemented Interfaces:**
Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, Object >>

```
public final class DestinationCollection extends Object implements Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >>
```

Klass som representerar samlingen av alla destinationer (ett namntre som mappar namnsträngar till destinationer (se 12.3.2.3, "Named Destinations") och (se 7.7.4, "Name Dictionary")) i pdf-dokumentet.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Lägger till det angivna objektet. |
| [clear](#clear--) | Samlingen är skrivskyddad. Kastar alltid ett NotSupportedException undantag. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Bestämmer om denna instans innehåller objektet. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Kopierar elementen i samlingen till en Array, med start vid ett specifikt Array-index. |
| [get_Item](#get_Item-int-) | Hämtar destinationsobjektet efter index. |
| [getExplicitDestination](#getExplicitDestination-java.lang.String-boolean-) | Returnerar den explicita destinationen efter namn. |
| [getPageNumber](#getPageNumber-java.lang.String-boolean-) | Returnerar sidnumret för destinationen efter namn. |
| [indexOf](#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Returnerar indexet för destinationen i samlingen. |
| [isReadOnly](#isReadOnly--) | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [iterator](#iterator--) | Returnerar enumeratorn. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Tar bort det angivna objektet. |
| [size](#size--) | Hämtar antalet element som finns i samlingen. |

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Lägger till det angivna objektet.

### clear {#clear--}
```
public void clear()
```

Samlingen är skrivskyddad. Kastar alltid ett NotSupportedException undantag.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Bestämmer om denna instans innehåller objektet.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Kopierar elementen i samlingen till en Array, med start vid ett specifikt Array-index.

### get_Item {#get_Item-int-}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object > get_Item(int index)
```

Hämtar destinationsobjektet efter index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Indexet för destinationen som ska hämtas. |

**Returns:**
Destination.

### getExplicitDestination {#getExplicitDestination-java.lang.String-boolean-}
Returnerar den explicita destinationen efter namn.

### getPageNumber {#getPageNumber-java.lang.String-boolean-}
Returnerar sidnumret för destinationen efter namn.

### indexOf {#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Returnerar indexet för destinationen i samlingen.

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Hämtar ett värde som indikerar om samlingen är skrivskyddad.

**Returns:**
booleskt värde

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >> iterator()
```

Returnerar enumeratorn.

**Returns:**
Enumeratören.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Tar bort det angivna objektet.

### size {#size--}
```
public int size()
```

Hämtar antalet element som finns i samlingen.

**Returns:**
int‑värde
