---
title: "com.aspose.pdf.boundscheckablelist"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar BoundsCheckableList - omslag runt System.Collections.Generic.List."
type: docs
weight: 10
url: /sv/java/com.aspose.pdf.boundscheckablelist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.boundscheckablelist.BoundsCheckableList<T>

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<T>, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<T>, com.aspose.ms.System.Collections.Generic.IGenericList<T>, com.aspose.ms.System.Collections.IEnumerable<T>, Iterable <T>

```
public class BoundsCheckableList<T extends IBoundsCheckableItem > extends Object implements com.aspose.ms.System.Collections.Generic.IGenericList<T>
```

Representerar BoundsCheckableList - omslag runt System.Collections.Generic.List.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [BoundsCheckableList](#BoundsCheckableList--) | Initierar en ny instans av BoundsCheckableList-klassen. |
| [BoundsCheckableList](#BoundsCheckableList-int-double-double-) | Initierar en ny instans av BoundsCheckableList-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addItem](#addItem-T-) | Lägger till ett objekt i slutet av System.Collections.Generic.List beroende på parametern "boundsCheckMode". |
| [clear](#clear--) | Tar bort alla element från System.Collections.Generic.List. |
| [containsItem](#containsItem-T-) | Avgör om ett element finns i System.Collections.Generic.List. |
| [copyToTArray](#copyToTArray-T:A-int-) | Kopierar hela System.Collections.Generic.List till en kompatibel endimensionell array, med start vid det angivna indexet i målarrayen. |
| [get_Item](#get_Item-int-) | Hämtar eller anger stycke från eller till samlingen. |
| [indexOfItem](#indexOfItem-T-) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten i hela System.Collections.Generic.List. |
| [insertItem](#insertItem-int-T-) | Infogar ett element i System.Collections.Generic.List på det angivna indexet. |
| [isReadOnly](#isReadOnly--) | Hämtar värdet som indikerar om samlingen är skrivskyddad. |
| [iterator](#iterator--) | Returnerar en enumerator som itererar genom System.Collections.Generic.List. |
| [removeAt](#removeAt-int-) | Tar bort elementet på det angivna indexet i System.Collections.Generic.List. |
| [removeItem](#removeItem-T-) | Tar bort den första förekomsten av ett specifikt objekt från System.Collections.Generic.List. |
| [set_Item](#set_Item-int-T-) | Hämtar eller anger stycke från eller till samlingen. |
| [size](#size--) | Hämtar antalet element som finns i System.Collections.Generic.List. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-) | Uppdaterar parametern boundsCheckMode för den initierade samlingen. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-double-double-) | Uppdaterar parametern boundsCheckMode för den initierade samlingen. |

### BoundsCheckableList {#BoundsCheckableList--}
```
public BoundsCheckableList()
```

Initierar en ny instans av BoundsCheckableList-klassen.

### BoundsCheckableList {#BoundsCheckableList-int-double-double-}
```
public BoundsCheckableList(int boundsCheckMode, double containerWidth, double containerHeight)
```

Initierar en ny instans av BoundsCheckableList-klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| boundsCheckMode |  | Gräns cCheck-läget. |
| containerWidth |  | Behållarens bredd. |
| containerHeight |  | Behållarens höjd. |

### addItem {#addItem-T-}
```
public final void addItem( T item)
```

Lägger till ett objekt i slutet av System.Collections.Generic.List beroende på parametern "boundsCheckMode".

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item |  | Objektet som ska läggas till i slutet av System.Collections.Generic.List. Värdet kan vara "null" för referenstyper. |

### clear {#clear--}
```
public final void clear()
```

Tar bort alla element från System.Collections.Generic.List.

### containsItem {#containsItem-T-}
```
public final boolean containsItem( T item)
```

Avgör om ett element finns i System.Collections.Generic.List.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item |  | Objektet att leta efter i System.Collections.Generic.List. Värdet kan vara null för referenstyper. |

**Returns:**
Sant om itemitem hittas i System.Collections.Generic.List; annars falskt.

### copyToTArray {#copyToTArray-T:A-int-}
```
public final void copyToTArray( T [] array, int arrayIndex)
```

Kopierar hela System.Collections.Generic.List till en kompatibel endimensionell array, med start vid det angivna indexet i målarrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array |  | Den endimensionella System.Array som är destinationen för elementen som kopieras från System.Collections.Generic.List. System.Array måste ha nollbaserad indexering. |
| arrayIndex |  | Det nollbaserade indexet i array där kopieringen börjar. |

### get_Item {#get_Item-int-}
```
public final T get_Item(int index)
```

Hämtar eller anger stycke från eller till samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Paragrafindexet. |

**Returns:**
elementet vid det angivna indexet.

### indexOfItem {#indexOfItem-T-}
```
public final int indexOfItem( T item)
```

Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten i hela System.Collections.Generic.List.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item |  | Objektet att leta efter i System.Collections.Generic.List. Värdet kan vara null för referenstyper. |

**Returns:**
Det nollbaserade indexet för den första förekomsten av itemitem i hela System.Collections.Generic.List, om den hittas; annars –1.

### insertItem {#insertItem-int-T-}
```
public final void insertItem(int index, T item)
```

Infogar ett element i System.Collections.Generic.List på det angivna indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Det nollbaserade indexet där item ska infogas. |
| item |  | Objektet att infoga. Värdet kan vara null för referenstyper. |

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Hämtar värdet som indikerar om samlingen är skrivskyddad.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< T > iterator()
```

Returnerar en enumerator som itererar genom System.Collections.Generic.List.

**Returns:**
En Enumerator för System.Collections.Generic.List.

### removeAt {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort elementet på det angivna indexet i System.Collections.Generic.List.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Det nollbaserade indexet för elementet som ska tas bort. |

### removeItem {#removeItem-T-}
```
public final boolean removeItem( T item)
```

Tar bort den första förekomsten av ett specifikt objekt från System.Collections.Generic.List.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item |  | Objektet att ta bort från System.Collections.Generic.List. Värdet kan vara null för referenstyper. |

**Returns:**
Sant om itemitem har tagits bort framgångsrikt; annars falskt. Denna metod returnerar också falskt om itemitem inte hittades i System.Collections.Generic.List.

### set_Item {#set_Item-int-T-}
```
public final void set_Item(int index, T value)
```

Hämtar eller anger stycke från eller till samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Paragrafindexet. |

### size {#size--}
```
public final int size()
```

Hämtar antalet element som finns i System.Collections.Generic.List.

**Returns:**
Antalet element som finns i System.Collections.Generic.List.

### updateBoundsCheckMode {#updateBoundsCheckMode-int-}
```
public final void updateBoundsCheckMode(int boundsCheckMode)
```

Uppdaterar parametern boundsCheckMode för den initierade samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| boundsCheckMode |  | Gränskontrollläget. |

### updateBoundsCheckMode {#updateBoundsCheckMode-int-double-double-}
```
public final void updateBoundsCheckMode(int boundsCheckMode, double containerWidth, double containerHeight)
```

Uppdaterar parametern boundsCheckMode för den initierade samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| boundsCheckMode |  | Gränskontrollläget. |
| containerWidth |  | Behållarens bredd. |
| containerHeight |  | Behållarens höjd. |
