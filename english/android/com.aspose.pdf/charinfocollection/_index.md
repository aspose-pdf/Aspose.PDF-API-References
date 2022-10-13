---
title: CharInfoCollection
second_title: Aspose.PDF for Java API Reference
description: Represents CharInfo objects collection.
type: docs
weight: 53
url: /java/com.aspose.pdf/charinfocollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class CharInfoCollection implements Iterable
```

Represents CharInfo objects collection.

--------------------

```
The example demonstrates how to iterate thought all the characters and retrieve the character

 	      //open document
 	      Document pdfDocument = new Document(inFile);
 	      //create TextFragmentAbsorber object to collect all the text objects of the page
 	      TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber();
 	      //accept the absorber for all the pages
 	      pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber);
 	      //get the extracted text fragments
 	      TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments();


	      //loop through the fragments
	      for (TextFragment textFragment : (```
Iterable
```)textFragmentCollection)
	      {
	          //loop through the segments
	          for (TextSegment textSegment : (```
Iterable
```) textFragment.getSegments())
	          {
	              //loop through the characters
	              ```
for (int i = 1; i <= textSegment.getText().length(); i++)
```
	              {

	                  CharInfo charInfo = textSegment.getCharacters().get_Item(i);

	                  // print character position and rectangle info

	                  System.out.println("XIndent : " + charInfo.getPosition().getXIndent());
	                  System.out.println("YIndent : " + charInfo.getPosition().getYIndent());


	                  System.out.println("Width : " + charInfo.getRectangle().getWidth());
	                  System.out.println("Height : " + charInfo.getRectangle().getHeight());

	              }

	          }
	      }
```

--------------------

Provides access to positioning information of text segment characters.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Gets the number of  CharInfo  object elements actually contained in the collection. |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to the collection. |
| [isSynchronized()](#isSynchronized--) | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [iterator()](#iterator--) | Returns an enumerator for the entire collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the CharInfo element at the specified index 1..n. |
### size() {#size--}
```
public int size()
```


Gets the number of  CharInfo  object elements actually contained in the collection.

**Returns:**
int - int value
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets an object that can be used to synchronize access to the collection.

**Returns:**
java.lang.Object - Object for synchronization
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Gets a value indicating whether access to the collection is synchronized (thread safe).

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
public System.Collections.IEnumerator iterator()
```


Returns an enumerator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - Enumerator object.
### get_Item(int index) {#get-Item-int-}
```
public CharInfo get_Item(int index)
```


Gets the CharInfo element at the specified index 1..n.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index within the collection. |

**Returns:**
[CharInfo](../../com.aspose.pdf/charinfo) - CharInfo object.
