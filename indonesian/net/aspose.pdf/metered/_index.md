---
title: "Kelas Metered"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Metered kelas. Menyediakan metode untuk mengatur kunci metered"
type: docs
weight: 7100
url: /id/net/aspose.pdf/metered/
---
## Metered class

Menyediakan metode untuk mengatur kunci terukur.

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
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | Dapatkan Nama Produk. |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | Menetapkan kunci publik dan privat metered. Jika Anda membeli lisensi metered, saat memulai aplikasi, API ini harus dipanggil, biasanya, ini sudah cukup. Namun, jika selalu gagal mengunggah data konsumsi dan melebihi 24 jam, lisensi akan diatur ke status evaluasi; untuk menghindari hal tersebut, Anda harus secara teratur memeriksa status lisensi, jika berada dalam status evaluasi, panggil API ini lagi. |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | Mendapatkan kredit konsumsi. |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | Mendapatkan ukuran file konsumsi. |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | Periksa apakah metered berlisensi. |

## Contoh

Dalam contoh ini, akan dicoba mengatur kunci publik dan pribadi berlisensi metered.

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

Menampilkan cara mengaktifkan lisensi Metered dan melacak kredit/konsumsi.

```csharp
[C#]

// Atur kunci publik dan pribadi berlisensi metered
var metered = new Aspose.Pdf.Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");
//Dapatkan Kredit Konsumsi dan Kuantitas saat ini
var wasCredit = Metered.GetConsumptionCredit();
var wasQuantity = Metered.GetConsumptionQuantity();
//Beroperasi menggunakan Aspose.Pdf
var doc = new Document();
doc.Pages.Add();
doc.Save(dataDir + "example.pdf");
//Tunggu sebentar untuk memastikan transaksi selesai
System.Threading.Thread.Sleep(10000);
//Dapatkan Kredit Konsumsi dan Kuantitas saat ini
var nowCredit = Metered.GetConsumptionCredit();
var nowQuantity = Metered.GetConsumptionQuantity();
//Tampilkan Info
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


