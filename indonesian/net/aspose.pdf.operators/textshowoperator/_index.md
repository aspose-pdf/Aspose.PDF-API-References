---
title: Class TextShowOperator
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Operators.TextShowOperator. Kelas dasar abstrak untuk semua operator yang digunakan untuk menampilkan teks Tj TJ dll
type: docs
weight: 7920
url: /id/net/aspose.pdf.operators/textshowoperator/
---
## Kelas TextShowOperator

Kelas dasar abstrak untuk semua operator yang digunakan untuk menampilkan teks (Tj, TJ, dll).

```csharp
public class TextShowOperator : TextOperator
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextShowOperator](textshowoperator/#constructor)() | Menginisialisasi TextShowOperator. |
| [TextShowOperator](textshowoperator/#constructor_1)(TextProperties) | Menginisialisasi TextShowOperator yang memungkinkan untuk melewatkan TextProperties. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Indeks operator dalam daftar operator halaman. |
| virtual [Text](../../aspose.pdf.operators/textshowoperator/text/) { get; set; } | Mendapatkan teks yang dikeluarkan operator di halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | Menerima objek pengunjung untuk memproses operator. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Mengembalikan teks dari operator dan parameternya. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Membandingkan instance ini dengan objek yang diberikan. |

### Lihat Juga

* kelas [TextOperator](../textoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)