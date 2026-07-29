---
title: "OptimizedMemoryStream"
linktitle: "OptimizedMemoryStream"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mendefinisikan MemoryStream yang dapat berisi kapasitas standar lebih banyak"
type: docs
weight: 3220
url: /id/java/com.aspose.pdf/optimizedmemorystream/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.IO.Stream com.aspose.pdf.OptimizedMemoryStream, com.aspose.ms.System.IO.Stream, com.aspose.pdf.OptimizedMemoryStream

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class OptimizedMemoryStream extends com.aspose.ms.System.IO.Stream
```

Mendefinisikan MemoryStream yang dapat berisi kapasitas standar lebih banyak

## Fields

| Field | Deskripsi |
| --- | --- |
| [DefaultBufferSize](#DefaultBufferSize) | Nilai ukuran buffer default dalam byte. |

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OptimizedMemoryStream](#OptimizedMemoryStream--) | Menginisialisasi sebuah instance baru dari kelas {@link OptimizedMemoryStream}. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-byte:A-) | Menginisialisasi sebuah instance baru dari kelas {@link OptimizedMemoryStream} berdasarkan array byte yang ditentukan. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-) | Menginisialisasi sebuah instance baru dari kelas {@link OptimizedMemoryStream}. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-byte:A-) | Menginisialisasi sebuah instance baru dari kelas {@link OptimizedMemoryStream} berdasarkan array byte yang ditentukan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [canRead](#canRead--) | Saat dioverride dalam kelas turunan, mendapatkan nilai yang menunjukkan apakah aliran saat ini mendukung pembacaan. |
| [canSeek](#canSeek--) | Saat dioverride dalam kelas turunan, mendapatkan nilai yang menunjukkan apakah aliran saat ini mendukung pencarian. |
| [canWrite](#canWrite--) | Saat dioverride dalam kelas turunan, mendapatkan nilai yang menunjukkan apakah aliran saat ini mendukung penulisan. |
| [flush](#flush--) | Fungsi tersebut dioverride. |
| [getBufferSize](#getBufferSize--) | Mendapatkan atau mengatur ukuran buffer yang mendasari. Nilai: Ukuran buffer. |
| [getFreeOnDispose](#getFreeOnDispose--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah akan membebaskan buffer dasar saat dibuang. |
| [getLength](#getLength--) | Saat dioverride dalam kelas turunan, mendapatkan panjang dalam byte dari aliran. |
| [getPosition](#getPosition--) | Saat dioverride dalam kelas turunan, mendapatkan atau mengatur posisi dalam aliran saat ini. |
| [read](#read-byte:A-int-int-) | Saat dioverride dalam kelas turunan, membaca urutan byte dari aliran saat ini dan memajukan posisi dalam aliran sebesar jumlah byte yang dibaca. |
| [readByte](#readByte--) | Membaca satu byte dari aliran dan memajukan posisi dalam aliran satu byte, atau mengembalikan -1 jika berada di akhir aliran. |
| [seek](#seek-long-int-) | Saat dioverride dalam kelas turunan, mengatur posisi dalam aliran saat ini. |
| [seek](#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-) | Saat dioverride dalam kelas turunan, mengatur posisi dalam aliran saat ini. |
| [setBufferSize](#setBufferSize-int-) | Mendapatkan atau mengatur ukuran buffer yang mendasari. Nilai: Ukuran buffer. |
| [setFreeOnDispose](#setFreeOnDispose-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah akan membebaskan buffer dasar saat dibuang. |
| [setLength](#setLength-long-) | Saat dioverride dalam kelas turunan, mengatur panjang aliran saat ini. |
| [setPosition](#setPosition-long-) | Saat dioverride dalam kelas turunan, mendapatkan atau mengatur posisi dalam aliran saat ini. Posisi saat ini dalam aliran. Nilai: |
| [toArray](#toArray--) | Mengonversi aliran saat ini menjadi array byte. |
| [write](#write-byte:A-int-int-) | Saat dioverride dalam kelas turunan, menulis urutan byte ke aliran saat ini dan memajukan posisi saat ini dalam aliran ini sebesar jumlah byte yang ditulis. |
| [writeByte](#writeByte-byte-) | Menulis satu byte ke posisi saat ini dalam aliran dan memajukan posisi dalam aliran satu byte. |
| [writeTo](#writeTo-com.aspose.ms.System.IO.Stream-) | Menulis ke aliran yang ditentukan. |

### DefaultBufferSize {#DefaultBufferSize}
```
public static final int DefaultBufferSize
```

Nilai ukuran buffer default dalam byte.

### OptimizedMemoryStream {#OptimizedMemoryStream--}
```
public OptimizedMemoryStream()
```

Menginisialisasi sebuah instance baru dari kelas {@link OptimizedMemoryStream}.

### OptimizedMemoryStream {#OptimizedMemoryStream-byte:A-}
```
public OptimizedMemoryStream(byte[] buffer)
```

Menginisialisasi sebuah instance baru dari kelas {@link OptimizedMemoryStream} berdasarkan array byte yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer |  | Array byte tak bertanda yang digunakan untuk membuat aliran saat ini. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-}
```
public OptimizedMemoryStream(int bufferSize)
```

Menginisialisasi sebuah instance baru dari kelas {@link OptimizedMemoryStream}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bufferSize |  | Ukuran buffer dasar. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-byte:A-}
```
public OptimizedMemoryStream(int bufferSize, byte[] buffer)
```

Menginisialisasi sebuah instance baru dari kelas {@link OptimizedMemoryStream} berdasarkan array byte yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bufferSize |  | Ukuran buffer dasar. |
| buffer |  | Array byte tak bertanda yang digunakan untuk membuat aliran saat ini. |

### canRead {#canRead--}
```
public boolean canRead()
```

Saat dioverride dalam kelas turunan, mendapatkan nilai yang menunjukkan apakah aliran saat ini mendukung pembacaan.

**Returns:**
true jika aliran mendukung pembacaan; jika tidak, false. Nilai:

### canSeek {#canSeek--}
```
public boolean canSeek()
```

Saat dioverride dalam kelas turunan, mendapatkan nilai yang menunjukkan apakah aliran saat ini mendukung pencarian.

**Returns:**
true jika aliran mendukung pencarian; jika tidak, false. Nilai:

### canWrite {#canWrite--}
```
public boolean canWrite()
```

Saat dioverride dalam kelas turunan, mendapatkan nilai yang menunjukkan apakah aliran saat ini mendukung penulisan.

**Returns:**
true jika aliran mendukung penulisan; jika tidak, false. Nilai:

### flush {#flush--}
```
public void flush()
```

Fungsi tersebut dioverride.

### getBufferSize {#getBufferSize--}
```
public final int getBufferSize()
```

Mendapatkan atau mengatur ukuran buffer yang mendasari. Nilai: Ukuran buffer.

**Returns:**
nilai int

### getFreeOnDispose {#getFreeOnDispose--}
```
public final boolean getFreeOnDispose()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah akan membebaskan buffer dasar saat dibuang.

