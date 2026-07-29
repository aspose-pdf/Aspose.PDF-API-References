---
title: "CosPdfDictionary"
linktitle: "CosPdfDictionary"
second_title: "Aspose.PDF för Java API-referens"
description: "En klass för åtkomst till ett objekts ordbok."
type: docs
weight: 20
url: /sv/java/com.aspose.pdf.dataeditor/cospdfdictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.dataeditor.CosPdfPrimitive com.aspose.pdf.dataeditor.CosPdfDictionary, com.aspose.pdf.dataeditor.CosPdfPrimitive, com.aspose.pdf.dataeditor.CosPdfDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, ICosPdfPrimitive >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, ICosPdfPrimitive, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>

```
public class CosPdfDictionary extends CosPdfPrimitive implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , ICosPdfPrimitive >
```

En klass för åtkomst till ett objekts ordbok.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [CosPdfDictionary](#CosPdfDictionary-com.aspose.pdf.Resources-) | Skapar en ordbok från resurser. @exception ArgumentNullException Resurserna är null. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Ange ICosPdfPrimitive till ordbok. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Ställ in {@link ICosPdfPrimitive} i ordboken. @exception ArgumentException Kasta undantag om nyckel/värde inte kan redigeras eller tas bort. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Lägg till postpar. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Lägg till post. |
| [clear](#clear--) | Tar bort alla poster från {@link CosPdfDictionary}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Avgör om CosPdfDictionary innehåller ett specifikt värde. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Returnerar true om den innehåller en post |
| [containsKey](#containsKey-java.lang.String-) | Avgör om {@link CosPdfDictionary} innehåller ett element med den angivna nyckeln. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Kopierar elementen i CosPdfDictionary till en Array, med start vid ett specifikt Array-index. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Kopiera till Array |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Document-) | Skapar en tom ordbok som kommer att bifogas dokumentet. |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Page-) | Skapar en tom ordbok som kommer att bifogas sidan. |
| [get_Item](#get_Item-java.lang.String-) | Hämtar eller anger elementet med den angivna nyckeln. |
| [getAllKeys](#getAllKeys--) | Fullständig samling av nycklar. Innehåller redigerbara och icke-redigerbara nycklar. |
| [getKeys](#getKeys--) | Samling av redigerbara nycklar. |
| [getValues](#getValues--) | Hämtar en {@link ICollection} som innehåller värdena i {@link CosPdfDictionary}. |
| [isReadOnly](#isReadOnly--) | Hämtar ett värde som indikerar om {@link CosPdfDictionary} är skrivskyddad. |
| [iterator](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Tar bort den första förekomsten av ett specifikt objekt från CosPdfDictionary . |
| [remove](#remove-java.lang.String-) | Tar bort elementet med den angivna nyckeln från {@link CosPdfDictionary}. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Ta bort post |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Ta bort post efter nyckel. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Hämtar eller anger elementet med den angivna nyckeln. @exception ArgumentNullException Nyckeln är null. @exception KeyNotFoundException Egenskapen hämtas och nyckeln hittas inte. @exception ArgumentException Kasta undantag om nyckeln inte kan redigeras/anges. |
| [size](#size--) | Hämtar antalet element som finns i {@link CosPdfDictionary}. |
| [toCosPdfDictionary](#toCosPdfDictionary--) | Försöker kasta detta objekt till {@link CosPdfDictionary}. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | För åtkomst till enkla datatyper som string, name, bool, number. Returnerar null för andra typer. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Försök att hämta värdet |

### CosPdfDictionary {#CosPdfDictionary-com.aspose.pdf.Resources-}
Skapar en ordbok från resurser. @exception ArgumentNullException Resurserna är null.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Ange ICosPdfPrimitive till ordbok.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Ställ in {@link ICosPdfPrimitive} i ordboken. @exception ArgumentException Kasta undantag om nyckel/värde inte kan redigeras eller tas bort.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Lägg till postpar.

### addItem {#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Lägg till post.

### clear {#clear--}
```
public final void clear()
```

Tar bort alla poster från {@link CosPdfDictionary}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Avgör om CosPdfDictionary innehåller ett specifikt värde.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Returnerar true om den innehåller en post

### containsKey {#containsKey-java.lang.String-}
Avgör om {@link CosPdfDictionary} innehåller ett element med den angivna nyckeln.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Kopierar elementen i CosPdfDictionary till en Array, med start vid ett specifikt Array-index.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Kopiera till Array

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Document-}
Skapar en tom ordbok som kommer att bifogas dokumentet.

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Page-}
Skapar en tom ordbok som kommer att bifogas sidan.

### get_Item {#get_Item-java.lang.String-}
Hämtar eller anger elementet med den angivna nyckeln.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Fullständig samling av nycklar. Innehåller redigerbara och icke-redigerbara nycklar.

**Returns:**
Lista med String-värden

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Samling av redigerbara nycklar.

**Returns:**
Lista med String-värden

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

Hämtar en {@link ICollection} som innehåller värdena i {@link CosPdfDictionary}.

**Returns:**
Lista över ICosPdfPrimitive-instansier

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Hämtar ett värde som indikerar om {@link CosPdfDictionary} är skrivskyddad.

**Returns:**
true om {@link CosPdfDictionary} är skrivskyddad; annars false.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returns:**
En enumerator som kan användas för att iterera genom samlingen.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Tar bort den första förekomsten av ett specifikt objekt från CosPdfDictionary .

### remove {#remove-java.lang.String-}
Tar bort elementet med den angivna nyckeln från {@link CosPdfDictionary}.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Ta bort post

### removeItemByKey {#removeItemByKey-java.lang.String-}
Ta bort post efter nyckel.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Hämtar eller anger elementet med den angivna nyckeln. @exception ArgumentNullException Nyckeln är null. @exception KeyNotFoundException Egenskapen hämtas och nyckeln hittas inte. @exception ArgumentException Kasta undantag om nyckeln inte kan redigeras/anges.

### size {#size--}
```
public final int size()
```

Hämtar antalet element som finns i {@link CosPdfDictionary}.

**Returns:**
int‑värde

### toCosPdfDictionary {#toCosPdfDictionary--}
```
public CosPdfDictionary toCosPdfDictionary()
```

Försöker kasta detta objekt till {@link CosPdfDictionary}.

**Returns:**
null om objektet inte är {@link CosPdfDictionary} annars {@link CosPdfDictionary}.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
För åtkomst till enkla datatyper som string, name, bool, number. Returnerar null för andra typer.

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Försök att hämta värdet
