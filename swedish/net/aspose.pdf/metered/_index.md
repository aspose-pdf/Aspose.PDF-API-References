---
title: "Klassen Metered"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Metered-klass. Tillhandahåller metoder för att ställa in metered-nyckel"
type: docs
weight: 7100
url: /sv/net/aspose.pdf/metered/
---
## Metered class

Tillhandahåller metoder för att ställa in mätad nyckel.

```csharp
public class Metered
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Metered](metered/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | Hämta produktnamnet. |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | Ställer in metered offentlig och privat nyckel. Om du köper en metered-licens, bör detta API anropas när applikationen startas; normalt är detta tillräckligt. Men om uppladdning av förbrukningsdata alltid misslyckas och överstiger 24 timmar, kommer licensen att sättas till utvärderingsstatus. För att undvika detta bör du regelbundet kontrollera licensstatusen, och om den är i utvärderingsstatus, anropa detta API igen. |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | Hämtar förbrukningskredit. |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | Hämtar förbrukningsfilens storlek. |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | Kontrollera om metered är licensierad. |

## Exempel

I det här exemplet kommer ett försök att ställa in metered offentlig och privat nyckel att göras.

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

Visar hur man aktiverar en Metered-licens och spårar kredit/förbrukning.

```csharp
[C#]

// Ställ in metered offentliga och privata nycklar
var metered = new Aspose.Pdf.Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");
//Hämta aktuell förbrukningskredit och kvantitet
var wasCredit = Metered.GetConsumptionCredit();
var wasQuantity = Metered.GetConsumptionQuantity();
//Arbeta med Aspose.Pdf
var doc = new Document();
doc.Pages.Add();
doc.Save(dataDir + "example.pdf");
//Liten väntan för att vara säker på att transaktionen är slutförd
System.Threading.Thread.Sleep(10000);
//Hämta aktuell förbrukningskredit och kvantitet
var nowCredit = Metered.GetConsumptionCredit();
var nowQuantity = Metered.GetConsumptionQuantity();
//Visa information
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

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


