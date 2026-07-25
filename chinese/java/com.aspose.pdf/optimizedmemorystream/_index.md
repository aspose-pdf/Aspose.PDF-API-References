---
title: "OptimizedMemoryStream"
linktitle: "OptimizedMemoryStream"
second_title: "Aspose.PDF for Java API 参考"
description: "定义一个可以容纳更大标准容量的 MemoryStream。"
type: docs
weight: 3220
url: /zh/java/com.aspose.pdf/optimizedmemorystream/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.IO.Stream com.aspose.pdf.OptimizedMemoryStream, com.aspose.ms.System.IO.Stream, com.aspose.pdf.OptimizedMemoryStream

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class OptimizedMemoryStream extends com.aspose.ms.System.IO.Stream
```

定义一个可以容纳更大标准容量的 MemoryStream。

## 字段

| 字段 | 描述 |
| --- | --- |
| [DefaultBufferSize](#DefaultBufferSize) | 默认缓冲区大小（字节）值。 |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OptimizedMemoryStream](#OptimizedMemoryStream--) | 初始化 {@link OptimizedMemoryStream} 类的新实例。 |
| [OptimizedMemoryStream](#OptimizedMemoryStream-byte:A-) | 基于指定的字节数组，初始化 {@link OptimizedMemoryStream} 类的新实例。 |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-) | 初始化 {@link OptimizedMemoryStream} 类的新实例。 |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-byte:A-) | 基于指定的字节数组，初始化 {@link OptimizedMemoryStream} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [canRead](#canRead--) | 在派生类中重写时，获取一个值，指示当前流是否支持读取。 |
| [canSeek](#canSeek--) | 在派生类中重写时，获取一个值，指示当前流是否支持定位。 |
| [canWrite](#canWrite--) | 在派生类中重写时，获取一个值，指示当前流是否支持写入。 |
| [flush](#flush--) | 该函数已被重写。 |
| [getBufferSize](#getBufferSize--) | 获取或设置底层缓冲区的大小。值：缓冲区大小。 |
| [getFreeOnDispose](#getFreeOnDispose--) | 获取或设置一个值，指示在释放时是否释放底层缓冲区。 |
| [getLength](#getLength--) | 在派生类中重写时，获取流的字节长度。 |
| [getPosition](#getPosition--) | 在派生类中重写时，获取或设置当前流中的位置。 |
| [read](#read-byte:A-int-int-) | 在派生类中重写时，从当前流读取一系列字节，并根据读取的字节数前移流中的位置。 |
| [readByte](#readByte--) | 从流中读取一个字节，并将流中的位置前移一个字节；如果已到达流末尾，则返回 -1。 |
| [seek](#seek-long-int-) | 在派生类中重写时，设置当前流中的位置。 |
| [seek](#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-) | 在派生类中重写时，设置当前流中的位置。 |
| [setBufferSize](#setBufferSize-int-) | 获取或设置底层缓冲区的大小。值：缓冲区大小。 |
| [setFreeOnDispose](#setFreeOnDispose-boolean-) | 获取或设置一个值，指示在释放时是否释放底层缓冲区。 |
| [setLength](#setLength-long-) | 在派生类中重写时，设置当前流的长度。 |
| [setPosition](#setPosition-long-) | 在派生类中重写时，获取或设置当前流中的位置。流中的当前位置信息。值： |
| [toArray](#toArray--) | 将当前流转换为字节数组。 |
| [write](#write-byte:A-int-int-) | 在派生类中重写时，将一系列字节写入当前流，并根据写入的字节数前移该流中的当前位置。 |
| [writeByte](#writeByte-byte-) | 在流的当前位写入一个字节，并将流中的位置前移一个字节。 |
| [writeTo](#writeTo-com.aspose.ms.System.IO.Stream-) | 写入指定的流。 |

### DefaultBufferSize {#DefaultBufferSize}
```
public static final int DefaultBufferSize
```

默认缓冲区大小（字节）值。

### OptimizedMemoryStream {#OptimizedMemoryStream--}
```
public OptimizedMemoryStream()
```

初始化 {@link OptimizedMemoryStream} 类的新实例。

### OptimizedMemoryStream {#OptimizedMemoryStream-byte:A-}
```
public OptimizedMemoryStream(byte[] buffer)
```

基于指定的字节数组，初始化 {@link OptimizedMemoryStream} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 缓冲区 |  | 用于创建当前流的无符号字节数组。 |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-}
```
public OptimizedMemoryStream(int bufferSize)
```

初始化 {@link OptimizedMemoryStream} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 缓冲区大小 |  | 底层缓冲区的大小。 |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-byte:A-}
```
public OptimizedMemoryStream(int bufferSize, byte[] buffer)
```

基于指定的字节数组，初始化 {@link OptimizedMemoryStream} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 缓冲区大小 |  | 底层缓冲区的大小。 |
| 缓冲区 |  | 用于创建当前流的无符号字节数组。 |

### canRead {#canRead--}
```
public boolean canRead()
```

在派生类中重写时，获取一个值，指示当前流是否支持读取。

**Returns:**
如果流支持读取则为 true；否则为 false。值：

### canSeek {#canSeek--}
```
public boolean canSeek()
```

在派生类中重写时，获取一个值，指示当前流是否支持定位。

**Returns:**
如果流支持定位则为 true；否则为 false。值：

### canWrite {#canWrite--}
```
public boolean canWrite()
```

在派生类中重写时，获取一个值，指示当前流是否支持写入。

**Returns:**
如果流支持写入则为 true；否则为 false。值：

### flush {#flush--}
```
public void flush()
```

该函数已被重写。

### getBufferSize {#getBufferSize--}
```
public final int getBufferSize()
```

获取或设置底层缓冲区的大小。值：缓冲区大小。

**Returns:**
int 值

### getFreeOnDispose {#getFreeOnDispose--}
```
public final boolean getFreeOnDispose()
```

获取或设置一个值，指示在释放时是否释放底层缓冲区。

**Returns:**
布尔值

### getLength {#getLength--}
```
public long getLength()
```

在派生类中重写时，获取流的字节长度。

**Returns:**
表示流长度（以字节为单位）的 long 值。值：

### getPosition {#getPosition--}
```
public long getPosition()
```

在派生类中重写时，获取或设置当前流中的位置。

**Returns:**
流中的当前位置。值：

### read {#read-byte:A-int-int-}
```
public int read(byte[] buffer, int offset, int count)
```

在派生类中重写时，从当前流读取一系列字节，并根据读取的字节数前移流中的位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 缓冲区 |  | 字节数组。当此方法返回时，缓冲区包含具有这些值的指定字节数组 |
| 偏移量 |  | 从当前流读取的数据开始存储的基于零的字节偏移量。 |
| 计数 |  | 从当前流读取的最大字节数。 |

**Returns:**
读取到缓冲区的字节总数。如果当前可用字节不足请求的字节数，则可能少于请求的字节数；如果已到达流的末尾，则为零 (0)。

### readByte {#readByte--}
```
public int readByte()
```

从流中读取一个字节，并将流中的位置前移一个字节；如果已到达流末尾，则返回 -1。

**Returns:**
字节，或在流末尾时为 -1。

### seek {#seek-long-int-}
```
public long seek(long offset, int origin)
```

在派生类中重写时，设置当前流中的位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 偏移量 |  | 相对于 {@code origin} 参数的字节偏移量。 |
| origin |  | 类型为 {@link SeekOrigin} 的值，指示用于获取新位置的参考点。 |

**Returns:**
当前流中的新位置。

### seek {#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-}
在派生类中重写时，设置当前流中的位置。

### setBufferSize {#setBufferSize-int-}
```
public final void setBufferSize(int value)
```

获取或设置底层缓冲区的大小。值：缓冲区大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setFreeOnDispose {#setFreeOnDispose-boolean-}
```
public final void setFreeOnDispose(boolean value)
```

获取或设置一个值，指示在释放时是否释放底层缓冲区。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setLength {#setLength-long-}
```
public void setLength(long value)
```

在派生类中重写时，设置当前流的长度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 当前流所需的字节长度。 |

### setPosition {#setPosition-long-}
```
public void setPosition(long value)
```

在派生类中重写时，获取或设置当前流中的位置。流中的当前位置信息。值：

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  |  |

### toArray {#toArray--}
```
public final byte[] toArray()
```

将当前流转换为字节数组。

**Returns:**
字节数组

### write {#write-byte:A-int-int-}
```
public void write(byte[] buffer, int offset, int count)
```

在派生类中重写时，将一系列字节写入当前流，并根据写入的字节数前移该流中的当前位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 缓冲区 |  | 字节数组。此方法将 {@code count} 字节从 {@code buffer} 复制到当前流。 |
| 偏移量 |  | 在 {@code buffer} 中开始将字节复制到当前流的基于零的字节偏移量。 |
| 计数 |  | 要写入当前流的字节数。 |

### writeByte {#writeByte-byte-}
```
public void writeByte(byte value)
```

在流的当前位写入一个字节，并将流中的位置前移一个字节。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 要写入流的字节。 |

### writeTo {#writeTo-com.aspose.ms.System.IO.Stream-}
写入指定的流。
