---
title: "AnnotationCollection"
linktitle: "AnnotationCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar en annoteringssamling."
type: docs
weight: 80
url: /sv/java/com.aspose.pdf/annotationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationCollection

**All Implemented Interfaces:**
Iterable < Annotation >

```
public final class AnnotationCollection extends Object implements Iterable < Annotation >
```

Klass som representerar en annoteringssamling.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [AnnotationCollection](#AnnotationCollection-com.aspose.pdf.Page-) | Konstruktor för AnnotationCollection. Skapar en annoteringssamling för annoteringar på den angivna sidan. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepterar en besökare för att bearbeta annoteringen. |
| [add](#add-com.aspose.pdf.Annotation-) | Lägger till annotering i samlingen. |
| [add](#add-com.aspose.pdf.Annotation-boolean-) | Lägger till annotering i samlingen. Om sidan är roterad kommer annoteringsrektangeln att omräknas därefter. |
| [clear](#clear--) | Tar bort alla annoteringar från samlingen. |
| [contains](#contains-com.aspose.pdf.Annotation-) | Kontrollerar om angiven annotering tillhör samlingen. |
| [copyTo](#copyTo-com.aspose.pdf.Annotation:A-int-) | Kopierar en array av annoteringar till samlingen. |
| [delete](#delete--) | Tar bort alla annoteringar från samlingen. |
| [delete](#delete-com.aspose.pdf.Annotation-) | Tar bort alla annoteringar från samlingen. |
| [delete](#delete-int-) | Tar bort annotering från samlingen efter index. |
| [findByName](#findByName-java.lang.String-) | Returnerar annotering efter dess namn. |
| [get_Item](#get_Item-int-) | Indexet för elementet som ska hämtas. |
| [getSyncRoot](#getSyncRoot--) | Hämtar ett objekt som kan användas för att synkronisera åtkomst till com.aspose.pdf.AnnotationCollection. |
| [isReadOnly](#isReadOnly--) | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [isSynchronized](#isSynchronized--) | Hämtar ett värde som indikerar om åtkomst till com.aspose.pdf.AnnotationCollection är synkroniserad (trådsäker). |
| [iterator](#iterator--) | Returnerar samlingens enumerator. |
| [remove](#remove-com.aspose.pdf.Annotation-) | Tar bort angiven annotation från samlingen. |
| [size](#size--) | Hämtar antalet annotationer i samlingen. |

### AnnotationCollection {#AnnotationCollection-com.aspose.pdf.Page-}
Konstruktor för AnnotationCollection. Skapar en annoteringssamling för annoteringar på den angivna sidan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepterar en besökare för att bearbeta annoteringen.

### add {#add-com.aspose.pdf.Annotation-}
Lägger till annotering i samlingen.

### add {#add-com.aspose.pdf.Annotation-boolean-}
Lägger till annotering i samlingen. Om sidan är roterad kommer annoteringsrektangeln att omräknas därefter.

### clear {#clear--}
```
public void clear()
```

Tar bort alla annoteringar från samlingen.

### contains {#contains-com.aspose.pdf.Annotation-}
Kontrollerar om angiven annotering tillhör samlingen.

### copyTo {#copyTo-com.aspose.pdf.Annotation:A-int-}
Kopierar en array av annoteringar till samlingen.

### delete {#delete--}
```
public void delete()
```

Tar bort alla annoteringar från samlingen.

### delete {#delete-com.aspose.pdf.Annotation-}
Tar bort alla annoteringar från samlingen.

### delete {#delete-int-}
```
public void delete(int index)
```

Tar bort annotering från samlingen efter index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index för annotation som ska tas bort. |

### findByName {#findByName-java.lang.String-}
Returnerar annotering efter dess namn.

### get_Item {#get_Item-int-}
```
public Annotation get_Item(int index)
```

Indexet för elementet som ska hämtas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Indexvärdet börjar från ett. |

**Returns:**
Annotationsobjekt

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Hämtar ett objekt som kan användas för att synkronisera åtkomst till com.aspose.pdf.AnnotationCollection.

**Returns:**
Objekt för synkronisering

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

Hämtar ett värde som indikerar om åtkomst till com.aspose.pdf.AnnotationCollection är synkroniserad (trådsäker).

**Returns:**
booleskt värde

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< Annotation > iterator()
```

Returnerar samlingens enumerator.

**Returns:**
Enumeratorobjekt

### remove {#remove-com.aspose.pdf.Annotation-}
Tar bort angiven annotation från samlingen.

### size {#size--}
```
public int size()
```

Hämtar antalet annotationer i samlingen.

**Returns:**
int‑värde
