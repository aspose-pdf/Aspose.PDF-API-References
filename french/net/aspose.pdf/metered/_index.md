---
title: "Classe Metered"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Metered classe. Fournit des méthodes pour définir la clé mesurée"
type: docs
weight: 7100
url: /fr/net/aspose.pdf/metered/
---
## Metered class

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
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | Définit la clé publique et privée mesurée. Si vous achetez une licence mesurée, au démarrage de l'application, cette API doit être appelée, généralement, cela suffit. Cependant, si le téléchargement des données de consommation échoue constamment et dépasse 24 heures, la licence sera mise en statut d'évaluation ; pour éviter ce cas, vous devez vérifier régulièrement le statut de la licence, et si elle est en statut d'évaluation, appeler à nouveau cette API. |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | Obtient le crédit de consommation. |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | Obtient la taille du fichier de consommation. |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | Vérifiez si Metered est licencié. |

## Exemples

Dans cet exemple, une tentative sera faite pour définir la clé publique et privée mesurée.

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

// Définir les clés publiques et privées mesurées
var metered = new Aspose.Pdf.Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");
//Obtenir le crédit de consommation actuel et la quantité
var wasCredit = Metered.GetConsumptionCredit();
var wasQuantity = Metered.GetConsumptionQuantity();
//Utiliser Aspose.Pdf
var doc = new Document();
doc.Pages.Add();
doc.Save(dataDir + "example.pdf");
//Petite attente pour s'assurer que la transaction est terminée
System.Threading.Thread.Sleep(10000);
//Obtenir le crédit de consommation actuel et la quantité
var nowCredit = Metered.GetConsumptionCredit();
var nowQuantity = Metered.GetConsumptionQuantity();
//Afficher les informations
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

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


