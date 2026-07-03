---
title: MemoryFontSource
second_title: Aspose.PDF for Java API Reference
description: Represents single font file source.
type: docs
weight: 3040
url: /java/com.aspose.pdf/memoryfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.MemoryFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.MemoryFontSource

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public final class MemoryFontSource extends FontSource implements com.aspose.ms.System.IDisposable, Closeable
```

Represents single font file source.

## Constructors

| Constructor | Description |
| --- | --- |
| [MemoryFontSource](#MemoryFontSource-byte:A-) | Initializes a new instance of {@code MemoryFontSource} class. |

## Methods

| Method | Description |
| --- | --- |
| [close](#close--) | Closes all resources used by this document. |
| [dispose](#dispose--) | Releases internal resources. This method is obsolete, use close() instead. |
| [equals](#equals-java.lang.Object-) | Check if font file source objects are equal. |
| [getFontBytes](#getFontBytes--) | Font file byte array. |
| [hashCode](#hashCode--) | Returns a hash code value for the object. This method is supported for the benefit of hash tables such as those provided by {@link java.util.HashMap}. <p> The general contract of {@code hashCode} is: <ul> <li>Whenever it is invoked on the same object more than once during an execution of a Java application, the {@code hashCode} method must consistently return the same integer, provided no information used in {@code equals} comparisons on the object is modified. This integer need not remain consistent from one execution of an application to another execution of the same application. <li>If two objects are equal according to the {@code equals(Object)} method, then calling the {@code hashCode} method on each of the two objects must produce the same integer result. <li>It is <em>not</em> required that if two objects are unequal according to the {@link java.lang.Object#equals(java.lang.Object)} method, then calling the {@code hashCode} method on each of the two objects must produce distinct integer results. However, the programmer should be aware that producing distinct integer results for unequal objects may improve the performance of hash tables. </ul> <p> As much as is reasonably practical, the hashCode method defined by class {@code Object} does return distinct integers for distinct objects. (This is typically implemented by converting the internal address of the object into an integer, but this implementation technique is not required by the Java<span style="font-size:70%"><sup>TM</sup></span> programming language.) |

### MemoryFontSource {#MemoryFontSource-byte:A-}
```
public MemoryFontSource(byte[] fontBytes)
```

Initializes a new instance of {@code MemoryFontSource} class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontBytes |  | Font file byte array. |

### close {#close--}
```
public void close()
```

Closes all resources used by this document.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Releases internal resources. This method is obsolete, use close() instead.

### equals {#equals-java.lang.Object-}
Check if font file source objects are equal.

### getFontBytes {#getFontBytes--}
```
public byte[] getFontBytes()
```

Font file byte array.

**Returns:**
byte[] array

### hashCode {#hashCode--}
```
public int hashCode()
```

Returns a hash code value for the object. This method is supported for the benefit of hash tables such as those provided by {@link java.util.HashMap}. <p> The general contract of {@code hashCode} is: <ul> <li>Whenever it is invoked on the same object more than once during an execution of a Java application, the {@code hashCode} method must consistently return the same integer, provided no information used in {@code equals} comparisons on the object is modified. This integer need not remain consistent from one execution of an application to another execution of the same application. <li>If two objects are equal according to the {@code equals(Object)} method, then calling the {@code hashCode} method on each of the two objects must produce the same integer result. <li>It is <em>not</em> required that if two objects are unequal according to the {@link java.lang.Object#equals(java.lang.Object)} method, then calling the {@code hashCode} method on each of the two objects must produce distinct integer results. However, the programmer should be aware that producing distinct integer results for unequal objects may improve the performance of hash tables. </ul> <p> As much as is reasonably practical, the hashCode method defined by class {@code Object} does return distinct integers for distinct objects. (This is typically implemented by converting the internal address of the object into an integer, but this implementation technique is not required by the Java<span style="font-size:70%"><sup>TM</sup></span> programming language.)

**Returns:**
a hash code value for this object. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode
