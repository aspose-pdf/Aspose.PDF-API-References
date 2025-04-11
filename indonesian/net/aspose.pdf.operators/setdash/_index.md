---
title: Class SetDash
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Operators.SetDash. Kelas yang mewakili operator d untuk mengatur pola garis putus-putus
type: docs
weight: 7690
url: /id/net/aspose.pdf.operators/setdash/
---
## Kelas SetDash

Kelas yang mewakili operator d (mengatur pola garis putus-putus).

```csharp
public class SetDash : Operator
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SetDash](setdash/)(int[], int) | Membuat operator pola putus-putus yang diatur. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Indeks operator dalam daftar operator halaman. |
| [Pattern](../../aspose.pdf.operators/setdash/pattern/) { get; set; } | Pola putus-putus. Elemen array harus berupa angka yang menentukan panjang putus-putus dan celah yang bergantian. Dalam kasus array dengan satu elemen, panjang putus-putus dan celah adalah sama. |
| [Phase](../../aspose.pdf.operators/setdash/phase/) { get; set; } | Fase putus-putus. Sebelum mulai menggambar jalur, array putus-putus harus diputar, menjumlahkan panjang putus-putus dan celah. Ketika panjang yang terakumulasi sama dengan nilai yang ditentukan oleh fase putus-putus, penggambaran jalur harus dimulai, dan array putus-putus harus digunakan secara siklis dari titik itu seterusnya. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept/)(IOperatorSelector) | Menerima objek pengunjung untuk memproses operator. |
| override [ToString](../../aspose.pdf.operators/setdash/tostring/)() | Mendapatkan representasi string dari operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Membandingkan instance ini dengan objek yang diberikan. |

### Lihat Juga

* kelas [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)