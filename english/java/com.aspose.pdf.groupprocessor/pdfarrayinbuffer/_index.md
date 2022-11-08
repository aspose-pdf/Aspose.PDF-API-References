---
title: PdfArrayInBuffer
second_title: Aspose.PDF for Java API Reference
description: For internal usage only
type: docs
weight: 11
url: /java/com.aspose.pdf.groupprocessor/pdfarrayinbuffer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.groupprocessor.PdfArrayInMemory

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public final class PdfArrayInBuffer extends PdfArrayInMemory implements System.IDisposable, Closeable
```

For internal usage only
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfArrayInBuffer(System.IO.FileStream stream, int bufferSize, System.Collections.Generic.Dictionary<ObjectKey,ByteRange> pdfObjects, long documentStartIndex)](#PdfArrayInBuffer-com.aspose.ms.System.IO.FileStream-int-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.groupprocessor.ObjectKey-com.aspose.pdf.groupprocessor.ByteRange--long-) |  |
| [PdfArrayInBuffer(byte[] bytes, System.Collections.Generic.Dictionary<ObjectKey,ByteRange> pdfObjects)](#PdfArrayInBuffer-byte---com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.groupprocessor.ObjectKey-com.aspose.pdf.groupprocessor.ByteRange--) |  |
## Methods

| Method | Description |
| --- | --- |
| [checkIfThisIsCommentsInMemory(int currentIndex)](#checkIfThisIsCommentsInMemory-int-) |  |
| [close()](#close--) | Closes all resources used by this instance. |
| [dispose()](#dispose--) | Closes all resources used by this instance. |
| [endParameterFinderInMemory(long[] index)](#endParameterFinderInMemory-long---) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractObjectKeyOnTheLeftSideInMemory(int index, ObjectKey[] key)](#extractObjectKeyOnTheLeftSideInMemory-int-com.aspose.pdf.groupprocessor.ObjectKey---) |  |
| [extractObjectKeyOnTheRightSide(long index, ObjectKey[] key)](#extractObjectKeyOnTheRightSide-long-com.aspose.pdf.groupprocessor.ObjectKey---) |  |
| [extractParameterInMemory(int startIndex)](#extractParameterInMemory-int-) |  |
| [findNextEndobject(long currentIndex)](#findNextEndobject-long-) |  |
| [findNextEndobjectInMemory(int currentIndex)](#findNextEndobjectInMemory-int-) |  |
| [findNextObject(long currentIndex, ObjectKey[] key)](#findNextObject-long-com.aspose.pdf.groupprocessor.ObjectKey---) |  |
| [findNextObjectInMemory(int currentIndex, ObjectKey[] key)](#findNextObjectInMemory-int-com.aspose.pdf.groupprocessor.ObjectKey---) |  |
| [forwardSpaceEaterInMemory(long[] index)](#forwardSpaceEaterInMemory-long---) |  |
| [getClass()](#getClass--) |  |
| [get_Item(int index)](#get-Item-int-) |  |
| [get_Item(long index)](#get-Item-long-) |  |
| [get_Item_PdfArrayInBuffer_New(int index)](#get-Item-PdfArrayInBuffer-New-int-) |  |
| [hashCode()](#hashCode--) |  |
| [indexOf(long indexFrom, byte pdfElement)](#indexOf-long-byte-) |  |
| [indexOf(long indexFrom, long indexTo, byte pdfElement)](#indexOf-long-long-byte-) |  |
| [indexOfEndobjInMemory(int indexFrom)](#indexOfEndobjInMemory-int-) |  |
| [indexOfInMemory(int indexFrom, int indexTo, byte pdfElement)](#indexOfInMemory-int-int-byte-) |  |
| [indexOfObjInMemory(int indexFrom)](#indexOfObjInMemory-int-) |  |
| [isEqual(byte[] firstArray, byte[] secondArray)](#isEqual-byte---byte---) |  |
| [lastIndexOf(byte pdfElement)](#lastIndexOf-byte-) |  |
| [lastIndexOf(long lastIndex, byte pdfElement)](#lastIndexOf-long-byte-) |  |
| [lastIndexOfInMemory(byte pdfElement)](#lastIndexOfInMemory-byte-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [subBytes(long indexFrom, long indexTo)](#subBytes-long-long-) |  |
| [subString(long indexFrom, long indexTo)](#subString-long-long-) |  |
| [subStringInMemory(int indexFrom, int indexTo)](#subStringInMemory-int-int-) |  |
| [toString()](#toString--) |  |
| [tryToExtractObjectKeyOnTheLeftSideInMemory(int index, ObjectKey[] key)](#tryToExtractObjectKeyOnTheLeftSideInMemory-int-com.aspose.pdf.groupprocessor.ObjectKey---) |  |
| [tryToExtractObjectKeyOnTheRightSideInMemory(int index, ObjectKey[] key, int[] changedIndex)](#tryToExtractObjectKeyOnTheRightSideInMemory-int-com.aspose.pdf.groupprocessor.ObjectKey---int---) |  |
| [tryToExtractObjectKeyOnTheRightSideInMemory(long index, ObjectKey[] key, long[] changedIndex)](#tryToExtractObjectKeyOnTheRightSideInMemory-long-com.aspose.pdf.groupprocessor.ObjectKey---long---) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfArrayInBuffer(System.IO.FileStream stream, int bufferSize, System.Collections.Generic.Dictionary<ObjectKey,ByteRange> pdfObjects, long documentStartIndex) {#PdfArrayInBuffer-com.aspose.ms.System.IO.FileStream-int-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.groupprocessor.ObjectKey-com.aspose.pdf.groupprocessor.ByteRange--long-}
```
public PdfArrayInBuffer(System.IO.FileStream stream, int bufferSize, System.Collections.Generic.Dictionary<ObjectKey,ByteRange> pdfObjects, long documentStartIndex)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.FileStream |  |
| bufferSize | int |  |
| pdfObjects | com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.pdf.groupprocessor.ObjectKey,com.aspose.pdf.groupprocessor.ByteRange> |  |
| documentStartIndex | long |  |

