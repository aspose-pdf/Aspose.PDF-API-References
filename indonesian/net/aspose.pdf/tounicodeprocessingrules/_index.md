---
title: "Kelas ToUnicodeProcessingRules"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.ToUnicodeProcessingRules. Kelas ini menjelaskan aturan yang dapat digunakan untuk menyelesaikan kesalahan Adobe Preflight 'Text cannot be mapped to Unicode'"
type: docs
weight: 11300
url: /id/net/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules class

Kelas ini menjelaskan aturan yang dapat digunakan untuk menyelesaikan kesalahan Adobe Preflight "Text cannot be mapped to Unicode".

```csharp
public class ToUnicodeProcessingRules
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | Menginisialisasi sebuah instance baru dari kelas `ToUnicodeProcessingRules`. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | Menginisialisasi instance baru dari kelas `ToUnicodeProcessingRules` dengan opsi yang ditentukan untuk menghapus spasi dari nama CMap. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | Menginisialisasi instance baru dari kelas `ToUnicodeProcessingRules` dengan opsi yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | Beberapa font tidak menyediakan informasi tentang unicode untuk beberapa simbol teks. Kekurangan informasi ini menyebabkan kesalahan "Text cannot be mapped to Unicode". Gunakan flag ini untuk memetakan simbol yang tidak terhubung ke unicode "space" (kode 32). |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | Beberapa font memiliki peta kode karakter ToUnicode dengan spasi di nama. Spasi tersebut dapat menyebabkan kesalahan pada pemetaan teks unicode. Flag ini menginstruksikan untuk menghapus spasi dari nama peta kode karakter ToUnicode. Nilai default false. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


