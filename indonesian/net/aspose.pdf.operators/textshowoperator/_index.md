---
title: "Kelas TextShowOperator"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Operators.TextShowOperator. Kelas dasar abstrak untuk semua operator yang digunakan untuk menampilkan teks Tj TJ, dll"
type: docs
weight: 8060
url: /id/net/aspose.pdf.operators/textshowoperator/
---
## TextShowOperator class

Kelas dasar abstrak untuk semua operator yang digunakan untuk menghasilkan teks (Tj, TJ, dll).

```csharp
public class TextShowOperator : TextOperator
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TextShowOperator](textshowoperator/#constructor)() | Menginisialisasi TextShowOperator. |
| [TextShowOperator](textshowoperator/#constructor_1)(TextProperties) | Menginisialisasi TextShowOperator yang memungkinkan melewatkan TextProperties. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Indeks operator dalam daftar operator halaman. |
| virtual [Text](../../aspose.pdf.operators/textshowoperator/text/) { get; set; } | Mendapatkan teks yang operator keluarkan pada halaman. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | Menerima objek visitor untuk memproses operator. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Mengembalikan teks operator dan parameternya. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Membandingkan instance ini dengan objek yang diberikan. |

### Lihat Juga

* class [TextOperator](../textoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


