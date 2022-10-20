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
| [get_Item_PdfArrayInBuffer_New(int index)](#get-Item-PdfArrayInBuffer-New-int-) |  |
| [get_Item(long index)](#get-Item-long-) |  |
| [indexOf(long indexFrom, long indexTo, byte pdfElement)](#indexOf-long-long-byte-) |  |
| [indexOf(long indexFrom, byte pdfElement)](#indexOf-long-byte-) |  |
| [lastIndexOf(byte pdfElement)](#lastIndexOf-byte-) |  |
| [lastIndexOf(long lastIndex, byte pdfElement)](#lastIndexOf-long-byte-) |  |
| [findNextObject(long currentIndex, ObjectKey[] key)](#findNextObject-long-com.aspose.pdf.groupprocessor.ObjectKey---) |  |
| [findNextEndobject(long currentIndex)](#findNextEndobject-long-) |  |
| [extractObjectKeyOnTheRightSide(long index, ObjectKey[] key)](#extractObjectKeyOnTheRightSide-long-com.aspose.pdf.groupprocessor.ObjectKey---) |  |
| [subBytes(long indexFrom, long indexTo)](#subBytes-long-long-) |  |
| [subString(long indexFrom, long indexTo)](#subString-long-long-) |  |
| [endParameterFinderInMemory(long[] index)](#endParameterFinderInMemory-long---) |  |
| [tryToExtractObjectKeyOnTheRightSideInMemory(long index, ObjectKey[] key, long[] changedIndex)](#tryToExtractObjectKeyOnTheRightSideInMemory-long-com.aspose.pdf.groupprocessor.ObjectKey---long---) |  |
| [forwardSpaceEaterInMemory(long[] index)](#forwardSpaceEaterInMemory-long---) |  |
| [isEqual(byte[] firstArray, byte[] secondArray)](#isEqual-byte---byte---) |  |
| [close()](#close--) | Closes all resources used by this instance. |
| [dispose()](#dispose--) | Closes all resources used by this instance. |
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
### endParameterFinderInMemory(long[] index) {#endParameterFinderInMemory-long---}
```
public void endParameterFinderInMemory(long[] index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | long[] |  |

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
### forwardSpaceEaterInMemory(long[] index) {#forwardSpaceEaterInMemory-long---}
```
public void forwardSpaceEaterInMemory(long[] index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | long[] |  |

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

