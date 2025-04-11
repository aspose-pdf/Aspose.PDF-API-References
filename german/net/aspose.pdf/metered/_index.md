---
title: Class Metered
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Metered-Klasse. Bietet Methoden zum Setzen des Metered-Schlüssels
type: docs
weight: 6960
url: /de/net/aspose.pdf/metered/
---
## Metered-Klasse

Bietet Methoden zum Setzen des Metered-Schlüssels.

```csharp
public class Metered
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Metered](metered/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | Holt den Produktnamen. |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | Setzt den öffentlichen und privaten Metered-Schlüssel. Wenn Sie eine Metered-Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden, normalerweise ist dies ausreichend. Wenn jedoch immer das Hochladen von Verbrauchsdaten fehlschlägt und 24 Stunden überschreitet, wird die Lizenz auf den Evaluierungsstatus gesetzt. Um dies zu vermeiden, sollten Sie regelmäßig den Lizenzstatus überprüfen. Wenn es sich um den Evaluierungsstatus handelt, rufen Sie diese API erneut auf. |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | Holt das Verbrauchsguthaben. |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | Holt die Dateigröße des Verbrauchs. |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | Überprüft, ob Metered lizenziert ist. |

## Beispiele

In diesem Beispiel wird versucht, den öffentlichen und privaten Metered-Schlüssel zu setzen.

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

Zeigt, wie man eine Metered-Lizenz aktiviert und Kredit/Verbrauch verfolgt.

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

### Siehe auch

* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)