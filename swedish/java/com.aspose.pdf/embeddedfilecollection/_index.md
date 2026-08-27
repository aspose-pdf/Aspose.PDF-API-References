---
title: "EmbeddedFileCollection"
linktitle: "EmbeddedFileCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar samling av inbäddade filer."
type: docs
weight: 1200
url: /sv/java/com.aspose.pdf/embeddedfilecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class EmbeddedFileCollection extends Object implements Iterable < FileSpecification >
```

Klass som representerar samling av inbäddade filer.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.FileSpecification-) | Lägger till inbäddad filspecificering i samlingen. |
| [add](#add-java.lang.String-com.aspose.pdf.FileSpecification-) | Lägger till fil i inbäddade filer med den angivna nyckeln. |
| [clear](#clear--) | Ta bort alla inbäddade filer från dokumentet. |
| [contains](#contains-com.aspose.pdf.FileSpecification-) | Avgör om samlingen innehåller angiven FileSpecification. Stöds inte. |
| [copyTo](#copyTo-com.aspose.pdf.FileSpecification:A-int-) | Kopierar array av FileSpecification-objekt till colleciton. |
| [delete](#delete--) | Ta bort alla inbäddade filer från dokumentet. |
| [delete](#delete-java.lang.String-) | Ta bort alla inbäddade filer från dokumentet. |
| [deleteByKey](#deleteByKey-java.lang.String-) | Raderar fil från samlingen med dess nyckel i samlingen. |
| [findByName](#findByName-java.lang.String-) | Returnerar inbäddad fil efter dess namn. |
| [get_Item](#get_Item-int-) | Hämtar inbäddad fil efter dess index. |
| [get_Item](#get_Item-java.lang.String-) | Hämtar inbäddad fil efter dess namn. |
| [getKeys](#getKeys--) | Returnerar lista över nycklar för filbilagor. |
| [getSyncRoot](#getSyncRoot--) | Hämtar ett objekt som kan användas för att synkronisera åtkomst till denna samling. |
| [isEmbeddedFilesExist](#isEmbeddedFilesExist--) | Kontrollera om strukturen för inbäddade filer finns. Returnera TRUE om strukturen finns, och FALSE om den inte finns. Om dokumentet aldrig har innehållit inbäddade filer – har denna struktur inte skapats och är frånvarande. |
| [isReadOnly](#isReadOnly--) | Bestämmer om samlingen är skrivskyddad. Returnerar alltid false. |
| [isSynchronized](#isSynchronized--) | Hämtar ett värde som indikerar om åtkomst till denna samling är synkroniserad (trådsäker). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Returnerar colleciton enumerator. |
| [iterator](#iterator--) | Returnerar colleciton enumerator. |
| [remove](#remove-com.aspose.pdf.FileSpecification-) | Tar bort specificerad FileSpecification från samlingen. Stöds inte. |
| [size](#size--) | Hämtar antalet inbäddade filer i samlingen. |

### add {#add-com.aspose.pdf.FileSpecification-}
Lägger till inbäddad filspecificering i samlingen.

### add {#add-java.lang.String-com.aspose.pdf.FileSpecification-}
Lägger till fil i inbäddade filer med den angivna nyckeln.

### clear {#clear--}
```
public void clear()
```

Ta bort alla inbäddade filer från dokumentet.

### contains {#contains-com.aspose.pdf.FileSpecification-}
Avgör om samlingen innehåller angiven FileSpecification. Stöds inte.

### copyTo {#copyTo-com.aspose.pdf.FileSpecification:A-int-}
Kopierar array av FileSpecification-objekt till colleciton.

### delete {#delete--}
```
public void delete()
```

Ta bort alla inbäddade filer från dokumentet.

### delete {#delete-java.lang.String-}
Ta bort alla inbäddade filer från dokumentet.

### deleteByKey {#deleteByKey-java.lang.String-}
Raderar fil från samlingen med dess nyckel i samlingen.

### findByName {#findByName-java.lang.String-}
Returnerar inbäddad fil efter dess namn.

### get_Item {#get_Item-int-}
```
public FileSpecification get_Item(int index)
```

Hämtar inbäddad fil efter dess index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index för inbäddad fil. Numrering startar från 1. |

**Returns:**
Hämtad inbäddad filspecificering

### get_Item {#get_Item-java.lang.String-}
Hämtar inbäddad fil efter dess namn.

### getKeys {#getKeys--}
```
public final List < String > getKeys()
```

Returnerar lista över nycklar för filbilagor.

**Returns:**
Lista med String-värden

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Hämtar ett objekt som kan användas för att synkronisera åtkomst till denna samling.

**Returns:**
Objekt för synkronisering

### isEmbeddedFilesExist {#isEmbeddedFilesExist--}
```
public boolean isEmbeddedFilesExist()
```

Kontrollera om strukturen för inbäddade filer finns. Returnera TRUE om strukturen finns, och FALSE om den inte finns. Om dokumentet aldrig har innehållit inbäddade filer – har denna struktur inte skapats och är frånvarande.

**Returns:**
booleskt värde

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Bestämmer om samlingen är skrivskyddad. Returnerar alltid false.

**Returns:**
booleskt värde

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Hämtar ett värde som indikerar om åtkomst till denna samling är synkroniserad (trådsäker).

**Returns:**
booleskt värde

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< FileSpecification > iterator_Rename_Namesake()
```

Returnerar colleciton enumerator.

**Returns:**
Enumerator för colleciton.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< FileSpecification > iterator()
```

Returnerar colleciton enumerator.

**Returns:**
Enumerator för colleciton.

### remove {#remove-com.aspose.pdf.FileSpecification-}
Tar bort specificerad FileSpecification från samlingen. Stöds inte.

### size {#size--}
```
public int size()
```

Hämtar antalet inbäddade filer i samlingen.

**Returns:**
int‑värde
