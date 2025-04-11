---
title: Class Metered
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Metered. Fournit des méthodes pour définir la clé mesurée
type: docs
weight: 6960
url: /fr/net/aspose.pdf/metered/
---
## Classe Metered

Fournit des méthodes pour définir la clé mesurée.

```csharp
public class Metered
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Metered](metered/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | Obtenir le nom du produit. |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | Définit la clé publique et la clé privée mesurées. Si vous achetez une licence mesurée, lorsque vous démarrez l'application, cette API doit être appelée, normalement, cela suffit. Cependant, si le téléchargement des données de consommation échoue toujours et dépasse 24 heures, la licence sera définie sur le statut d'évaluation, pour éviter ce cas, vous devez vérifier régulièrement le statut de la licence, s'il est en statut d'évaluation, appelez à nouveau cette API. |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | Obtient le crédit de consommation. |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | Obtient la taille du fichier de consommation. |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | Vérifie si la licence mesurée est active. |

## Exemples

Dans cet exemple, une tentative sera faite pour définir la clé publique et la clé privée mesurées.

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

Montre comment activer une licence mesurée et suivre le crédit/la consommation.

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

### Voir aussi

* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)