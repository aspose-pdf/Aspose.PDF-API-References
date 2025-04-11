---
title: Class Metered
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Metered. Menyediakan metode untuk mengatur kunci metered
type: docs
weight: 6960
url: /id/net/aspose.pdf/metered/
---
## Kelas Metered

Menyediakan metode untuk mengatur kunci metered.

```csharp
public class Metered
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Metered](metered/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | Mendapatkan Nama Produk. |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | Mengatur kunci publik dan privat metered. Jika Anda membeli lisensi metered, saat memulai aplikasi, API ini harus dipanggil, biasanya, ini sudah cukup. Namun, jika selalu gagal mengunggah data konsumsi dan melebihi 24 jam, lisensi akan diatur ke status evaluasi, untuk menghindari kasus tersebut, Anda harus secara teratur memeriksa status lisensi, jika statusnya evaluasi, panggil API ini lagi. |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | Mendapatkan kredit konsumsi. |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | Mendapatkan ukuran file konsumsi. |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | Memeriksa apakah metered memiliki lisensi. |

## Contoh

Dalam contoh ini, akan dilakukan upaya untuk mengatur kunci publik dan privat metered.

```csharp
[C#]

var metered = new Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");
```

```csharp
[Visual Basic]

Dim metered As Metered = New Metered
metered.SetMeteredKey("PublicKey", "PrivateKey")
```

Menunjukkan cara mengaktifkan lisensi Metered dan melacak kredit/konsumsi.

```csharp
[C#]

// Set metered public and private keys
var metered = new Aspose.Pdf.Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");
//Get current Consumption Credit and Quantity
var wasCredit = Metered.GetConsumptionCredit();
var wasQuantity = Metered.GetConsumptionQuantity();
//Operate using Aspose.Pdf
var doc = new Document();
doc.Pages.Add();
doc.Save(dataDir + "example.pdf");
//Little wait to be sure the transaction completed
System.Threading.Thread.Sleep(10000);
//Get current Consumption Credit and Quantity
var nowCredit = Metered.GetConsumptionCredit();
var nowQuantity = Metered.GetConsumptionQuantity();
//Show Info
Console.WriteLine("Credit: was={0} now={1} difference={2}", wasCredit, nowCredit, nowCredit - wasCredit);
Console.WriteLine("Quantity: was={0} now={1} difference={2}", wasQuantity, nowQuantity, nowQuantity - wasQuantity);
```

```csharp
[Visual Basic]

' Set metered public And private keys
Dim metered = New Aspose.Pdf.Metered()
metered.SetMeteredKey("PublicKey", "PrivateKey")
'Get current Consumption Credit And Quantity
Dim wasCredit = Metered.GetConsumptionCredit()
Dim wasQuantity = Metered.GetConsumptionQuantity()
'Operate using Aspose.Pdf
Dim doc = New Document()
doc.Pages.Add()
doc.Save(dataDir + "example.pdf")
'Little wait to be sure the transaction completed
System.Threading.Thread.Sleep(10000)
'Get current Consumption Credit And Quantity
Dim nowCredit = Metered.GetConsumptionCredit()
Dim nowQuantity = Metered.GetConsumptionQuantity()
'Show Info
Console.WriteLine("Credit: was={0} now={1} difference={2}", wasCredit, nowCredit, nowCredit - wasCredit)
Console.WriteLine("Quantity: was={0} now={1} difference={2}", wasQuantity, nowQuantity, nowQuantity - wasQuantity)
```

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)