---
title: "FontCollection"
linktitle: "FontCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Representerar teckensamlingssamling. </p> <hr> <pre> Exemplet visar hur man gör alla teckensnitt som deklarerats på sidan inbäddade. // Open document Document doc = new."
type: docs
weight: 1670
url: /sv/java/com.aspose.pdf/fontcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontCollection

**All Implemented Interfaces:**
Iterable < Font >

```
public final class FontCollection extends Object implements Iterable < Font >
```

<p> Representerar teckensamlingssamling. </p> <hr> <pre> Exemplet visar hur man gör alla teckensnitt som deklarerats på sidan inbäddade. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // säkerställ att alla teckensnitt som deklarerats i sidresurser är inbäddade // observera att om teckensnitt deklareras i formulärresurser är de inte åtkomliga från sidresurser for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save("D:\\Tests\\input.pdf"); </pre> <hr> <p> Teckensamlingssamlingar som representeras av {@code FontCollection}-klassen används i flera scenarier. Till exempel i resurser med {@code Resources.Fonts}-egenskapen. </p>

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.Font-) | Lägger till teckensnitt i samlingen. |
| [add](#add-com.aspose.pdf.Font-java.lang.String:A-) | Lägger till ett nytt teckensnitt i teckensnittresurserna och returnerar det automatiskt tilldelade namnet på teckensnittresursen. |
| [add](#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-) | Lägg till nytt teckensnitt i teckensamlingssamlingen. |
| [add](#add-java.lang.String-java.lang.String-) | Lägger till en ny teckensnittspost i teckensnittresurserna med angivet grundteckensnittsnamn. |
| [clear_Rename_Namesake](#clear_Rename_Namesake--) | / * / * Lägger till teckensnitt i samlingen. / * / * |
| [contains](#contains-com.aspose.pdf.Font-) | Avgör om samlingen innehåller ett specifikt värde. |
| [contains](#contains-java.lang.String-) | Kontrollerar om teckensnittet finns i teckensamlingssamlingen. |
| [copyTo](#copyTo-com.aspose.pdf.Font:A-int-) | Kopierar hela samlingen till en kompatibel endimensionell Array, med start vid det angivna indexet i målarrayen. |
| [delete](#delete-java.lang.String-) | Tar bort teckensnitt med angivet resursnamn |
| [get_Item](#get_Item-int-) | Hämtar teckensnittselementet på det angivna indexet. |
| [get_Item](#get_Item-java.lang.String-) | Hämtar teckensnitt från samlingen med teckensnittsnamn. Undantag kastas om teckensnittet inte hittades. |
| [getFontsDictionary](#getFontsDictionary--) | Hämta IPdfDictionary-objekt |
| [getHash](#getHash--) |  |
| [getSyncRoot](#getSyncRoot--) | Hämtar ett objekt som kan användas för att synkronisera åtkomst till samlingen. |
| [isReadOnly](#isReadOnly--) | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [isSynchronized](#isSynchronized--) | Hämtar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Returnerar en enumerator för hela samlingen. |
| [iterator](#iterator--) | Returnerar en enumerator för hela samlingen. |
| [remove](#remove-com.aspose.pdf.Font-) | Tar bort specificerat objekt från samlingen. |
| [size](#size--) | Hämtar antalet {@code Font}-objektelement som faktiskt finns i samlingen. |

### add {#add-com.aspose.pdf.Font-}
Lägger till teckensnitt i samlingen.

### add {#add-com.aspose.pdf.Font-java.lang.String:A-}
Lägger till ett nytt teckensnitt i teckensnittresurserna och returnerar det automatiskt tilldelade namnet på teckensnittresursen.

### add {#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-}
Lägg till nytt teckensnitt i teckensamlingssamlingen.

### add {#add-java.lang.String-java.lang.String-}
Lägger till en ny teckensnittspost i teckensnittresurserna med angivet grundteckensnittsnamn.

### clear_Rename_Namesake {#clear_Rename_Namesake--}
```
public void clear_Rename_Namesake()
```

/ * / * Lägger till teckensnitt i samlingen. / * / *

### contains {#contains-com.aspose.pdf.Font-}
Avgör om samlingen innehåller ett specifikt värde.

### contains {#contains-java.lang.String-}
Kontrollerar om teckensnittet finns i teckensamlingssamlingen.

### copyTo {#copyTo-com.aspose.pdf.Font:A-int-}
Kopierar hela samlingen till en kompatibel endimensionell Array, med start vid det angivna indexet i målarrayen.

### delete {#delete-java.lang.String-}
Tar bort teckensnitt med angivet resursnamn

### get_Item {#get_Item-int-}
```
public Font get_Item(int index)
```

Hämtar teckensnittselementet på det angivna indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index inom samlingen. |

**Returns:**
Teckensnittobjekt.

### get_Item {#get_Item-java.lang.String-}
Hämtar teckensnitt från samlingen med teckensnittsnamn. Undantag kastas om teckensnittet inte hittades.

### getFontsDictionary {#getFontsDictionary--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getFontsDictionary()
```

Hämta IPdfDictionary-objekt

**Returns:**
IPdfDictionary‑objekt

### getHash {#getHash--}
```
public com.aspose.pdf.engine.collections.HashDictionary< String , Font > getHash()
```



### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Hämtar ett objekt som kan användas för att synkronisera åtkomst till samlingen.

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

Hämtar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker).

**Returns:**
booleskt värde

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Returnerar en enumerator för hela samlingen.

**Returns:**
Enumerator‑objekt.

### iterator {#iterator--}
```
public Iterator < Font > iterator()
```

Returnerar en enumerator för hela samlingen.

**Returns:**
Enumerator‑objekt.

### remove {#remove-com.aspose.pdf.Font-}
Tar bort specificerat objekt från samlingen.

### size {#size--}
```
public int size()
```

Hämtar antalet {@code Font}-objektelement som faktiskt finns i samlingen.

**Returns:**
int‑värde