### PdfArrayInBuffer(byte[] bytes, System.Collections.Generic.Dictionary<ObjectKey,ByteRange> pdfObjects) {#PdfArrayInBuffer-byte---com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.groupprocessor.ObjectKey-com.aspose.pdf.groupprocessor.ByteRange--}
```
public PdfArrayInBuffer(byte[] bytes, System.Collections.Generic.Dictionary<ObjectKey,ByteRange> pdfObjects)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bytes | byte[] |  |
| pdfObjects | com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.pdf.groupprocessor.ObjectKey,com.aspose.pdf.groupprocessor.ByteRange> |  |

### checkIfThisIsCommentsInMemory(int currentIndex) {#checkIfThisIsCommentsInMemory-int-}
```
public boolean checkIfThisIsCommentsInMemory(int currentIndex)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| currentIndex | int |  |

**Returns:**
boolean
### close() {#close--}
```
public void close()
```


Closes all resources used by this instance.

### dispose() {#dispose--}
```
public void dispose()
```


Closes all resources used by this instance.

This method is obsolete, use close() instead.

### endParameterFinderInMemory(long[] index) {#endParameterFinderInMemory-long---}
```
public void endParameterFinderInMemory(long[] index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | long[] |  |

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
### extractObjectKeyOnTheLeftSideInMemory(int index, ObjectKey[] key) {#extractObjectKeyOnTheLeftSideInMemory-int-com.aspose.pdf.groupprocessor.ObjectKey---}
```
public void extractObjectKeyOnTheLeftSideInMemory(int index, ObjectKey[] key)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |

### extractObjectKeyOnTheRightSide(long index, ObjectKey[] key) {#extractObjectKeyOnTheRightSide-long-com.aspose.pdf.groupprocessor.ObjectKey---}
```
public long extractObjectKeyOnTheRightSide(long index, ObjectKey[] key)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | long |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |

**Returns:**
long
### extractParameterInMemory(int startIndex) {#extractParameterInMemory-int-}
```
public String extractParameterInMemory(int startIndex)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int |  |

**Returns:**
java.lang.String
### findNextEndobject(long currentIndex) {#findNextEndobject-long-}
```
public long findNextEndobject(long currentIndex)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| currentIndex | long |  |

**Returns:**
long
### findNextEndobjectInMemory(int currentIndex) {#findNextEndobjectInMemory-int-}
```
public int findNextEndobjectInMemory(int currentIndex)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| currentIndex | int |  |

**Returns:**
int
### findNextObject(long currentIndex, ObjectKey[] key) {#findNextObject-long-com.aspose.pdf.groupprocessor.ObjectKey---}
```
public long findNextObject(long currentIndex, ObjectKey[] key)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| currentIndex | long |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |

**Returns:**
long
### findNextObjectInMemory(int currentIndex, ObjectKey[] key) {#findNextObjectInMemory-int-com.aspose.pdf.groupprocessor.ObjectKey---}
```
public int findNextObjectInMemory(int currentIndex, ObjectKey[] key)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| currentIndex | int |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |

