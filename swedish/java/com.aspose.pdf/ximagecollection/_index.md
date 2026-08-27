---
title: "XImageCollection"
linktitle: "XImageCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen som representerar XImage-samling."
type: docs
weight: 5630
url: /sv/java/com.aspose.pdf/ximagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XImageCollection

**All Implemented Interfaces:**
Iterable < XImage >

```
public final class XImageCollection extends Object implements Iterable < XImage >
```

Klassen som representerar XImage-samling.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.BitmapInfo-) | Lägger till enhet i slutet av samlingen, så enheten kan nås via det sista indexet. |
| [add](#add-com.aspose.pdf.BitmapInfo-com.aspose.pdf.ImageFilterType-) | Lägger till enhet i slutet av samlingen, så enheten kan nås via det sista indexet. |
| [add](#add-java.awt.image.BufferedImage-) | Lägger till enhet i slutet av samlingen, så enheten kan nås via det sista indexet. |
| [add](#add-java.awt.image.BufferedImage-com.aspose.pdf.ImageFilterType-) | Lägger till enhet i slutet av samlingen, så enheten kan nås via det sista indexet. |
| [add](#add-java.io.InputStream-) | Lägger till enhet i slutet av samlingen, så enheten kan nås via det sista indexet. |
| [add](#add-java.io.InputStream-com.aspose.pdf.ImageFilterType-) | Lägger till enhet i slutet av samlingen, så enheten kan nås via det sista indexet. |
| [add](#add-java.io.InputStream-int-) | Lägger till enhet i slutet av samlingen, så enheten kan nås via det sista indexet. |
| [add](#add-com.aspose.pdf.XImage-) | Lägger till ny bild i bildlistan. Denna metod lägger till bilden som referens till samma PdfObject (vilket möjliggör minskad filstorlek). |
| [add](#add-com.aspose.pdf.engine.XImageAddingParams-java.lang.String:A-) |  |
| [addWithImageFilterType](#addWithImageFilterType-java.io.InputStream-com.aspose.pdf.ImageFilterType-) | Lägger till enhet i slutet av samlingen, så enheten kan nås via det sista indexet. |
| [clear](#clear--) | Rensar alla objekt från samlingen. |
| [contains](#contains-com.aspose.pdf.XImage-) | Avgör om samlingen innehåller ett specifikt värde. |
| [copyTo](#copyTo-com.aspose.pdf.XImage:A-int-) | Kopierar bildarray till samlingen. |
| [delete](#delete--) | Tar bort bilder från samlingen. |
| [delete](#delete-int-) | Tar bort index från samlingen med index. |
| [delete](#delete-int-int-) | Tar bort index från samlingen med index och utför den åtgärd som anges av action-parameter. |
| [delete](#delete-java.lang.String-) | Tar bort bilder från samlingen. |
| [delete](#delete-java.lang.String-int-) | Tar bort bilder från samlingen. |
| [get_Item](#get_Item-int-) | Hämtar bild från samlingen efter dess index. |
| [get_Item](#get_Item-java.lang.String-) | Hämtar bild från samlingen efter dess namn. |
| [getImageName](#getImageName-com.aspose.pdf.XImage-) | Returnerar namn i bildlistan som är nyckeln för den angivna bilden. |
| [getNames](#getNames--) | Hämtar en array med bildnamn. |
| [getSyncRoot](#getSyncRoot--) | Returnerar synkroniseringsobjekt. |
| [hasImage](#hasImage-java.lang.String-) |  |
| [isReadOnly](#isReadOnly--) | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [isSynchronized](#isSynchronized--) | Returnerar true om objektet är synkroniserat. |
| [iterator](#iterator--) | Returnerar samlingens enumerator. |
| [remove](#remove-com.aspose.pdf.XImage-) | Stöds ännu inte, kastar undantag. Kastar alltid NotImplementedException |
| [replace](#replace-int-java.io.InputStream-) | Ersätt Image i samlingen med en annan Image. |
| [replace](#replace-int-java.io.InputStream-int-) | Ersätt Image i samlingen med en annan Image. |
| [replace](#replace-int-java.io.InputStream-int-boolean-) | Ersätt Image i samlingen med en annan Image. |
| [saveJpxWithQuality](#saveJpxWithQuality-com.aspose.ms.System.Drawing.Image-) |  |
| [size](#size--) | Antal bilder i samlingen. |

### add {#add-com.aspose.pdf.BitmapInfo-}
Lägger till enhet i slutet av samlingen, så enheten kan nås via det sista indexet.

### add {#add-com.aspose.pdf.BitmapInfo-com.aspose.pdf.ImageFilterType-}
Lägger till enhet i slutet av samlingen, så enheten kan nås via det sista indexet.

### add {#add-java.awt.image.BufferedImage-}
Lägger till enhet i slutet av samlingen, så enheten kan nås via det sista indexet.

### add {#add-java.awt.image.BufferedImage-com.aspose.pdf.ImageFilterType-}
Lägger till enhet i slutet av samlingen, så enheten kan nås via det sista indexet.

### add {#add-java.io.InputStream-}
Lägger till enhet i slutet av samlingen, så enheten kan nås via det sista indexet.

### add {#add-java.io.InputStream-com.aspose.pdf.ImageFilterType-}
Lägger till enhet i slutet av samlingen, så enheten kan nås via det sista indexet.

### add {#add-java.io.InputStream-int-}
Lägger till enhet i slutet av samlingen, så enheten kan nås via det sista indexet.

### add {#add-com.aspose.pdf.XImage-}
Lägger till ny bild i bildlistan. Denna metod lägger till bilden som referens till samma PdfObject (vilket möjliggör minskad filstorlek).

### add {#add-com.aspose.pdf.engine.XImageAddingParams-java.lang.String:A-}


### addWithImageFilterType {#addWithImageFilterType-java.io.InputStream-com.aspose.pdf.ImageFilterType-}
Lägger till enhet i slutet av samlingen, så enheten kan nås via det sista indexet.

### clear {#clear--}
```
public void clear()
```

Rensar alla objekt från samlingen.

### contains {#contains-com.aspose.pdf.XImage-}
Avgör om samlingen innehåller ett specifikt värde.

### copyTo {#copyTo-com.aspose.pdf.XImage:A-int-}
Kopierar bildarray till samlingen.

### delete {#delete--}
```
public void delete()
```

Tar bort bilder från samlingen.

### delete {#delete-int-}
```
public void delete(int index)
```

Tar bort index från samlingen med index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Bildindex. |

### delete {#delete-int-int-}
```
public final void delete(int index, int action)
```

Tar bort index från samlingen med index och utför den åtgärd som anges av action-parameter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index för bilden som ska tas bort. |
| åtgärd |  | ImageDeleteAction-element. Åtgärd som utförs efter att bilden har tagits bort. |

### delete {#delete-java.lang.String-}
Tar bort bilder från samlingen.

### delete {#delete-java.lang.String-int-}
Tar bort bilder från samlingen.

### get_Item {#get_Item-int-}
```
public XImage get_Item(int index)
```

Hämtar bild från samlingen efter dess index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Bildindex |

**Returns:**
Hämtad bild.

### get_Item {#get_Item-java.lang.String-}
Hämtar bild från samlingen efter dess namn.

### getImageName {#getImageName-com.aspose.pdf.XImage-}
Returnerar namn i bildlistan som är nyckeln för den angivna bilden.

### getNames {#getNames--}
```
public String [] getNames()
```

Hämtar en array med bildnamn.

**Returns:**
String[] array

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Returnerar synkroniseringsobjekt.

**Returns:**
Objektelement

### hasImage {#hasImage-java.lang.String-}


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
booleskt värde

### iterator {#iterator--}
```
public Iterator < XImage > iterator()
```

Returnerar samlingens enumerator.

**Returns:**
Enumerator för samling

### remove {#remove-com.aspose.pdf.XImage-}
Stöds ännu inte, kastar undantag. Kastar alltid NotImplementedException

### replace {#replace-int-java.io.InputStream-}
Ersätt Image i samlingen med en annan Image.

### replace {#replace-int-java.io.InputStream-int-}
Ersätt Image i samlingen med en annan Image.

### replace {#replace-int-java.io.InputStream-int-boolean-}
Ersätt Image i samlingen med en annan Image.

### saveJpxWithQuality {#saveJpxWithQuality-com.aspose.ms.System.Drawing.Image-}


### size {#size--}
```
public int size()
```

Antal bilder i samlingen.

**Returns:**
int‑värde
