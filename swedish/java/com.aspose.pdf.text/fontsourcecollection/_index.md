---
title: "FontSourceCollection"
linktitle: "FontSourceCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar samling av teckensnittskällor."
type: docs
weight: 40
url: /sv/java/com.aspose.pdf.text/fontsourcecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSourceCollection

**All Implemented Interfaces:**
Iterable < FontSource >

```
public final class FontSourceCollection extends Object implements Iterable < FontSource >
```

Representerar samling av teckensnittskällor.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [CollectionChanged](#CollectionChanged) | CollectionChanged händelse |

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FontSourceCollection](#FontSourceCollection--) | Initierar samlingsobjekt |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.FontSource-) | Lägger till ett nytt teckensnittskällobjekt i samlingen. |
| [clear](#clear--) | Rensar teckensnittskällsamlingen. |
| [contains](#contains-com.aspose.pdf.FontSource-) | Bestämmer om ett element finns i samlingen. |
| [copyTo](#copyTo-com.aspose.pdf.FontSource:A-int-) | Kopierar hela samlingen till en kompatibel endimensionell Array, med start vid det angivna indexet i målarrayen. |
| [delete](#delete-com.aspose.pdf.FontSource-) | Tar bort fontkäll-elementet. |
| [getItem](#getItem-int-) | Hämtar teckensnittselementet på det angivna indexet. |
| [getSyncRoot](#getSyncRoot--) | Hämtar ett objekt som kan användas för att synkronisera åtkomst till samlingen. |
| [isSynchronized](#isSynchronized--) | Hämtar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [iterator](#iterator--) | Returnerar en enumerator för hela samlingen. |
| [remove](#remove-com.aspose.pdf.FontSource-) | Tar bort fontkäll-elementet. |
| [size](#size--) | Hämtar antalet Font-objektelement som faktiskt finns i samlingen. |

### CollectionChanged {#CollectionChanged}
```
public final PdfEvent <com.aspose.ms.System.EventHandler> CollectionChanged
```

CollectionChanged händelse

### FontSourceCollection {#FontSourceCollection--}
```
public FontSourceCollection()
```

Initierar samlingsobjekt

### add {#add-com.aspose.pdf.FontSource-}
Lägger till ett nytt teckensnittskällobjekt i samlingen.

### clear {#clear--}
```
public void clear()
```

Rensar teckensnittskällsamlingen.

### contains {#contains-com.aspose.pdf.FontSource-}
Bestämmer om ett element finns i samlingen.

### copyTo {#copyTo-com.aspose.pdf.FontSource:A-int-}
Kopierar hela samlingen till en kompatibel endimensionell Array, med start vid det angivna indexet i målarrayen.

### delete {#delete-com.aspose.pdf.FontSource-}
Tar bort fontkäll-elementet.

### getItem {#getItem-int-}
```
public FontSource getItem(int index)
```

Hämtar teckensnittselementet på det angivna indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index inom samlingen. |

**Returns:**
Fontkällobjekt.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Hämtar ett objekt som kan användas för att synkronisera åtkomst till samlingen.

**Returns:**
Objektelement

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Hämtar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker).

**Returns:**
booleskt värde

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator()
```

Returnerar en enumerator för hela samlingen.

**Returns:**
Enumerator‑objekt.

### remove {#remove-com.aspose.pdf.FontSource-}
Tar bort fontkäll-elementet.

### size {#size--}
```
public int size()
```

Hämtar antalet Font-objektelement som faktiskt finns i samlingen.

**Returns:**
int‑värde
