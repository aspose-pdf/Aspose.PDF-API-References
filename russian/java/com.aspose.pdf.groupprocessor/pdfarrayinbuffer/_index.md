---
title: PdfArrayInBuffer
second_title: Aspose.PDF для справки по Java API
description: Только для внутреннего использования
type: docs
weight: 11
url: /ru/java/com.aspose.pdf.groupprocessor/pdfarrayinbuffer/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.groupprocessor.PdfArrayInMemory

**Все реализованные интерфейсы:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public final class PdfArrayInBuffer extends PdfArrayInMemory implements System.IDisposable, Closeable
```

Только для внутреннего использования
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfArrayInBuffer(System.IO.FileStream stream, int bufferSize, System.Collections.Generic.Dictionary<ObjectKey,ByteRange> pdfObjects, long documentStartIndex)](#PdfArrayInBuffer-com.aspose.ms.System.IO.FileStream-int-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.groupprocessor.ObjectKey-com.aspose.pdf.groupprocessor.ByteRange--long-) |  |
| [PdfArrayInBuffer(byte[] bytes, System.Collections.Generic.Dictionary<ObjectKey,ByteRange> pdfObjects)](#PdfArrayInBuffer-byte---com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.groupprocessor.ObjectKey-com.aspose.pdf.groupprocessor.ByteRange--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [checkIfThisIsCommentsInMemory(int currentIndex)](#checkIfThisIsCommentsInMemory-int-) |  |
| [close()](#close--) | Закрывает все ресурсы, используемые этим экземпляром. |
| [dispose()](#dispose--) | Закрывает все ресурсы, используемые этим экземпляром. |
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


**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.FileStream |  |
| bufferSize | int |  |
| pdfObjects | com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.pdf.groupprocessor.ObjectKey,com.aspose.pdf.groupprocessor.ByteRange> |  |
| documentStartIndex | long |  |

### PdfArrayInBuffer(byte[] bytes, System.Collections.Generic.Dictionary<ObjectKey,ByteRange> pdfObjects) {#PdfArrayInBuffer-byte---com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.groupprocessor.ObjectKey-com.aspose.pdf.groupprocessor.ByteRange--}
```
public PdfArrayInBuffer(byte[] bytes, System.Collections.Generic.Dictionary<ObjectKey,ByteRange> pdfObjects)
```


**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | byte[] |  |
| pdfObjects | com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.pdf.groupprocessor.ObjectKey,com.aspose.pdf.groupprocessor.ByteRange> |  |

### checkIfThisIsCommentsInMemory(int currentIndex) {#checkIfThisIsCommentsInMemory-int-}
```
public boolean checkIfThisIsCommentsInMemory(int currentIndex)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| currentIndex | int |  |

**Возвращает:**
логический
### close() {#close--}
```
public void close()
```


Закрывает все ресурсы, используемые этим экземпляром.

### dispose() {#dispose--}
```
public void dispose()
```


Закрывает все ресурсы, используемые этим экземпляром.

Этот метод устарел, вместо него используйте close().

### endParameterFinderInMemory(long[] index) {#endParameterFinderInMemory-long---}
```
public void endParameterFinderInMemory(long[] index)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | long[] |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Возвращает:**
логический
### extractObjectKeyOnTheLeftSideInMemory(int index, ObjectKey[] key) {#extractObjectKeyOnTheLeftSideInMemory-int-com.aspose.pdf.groupprocessor.ObjectKey---}
```
public void extractObjectKeyOnTheLeftSideInMemory(int index, ObjectKey[] key)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |

### extractObjectKeyOnTheRightSide(long index, ObjectKey[] key) {#extractObjectKeyOnTheRightSide-long-com.aspose.pdf.groupprocessor.ObjectKey---}
```
public long extractObjectKeyOnTheRightSide(long index, ObjectKey[] key)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | long |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |

**Возвращает:**
длинная
### extractParameterInMemory(int startIndex) {#extractParameterInMemory-int-}
```
public String extractParameterInMemory(int startIndex)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int |  |

**Возвращает:**
java.lang.String
### findNextEndobject(long currentIndex) {#findNextEndobject-long-}
```
public long findNextEndobject(long currentIndex)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| currentIndex | long |  |

**Возвращает:**
длинная
### findNextEndobjectInMemory(int currentIndex) {#findNextEndobjectInMemory-int-}
```
public int findNextEndobjectInMemory(int currentIndex)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| currentIndex | int |  |

**Возвращает:**
инт
### findNextObject(long currentIndex, ObjectKey[] key) {#findNextObject-long-com.aspose.pdf.groupprocessor.ObjectKey---}
```
public long findNextObject(long currentIndex, ObjectKey[] key)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| currentIndex | long |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |

**Возвращает:**
длинная
### findNextObjectInMemory(int currentIndex, ObjectKey[] key) {#findNextObjectInMemory-int-com.aspose.pdf.groupprocessor.ObjectKey---}
```
public int findNextObjectInMemory(int currentIndex, ObjectKey[] key)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| currentIndex | int |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |

