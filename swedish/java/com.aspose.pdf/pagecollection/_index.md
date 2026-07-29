---
title: "PageCollection"
linktitle: "PageCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "Samling av PDF‑dokumentets sidor."
type: docs
weight: 3340
url: /sv/java/com.aspose.pdf/pagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageCollection

**All Implemented Interfaces:**
Iterable < Page >

```
public final class PageCollection extends Object implements Iterable < Page >
```

Samling av PDF‑dokumentets sidor.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepterar {@code AnnotationSelector} besökarobjekt som tillhandahåller funktionalitet för att arbeta med annotationer. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Accepterar {@code ImagePlacementAbsorber} besökarobjekt som tillhandahåller funktionalitet för att arbeta med bildplaceringsobjekt. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | Accepterar {@code TextAbsorber} besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Accepterar {@code TextFragmentAbsorber} besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| [add_Rename_Namesake](#add_Rename_Namesake-com.aspose.pdf.Page-) | Lägger till sida i samlingen. |
| [add](#add--) | Lägger till en tom sida. Om dokumentet redan innehåller sidor med olika storlekar, kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor, kommer storleken på den första sidan att användas. |
| [add](#add-java.lang.Iterable-) | Lägger till en tom sida. Om dokumentet redan innehåller sidor med olika storlekar, kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor, kommer storleken på den första sidan att användas. |
| [add](#add-java.util.List-) | Lägger till en tom sida. Om dokumentet redan innehåller sidor med olika storlekar, kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor, kommer storleken på den första sidan att användas. |
| [add](#add-com.aspose.pdf.Page-) | Lägger till en tom sida. Om dokumentet redan innehåller sidor med olika storlekar, kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor, kommer storleken på den första sidan att användas. |
| [add](#add-com.aspose.pdf.Page:A-) | Lägger till en tom sida. Om dokumentet redan innehåller sidor med olika storlekar, kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor, kommer storleken på den första sidan att användas. |
| [beginUpdate](#beginUpdate--) | Uppdaterar när gruppändringar påbörjas. |
| [clear](#clear--) | Rensa sidinsamling. |
| [contains](#contains-com.aspose.pdf.Page-) | Bestämmer om denna instans innehåller objektet. |
| [copyTo](#copyTo-com.aspose.pdf.Page:A-int-) | Kopierar sidor till dokumentet. |
| [delete](#delete--) | Tar bort alla sidor från samlingen. |
| [delete](#delete-int-) | Ta bort angiven sida. |
| [delete](#delete-java.lang.Integer:A-) | Tar bort alla sidor från samlingen. |
| [endUpdate](#endUpdate--) | Uppdaterar när gruppändringar är slutförda. |
| [findByPdfObject](#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-) |  |
| [flatten](#flatten--) | Tar bort alla fält som finns på sidorna och placerar deras värden istället. |
| [freeMemory](#freeMemory--) | Rensar cachad data |
| [get_Item](#get_Item-int-) | Hämtar sida efter index. |
| [getSyncRoot](#getSyncRoot--) | Hämtar synkroniseringsobjektet för samlingen. |
| [getUnrestricted](#getUnrestricted-int-) | Returnerar sida efter dess index. {@code Page} |
| [indexOf](#indexOf-com.aspose.pdf.Page-) | <p> Returnerar index för den angivna sidan. </p> |
| [insert](#insert-int-) | Infoga en tom sida i samlingen på den angivna positionen. Om dokumentet redan innehåller sidor med olika storlekar, kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor, kommer storleken på den första sidan att användas. |
| [insert](#insert-int-java.lang.Iterable-) | Infogar sidor från samlingen i dokumentet. |
| [insert](#insert-int-java.util.List-) | Infogar sidor från samlingen i dokumentet. |
| [insert](#insert-int-com.aspose.pdf.Page-) | Infogar sida i sidinsamlingen på angiven plats. |
| [insert](#insert-int-com.aspose.pdf.Page:A-) | Infogar sidor från arrayen i dokumentet. |
| [isEmpty](#isEmpty--) | Returnerar TRUE om samlingen är tom. |
| [isReadOnly](#isReadOnly--) | Hämtar värde som indikerar om samlingen är skrivskyddad. Returnerar alltid falskt. |
| [isSynchronized](#isSynchronized--) | Returnerar true om objektet är synkroniserat. |
| [iterator](#iterator--) | Returnerar enumerator för sidor. |
| [remove](#remove-com.aspose.pdf.Page-) | Tar bort det angivna objektet, kastar undantag. |
| [size](#size--) | Hämtar antalet sidor i dokumentet. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepterar {@code AnnotationSelector} besökarobjekt som tillhandahåller funktionalitet för att arbeta med annotationer.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
Accepterar {@code ImagePlacementAbsorber} besökarobjekt som tillhandahåller funktionalitet för att arbeta med bildplaceringsobjekt.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
Accepterar {@code TextAbsorber} besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
Accepterar {@code TextFragmentAbsorber} besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt.

### add_Rename_Namesake {#add_Rename_Namesake-com.aspose.pdf.Page-}
Lägger till sida i samlingen.

### add {#add--}
```
public Page add()
```

Lägger till en tom sida. Om dokumentet redan innehåller sidor med olika storlekar, kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor, kommer storleken på den första sidan att användas.

**Returns:**
Sida tillagd.

### add {#add-java.lang.Iterable-}
Lägger till en tom sida. Om dokumentet redan innehåller sidor med olika storlekar, kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor, kommer storleken på den första sidan att användas.

**Returns:**
Sida tillagd.

### add {#add-java.util.List-}
Lägger till en tom sida. Om dokumentet redan innehåller sidor med olika storlekar, kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor, kommer storleken på den första sidan att användas.

**Returns:**
Sida tillagd.

### add {#add-com.aspose.pdf.Page-}
Lägger till en tom sida. Om dokumentet redan innehåller sidor med olika storlekar, kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor, kommer storleken på den första sidan att användas.

**Returns:**
Sida tillagd.

### add {#add-com.aspose.pdf.Page:A-}
Lägger till en tom sida. Om dokumentet redan innehåller sidor med olika storlekar, kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor, kommer storleken på den första sidan att användas.

**Returns:**
Sida tillagd.

### beginUpdate {#beginUpdate--}
```
public final void beginUpdate()
```

Uppdaterar när gruppändringar påbörjas.

### clear {#clear--}
```
public void clear()
```

Rensa sidinsamling.

### contains {#contains-com.aspose.pdf.Page-}
Bestämmer om denna instans innehåller objektet.

### copyTo {#copyTo-com.aspose.pdf.Page:A-int-}
Kopierar sidor till dokumentet.

### delete {#delete--}
```
public void delete()
```

Tar bort alla sidor från samlingen.

### delete {#delete-int-}
```
public void delete(int index)
```

Ta bort angiven sida.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Nummer på sidan som kommer att tas bort. Sidnummer börjar från 1. |

### delete {#delete-java.lang.Integer:A-}
Tar bort alla sidor från samlingen.

### endUpdate {#endUpdate--}
```
public final void endUpdate()
```

Uppdaterar när gruppändringar är slutförda.

### findByPdfObject {#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-}


### flatten {#flatten--}
```
public void flatten()
```

Tar bort alla fält som finns på sidorna och placerar deras värden istället.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Rensar cachad data

### get_Item {#get_Item-int-}
```
public Page get_Item(int index)
```

Hämtar sida efter index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index för sida. |

**Returns:**
Hämtad sida.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Hämtar synkroniseringsobjektet för samlingen.

**Returns:**
Objekt för synkronisering

### getUnrestricted {#getUnrestricted-int-}
```
public Page getUnrestricted(int index)
```

Returnerar sida efter dess index. {@code Page}

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index för begärd sida. Sidor är numrerade från 1. |

**Returns:**
Begärd sida

### indexOf {#indexOf-com.aspose.pdf.Page-}
<p> Returnerar index för den angivna sidan. </p>

### insert {#insert-int-}
```
public Page insert(int pageNumber)
```

Infoga en tom sida i samlingen på den angivna positionen. Om dokumentet redan innehåller sidor med olika storlekar, kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor, kommer storleken på den första sidan att användas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber |  | Position för den nya sidan. |

**Returns:**
Infogad sida.

### insert {#insert-int-java.lang.Iterable-}
Infogar sidor från samlingen i dokumentet.

### insert {#insert-int-java.util.List-}
Infogar sidor från samlingen i dokumentet.

### insert {#insert-int-com.aspose.pdf.Page-}
Infogar sida i sidinsamlingen på angiven plats.

### insert {#insert-int-com.aspose.pdf.Page:A-}
Infogar sidor från arrayen i dokumentet.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Returnerar TRUE om samlingen är tom.

**Returns:**
booleskt värde

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Hämtar värde som indikerar om samlingen är skrivskyddad. Returnerar alltid falskt.

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
public Iterator < Page > iterator()
```

Returnerar enumerator för sidor.

**Returns:**
Uppräkning av sidor

### remove {#remove-com.aspose.pdf.Page-}
Tar bort det angivna objektet, kastar undantag.

### size {#size--}
```
public int size()
```

Hämtar antalet sidor i dokumentet.

**Returns:**
int‑värde
