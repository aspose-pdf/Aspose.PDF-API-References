---
title: "Kelas OptimizedMemoryStream"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.OptimizedMemoryStream. Mendefinisikan MemoryStream yang dapat menampung kapasitas standar lebih besar"
type: docs
weight: 8130
url: /id/net/aspose.pdf/optimizedmemorystream/
---
## OptimizedMemoryStream class

Mendefinisikan MemoryStream yang dapat berisi kapasitas standar lebih besar.

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
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize/) { get; set; } | Mendapatkan atau mengatur ukuran buffer yang mendasari. |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread/) { get; } | Saat dioverride dalam kelas turunan, mendapatkan nilai yang menunjukkan apakah aliran saat ini mendukung pembacaan. |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek/) { get; } | Saat dioverride dalam kelas turunan, mendapatkan nilai yang menunjukkan apakah aliran saat ini mendukung pencarian. |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite/) { get; } | Saat dioverride dalam kelas turunan, mendapatkan nilai yang menunjukkan apakah aliran saat ini mendukung penulisan. |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah akan membebaskan buffer yang mendasari saat dibuang. |
| override [Length](../../aspose.pdf/optimizedmemorystream/length/) { get; } | Saat dioverride dalam kelas turunan, mendapatkan panjang aliran dalam byte. |
| override [Position](../../aspose.pdf/optimizedmemorystream/position/) { get; set; } | Saat dioverride dalam kelas turunan, mendapatkan atau mengatur posisi dalam aliran saat ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush/)() | Fungsi yang dioverride. |
| override [Read](../../aspose.pdf/optimizedmemorystream/read/#read)(byte[], int, int) | Saat dioverride dalam kelas turunan, membaca urutan byte dari aliran saat ini dan memajukan posisi dalam aliran sebesar jumlah byte yang dibaca. |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte/)() | Membaca satu byte dari aliran dan memajukan posisi dalam aliran satu byte, atau mengembalikan -1 jika berada di akhir aliran. |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek/)(long, SeekOrigin) | Saat dioverride dalam kelas turunan, mengatur posisi dalam aliran saat ini. |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength/)(long) | Saat dioverride dalam kelas turunan, mengatur panjang aliran saat ini. |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray/)() | Mengonversi aliran saat ini menjadi array byte. |
| override [Write](../../aspose.pdf/optimizedmemorystream/write/#write)(byte[], int, int) | Ketika dioverride dalam kelas turunan, menulis urutan byte ke aliran saat ini dan memajukan posisi saat ini dalam aliran ini sebanyak jumlah byte yang ditulis. |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte/)(byte) | Menulis satu byte ke posisi saat ini dalam aliran dan memajukan posisi dalam aliran sebesar satu byte. |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto/)(Stream) | Menulis ke aliran yang ditentukan. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize/) | Nilai ukuran buffer default dalam byte. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


