---
title: Class Metered
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Metered. Fornece métodos para definir a chave metered
type: docs
weight: 6960
url: /pt/net/aspose.pdf/metered/
---
## Classe Metered

Fornece métodos para definir a chave metered.

```csharp
public class Metered
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Metered](metered/)() | O construtor padrão. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | Obtém o nome do produto. |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | Define a chave pública e privada metered. Se você adquirir uma licença metered, ao iniciar o aplicativo, esta API deve ser chamada, normalmente, isso é suficiente. No entanto, se sempre falhar ao enviar dados de consumo e exceder 24 horas, a licença será definida como status de avaliação, para evitar tal caso, você deve verificar regularmente o status da licença, se estiver no status de avaliação, chame esta API novamente. |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | Obtém crédito de consumo. |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | Obtém o tamanho do arquivo de consumo. |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | Verifica se o metered está licenciado. |

## Exemplos

Neste exemplo, será feita uma tentativa de definir a chave pública e privada metered.

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

Mostra como ativar uma licença Metered e rastrear crédito/consumo.

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

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)