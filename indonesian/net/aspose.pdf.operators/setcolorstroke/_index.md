---
title: "Kelas SetColorStroke"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Operators.SetColorStroke class. Kelas yang mewakili operator SC untuk mengatur warna pada operator warna stroking."
type: docs
weight: 7820
url: /id/net/aspose.pdf.operators/setcolorstroke/
---
## SetColorStroke class

Kelas yang merepresentasikan operator SC (mengatur warna untuk operasi stroking).

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | Menginisialisasi operator. |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | Atur warna untuk operator stroking pada ruang warna DeviceGray, CalGray, dan Indexed. |
| [SetColorStroke](setcolorstroke/#constructor_4)(double[]) | Konstruktor yang memungkinkan mengatur komponen warna. |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | Atur warna untuk operator stroking pada ruang warna DeviceRGB, CalRGB, dan Lab. |
| [SetColorStroke](setcolorstroke/#constructor_3)(double, double, double, double) | Atur warna untuk operator stroking pada ruang warna CMYK. |

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
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | Menerima objek visitor untuk memproses operator. |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | Mengembalikan warna yang ditentukan oleh operator. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Mengembalikan teks operator dan parameternya. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Membandingkan instance ini dengan objek yang diberikan. |

### Lihat Juga

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


