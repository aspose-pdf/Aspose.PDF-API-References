---
title: "CharInfoCollection"
linktitle: "CharInfoCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Representerar en samling av CharInfo-objekt. </p> <hr> <pre> Exemplet visar hur man itererar genom alla tecken och hämtar tecknet //open document Document."
type: docs
weight: 570
url: /sv/java/com.aspose.pdf/charinfocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CharInfoCollection

**All Implemented Interfaces:**
Iterable < CharInfo >

```
public final class CharInfoCollection extends Object implements Iterable < CharInfo >
```

<p> Representerar CharInfo-objektssamling. </p> <hr> <pre> Exemplet demonstrerar hur man itererar genom alla tecken och hämtar tecknet //open document Document pdfDocument = new Document(inFile); //create TextFragmentAbsorber object to collect all the text objects of the page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accept the absorber for all the pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //get the extracted text fragments TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //loop through the fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //loop through the segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //loop through the characters {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // print character position and rectangle info System.out.println("XIndent : " + charInfo.getPosition().getXIndent()); System.out.println("YIndent : " + charInfo.getPosition().getYIndent()); System.out.println("Width : " + charInfo.getRectangle().getWidth()); System.out.println("Height : " + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> Tillhandahåller åtkomst till positionsinformation för teckensegmentets tecken. </p>

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.CharInfo-) | Stöds ännu inte. Samlingen är skrivskyddad, kastar undantag. |
| [clear](#clear--) | Stöds ännu inte. Samlingen är skrivskyddad. Kastar alltid NotImplementedException. |
| [contains](#contains-com.aspose.pdf.CharInfo-) | Avgör om samlingen innehåller ett specifikt värde. |
| [copyTo](#copyTo-com.aspose.pdf.CharInfo:A-int-) | Kopierar hela samlingen till en kompatibel endimensionell Array, med start vid det angivna indexet i målarrayen. |
| [get_Item](#get_Item-int-) | Hämtar CharInfo‑elementet vid det angivna indexet 1..n. |
| [getSyncRoot](#getSyncRoot--) | Hämtar ett objekt som kan användas för att synkronisera åtkomst till samlingen. |
| [isReadOnly](#isReadOnly--) | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [isSynchronized](#isSynchronized--) | Hämtar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Returnerar en enumerator för hela samlingen. |
| [iterator](#iterator--) | Returnerar en enumerator för hela samlingen. |
| [remove](#remove-com.aspose.pdf.CharInfo-) | Stöds ännu inte. Samlingen är skrivskyddad, kastar undantag. |
| [size](#size--) | Hämtar antalet {@code CharInfo}-objektelement som faktiskt finns i samlingen. |

### add {#add-com.aspose.pdf.CharInfo-}
Stöds ännu inte. Samlingen är skrivskyddad, kastar undantag.

### clear {#clear--}
```
public void clear()
```

Stöds ännu inte. Samlingen är skrivskyddad. Kastar alltid NotImplementedException.

### contains {#contains-com.aspose.pdf.CharInfo-}
Avgör om samlingen innehåller ett specifikt värde.

### copyTo {#copyTo-com.aspose.pdf.CharInfo:A-int-}
Kopierar hela samlingen till en kompatibel endimensionell Array, med start vid det angivna indexet i målarrayen.

### get_Item {#get_Item-int-}
```
public CharInfo get_Item(int index)
```

Hämtar CharInfo‑elementet vid det angivna indexet 1..n.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index inom samlingen. |

**Returns:**
CharInfo‑objekt.

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
public com.aspose.ms.System.Collections.IEnumerator< CharInfo > iterator()
```

Returnerar en enumerator för hela samlingen.

**Returns:**
Enumerator‑objekt.

### remove {#remove-com.aspose.pdf.CharInfo-}
Stöds ännu inte. Samlingen är skrivskyddad, kastar undantag.

### size {#size--}
```
public int size()
```

Hämtar antalet {@code CharInfo}-objektelement som faktiskt finns i samlingen.

**Returns:**
int‑värde
