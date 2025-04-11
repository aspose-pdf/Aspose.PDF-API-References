---
title: Class Metered
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Metered. Fornisce metodi per impostare la chiave metered
type: docs
weight: 6960
url: /it/net/aspose.pdf/metered/
---
## Classe Metered

Fornisce metodi per impostare la chiave metered.

```csharp
public class Metered
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Metered](metered/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | Ottiene il nome del prodotto. |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | Imposta la chiave pubblica e privata metered. Se acquisti una licenza metered, quando avvii l'applicazione, questa API dovrebbe essere chiamata, normalmente, questo è sufficiente. Tuttavia, se fallisce sempre nel caricare i dati di consumo e supera le 24 ore, la licenza sarà impostata su stato di valutazione, per evitare tale caso, dovresti controllare regolarmente lo stato della licenza, se è in stato di valutazione, chiama di nuovo questa API. |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | Ottiene il credito di consumo. |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | Ottiene la dimensione del file di consumo. |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | Controlla se il metered è licenziato. |

## Esempi

In questo esempio, si tenterà di impostare la chiave pubblica e privata metered.

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

Mostra come attivare una licenza Metered e tracciare credito/consumo.

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

### Vedi Anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)