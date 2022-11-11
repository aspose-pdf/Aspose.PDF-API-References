---
title: CharInfoCollection
second_title: Aspose.PDF for Java API Reference
description: Represents CharInfo objects collection.
type: docs
weight: 57
url: /java/com.aspose.pdf/charinfocollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class CharInfoCollection implements Iterable<CharInfo>
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
| [add(CharInfo item)](#add-com.aspose.pdf.CharInfo-) | Not supported yet. |
| [clear()](#clear--) | Not supported yet. |
| [contains(CharInfo item)](#contains-com.aspose.pdf.CharInfo-) | Determines whether the collection contains a specific value. |
| [copyTo(CharInfo[] array, int index)](#copyTo-com.aspose.pdf.CharInfo---int-) | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the CharInfo element at the specified index 1..n. |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether collection is read-only |
| [isSynchronized()](#isSynchronized--) | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [iterator()](#iterator--) | Returns an enumerator for the entire collection. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) | Returns an enumerator for the entire collection. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(CharInfo item)](#remove-com.aspose.pdf.CharInfo-) | Not supported yet. |
| [size()](#size--) | Gets the number of  CharInfo  object elements actually contained in the collection. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(CharInfo item) {#add-com.aspose.pdf.CharInfo-}
```
public void add(CharInfo item)
```


Not supported yet.

Collection is read-only, throws exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [CharInfo](../../com.aspose.pdf/charinfo) | CharInfo instance to add. |

### clear() {#clear--}
```
public void clear()
```


Not supported yet.

Collection is read-only. Always throws NotImplementedException.

### contains(CharInfo item) {#contains-com.aspose.pdf.CharInfo-}
```
public boolean contains(CharInfo item)
```


Determines whether the collection contains a specific value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [CharInfo](../../com.aspose.pdf/charinfo) | The object to locate in the collection |

**Returns:**
boolean - true if item is found in the collection; otherwise, false.
### copyTo(CharInfo[] array, int index) {#copyTo-com.aspose.pdf.CharInfo---int-}
```
public void copyTo(CharInfo[] array, int index)
```


Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [CharInfo\[\]](../../com.aspose.pdf/charinfo) | Array of objects which will be copied. |
| index | int | Starting index from which copying will be started. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets an object that can be used to synchronize access to the collection.

**Returns:**
java.lang.Object - Object for synchronization
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets a value indicating whether collection is read-only

**Returns:**
boolean - boolean value
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Gets a value indicating whether access to the collection is synchronized (thread safe).

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
public System.Collections.IEnumerator<CharInfo> iterator()
```


Returns an enumerator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.pdf.CharInfo> - Enumerator object.
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.IEnumerator iterator_Rename_Namesake()
```


Returns an enumerator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - Enumerator object.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(CharInfo item) {#remove-com.aspose.pdf.CharInfo-}
```
public boolean remove(CharInfo item)
```


Not supported yet.

Collection is read-only, throws exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [CharInfo](../../com.aspose.pdf/charinfo) | CharInfo instance to remove. |

**Returns:**
boolean - boolean value.
### size() {#size--}
```
public int size()
```


Gets the number of  CharInfo  object elements actually contained in the collection.

**Returns:**
int - int value
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

