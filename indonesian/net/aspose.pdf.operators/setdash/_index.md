---
title: "Kelas SetDash"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Operators.SetDash. Kelas yang mewakili operator d untuk mengatur pola dash garis"
type: docs
weight: 7830
url: /id/net/aspose.pdf.operators/setdash/
---
## SetDash class

Kelas yang merepresentasikan operator d (mengatur pola dash garis).

```csharp
public class SetDash : Operator
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SetDash](setdash/)(int[], int) | Membuat operator pengaturan pola dash. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Indeks operator dalam daftar operator halaman. |
| [Pattern](../../aspose.pdf.operators/setdash/pattern/) { get; set; } | Pola dash. Elemen array harus berupa angka yang menentukan panjang dash dan celah yang bergantian. Jika array hanya memiliki satu elemen, panjang dash dan celah akan sama. |
| [Phase](../../aspose.pdf.operators/setdash/phase/) { get; set; } | Fase dash. Sebelum memulai menggambar jalur, array dash harus diputar, menjumlahkan panjang dash dan celah. Ketika panjang terakumulasi sama dengan nilai yang ditentukan oleh fase dash, penggambaran jalur akan dimulai, dan array dash akan digunakan secara siklik dari titik tersebut. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept/)(IOperatorSelector) | Menerima objek visitor untuk memproses operator. |
| override [ToString](../../aspose.pdf.operators/setdash/tostring/)() | Mendapatkan representasi string operator. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Membandingkan instance ini dengan objek yang diberikan. |

### Lihat Juga

* class [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


