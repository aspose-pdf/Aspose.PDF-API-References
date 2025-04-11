---
title: Class OptimizedMemoryStream
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.OptimizedMemoryStream. Mendefinisikan MemoryStream yang dapat menampung kapasitas lebih standar
type: docs
weight: 7990
url: /id/net/aspose.pdf/optimizedmemorystream/
---
## Kelas OptimizedMemoryStream

Mendefinisikan MemoryStream yang dapat menampung kapasitas lebih standar

```csharp
public class OptimizedMemoryStream : Stream
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor)() | Menginisialisasi instance baru dari kelas `OptimizedMemoryStream`. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_1)(byte[]) | Menginisialisasi instance baru dari kelas `OptimizedMemoryStream` berdasarkan array byte yang ditentukan. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_2)(int) | Menginisialisasi instance baru dari kelas `OptimizedMemoryStream`. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_3)(int, byte[]) | Menginisialisasi instance baru dari kelas `OptimizedMemoryStream` berdasarkan array byte yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize/) { get; set; } | Mendapatkan atau menetapkan ukuran buffer yang mendasari. |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread/) { get; } | Ketika dioverride dalam kelas turunan, mendapatkan nilai yang menunjukkan apakah stream saat ini mendukung pembacaan. |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek/) { get; } | Ketika dioverride dalam kelas turunan, mendapatkan nilai yang menunjukkan apakah stream saat ini mendukung pencarian. |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite/) { get; } | Ketika dioverride dalam kelas turunan, mendapatkan nilai yang menunjukkan apakah stream saat ini mendukung penulisan. |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose/) { get; set; } | Mendapatkan atau menetapkan nilai yang menunjukkan apakah akan membebaskan buffer yang mendasari saat dibuang. |
| override [Length](../../aspose.pdf/optimizedmemorystream/length/) { get; } | Ketika dioverride dalam kelas turunan, mendapatkan panjang dalam byte dari stream. |
| override [Position](../../aspose.pdf/optimizedmemorystream/position/) { get; set; } | Ketika dioverride dalam kelas turunan, mendapatkan atau menetapkan posisi dalam stream saat ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush/)() | Fungsi yang dioverride. |
| override [Read](../../aspose.pdf/optimizedmemorystream/read/#read)(byte[], int, int) | Ketika dioverride dalam kelas turunan, membaca urutan byte dari stream saat ini dan memajukan posisi dalam stream dengan jumlah byte yang dibaca. |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte/)() | Membaca satu byte dari stream dan memajukan posisi dalam stream dengan satu byte, atau mengembalikan -1 jika di akhir stream. |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek/)(long, SeekOrigin) | Ketika dioverride dalam kelas turunan, menetapkan posisi dalam stream saat ini. |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength/)(long) | Ketika dioverride dalam kelas turunan, menetapkan panjang stream saat ini. |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray/)() | Mengonversi stream saat ini menjadi array byte. |
| override [Write](../../aspose.pdf/optimizedmemorystream/write/#write)(byte[], int, int) | Ketika dioverride dalam kelas turunan, menulis urutan byte ke stream saat ini dan memajukan posisi saat ini dalam stream ini dengan jumlah byte yang ditulis. |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte/)(byte) | Menulis satu byte ke posisi saat ini dalam stream dan memajukan posisi dalam stream dengan satu byte. |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto/)(Stream) | Menulis ke stream yang ditentukan. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize/) | Nilai ukuran buffer default dalam byte. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)