**Возвращает:**
инт
### forwardSpaceEaterInMemory(long[] index) {#forwardSpaceEaterInMemory-long---}
```
public void forwardSpaceEaterInMemory(long[] index)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | long[] |  |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### get_Item(int index) {#get-Item-int-}
```
public byte get_Item(int index)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
байт
### get_Item(long index) {#get-Item-long-}
```
public byte get_Item(long index)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | long |  |

**Возвращает:**
байт
### get_Item_PdfArrayInBuffer_New(int index) {#get-Item-PdfArrayInBuffer-New-int-}
```
public byte get_Item_PdfArrayInBuffer_New(int index)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
байт
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### indexOf(long indexFrom, byte pdfElement) {#indexOf-long-byte-}
```
public long indexOf(long indexFrom, byte pdfElement)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| indexFrom | long |  |
| pdfElement | byte |  |

**Возвращает:**
длинная
### indexOf(long indexFrom, long indexTo, byte pdfElement) {#indexOf-long-long-byte-}
```
public long indexOf(long indexFrom, long indexTo, byte pdfElement)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| indexFrom | long |  |
| indexTo | long |  |
| pdfElement | byte |  |

**Возвращает:**
длинная
### indexOfEndobjInMemory(int indexFrom) {#indexOfEndobjInMemory-int-}
```
public int indexOfEndobjInMemory(int indexFrom)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| indexFrom | int |  |

**Возвращает:**
инт
### indexOfInMemory(int indexFrom, int indexTo, byte pdfElement) {#indexOfInMemory-int-int-byte-}
```
public int indexOfInMemory(int indexFrom, int indexTo, byte pdfElement)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| indexFrom | int |  |
| indexTo | int |  |
| pdfElement | byte |  |

**Возвращает:**
инт
### indexOfObjInMemory(int indexFrom) {#indexOfObjInMemory-int-}
```
public int indexOfObjInMemory(int indexFrom)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| indexFrom | int |  |

**Возвращает:**
инт
### isEqual(byte[] firstArray, byte[] secondArray) {#isEqual-byte---byte---}
```
public static boolean isEqual(byte[] firstArray, byte[] secondArray)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstArray | byte[] |  |
| secondArray | byte[] |  |

**Возвращает:**
логический
### lastIndexOf(byte pdfElement) {#lastIndexOf-byte-}
```
public long lastIndexOf(byte pdfElement)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfElement | byte |  |

**Возвращает:**
длинная
### lastIndexOf(long lastIndex, byte pdfElement) {#lastIndexOf-long-byte-}
```
public long lastIndexOf(long lastIndex, byte pdfElement)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| lastIndex | long |  |
| pdfElement | byte |  |

**Возвращает:**
длинная
### lastIndexOfInMemory(byte pdfElement) {#lastIndexOfInMemory-byte-}
```
public int lastIndexOfInMemory(byte pdfElement)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfElement | byte |  |

**Возвращает:**
инт
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




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| indexFrom | long |  |
| indexTo | long |  |

**Возвращает:**
байт[]
### subString(long indexFrom, long indexTo) {#subString-long-long-}
```
public String subString(long indexFrom, long indexTo)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| indexFrom | long |  |
| indexTo | long |  |

**Возвращает:**
java.lang.String
### subStringInMemory(int indexFrom, int indexTo) {#subStringInMemory-int-int-}
```
public String subStringInMemory(int indexFrom, int indexTo)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| indexFrom | int |  |
| indexTo | int |  |

**Возвращает:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### tryToExtractObjectKeyOnTheLeftSideInMemory(int index, ObjectKey[] key) {#tryToExtractObjectKeyOnTheLeftSideInMemory-int-com.aspose.pdf.groupprocessor.ObjectKey---}
```
public boolean tryToExtractObjectKeyOnTheLeftSideInMemory(int index, ObjectKey[] key)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |

**Возвращает:**
логический
### tryToExtractObjectKeyOnTheRightSideInMemory(int index, ObjectKey[] key, int[] changedIndex) {#tryToExtractObjectKeyOnTheRightSideInMemory-int-com.aspose.pdf.groupprocessor.ObjectKey---int---}
```
public boolean tryToExtractObjectKeyOnTheRightSideInMemory(int index, ObjectKey[] key, int[] changedIndex)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |
| changedIndex | int[] |  |

**Возвращает:**
логический
### tryToExtractObjectKeyOnTheRightSideInMemory(long index, ObjectKey[] key, long[] changedIndex) {#tryToExtractObjectKeyOnTheRightSideInMemory-long-com.aspose.pdf.groupprocessor.ObjectKey---long---}
```
public boolean tryToExtractObjectKeyOnTheRightSideInMemory(long index, ObjectKey[] key, long[] changedIndex)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | long |  |
| key | com.aspose.pdf.groupprocessor.ObjectKey[] |  |
| changedIndex | long[] |  |

**Возвращает:**
логический
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
