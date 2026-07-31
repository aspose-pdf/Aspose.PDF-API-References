---
title: "Kelas SetColor"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Operators.SetColor. Mewakili kelas untuk operator sc yang mengatur warna untuk operasi non-stroking."
type: docs
weight: 7770
url: /id/net/aspose.pdf.operators/setcolor/
---
## SetColor class

Merepresentasikan kelas untuk operator sc (mengatur warna untuk operasi non-stroking).

```csharp
public class SetColor : BasicSetColorOperator
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SetColor](setcolor/#constructor)() | Menginisialisasi operator. |
| [SetColor](setcolor/#constructor_1)(double) | Atur warna untuk operator stroking pada ruang warna DeviceGray, CalGray, dan Indexed. |
| [SetColor](setcolor/#constructor_4)(double[]) | Konstruktor yang memungkinkan untuk menentukan komponen warna. |
| [SetColor](setcolor/#constructor_2)(double, double, double) | Atur warna untuk operator stroking pada ruang warna DeviceRGB, CalRGB, dan Lab. |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | Mengatur warna untuk operator non-stroking pada ruang warna CMYK |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | Mendapatkan atau mengatur komponen biru. |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | Mendapatkan atau mengatur komponen cyan. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Mendapatkan array komponen warna. |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | Mendapatkan atau mengatur komponen hijau. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Mendapatkan komponen hitam dari warna abu-abu. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Indeks operator dalam daftar operator halaman. |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | Mendapatkan atau mengatur komponen hitam. |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | Mendapatkan atau mengatur komponen magenta. |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | Mendapatkan atau mengatur komponen merah. |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | Mendapatkan atau mengatur komponen kuning. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | Menerima objek visitor untuk memproses operator. |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | Mengembalikan warna yang ditentukan oleh operator. |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | Mengembalikan representasi string warna. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Membandingkan instance ini dengan objek yang diberikan. |

### Lihat Juga

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