**Returns:**
int
### forwardSpaceEaterInMemory(long[] index) {#forwardSpaceEaterInMemory-long---}
```
public void forwardSpaceEaterInMemory(long[] index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | long[] |  |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### get_Item(int index) {#get-Item-int-}
```
public byte get_Item(int index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
byte
### get_Item(long index) {#get-Item-long-}
```
public byte get_Item(long index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | long |  |

**Returns:**
byte
### get_Item_PdfArrayInBuffer_New(int index) {#get-Item-PdfArrayInBuffer-New-int-}
```
public byte get_Item_PdfArrayInBuffer_New(int index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
byte
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indexOf(long indexFrom, byte pdfElement) {#indexOf-long-byte-}
```
public long indexOf(long indexFrom, byte pdfElement)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| indexFrom | long |  |
| pdfElement | byte |  |

**Returns:**
long
### indexOf(long indexFrom, long indexTo, byte pdfElement) {#indexOf-long-long-byte-}
```
public long indexOf(long indexFrom, long indexTo, byte pdfElement)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| indexFrom | long |  |
| indexTo | long |  |
| pdfElement | byte |  |

**Returns:**
long
### indexOfEndobjInMemory(int indexFrom) {#indexOfEndobjInMemory-int-}
```
public int indexOfEndobjInMemory(int indexFrom)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| indexFrom | int |  |

**Returns:**
int
### indexOfInMemory(int indexFrom, int indexTo, byte pdfElement) {#indexOfInMemory-int-int-byte-}
```
public int indexOfInMemory(int indexFrom, int indexTo, byte pdfElement)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| indexFrom | int |  |
| indexTo | int |  |
| pdfElement | byte |  |

**Returns:**
int
### indexOfObjInMemory(int indexFrom) {#indexOfObjInMemory-int-}
```
public int indexOfObjInMemory(int indexFrom)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| indexFrom | int |  |

**Returns:**
int
### isEqual(byte[] firstArray, byte[] secondArray) {#isEqual-byte---byte---}
```
public static boolean isEqual(byte[] firstArray, byte[] secondArray)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstArray | byte[] |  |
| secondArray | byte[] |  |

**Returns:**
boolean
### lastIndexOf(byte pdfElement) {#lastIndexOf-byte-}
```
public long lastIndexOf(byte pdfElement)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfElement | byte |  |

**Returns:**
long
### lastIndexOf(long lastIndex, byte pdfElement) {#lastIndexOf-long-byte-}
```
public long lastIndexOf(long lastIndex, byte pdfElement)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lastIndex | long |  |
| pdfElement | byte |  |

**Returns:**
long
### lastIndexOfInMemory(byte pdfElement) {#lastIndexOfInMemory-byte-}
```
public int lastIndexOfInMemory(byte pdfElement)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfElement | byte |  |

**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### subBytes(long indexFrom, long indexTo) {#subBytes-long-long-}
```
public byte[] subBytes(long indexFrom, long indexTo)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| indexFrom | long |  |
| indexTo | long |  |

**Returns:**
byte[]
### subString(long indexFrom, long indexTo) {#subString-long-long-}
```
public String subString(long indexFrom, long indexTo)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| indexFrom | long |  |
| indexTo | long |  |

**Returns:**
java.lang.String
### subStringInMemory(int indexFrom, int indexTo) {#subStringInMemory-int-int-}
```
public String subStringInMemory(int indexFrom, int indexTo)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| indexFrom | int |  |
| indexTo | int |  |

**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryToExtractObjectKeyOnTheLeftSideInMemory(int index, ObjectKey[] key) {#tryToExtractObjectKeyOnTheLeftSideInMemory-int-com.aspose.pdf.groupprocessor.ObjectKey---}
```
public boolean tryToExtractObjectKeyOnTheLeftSideInMemory(int index, ObjectKey[] key)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |

**Returns:**
boolean
### tryToExtractObjectKeyOnTheRightSideInMemory(int index, ObjectKey[] key, int[] changedIndex) {#tryToExtractObjectKeyOnTheRightSideInMemory-int-com.aspose.pdf.groupprocessor.ObjectKey---int---}
```
public boolean tryToExtractObjectKeyOnTheRightSideInMemory(int index, ObjectKey[] key, int[] changedIndex)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |
| changedIndex | int[] |  |

**Returns:**
boolean
### tryToExtractObjectKeyOnTheRightSideInMemory(long index, ObjectKey[] key, long[] changedIndex) {#tryToExtractObjectKeyOnTheRightSideInMemory-long-com.aspose.pdf.groupprocessor.ObjectKey---long---}
```
public boolean tryToExtractObjectKeyOnTheRightSideInMemory(long index, ObjectKey[] key, long[] changedIndex)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | long |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |
| changedIndex | long[] |  |

**Returns:**
boolean
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

