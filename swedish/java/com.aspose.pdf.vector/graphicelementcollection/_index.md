---
title: "GraphicElementCollection"
linktitle: "GraphicElementCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar {@link GraphicElement}-samling."
type: docs
weight: 20
url: /sv/java/com.aspose.pdf.vector/graphicelementcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElementCollection

**All Implemented Interfaces:**
Iterable < GraphicElement >

```
public final class GraphicElementCollection extends Object implements Iterable < GraphicElement >
```

Representerar {@link GraphicElement}-samling.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [GraphicElementCollection](#GraphicElementCollection--) | Initierar den nya samlingen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.vector.GraphicElement-) | Lägger till ett nytt {@link GraphicElement} i samlingen. Alla objekt i samlingen måste ha samma {@code GraphicElement.Parent}({@link GraphicElement#getParent}). |
| [clear](#clear--) | Rensar samlingen. |
| [contains](#contains-com.aspose.pdf.vector.GraphicElement-) | Bestämmer om ett element finns i samlingen. |
| [copyTo](#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-) | Kopierar hela samlingen till en kompatibel endimensionell Array, med start vid det angivna indexet i målarrayen. |
| [get_Item](#get_Item-int-) | Hämtar {@link GraphicElement}-elementet på det angivna indexet. |
| [isReadOnly](#isReadOnly--) | Hämtar ett värde som indikerar om samlingen är skrivskyddad. Returnerar alltid falskt. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Returnerar en enumerator för hela samlingen. |
| [iterator](#iterator--) | Returnerar en enumerator för hela samlingen. |
| [remove](#remove-com.aspose.pdf.vector.GraphicElement-) | Tar bort {@link GraphicElement}-elementet. |
| [size](#size--) | Hämtar antalet {@link GraphicElement}-objektelement som faktiskt finns i samlingen. |
| [toList](#toList--) | Returnerar den inre samlingen för obegränsad enumeration. |
| [toString](#toString--) | Hämtar en strängrepresentation av denna samling. |

### GraphicElementCollection {#GraphicElementCollection--}
```
public GraphicElementCollection()
```

Initierar den nya samlingen.

### add {#add-com.aspose.pdf.vector.GraphicElement-}
Lägger till ett nytt {@link GraphicElement} i samlingen. Alla objekt i samlingen måste ha samma {@code GraphicElement.Parent}({@link GraphicElement#getParent}).

### clear {#clear--}
```
public final void clear()
```

Rensar samlingen.

### contains {#contains-com.aspose.pdf.vector.GraphicElement-}
Bestämmer om ett element finns i samlingen.

### copyTo {#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-}
Kopierar hela samlingen till en kompatibel endimensionell Array, med start vid det angivna indexet i målarrayen.

### get_Item {#get_Item-int-}
```
public final GraphicElement get_Item(int index)
```

Hämtar {@link GraphicElement}-elementet på det angivna indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index inom samlingen. |

**Returns:**
{@link GraphicElement}.

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Hämtar ett värde som indikerar om samlingen är skrivskyddad. Returnerar alltid falskt.

**Returns:**
booleskt värde

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public final com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Returnerar en enumerator för hela samlingen.

**Returns:**
Enumerator‑objekt.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< GraphicElement > iterator()
```

Returnerar en enumerator för hela samlingen.

**Returns:**
Enumerator‑objekt.

### remove {#remove-com.aspose.pdf.vector.GraphicElement-}
Tar bort {@link GraphicElement}-elementet.

### size {#size--}
```
public final int size()
```

Hämtar antalet {@link GraphicElement}-objektelement som faktiskt finns i samlingen.

**Returns:**
int‑värde

### toList {#toList--}
```
public final com.aspose.ms.System.Collections.Generic.List< GraphicElement > toList()
```

Returnerar den inre samlingen för obegränsad enumeration.

**Returns:**
Inre lista

### toString {#toString--}
```
public String toString()
```

Hämtar en strängrepresentation av denna samling.

**Returns:**
Strängen.
