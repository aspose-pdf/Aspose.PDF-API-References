---
title: Class SetColorStroke
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Operators.SetColorStroke. Kelas yang mewakili operator SC untuk mengatur warna untuk operator warna garis.
type: docs
weight: 7680
url: /id/net/aspose.pdf.operators/setcolorstroke/
---
## Kelas SetColorStroke

Kelas yang mewakili operator SC untuk mengatur warna untuk operator warna garis.

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | Menginisialisasi operator. |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | Mengatur warna untuk operator garis untuk ruang warna DeviceGray, CalGray, dan Indexed. |
| [SetColorStroke](setcolorstroke/#constructor_4)(double[]) | Konstruktor yang memungkinkan untuk mengatur komponen warna. |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | Mengatur warna untuk operator garis untuk ruang warna DeviceRGB, CalRGB, dan Lab. |
| [SetColorStroke](setcolorstroke/#constructor_3)(double, double, double, double) | Mengatur warna untuk operator garis untuk ruang warna CMYK. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolorstroke/b/) { get; set; } | Mendapatkan atau mengatur komponen biru. |
| [C](../../aspose.pdf.operators/setcolorstroke/c/) { get; set; } | Mendapatkan atau mengatur komponen cyan. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Mendapatkan array komponen warna. |
| [G](../../aspose.pdf.operators/setcolorstroke/g/) { get; set; } | Mendapatkan atau mengatur komponen hijau. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Mendapatkan komponen hitam dari warna abu-abu. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Indeks operator dalam daftar operator halaman. |
| [K](../../aspose.pdf.operators/setcolorstroke/k/) { get; set; } | Mendapatkan atau mengatur komponen hitam. |
| [M](../../aspose.pdf.operators/setcolorstroke/m/) { get; set; } | Mendapatkan atau mengatur komponen magenta. |
| [R](../../aspose.pdf.operators/setcolorstroke/r/) { get; set; } | Mendapatkan atau mengatur komponen merah. |
| [Y](../../aspose.pdf.operators/setcolorstroke/y/) { get; set; } | Mendapatkan atau mengatur komponen kuning. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | Menerima objek pengunjung untuk memproses operator. |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | Mengembalikan warna yang ditentukan oleh operator. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Mengembalikan teks dari operator dan parameternya. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Membandingkan instance ini dengan objek yang diberikan. |

### Lihat Juga

* kelas [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)