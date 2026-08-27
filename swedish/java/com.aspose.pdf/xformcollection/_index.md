---
title: "XFormCollection"
linktitle: "XFormCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen representerar en samling av XFormCollection."
type: docs
weight: 5600
url: /sv/java/com.aspose.pdf/xformcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFormCollection

**All Implemented Interfaces:**
Iterable < XForm >

```
public final class XFormCollection extends Object implements Iterable < XForm >
```

Klassen representerar en samling av XFormCollection.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.XForm-) | Lägger till en ny XForm i samlingen. |
| [clear](#clear--) | Rensar alla objekt från samlingen. |
| [contains](#contains-com.aspose.pdf.XForm-) | Avgör om samlingen innehåller ett specifikt värde. |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | Kopierar XFormCollection till samlingen. |
| [delete](#delete--) | Tar bort alla XForms från samlingen. |
| [delete](#delete-int-) | Ta bort XForm från samlingen. |
| [delete](#delete-java.lang.String-) | Tar bort alla XForms från samlingen. |
| [freeMemory](#freeMemory--) | Rensar cachad data, frigör minne osv. |
| [get_Item](#get_Item-int-) | Returnerar XForm efter index. |
| [get_Item](#get_Item-java.lang.String-) | Returnerar XForm efter dess namn. Ett undantag kastas om XForm med angivet namn inte hittas. |
| [getFormName](#getFormName-com.aspose.pdf.XForm-) | Returnerar namnet på formuläret i denna formulärsamling |
| [getSyncRoot](#getSyncRoot--) | Synkroniseringsobjekt. |
| [hasForm](#hasForm-java.lang.String-) |  |
| [isReadOnly](#isReadOnly--) | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [isSynchronized](#isSynchronized--) | Returnerar true om objektet är synkroniserat. |
| [iterator](#iterator--) | Returnerar samlingens enumerator. |
| [remove](#remove-com.aspose.pdf.XForm-) | Tar bort specificerat objekt från samlingen. |
| [size](#size--) | Hämtar antalet XForms i samlingen. |

### add {#add-com.aspose.pdf.XForm-}
Lägger till en ny XForm i samlingen.

### clear {#clear--}
```
public void clear()
```

Rensar alla objekt från samlingen.

### contains {#contains-com.aspose.pdf.XForm-}
Avgör om samlingen innehåller ett specifikt värde.

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
Kopierar XFormCollection till samlingen.

### delete {#delete--}
```
public void delete()
```

Tar bort alla XForms från samlingen.

### delete {#delete-int-}
```
public void delete(int index)
```

Ta bort XForm från samlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index för XForm som ska tas bort |

### delete {#delete-java.lang.String-}
Tar bort alla XForms från samlingen.

### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

Rensar cachad data, frigör minne osv.

### get_Item {#get_Item-int-}
```
public XForm get_Item(int index)
```

Returnerar XForm efter index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index för XFormCollection. XForms numrering startar från 1 |

**Returns:**
Hämtad XForm

### get_Item {#get_Item-java.lang.String-}
Returnerar XForm efter dess namn. Ett undantag kastas om XForm med angivet namn inte hittas.

### getFormName {#getFormName-com.aspose.pdf.XForm-}
Returnerar namnet på formuläret i denna formulärsamling

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Synkroniseringsobjekt.

**Returns:**
Object

### hasForm {#hasForm-java.lang.String-}


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

Returnerar true om objektet är synkroniserat.

**Returns:**
boolean

### iterator {#iterator--}
```
public Iterator < XForm > iterator()
```

Returnerar samlingens enumerator.

**Returns:**
Enumerator för samlingen

### remove {#remove-com.aspose.pdf.XForm-}
Tar bort specificerat objekt från samlingen.

### size {#size--}
```
public int size()
```

Hämtar antalet XForms i samlingen.

**Returns:**
int‑värde