**Returns:**
nilai boolean

### getLength {#getLength--}
```
public long getLength()
```

Saat dioverride dalam kelas turunan, mendapatkan panjang dalam byte dari aliran.

**Returns:**
Nilai long yang mewakili panjang aliran dalam byte. Nilai:

### getPosition {#getPosition--}
```
public long getPosition()
```

Saat dioverride dalam kelas turunan, mendapatkan atau mengatur posisi dalam aliran saat ini.

**Returns:**
Posisi saat ini dalam aliran. Nilai:

### read {#read-byte:A-int-int-}
```
public int read(byte[] buffer, int offset, int count)
```

Saat dioverride dalam kelas turunan, membaca urutan byte dari aliran saat ini dan memajukan posisi dalam aliran sebesar jumlah byte yang dibaca.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer |  | Array byte. Ketika metode ini mengembalikan, buffer berisi array byte yang ditentukan dengan nilai-nilai |
| offset |  | Offset byte berbasis nol di mana mulai menyimpan data yang dibaca dari aliran saat ini. |
| jumlah |  | Jumlah maksimum byte yang akan dibaca dari aliran saat ini. |

**Returns:**
The total number of bytes read into the buffer. This can be less than the number of bytes requested if that many bytes are not currently available, or zero (0) if the end of the stream has been reached.

### readByte {#readByte--}
```
public int readByte()
```

Membaca satu byte dari aliran dan memajukan posisi dalam aliran satu byte, atau mengembalikan -1 jika berada di akhir aliran.

**Returns:**
byte atau -1 jika berada di akhir aliran.

### seek {#seek-long-int-}
```
public long seek(long offset, int origin)
```

Saat dioverride dalam kelas turunan, mengatur posisi dalam aliran saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| offset |  | Offset byte relatif terhadap parameter {@code origin}. |
| origin |  | Nilai bertipe {@link SeekOrigin} yang menunjukkan titik referensi yang digunakan untuk memperoleh posisi baru. |

**Returns:**
Posisi baru dalam aliran saat ini.

### seek {#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-}
Saat dioverride dalam kelas turunan, mengatur posisi dalam aliran saat ini.

### setBufferSize {#setBufferSize-int-}
```
public final void setBufferSize(int value)
```

Mendapatkan atau mengatur ukuran buffer yang mendasari. Nilai: Ukuran buffer.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setFreeOnDispose {#setFreeOnDispose-boolean-}
```
public final void setFreeOnDispose(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah akan membebaskan buffer dasar saat dibuang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setLength {#setLength-long-}
```
public void setLength(long value)
```

Saat dioverride dalam kelas turunan, mengatur panjang aliran saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Panjang yang diinginkan dari aliran saat ini dalam byte. |

### setPosition {#setPosition-long-}
```
public void setPosition(long value)
```

Saat dioverride dalam kelas turunan, mendapatkan atau mengatur posisi dalam aliran saat ini. Posisi saat ini dalam aliran. Nilai:

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  |  |

### toArray {#toArray--}
```
public final byte[] toArray()
```

Mengonversi aliran saat ini menjadi array byte.

**Returns:**
Array byte

### write {#write-byte:A-int-int-}
```
public void write(byte[] buffer, int offset, int count)
```

Saat dioverride dalam kelas turunan, menulis urutan byte ke aliran saat ini dan memajukan posisi saat ini dalam aliran ini sebesar jumlah byte yang ditulis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer |  | Array byte. Metode ini menyalin {@code count} byte dari {@code buffer} ke aliran saat ini. |
| offset |  | Offset byte berbasis nol dalam {@code buffer} tempat memulai penyalinan byte ke aliran saat ini. |
| jumlah |  | Jumlah byte yang akan ditulis ke aliran saat ini. |

### writeByte {#writeByte-byte-}
```
public void writeByte(byte value)
```

Menulis satu byte ke posisi saat ini dalam aliran dan memajukan posisi dalam aliran satu byte.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Byte yang akan ditulis ke aliran. |

### writeTo {#writeTo-com.aspose.ms.System.IO.Stream-}
Menulis ke aliran yang ditentukan.
