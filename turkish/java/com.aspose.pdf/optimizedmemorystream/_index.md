---
title: "OptimizedMemoryStream"
linktitle: "OptimizedMemoryStream"
second_title: "Aspose.PDF for Java API Referansı"
description: "Daha standart kapasite içerebilen bir MemoryStream tanımlar"
type: docs
weight: 3220
url: /tr/java/com.aspose.pdf/optimizedmemorystream/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.IO.Stream com.aspose.pdf.OptimizedMemoryStream, com.aspose.ms.System.IO.Stream, com.aspose.pdf.OptimizedMemoryStream

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class OptimizedMemoryStream extends com.aspose.ms.System.IO.Stream
```

Daha standart kapasite içerebilen bir MemoryStream tanımlar

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [DefaultBufferSize](#DefaultBufferSize) | Varsayılan tampon boyutu değeri bayt cinsindendir. |

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OptimizedMemoryStream](#OptimizedMemoryStream--) | Yeni bir {@link OptimizedMemoryStream} sınıfı örneğini başlatır. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-byte:A-) | Belirtilen bayt dizisine dayalı olarak yeni bir {@link OptimizedMemoryStream} sınıfı örneğini başlatır. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-) | Yeni bir {@link OptimizedMemoryStream} sınıfı örneğini başlatır. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-byte:A-) | Belirtilen bayt dizisine dayalı olarak yeni bir {@link OptimizedMemoryStream} sınıfı örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [canRead](#canRead--) | Türetilmiş bir sınıfta geçersiz kılındığında, mevcut akışın okuma desteği olup olmadığını gösteren bir değer alır. |
| [canSeek](#canSeek--) | Türetilmiş bir sınıfta geçersiz kılındığında, mevcut akışın konumlandırma desteği olup olmadığını gösteren bir değer alır. |
| [canWrite](#canWrite--) | Türetilmiş bir sınıfta geçersiz kılındığında, mevcut akışın yazma desteği olup olmadığını gösteren bir değer alır. |
| [flush](#flush--) | Fonksiyon geçersiz kılındı. |
| [getBufferSize](#getBufferSize--) | Temel tamponların boyutunu alır veya ayarlar. Değer: Tamponların boyutu. |
| [getFreeOnDispose](#getFreeOnDispose--) | Dispose edildiğinde temel tamponların serbest bırakılıp bırakılmayacağını gösteren bir değeri alır veya ayarlar. |
| [getLength](#getLength--) | Türetilmiş bir sınıfta geçersiz kılındığında, akışın bayt cinsinden uzunluğunu alır. |
| [getPosition](#getPosition--) | Türetilmiş bir sınıfta geçersiz kılındığında, geçerli akış içindeki konumu alır veya ayarlar. |
| [read](#read-byte:A-int-int-) | Türetilmiş bir sınıfta geçersiz kılındığında, geçerli akıştan bir bayt dizisi okur ve akıştaki konumu okunan bayt sayısı kadar ilerletir. |
| [readByte](#readByte--) | Akıştan bir bayt okur ve akıştaki konumu bir bayt ilerletir; akışın sonunda ise -1 döndürür. |
| [seek](#seek-long-int-) | Türetilmiş bir sınıfta geçersiz kılındığında, geçerli akış içindeki konumu ayarlar. |
| [seek](#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-) | Türetilmiş bir sınıfta geçersiz kılındığında, geçerli akış içindeki konumu ayarlar. |
| [setBufferSize](#setBufferSize-int-) | Temel tamponların boyutunu alır veya ayarlar. Değer: Tamponların boyutu. |
| [setFreeOnDispose](#setFreeOnDispose-boolean-) | Dispose edildiğinde temel tamponların serbest bırakılıp bırakılmayacağını gösteren bir değeri alır veya ayarlar. |
| [setLength](#setLength-long-) | Türetilmiş bir sınıfta geçersiz kılındığında, geçerli akışın uzunluğunu ayarlar. |
| [setPosition](#setPosition-long-) | Türetilmiş bir sınıfta geçersiz kılındığında, geçerli akış içindeki konumu alır veya ayarlar. Akış içindeki mevcut konum. Değer: |
| [toArray](#toArray--) | Geçerli akışı bir bayt dizisine dönüştürür. |
| [write](#write-byte:A-int-int-) | Türetilmiş bir sınıfta geçersiz kılındığında, bir bayt dizisini geçerli akışa yazar ve bu akıştaki mevcut konumu yazılan bayt sayısı kadar ilerletir. |
| [writeByte](#writeByte-byte-) | Akıştaki mevcut konuma bir bayt yazar ve akıştaki konumu bir bayt ilerletir. |
| [writeTo](#writeTo-com.aspose.ms.System.IO.Stream-) | Belirtilen akışa yazar. |

### DefaultBufferSize {#DefaultBufferSize}
```
public static final int DefaultBufferSize
```

Varsayılan tampon boyutu değeri bayt cinsindendir.

### OptimizedMemoryStream {#OptimizedMemoryStream--}
```
public OptimizedMemoryStream()
```

Yeni bir {@link OptimizedMemoryStream} sınıfı örneğini başlatır.

### OptimizedMemoryStream {#OptimizedMemoryStream-byte:A-}
```
public OptimizedMemoryStream(byte[] buffer)
```

Belirtilen bayt dizisine dayalı olarak yeni bir {@link OptimizedMemoryStream} sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon |  | Geçerli akışı oluşturmak için kullanılacak işaretsiz bayt dizisi. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-}
```
public OptimizedMemoryStream(int bufferSize)
```

Yeni bir {@link OptimizedMemoryStream} sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tamponBoyutu |  | Temel tamponların boyutu. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-byte:A-}
```
public OptimizedMemoryStream(int bufferSize, byte[] buffer)
```

Belirtilen bayt dizisine dayalı olarak yeni bir {@link OptimizedMemoryStream} sınıfı örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tamponBoyutu |  | Temel tamponların boyutu. |
| tampon |  | Geçerli akışı oluşturmak için kullanılacak işaretsiz bayt dizisi. |

### canRead {#canRead--}
```
public boolean canRead()
```

Türetilmiş bir sınıfta geçersiz kılındığında, mevcut akışın okuma desteği olup olmadığını gösteren bir değer alır.

**Returns:**
Akış okuma destekliyorsa true; aksi takdirde false. Değer:

### canSeek {#canSeek--}
```
public boolean canSeek()
```

Türetilmiş bir sınıfta geçersiz kılındığında, mevcut akışın konumlandırma desteği olup olmadığını gösteren bir değer alır.

**Returns:**
Akış konum değiştirme (seeking) destekliyorsa true; aksi takdirde false. Değer:

### canWrite {#canWrite--}
```
public boolean canWrite()
```

Türetilmiş bir sınıfta geçersiz kılındığında, mevcut akışın yazma desteği olup olmadığını gösteren bir değer alır.

**Returns:**
Akış yazma destekliyorsa true; aksi takdirde false. Değer:

### flush {#flush--}
```
public void flush()
```

Fonksiyon geçersiz kılındı.

### getBufferSize {#getBufferSize--}
```
public final int getBufferSize()
```

Temel tamponların boyutunu alır veya ayarlar. Değer: Tamponların boyutu.

**Returns:**
int değer

### getFreeOnDispose {#getFreeOnDispose--}
```
public final boolean getFreeOnDispose()
```

Dispose edildiğinde temel tamponların serbest bırakılıp bırakılmayacağını gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean değer

### getLength {#getLength--}
```
public long getLength()
```

Türetilmiş bir sınıfta geçersiz kılındığında, akışın bayt cinsinden uzunluğunu alır.

**Returns:**
Akışın bayt cinsinden uzunluğunu temsil eden uzun bir değer. Değer:

### getPosition {#getPosition--}
```
public long getPosition()
```

Türetilmiş bir sınıfta geçersiz kılındığında, geçerli akış içindeki konumu alır veya ayarlar.

**Returns:**
Akış içindeki mevcut konum. Değer:

### read {#read-byte:A-int-int-}
```
public int read(byte[] buffer, int offset, int count)
```

Türetilmiş bir sınıfta geçersiz kılındığında, geçerli akıştan bir bayt dizisi okur ve akıştaki konumu okunan bayt sayısı kadar ilerletir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon |  | Bir bayt dizisi. Bu yöntem döndüğünde, tampon belirtilen bayt dizisini değerleriyle birlikte içerir |
| ofset |  | Geçerli akıştan okunan verilerin depolanmaya başlanacağı sıfır tabanlı bayt ofseti. |
| sayım |  | Geçerli akıştan okunacak azami bayt sayısı. |

**Returns:**
The total number of bytes read into the buffer. This can be less than the number of bytes requested if that many bytes are not currently available, or zero (0) if the end of the stream has been reached.

### readByte {#readByte--}
```
public int readByte()
```

Akıştan bir bayt okur ve akıştaki konumu bir bayt ilerletir; akışın sonunda ise -1 döndürür.

**Returns:**
byte or -1 if at the end of the stream.

### seek {#seek-long-int-}
```
public long seek(long offset, int origin)
```

Türetilmiş bir sınıfta geçersiz kılındığında, geçerli akış içindeki konumu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ofset |  | A byte offset relative to the {@code origin} parameter. |
| origin |  | A value of type {@link SeekOrigin} indicating the reference point used to obtain the new position. |

**Returns:**
The new position within the current stream.

### seek {#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-}
Türetilmiş bir sınıfta geçersiz kılındığında, geçerli akış içindeki konumu ayarlar.

### setBufferSize {#setBufferSize-int-}
```
public final void setBufferSize(int value)
```

Temel tamponların boyutunu alır veya ayarlar. Değer: Tamponların boyutu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setFreeOnDispose {#setFreeOnDispose-boolean-}
```
public final void setFreeOnDispose(boolean value)
```

Dispose edildiğinde temel tamponların serbest bırakılıp bırakılmayacağını gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setLength {#setLength-long-}
```
public void setLength(long value)
```

Türetilmiş bir sınıfta geçersiz kılındığında, geçerli akışın uzunluğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | The desired length of the current stream in bytes. |

### setPosition {#setPosition-long-}
```
public void setPosition(long value)
```

Türetilmiş bir sınıfta geçersiz kılındığında, geçerli akış içindeki konumu alır veya ayarlar. Akış içindeki mevcut konum. Değer:

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  |  |

### toArray {#toArray--}
```
public final byte[] toArray()
```

Geçerli akışı bir bayt dizisine dönüştürür.

**Returns:**
An array of bytes

### write {#write-byte:A-int-int-}
```
public void write(byte[] buffer, int offset, int count)
```

Türetilmiş bir sınıfta geçersiz kılındığında, bir bayt dizisini geçerli akışa yazar ve bu akıştaki mevcut konumu yazılan bayt sayısı kadar ilerletir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tampon |  | An array of bytes. This method copies {@code count} bytes from {@code buffer} to the current stream. |
| ofset |  | The zero-based byte offset in {@code buffer} at which to begin copying bytes to the current stream. |
| sayım |  | The number of bytes to be written to the current stream. |

### writeByte {#writeByte-byte-}
```
public void writeByte(byte value)
```

Akıştaki mevcut konuma bir bayt yazar ve akıştaki konumu bir bayt ilerletir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | The byte to write to the stream. |

### writeTo {#writeTo-com.aspose.ms.System.IO.Stream-}
Belirtilen akışa yazar.
