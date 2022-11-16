---
title: PdfArrayInBuffer
second_title: 用于 Java API 参考的 Aspose.PDF
description: 仅供内部使用
type: docs
weight: 11
url: /zh/java/com.aspose.pdf.groupprocessor/pdfarrayinbuffer/
---
**遗产：**
java.lang.Object, com.aspose.pdf.groupprocessor.PdfArrayInMemory

**所有已实现的接口：**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public final class PdfArrayInBuffer extends PdfArrayInMemory implements System.IDisposable, Closeable
```

仅供内部使用
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfArrayInBuffer(System.IO.FileStream stream, int bufferSize, System.Collections.Generic.Dictionary<ObjectKey,ByteRange> pdfObjects, long documentStartIndex)](#PdfArrayInBuffer-com.aspose.ms.System.IO.FileStream-int-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.groupprocessor.ObjectKey-com.aspose.pdf.groupprocessor.ByteRange--long-) |  |
| [PdfArrayInBuffer(byte[] bytes, System.Collections.Generic.Dictionary<ObjectKey,ByteRange> pdfObjects)](#PdfArrayInBuffer-byte---com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.groupprocessor.ObjectKey-com.aspose.pdf.groupprocessor.ByteRange--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [checkIfThisIsCommentsInMemory(int currentIndex)](#checkIfThisIsCommentsInMemory-int-) |  |
| [close()](#close--) | 关闭此实例使用的所有资源。 |
| [dispose()](#dispose--) | 关闭此实例使用的所有资源。 |
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


**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.FileStream |  |
| bufferSize | int |  |
| pdfObjects | com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.pdf.groupprocessor.ObjectKey,com.aspose.pdf.groupprocessor.ByteRange> |  |
| documentStartIndex | long |  |

### PdfArrayInBuffer(byte[] bytes, System.Collections.Generic.Dictionary<ObjectKey,ByteRange> pdfObjects) {#PdfArrayInBuffer-byte---com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.groupprocessor.ObjectKey-com.aspose.pdf.groupprocessor.ByteRange--}
```
public PdfArrayInBuffer(byte[] bytes, System.Collections.Generic.Dictionary<ObjectKey,ByteRange> pdfObjects)
```


**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| bytes | byte[] |  |
| pdfObjects | com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.pdf.groupprocessor.ObjectKey,com.aspose.pdf.groupprocessor.ByteRange> |  |

### checkIfThisIsCommentsInMemory(int currentIndex) {#checkIfThisIsCommentsInMemory-int-}
```
public boolean checkIfThisIsCommentsInMemory(int currentIndex)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| currentIndex | int |  |

**退货：**
布尔值
### close() {#close--}
```
public void close()
```


关闭此实例使用的所有资源。

### dispose() {#dispose--}
```
public void dispose()
```


关闭此实例使用的所有资源。

此方法已过时，请改用 close() 。

### endParameterFinderInMemory(long[] index) {#endParameterFinderInMemory-long---}
```
public void endParameterFinderInMemory(long[] index)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | long[] |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### extractObjectKeyOnTheLeftSideInMemory(int index, ObjectKey[] key) {#extractObjectKeyOnTheLeftSideInMemory-int-com.aspose.pdf.groupprocessor.ObjectKey---}
```
public void extractObjectKeyOnTheLeftSideInMemory(int index, ObjectKey[] key)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |

### extractObjectKeyOnTheRightSide(long index, ObjectKey[] key) {#extractObjectKeyOnTheRightSide-long-com.aspose.pdf.groupprocessor.ObjectKey---}
```
public long extractObjectKeyOnTheRightSide(long index, ObjectKey[] key)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | long |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |

**退货：**
长
### extractParameterInMemory(int startIndex) {#extractParameterInMemory-int-}
```
public String extractParameterInMemory(int startIndex)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int |  |

**退货：**
java.lang.字符串
### findNextEndobject(long currentIndex) {#findNextEndobject-long-}
```
public long findNextEndobject(long currentIndex)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| currentIndex | long |  |

**退货：**
长
### findNextEndobjectInMemory(int currentIndex) {#findNextEndobjectInMemory-int-}
```
public int findNextEndobjectInMemory(int currentIndex)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| currentIndex | int |  |

**退货：**
整数
### findNextObject(long currentIndex, ObjectKey[] key) {#findNextObject-long-com.aspose.pdf.groupprocessor.ObjectKey---}
```
public long findNextObject(long currentIndex, ObjectKey[] key)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| currentIndex | long |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |

**退货：**
长
### findNextObjectInMemory(int currentIndex, ObjectKey[] key) {#findNextObjectInMemory-int-com.aspose.pdf.groupprocessor.ObjectKey---}
```
public int findNextObjectInMemory(int currentIndex, ObjectKey[] key)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| currentIndex | int |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |

