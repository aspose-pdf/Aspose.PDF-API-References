---
title: Class Metered
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Metered klass. Tillhandahåller metoder för att ställa in metered nyckel
type: docs
weight: 6960
url: /sv/net/aspose.pdf/metered/
---
## Metered klass

Tillhandahåller metoder för att ställa in metered nyckel.

```csharp
public class Metered
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Metered](metered/)() | Standardkonstruktören. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | Hämta produktnamnet. |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | Ställer in metered offentlig och privat nyckel. Om du köper metered licens, när du startar applikationen, bör denna API anropas, normalt är detta tillräckligt. Men om det alltid misslyckas med att ladda upp konsumtionsdata och överskrider 24 timmar, kommer licensen att sättas till utvärderingsstatus, för att undvika sådana fall bör du regelbundet kontrollera licensens status, om den är i utvärderingsstatus, anropa denna API igen. |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | Hämtar konsumtionskredit. |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | Hämtar konsumtionsfilstorlek. |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | Kontrollerar om metered är licensierad. |

## Exempel

I detta exempel kommer ett försök att göras att ställa in metered offentlig och privat nyckel.

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

Visar hur man aktiverar en Metered licens och spårar kredit/konsumtion.

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

### Se Även

* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)