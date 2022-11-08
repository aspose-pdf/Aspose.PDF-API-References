---
title: OptimizedMemoryStream
second_title: Aspose.PDF for Java API Reference
description: Defines a MemoryStream that can contains more standard capacity
type: docs
weight: 236
url: /java/com.aspose.pdf/optimizedmemorystream/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.IO.Stream
```
public class OptimizedMemoryStream extends System.IO.Stream
```

Defines a MemoryStream that can contains more standard capacity
## Constructors

| Constructor | Description |
| --- | --- |
| [OptimizedMemoryStream()](#OptimizedMemoryStream--) | Initializes a new instance of the [OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream) class. |
| [OptimizedMemoryStream(int bufferSize, byte[] buffer)](#OptimizedMemoryStream-int-byte---) | Initializes a new instance of the [OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream) class based on the specified byte array. |
| [OptimizedMemoryStream(int bufferSize)](#OptimizedMemoryStream-int-) | Initializes a new instance of the [OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream) class. |
| [OptimizedMemoryStream(byte[] buffer)](#OptimizedMemoryStream-byte---) | Initializes a new instance of the [OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream) class based on the specified byte array. |
## Fields

| Field | Description |
| --- | --- |
| [DefaultBufferSize](#DefaultBufferSize) | Default buffer size value in bytes. |
| [Null](#Null) |  |
## Methods

| Method | Description |
| --- | --- |
| [_synchronized(System.IO.Stream arg0)](#-synchronized-com.aspose.ms.System.IO.Stream-) |  |
| [beginRead(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4)](#beginRead-byte---int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [beginWrite(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4)](#beginWrite-byte---int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-) |  |
| [canRead()](#canRead--) | When overridden in a derived class, gets a value indicating whether the current stream supports reading. |
| [canSeek()](#canSeek--) | When overridden in a derived class, gets a value indicating whether the current stream supports seeking. |
| [canTimeout()](#canTimeout--) |  |
| [canWrite()](#canWrite--) | When overridden in a derived class, gets a value indicating whether the current stream supports writing. |
| [close()](#close--) |  |
| [copyTo(System.IO.Stream arg0)](#copyTo-com.aspose.ms.System.IO.Stream-) |  |
| [copyTo(System.IO.Stream arg0, int arg1)](#copyTo-com.aspose.ms.System.IO.Stream-int-) |  |
| [dispose()](#dispose--) |  |
| [endRead(System.IAsyncResult arg0)](#endRead-com.aspose.ms.System.IAsyncResult-) |  |
| [endWrite(System.IAsyncResult arg0)](#endWrite-com.aspose.ms.System.IAsyncResult-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | The function overrided. |
| [fromJava(InputStream arg0)](#fromJava-java.io.InputStream-) |  |
| [getBufferSize()](#getBufferSize--) | Gets or sets the size of the underlying buffers. |
| [getClass()](#getClass--) |  |
| [getFreeOnDispose()](#getFreeOnDispose--) | Gets or sets a value indicating whether to free the underlying buffers on dispose. |
| [getLength()](#getLength--) | When overridden in a derived class, gets the length in bytes of the stream. |
| [getPosition()](#getPosition--) | When overridden in a derived class, gets or sets the position within the current stream. |
| [getReadTimeout()](#getReadTimeout--) |  |
| [getWriteTimeout()](#getWriteTimeout--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | When overridden in a derived class, reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read. |
| [readByte()](#readByte--) | Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream. |
| [seek(long offset, int origin)](#seek-long-int-) | When overridden in a derived class, sets the position within the current stream. |
| [setBufferSize(int value)](#setBufferSize-int-) | Gets or sets the size of the underlying buffers. |
| [setFreeOnDispose(boolean value)](#setFreeOnDispose-boolean-) | Gets or sets a value indicating whether to free the underlying buffers on dispose. |
| [setLength(long value)](#setLength-long-) | When overridden in a derived class, sets the length of the current stream. |
| [setPosition(long value)](#setPosition-long-) | When overridden in a derived class, gets or sets the position within the current stream. |
| [setReadTimeout(int arg0)](#setReadTimeout-int-) |  |
| [setWriteTimeout(int arg0)](#setWriteTimeout-int-) |  |
| [toArray()](#toArray--) | Converts the current stream to a byte array. |
| [toInputStream()](#toInputStream--) |  |
| [toJava(System.IO.Stream arg0)](#toJava-com.aspose.ms.System.IO.Stream-) |  |
| [toOutputStream()](#toOutputStream--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | When overridden in a derived class, writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written. |
| [writeByte(byte value)](#writeByte-byte-) | Writes a byte to the current position in the stream and advances the position within the stream by one byte. |
| [writeTo(System.IO.Stream stream)](#writeTo-com.aspose.ms.System.IO.Stream-) | Writes to the specified stream. |
### OptimizedMemoryStream() {#OptimizedMemoryStream--}
```
public OptimizedMemoryStream()
```


Initializes a new instance of the [OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream) class.

### OptimizedMemoryStream(int bufferSize, byte[] buffer) {#OptimizedMemoryStream-int-byte---}
```
public OptimizedMemoryStream(int bufferSize, byte[] buffer)
```


Initializes a new instance of the [OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream) class based on the specified byte array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bufferSize | int | Size of the underlying buffers. |
| buffer | byte[] | The array of unsigned bytes from which to create the current stream. |

### OptimizedMemoryStream(int bufferSize) {#OptimizedMemoryStream-int-}
```
public OptimizedMemoryStream(int bufferSize)
```


Initializes a new instance of the [OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bufferSize | int | Size of the underlying buffers. |

### OptimizedMemoryStream(byte[] buffer) {#OptimizedMemoryStream-byte---}
```
public OptimizedMemoryStream(byte[] buffer)
```


Initializes a new instance of the [OptimizedMemoryStream](../../com.aspose.pdf/optimizedmemorystream) class based on the specified byte array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer | byte[] | The array of unsigned bytes from which to create the current stream. |

### DefaultBufferSize {#DefaultBufferSize}
```
public static final int DefaultBufferSize
```


Default buffer size value in bytes.

### Null {#Null}
```
public static System.IO.Stream Null
```


### _synchronized(System.IO.Stream arg0) {#-synchronized-com.aspose.ms.System.IO.Stream-}
```
public static System.IO.Stream _synchronized(System.IO.Stream arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IO.Stream |  |

**Returns:**
com.aspose.ms.System.IO.Stream
### beginRead(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4) {#beginRead-byte---int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public System.IAsyncResult beginRead(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | byte[] |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | com.aspose.ms.System.AsyncCallback |  |
| arg4 | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### beginWrite(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4) {#beginWrite-byte---int-int-com.aspose.ms.System.AsyncCallback-java.lang.Object-}
```
public System.IAsyncResult beginWrite(byte[] arg0, int arg1, int arg2, System.AsyncCallback arg3, Object arg4)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | byte[] |  |
| arg1 | int |  |
| arg2 | int |  |
| arg3 | com.aspose.ms.System.AsyncCallback |  |
| arg4 | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.IAsyncResult
### canRead() {#canRead--}
```
public boolean canRead()
```


When overridden in a derived class, gets a value indicating whether the current stream supports reading.

**Returns:**
boolean - true if the stream supports reading; otherwise, false. Value:
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


When overridden in a derived class, gets a value indicating whether the current stream supports seeking.

**Returns:**
boolean - true if the stream supports seeking; otherwise, false. Value:
### canTimeout() {#canTimeout--}
```
public boolean canTimeout()
```




**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


When overridden in a derived class, gets a value indicating whether the current stream supports writing.

**Returns:**
boolean - true if the stream supports writing; otherwise, false. Value:
### close() {#close--}
```
public void close()
```




### copyTo(System.IO.Stream arg0) {#copyTo-com.aspose.ms.System.IO.Stream-}
```
public void copyTo(System.IO.Stream arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IO.Stream |  |

### copyTo(System.IO.Stream arg0, int arg1) {#copyTo-com.aspose.ms.System.IO.Stream-int-}
```
public void copyTo(System.IO.Stream arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
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




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IAsyncResult |  |

**Returns:**
int
### endWrite(System.IAsyncResult arg0) {#endWrite-com.aspose.ms.System.IAsyncResult-}
```
public void endWrite(System.IAsyncResult arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IAsyncResult |  |

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
### flush() {#flush--}
```
public void flush()
```


The function overrided.

### fromJava(InputStream arg0) {#fromJava-java.io.InputStream-}
```
public static System.IO.Stream fromJava(InputStream arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.io.InputStream |  |

**Returns:**
com.aspose.ms.System.IO.Stream
### getBufferSize() {#getBufferSize--}
```
public final int getBufferSize()
```


Gets or sets the size of the underlying buffers.

Value: The buffers size.

**Returns:**
int - int value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFreeOnDispose() {#getFreeOnDispose--}
```
public final boolean getFreeOnDispose()
```


Gets or sets a value indicating whether to free the underlying buffers on dispose.

**Returns:**
boolean - boolean value
### getLength() {#getLength--}
```
public long getLength()
```


When overridden in a derived class, gets the length in bytes of the stream.

**Returns:**
long - A long value representing the length of the stream in bytes. Value:
### getPosition() {#getPosition--}
```
public long getPosition()
```


When overridden in a derived class, gets or sets the position within the current stream.

**Returns:**
long - The current position within the stream. Value:
### getReadTimeout() {#getReadTimeout--}
```
public int getReadTimeout()
```




**Returns:**
int
### getWriteTimeout() {#getWriteTimeout--}
```
public int getWriteTimeout()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




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




### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


When overridden in a derived class, reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer | byte[] | An array of bytes. When this method returns, the buffer contains the specified byte array with the values |
| offset | int | The zero-based byte offset in at which to begin storing the data read from the current stream. |
| count | int | The maximum number of bytes to be read from the current stream. |

**Returns:**
int - The total number of bytes read into the buffer. This can be less than the number of bytes requested if that many bytes are not currently available, or zero (0) if the end of the stream has been reached.
### readByte() {#readByte--}
```
public int readByte()
```


Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream.

**Returns:**
int - byte or -1 if at the end of the stream.
### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


When overridden in a derived class, sets the position within the current stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| offset | long | A byte offset relative to the  origin  parameter. |
| origin | int | A value of type [SeekOrigin](../../com.aspose.pdf/seekorigin) indicating the reference point used to obtain the new position. |

**Returns:**
long - The new position within the current stream.
### setBufferSize(int value) {#setBufferSize-int-}
```
public final void setBufferSize(int value)
```


Gets or sets the size of the underlying buffers.

Value: The buffers size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setFreeOnDispose(boolean value) {#setFreeOnDispose-boolean-}
```
public final void setFreeOnDispose(boolean value)
```


Gets or sets a value indicating whether to free the underlying buffers on dispose.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


When overridden in a derived class, sets the length of the current stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The desired length of the current stream in bytes. |

### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


When overridden in a derived class, gets or sets the position within the current stream.

The current position within the stream. Value:

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setReadTimeout(int arg0) {#setReadTimeout-int-}
```
public void setReadTimeout(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### setWriteTimeout(int arg0) {#setWriteTimeout-int-}
```
public void setWriteTimeout(int arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | int |  |

### toArray() {#toArray--}
```
public final byte[] toArray()
```


Converts the current stream to a byte array.

**Returns:**
byte[] - An array of bytes
### toInputStream() {#toInputStream--}
```
public InputStream toInputStream()
```




**Returns:**
java.io.InputStream
### toJava(System.IO.Stream arg0) {#toJava-com.aspose.ms.System.IO.Stream-}
```
public static InputStream toJava(System.IO.Stream arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.IO.Stream |  |

**Returns:**
java.io.InputStream
### toOutputStream() {#toOutputStream--}
```
public OutputStream toOutputStream()
```




**Returns:**
java.io.OutputStream
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

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


When overridden in a derived class, writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer | byte[] | An array of bytes. This method copies  count  bytes from  buffer  to the current stream. |
| offset | int | The zero-based byte offset in  buffer  at which to begin copying bytes to the current stream. |
| count | int | The number of bytes to be written to the current stream. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


Writes a byte to the current position in the stream and advances the position within the stream by one byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | The byte to write to the stream. |

### writeTo(System.IO.Stream stream) {#writeTo-com.aspose.ms.System.IO.Stream-}
```
public final void writeTo(System.IO.Stream stream)
```


Writes to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream. |

