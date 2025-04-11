---
title: Class ToUnicodeProcessingRules
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.ToUnicodeProcessingRules. Kelas ini menjelaskan aturan yang dapat digunakan untuk menyelesaikan kesalahan Adobe Preflight "Teks tidak dapat dipetakan ke Unicode"
type: docs
weight: 11110
url: /id/net/aspose.pdf/tounicodeprocessingrules/
---
## Kelas ToUnicodeProcessingRules

Kelas ini menjelaskan aturan yang dapat digunakan untuk menyelesaikan kesalahan Adobe Preflight "Teks tidak dapat dipetakan ke Unicode".

```csharp
public class ToUnicodeProcessingRules
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | Menginisialisasi instance baru dari kelas `ToUnicodeProcessingRules`. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | Menginisialisasi instance baru dari kelas `ToUnicodeProcessingRules` dengan opsi yang ditentukan untuk menghapus spasi dari nama CMap. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | Menginisialisasi instance baru dari kelas `ToUnicodeProcessingRules` dengan opsi yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | Beberapa font tidak menyediakan informasi tentang unicode untuk beberapa simbol teks. Kekurangan informasi ini menyebabkan kesalahan "Teks tidak dapat dipetakan ke Unicode". Gunakan bendera ini untuk memetakan simbol yang tidak terhubung pada unicode "spasi" (kode 32). |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | Beberapa font memiliki peta kode karakter ToUnicode dengan spasi dalam nama. Spasi ini dapat menyebabkan kesalahan dalam pemetaan teks unicode. Bendera ini memerintahkan untuk menghapus spasi dari nama peta kode karakter ToUnicode. Secara default false. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)