**退货：**
整数
### forwardSpaceEaterInMemory(long[] index) {#forwardSpaceEaterInMemory-long---}
```
public void forwardSpaceEaterInMemory(long[] index)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | long[] |  |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### get_Item(int index) {#get-Item-int-}
```
public byte get_Item(int index)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**退货：**
字节
### get_Item(long index) {#get-Item-long-}
```
public byte get_Item(long index)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | long |  |

**退货：**
字节
### get_Item_PdfArrayInBuffer_New(int index) {#get-Item-PdfArrayInBuffer-New-int-}
```
public byte get_Item_PdfArrayInBuffer_New(int index)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**退货：**
字节
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### indexOf(long indexFrom, byte pdfElement) {#indexOf-long-byte-}
```
public long indexOf(long indexFrom, byte pdfElement)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| indexFrom | long |  |
| pdfElement | byte |  |

**退货：**
长
### indexOf(long indexFrom, long indexTo, byte pdfElement) {#indexOf-long-long-byte-}
```
public long indexOf(long indexFrom, long indexTo, byte pdfElement)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| indexFrom | long |  |
| indexTo | long |  |
| pdfElement | byte |  |

**退货：**
长
### indexOfEndobjInMemory(int indexFrom) {#indexOfEndobjInMemory-int-}
```
public int indexOfEndobjInMemory(int indexFrom)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| indexFrom | int |  |

**退货：**
整数
### indexOfInMemory(int indexFrom, int indexTo, byte pdfElement) {#indexOfInMemory-int-int-byte-}
```
public int indexOfInMemory(int indexFrom, int indexTo, byte pdfElement)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| indexFrom | int |  |
| indexTo | int |  |
| pdfElement | byte |  |

**退货：**
整数
### indexOfObjInMemory(int indexFrom) {#indexOfObjInMemory-int-}
```
public int indexOfObjInMemory(int indexFrom)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| indexFrom | int |  |

**退货：**
整数
### isEqual(byte[] firstArray, byte[] secondArray) {#isEqual-byte---byte---}
```
public static boolean isEqual(byte[] firstArray, byte[] secondArray)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| firstArray | byte[] |  |
| secondArray | byte[] |  |

**退货：**
布尔值
### lastIndexOf(byte pdfElement) {#lastIndexOf-byte-}
```
public long lastIndexOf(byte pdfElement)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdfElement | byte |  |

**退货：**
长
### lastIndexOf(long lastIndex, byte pdfElement) {#lastIndexOf-long-byte-}
```
public long lastIndexOf(long lastIndex, byte pdfElement)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| lastIndex | long |  |
| pdfElement | byte |  |

**退货：**
长
### lastIndexOfInMemory(byte pdfElement) {#lastIndexOfInMemory-byte-}
```
public int lastIndexOfInMemory(byte pdfElement)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdfElement | byte |  |

**退货：**
整数
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




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| indexFrom | long |  |
| indexTo | long |  |

**退货：**
字节[]
### subString(long indexFrom, long indexTo) {#subString-long-long-}
```
public String subString(long indexFrom, long indexTo)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| indexFrom | long |  |
| indexTo | long |  |

**退货：**
java.lang.字符串
### subStringInMemory(int indexFrom, int indexTo) {#subStringInMemory-int-int-}
```
public String subStringInMemory(int indexFrom, int indexTo)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| indexFrom | int |  |
| indexTo | int |  |

**退货：**
java.lang.字符串
### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### tryToExtractObjectKeyOnTheLeftSideInMemory(int index, ObjectKey[] key) {#tryToExtractObjectKeyOnTheLeftSideInMemory-int-com.aspose.pdf.groupprocessor.ObjectKey---}
```
public boolean tryToExtractObjectKeyOnTheLeftSideInMemory(int index, ObjectKey[] key)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |

**退货：**
布尔值
### tryToExtractObjectKeyOnTheRightSideInMemory(int index, ObjectKey[] key, int[] changedIndex) {#tryToExtractObjectKeyOnTheRightSideInMemory-int-com.aspose.pdf.groupprocessor.ObjectKey---int---}
```
public boolean tryToExtractObjectKeyOnTheRightSideInMemory(int index, ObjectKey[] key, int[] changedIndex)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |
| changedIndex | int[] |  |

**退货：**
布尔值
### tryToExtractObjectKeyOnTheRightSideInMemory(long index, ObjectKey[] key, long[] changedIndex) {#tryToExtractObjectKeyOnTheRightSideInMemory-long-com.aspose.pdf.groupprocessor.ObjectKey---long---}
```
public boolean tryToExtractObjectKeyOnTheRightSideInMemory(long index, ObjectKey[] key, long[] changedIndex)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | long |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |
| changedIndex | long[] |  |

**退货：**
布尔值
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
