---
title: OptimizedMemoryStream
second_title: Aspose.PDF for Java API Reference
description: Defines a MemoryStream that can contains more standard capacity
type: docs
weight: 3220
url: /java/com.aspose.pdf/optimizedmemorystream/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.IO.Stream com.aspose.pdf.OptimizedMemoryStream, com.aspose.ms.System.IO.Stream, com.aspose.pdf.OptimizedMemoryStream

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class OptimizedMemoryStream extends com.aspose.ms.System.IO.Stream
```

Defines a MemoryStream that can contains more standard capacity

## Fields

| Field | Description |
| --- | --- |
| [DefaultBufferSize](#DefaultBufferSize) | Default buffer size value in bytes. |

## Constructors

| Constructor | Description |
| --- | --- |
| [OptimizedMemoryStream](#OptimizedMemoryStream--) | Initializes a new instance of the {@link OptimizedMemoryStream} class. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-byte:A-) | Initializes a new instance of the {@link OptimizedMemoryStream} class based on the specified byte array. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-) | Initializes a new instance of the {@link OptimizedMemoryStream} class. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-byte:A-) | Initializes a new instance of the {@link OptimizedMemoryStream} class based on the specified byte array. |

## Methods

| Method | Description |
| --- | --- |
| [canRead](#canRead--) | When overridden in a derived class, gets a value indicating whether the current stream supports reading. |
| [canSeek](#canSeek--) | When overridden in a derived class, gets a value indicating whether the current stream supports seeking. |
| [canWrite](#canWrite--) | When overridden in a derived class, gets a value indicating whether the current stream supports writing. |
| [flush](#flush--) | The function overrided. |
| [getBufferSize](#getBufferSize--) | Gets or sets the size of the underlying buffers. Value: The buffers size. |
| [getFreeOnDispose](#getFreeOnDispose--) | Gets or sets a value indicating whether to free the underlying buffers on dispose. |
| [getLength](#getLength--) | When overridden in a derived class, gets the length in bytes of the stream. |
| [getPosition](#getPosition--) | When overridden in a derived class, gets or sets the position within the current stream. |
| [read](#read-byte:A-int-int-) | When overridden in a derived class, reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read. |
| [readByte](#readByte--) | Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream. |
| [seek](#seek-long-int-) | When overridden in a derived class, sets the position within the current stream. |
| [seek](#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-) | When overridden in a derived class, sets the position within the current stream. |
| [setBufferSize](#setBufferSize-int-) | Gets or sets the size of the underlying buffers. Value: The buffers size. |
| [setFreeOnDispose](#setFreeOnDispose-boolean-) | Gets or sets a value indicating whether to free the underlying buffers on dispose. |
| [setLength](#setLength-long-) | When overridden in a derived class, sets the length of the current stream. |
| [setPosition](#setPosition-long-) | When overridden in a derived class, gets or sets the position within the current stream. The current position within the stream. Value: |
| [toArray](#toArray--) | Converts the current stream to a byte array. |
| [write](#write-byte:A-int-int-) | When overridden in a derived class, writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written. |
| [writeByte](#writeByte-byte-) | Writes a byte to the current position in the stream and advances the position within the stream by one byte. |
| [writeTo](#writeTo-com.aspose.ms.System.IO.Stream-) | Writes to the specified stream. |

### DefaultBufferSize {#DefaultBufferSize}
```
public static final int DefaultBufferSize
```

Default buffer size value in bytes.

### OptimizedMemoryStream {#OptimizedMemoryStream--}
```
public OptimizedMemoryStream()
```

Initializes a new instance of the {@link OptimizedMemoryStream} class.

### OptimizedMemoryStream {#OptimizedMemoryStream-byte:A-}
```
public OptimizedMemoryStream(byte[] buffer)
```

Initializes a new instance of the {@link OptimizedMemoryStream} class based on the specified byte array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer |  | The array of unsigned bytes from which to create the current stream. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-}
```
public OptimizedMemoryStream(int bufferSize)
```

Initializes a new instance of the {@link OptimizedMemoryStream} class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bufferSize |  | Size of the underlying buffers. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-byte:A-}
```
public OptimizedMemoryStream(int bufferSize, byte[] buffer)
```

Initializes a new instance of the {@link OptimizedMemoryStream} class based on the specified byte array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bufferSize |  | Size of the underlying buffers. |
| buffer |  | The array of unsigned bytes from which to create the current stream. |

### canRead {#canRead--}
```
public boolean canRead()
```

When overridden in a derived class, gets a value indicating whether the current stream supports reading.

**Returns:**
true if the stream supports reading; otherwise, false. Value:

### canSeek {#canSeek--}
```
public boolean canSeek()
```

When overridden in a derived class, gets a value indicating whether the current stream supports seeking.

**Returns:**
true if the stream supports seeking; otherwise, false. Value:

### canWrite {#canWrite--}
```
public boolean canWrite()
```

When overridden in a derived class, gets a value indicating whether the current stream supports writing.

**Returns:**
true if the stream supports writing; otherwise, false. Value:

### flush {#flush--}
```
public void flush()
```

The function overrided.

### getBufferSize {#getBufferSize--}
```
public final int getBufferSize()
```

Gets or sets the size of the underlying buffers. Value: The buffers size.

**Returns:**
int value

### getFreeOnDispose {#getFreeOnDispose--}
```
public final boolean getFreeOnDispose()
```

Gets or sets a value indicating whether to free the underlying buffers on dispose.

**Returns:**
boolean value

### getLength {#getLength--}
```
public long getLength()
```

When overridden in a derived class, gets the length in bytes of the stream.

**Returns:**
A long value representing the length of the stream in bytes. Value:

### getPosition {#getPosition--}
```
public long getPosition()
```

When overridden in a derived class, gets or sets the position within the current stream.

**Returns:**
The current position within the stream. Value:

### read {#read-byte:A-int-int-}
```
public int read(byte[] buffer, int offset, int count)
```

When overridden in a derived class, reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer |  | An array of bytes. When this method returns, the buffer contains the specified byte array with the values |
| offset |  | The zero-based byte offset in at which to begin storing the data read from the current stream. |
| count |  | The maximum number of bytes to be read from the current stream. |

**Returns:**
The total number of bytes read into the buffer. This can be less than the number of bytes requested if that many bytes are not currently available, or zero (0) if the end of the stream has been reached.

### readByte {#readByte--}
```
public int readByte()
```

Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream.

**Returns:**
byte or -1 if at the end of the stream.

### seek {#seek-long-int-}
```
public long seek(long offset, int origin)
```

When overridden in a derived class, sets the position within the current stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| offset |  | A byte offset relative to the {@code origin} parameter. |
| origin |  | A value of type {@link SeekOrigin} indicating the reference point used to obtain the new position. |

**Returns:**
The new position within the current stream.

### seek {#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-}
When overridden in a derived class, sets the position within the current stream.

### setBufferSize {#setBufferSize-int-}
```
public final void setBufferSize(int value)
```

Gets or sets the size of the underlying buffers. Value: The buffers size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setFreeOnDispose {#setFreeOnDispose-boolean-}
```
public final void setFreeOnDispose(boolean value)
```

Gets or sets a value indicating whether to free the underlying buffers on dispose.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setLength {#setLength-long-}
```
public void setLength(long value)
```

When overridden in a derived class, sets the length of the current stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | The desired length of the current stream in bytes. |

### setPosition {#setPosition-long-}
```
public void setPosition(long value)
```

When overridden in a derived class, gets or sets the position within the current stream. The current position within the stream. Value:

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  |  |

### toArray {#toArray--}
```
public final byte[] toArray()
```

Converts the current stream to a byte array.

**Returns:**
An array of bytes

### write {#write-byte:A-int-int-}
```
public void write(byte[] buffer, int offset, int count)
```

When overridden in a derived class, writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer |  | An array of bytes. This method copies {@code count} bytes from {@code buffer} to the current stream. |
| offset |  | The zero-based byte offset in {@code buffer} at which to begin copying bytes to the current stream. |
| count |  | The number of bytes to be written to the current stream. |

### writeByte {#writeByte-byte-}
```
public void writeByte(byte value)
```

Writes a byte to the current position in the stream and advances the position within the stream by one byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | The byte to write to the stream. |

### writeTo {#writeTo-com.aspose.ms.System.IO.Stream-}
Writes to the specified stream.
