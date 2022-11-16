---
title: OptimizedMemoryStream
second_title: 用于 Java API 参考的 Aspose.PDF
description: 定义一个可以包含更多标准容量的 MemoryStream
type: docs
weight: 236
url: /zh/java/com.aspose.pdf/optimizedmemorystream/
---
**遗产：**
java.lang.Object, com.aspose.ms.System.IO.Stream
```
public class OptimizedMemoryStream extends System.IO.Stream
```

定义一个可以包含更多标准容量的 MemoryStream
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OptimizedMemoryStream()](#OptimizedMemoryStream--) | 初始化一个新的实例[OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream)班级。 |
| [OptimizedMemoryStream(int bufferSize, byte[] buffer)](#OptimizedMemoryStream-int-byte---) | 初始化一个新的实例[OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream)基于指定字节数组的类。 |
| [OptimizedMemoryStream(int bufferSize)](#OptimizedMemoryStream-int-) | 初始化一个新的实例[OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream)班级。 |
| [OptimizedMemoryStream(byte[] buffer)](#OptimizedMemoryStream-byte---) | 初始化一个新的实例[OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream)基于指定字节数组的类。 |
## 领域

| 场地 | 描述 |
| --- | --- |
| [DefaultBufferSize](#DefaultBufferSize) | 默认缓冲区大小值（以字节为单位）。 |
| [Null](#Null) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [_synchronized(System.IO.Stream arg0)](#-synchronized-com.aspose.ms.System.IO.Stream-) |  |
| [beginRead(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4)](#beginRead-byte---int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [beginWrite(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4)](#beginWrite-byte---int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [canRead()](#canRead--) | 当在派生类中重写时，获取一个值，该值指示当前流是否支持读取。 |
| [canSeek()](#canSeek--) | 当在派生类中重写时，获取一个值，该值指示当前流是否支持查找。 |
| [canTimeout()](#canTimeout--) |  |
| [canWrite()](#canWrite--) | 当在派生类中重写时，获取一个值，该值指示当前流是否支持写入。 |
| [close()](#close--) |  |
| [copyTo(System.IO.Stream arg0)](#copyTo-com.aspose.ms.System.IO.Stream-) |  |
| [copyTo(System.IO.Stream arg0, int arg1)](#copyTo-com.aspose.ms.System.IO.Stream-int-) |  |
| [dispose()](#dispose--) |  |
| [endRead(System.IAsyncResult arg0)](#endRead-com.aspose.ms.System.IAsyncResult-) |  |
| [endWrite(System.IAsyncResult arg0)](#endWrite-com.aspose.ms.System.IAsyncResult-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | 函数被覆盖。 |
| [fromJava(InputStream arg0)](#fromJava-java.io.InputStream-) |  |
| [getBufferSize()](#getBufferSize--) | 获取或设置基础缓冲区的大小。 |
| [getClass()](#getClass--) |  |
| [getFreeOnDispose()](#getFreeOnDispose--) | 获取或设置一个值，该值指示是否在处置时释放基础缓冲区。 |
| [getLength()](#getLength--) | 在派生类中重写时，获取流的字节长度。 |
| [getPosition()](#getPosition--) | 在派生类中重写时，获取或设置当前流中的位置。 |
| [getReadTimeout()](#getReadTimeout--) |  |
| [getWriteTimeout()](#getWriteTimeout--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | 当在派生类中重写时，从当前流中读取字节序列，并按读取的字节数推进流中的位置。 |
| [readByte()](#readByte--) | 从流中读取一个字节并将流中的位置前进一个字节，如果在流的末尾则返回 -1。 |
| [seek(long offset, int origin)](#seek-long-int-) | 在派生类中重写时，设置当前流中的位置。 |
| [setBufferSize(int value)](#setBufferSize-int-) | 获取或设置基础缓冲区的大小。 |
| [setFreeOnDispose(boolean value)](#setFreeOnDispose-boolean-) | 获取或设置一个值，该值指示是否在处置时释放基础缓冲区。 |
| [setLength(long value)](#setLength-long-) | 在派生类中重写时，设置当前流的长度。 |
| [setPosition(long value)](#setPosition-long-) | 在派生类中重写时，获取或设置当前流中的位置。 |
| [setReadTimeout(int arg0)](#setReadTimeout-int-) |  |
| [setWriteTimeout(int arg0)](#setWriteTimeout-int-) |  |
| [toArray()](#toArray--) | 将当前流转换为字节数组。 |
| [toInputStream()](#toInputStream--) |  |
| [toJava(System.IO.Stream arg0)](#toJava-com.aspose.ms.System.IO.Stream-) |  |
| [toOutputStream()](#toOutputStream--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | 当在派生类中重写时，将一个字节序列写入当前流，并将该流中的当前位置推进写入的字节数。 |
| [writeByte(byte value)](#writeByte-byte-) | 将一个字节写入流中的当前位置，并将流中的位置前进一个字节。 |
| [writeTo(System.IO.Stream stream)](#writeTo-com.aspose.ms.System.IO.Stream-) | 写入指定的流。 |
### OptimizedMemoryStream() {#OptimizedMemoryStream--}
```
public OptimizedMemoryStream()
```


初始化一个新的实例[OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream)班级。

### OptimizedMemoryStream(int bufferSize, byte[] buffer) {#OptimizedMemoryStream-int-byte---}
```
public OptimizedMemoryStream(int bufferSize, byte[] buffer)
```


初始化一个新的实例[OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream)基于指定字节数组的类。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| bufferSize | int | 底层缓冲区的大小。 |
| buffer | byte[] | 从中创建当前流的无符号字节数组。 |

### OptimizedMemoryStream(int bufferSize) {#OptimizedMemoryStream-int-}
```
public OptimizedMemoryStream(int bufferSize)
```


初始化一个新的实例[OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream)班级。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| bufferSize | int | 底层缓冲区的大小。 |

### OptimizedMemoryStream(byte[] buffer) {#OptimizedMemoryStream-byte---}
```
public OptimizedMemoryStream(byte[] buffer)
```


初始化一个新的实例[OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream)基于指定字节数组的类。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| buffer | byte[] | 从中创建当前流的无符号字节数组。 |

### DefaultBufferSize {#DefaultBufferSize}
```
public static final int DefaultBufferSize
```


默认缓冲区大小值（以字节为单位）。

### Null {#Null}
```
public static System.IO.Stream Null
```


### _synchronized(System.IO.Stream arg0) {#-synchronized-com.aspose.ms.System.IO.Stream-}
```
public static System.IO.Stream _synchronized(System.IO.Stream arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IO.Stream |  |

**退货：**
com.aspose.ms.System.IO.Stream
### beginRead(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4) {#beginRead-byte---int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public System.IAsyncResult beginRead(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | byte[] |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | com.aspose.ms.System.AsyncCallback |  |
| arg4 | java.lang.Object |  |

**退货：**
com.aspose.ms.System.IAsyncResult
### beginWrite(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4) {#beginWrite-byte---int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public System.IAsyncResult beginWrite(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | byte[] |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | com.aspose.ms.System.AsyncCallback |  |
| arg4 | java.lang.Object |  |

**退货：**
com.aspose.ms.System.IAsyncResult
### canRead() {#canRead--}
```
public boolean canRead()
```


当在派生类中重写时，获取一个值，该值指示当前流是否支持读取。

**退货：**
boolean - 如果流支持读取则为 true；否则，假的。价值：
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


当在派生类中重写时，获取一个值，该值指示当前流是否支持查找。

**退货：**
boolean - 如果流支持搜索则为 true；否则，假的。价值：
### canTimeout() {#canTimeout--}
```
public boolean canTimeout()
```




**退货：**
布尔值
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


当在派生类中重写时，获取一个值，该值指示当前流是否支持写入。

**退货：**
boolean - 如果流支持写入则为 true；否则，假的。价值：
### close() {#close--}
```
public void close()
```




### copyTo(System.IO.Stream arg0) {#copyTo-com.aspose.ms.System.IO.Stream-}
```
public void copyTo(System.IO.Stream arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IO.Stream |  |

### copyTo(System.IO.Stream arg0, int arg1) {#copyTo-com.aspose.ms.System.IO.Stream-int-}
```
public void copyTo(System.IO.Stream arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IO.Stream |  |
| arg1 | int |  |

### dispose() {#dispose--}
```
public void dispose()
```




### endRead(System.IAsyncResult arg0) {#endRead-com.aspose.ms.System.IAsyncResult-}
```
public int endRead(System.IAsyncResult arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IAsyncResult |  |

**退货：**
整数
### endWrite(System.IAsyncResult arg0) {#endWrite-com.aspose.ms.System.IAsyncResult-}
```
public void endWrite(System.IAsyncResult arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IAsyncResult |  |

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
### flush() {#flush--}
```
public void flush()
```


函数被覆盖。

### fromJava(InputStream arg0) {#fromJava-java.io.InputStream-}
```
public static System.IO.Stream fromJava(InputStream arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.io.InputStream |  |

**退货：**
com.aspose.ms.System.IO.Stream
### getBufferSize() {#getBufferSize--}
```
public final int getBufferSize()
```


获取或设置基础缓冲区的大小。

值：缓冲区大小。

**退货：**
int - 整数值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getFreeOnDispose() {#getFreeOnDispose--}
```
public final boolean getFreeOnDispose()
```


获取或设置一个值，该值指示是否在处置时释放基础缓冲区。

**退货：**
boolean - 布尔值
### getLength() {#getLength--}
```
public long getLength()
```


在派生类中重写时，获取流的字节长度。

**退货：**
long - 一个 long 值，表示流的长度（以字节为单位）。价值：
### getPosition() {#getPosition--}
```
public long getPosition()
```


在派生类中重写时，获取或设置当前流中的位置。

**退货：**
long - 流中的当前位置。价值：
### getReadTimeout() {#getReadTimeout--}
```
public int getReadTimeout()
```




**退货：**
整数
### getWriteTimeout() {#getWriteTimeout--}
```
public int getWriteTimeout()
```




**退货：**
整数
### hashCode() {#hashCode--}
```
public native int hashCode()
```




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




### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


当在派生类中重写时，从当前流中读取字节序列，并按读取的字节数推进流中的位置。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| buffer | byte[] | 字节数组。当此方法返回时，缓冲区包含具有值的指定字节数组 |
| offset | int | 开始存储从当前流读取的数据的从零开始的字节偏移量。 |
| count | int | 要从当前流中读取的最大字节数。 |

**退货：**
int - 读入缓冲区的总字节数。如果当前没有那么多字节可用，则这可能小于请求的字节数，或者如果已到达流的末尾，则为零 (0)。
### readByte() {#readByte--}
```
public int readByte()
```


从流中读取一个字节并将流中的位置前进一个字节，如果在流的末尾则返回 -1。

**退货：**
int - 字节或 -1 如果在流的末尾。
### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


在派生类中重写时，设置当前流中的位置。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| offset | long | 相对于 origin 参数的字节偏移量。 |
| origin | int | 类型值[SeekOrigin](../../com.aspose.pdf/seekorigin)指示用于获取新位置的参考点。 |

**退货：**
long - 当前流中的新位置。
### setBufferSize(int value) {#setBufferSize-int-}
```
public final void setBufferSize(int value)
```


获取或设置基础缓冲区的大小。

值：缓冲区大小。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setFreeOnDispose(boolean value) {#setFreeOnDispose-boolean-}
```
public final void setFreeOnDispose(boolean value)
```


获取或设置一个值，该值指示是否在处置时释放基础缓冲区。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


在派生类中重写时，设置当前流的长度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | long | 当前流的所需长度（以字节为单位）。 |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


在派生类中重写时，获取或设置当前流中的位置。

流中的当前位置。价值：

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### setReadTimeout(int arg0) {#setReadTimeout-int-}
```
public void setReadTimeout(int arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |

### setWriteTimeout(int arg0) {#setWriteTimeout-int-}
```
public void setWriteTimeout(int arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | int |  |

### toArray() {#toArray--}
```
public final byte[] toArray()
```


将当前流转换为字节数组。

**退货：**
字节[] - 字节数组
### toInputStream() {#toInputStream--}
```
public InputStream toInputStream()
```




**退货：**
java.io.InputStream
### toJava(System.IO.Stream arg0) {#toJava-com.aspose.ms.System.IO.Stream-}
```
public static InputStream toJava(System.IO.Stream arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IO.Stream |  |

**退货：**
java.io.InputStream
### toOutputStream() {#toOutputStream--}
```
public OutputStream toOutputStream()
```




**退货：**
java.io.OutputStream
### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
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

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


当在派生类中重写时，将一个字节序列写入当前流，并将该流中的当前位置推进写入的字节数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| buffer | byte[] | 字节数组。此方法将计数字节从缓冲区复制到当前流。 |
| offset | int | 缓冲区中从零开始的字节偏移量，从该偏移量开始将字节复制到当前流。 |
| count | int | 要写入当前流的字节数。 |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


将一个字节写入流中的当前位置，并将流中的位置前进一个字节。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | byte | 要写入流的字节。 |

### writeTo(System.IO.Stream stream) {#writeTo-com.aspose.ms.System.IO.Stream-}
```
public final void writeTo(System.IO.Stream stream)
```


写入指定的流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 流。 |
