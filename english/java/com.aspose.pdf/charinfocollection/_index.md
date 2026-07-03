---
title: CharInfoCollection
second_title: Aspose.PDF for Java API Reference
description: <p> Represents CharInfo objects collection. </p> <hr> <pre> The example demonstrates how to iterate thought all the characters and retrieve the character //open document Document.
type: docs
weight: 570
url: /java/com.aspose.pdf/charinfocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CharInfoCollection

**All Implemented Interfaces:**
Iterable < CharInfo >

```
public final class CharInfoCollection extends Object implements Iterable < CharInfo >
```

<p> Represents CharInfo objects collection. </p> <hr> <pre> The example demonstrates how to iterate thought all the characters and retrieve the character //open document Document pdfDocument = new Document(inFile); //create TextFragmentAbsorber object to collect all the text objects of the page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accept the absorber for all the pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //get the extracted text fragments TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //loop through the fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //loop through the segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //loop through the characters {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // print character position and rectangle info System.out.println("XIndent : " + charInfo.getPosition().getXIndent()); System.out.println("YIndent : " + charInfo.getPosition().getYIndent()); System.out.println("Width : " + charInfo.getRectangle().getWidth()); System.out.println("Height : " + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> Provides access to positioning information of text segment characters. </p>

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.CharInfo-) | Not supported yet. Collection is read-only, throws exception. |
| [clear](#clear--) | Not supported yet. Collection is read-only. Always throws NotImplementedException. |
| [contains](#contains-com.aspose.pdf.CharInfo-) | Determines whether the collection contains a specific value. |
| [copyTo](#copyTo-com.aspose.pdf.CharInfo:A-int-) | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array |
| [get_Item](#get_Item-int-) | Gets the CharInfo element at the specified index 1..n. |
| [getSyncRoot](#getSyncRoot--) | Gets an object that can be used to synchronize access to the collection. |
| [isReadOnly](#isReadOnly--) | Gets a value indicating whether collection is read-only |
| [isSynchronized](#isSynchronized--) | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Returns an enumerator for the entire collection. |
| [iterator](#iterator--) | Returns an enumerator for the entire collection. |
| [remove](#remove-com.aspose.pdf.CharInfo-) | Not supported yet. Collection is read-only, throws exception. |
| [size](#size--) | Gets the number of {@code CharInfo} object elements actually contained in the collection. |

### add {#add-com.aspose.pdf.CharInfo-}
Not supported yet. Collection is read-only, throws exception.

### clear {#clear--}
```
public void clear()
```

Not supported yet. Collection is read-only. Always throws NotImplementedException.

### contains {#contains-com.aspose.pdf.CharInfo-}
Determines whether the collection contains a specific value.

### copyTo {#copyTo-com.aspose.pdf.CharInfo:A-int-}
Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array

### get_Item {#get_Item-int-}
```
public CharInfo get_Item(int index)
```

Gets the CharInfo element at the specified index 1..n.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index within the collection. |

**Returns:**
CharInfo object.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Gets an object that can be used to synchronize access to the collection.

**Returns:**
Object for synchronization

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Gets a value indicating whether collection is read-only

**Returns:**
boolean value

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Gets a value indicating whether access to the collection is synchronized (thread safe).

**Returns:**
boolean value

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Returns an enumerator for the entire collection.

**Returns:**
Enumerator object.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< CharInfo > iterator()
```

Returns an enumerator for the entire collection.

**Returns:**
Enumerator object.

### remove {#remove-com.aspose.pdf.CharInfo-}
Not supported yet. Collection is read-only, throws exception.

### size {#size--}
```
public int size()
```

Gets the number of {@code CharInfo} object elements actually contained in the collection.

**Returns:**
int value
