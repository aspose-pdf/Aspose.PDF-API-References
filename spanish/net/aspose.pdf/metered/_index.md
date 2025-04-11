---
title: Class Metered
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Metered. Proporciona métodos para establecer la clave medida
type: docs
weight: 6960
url: /es/net/aspose.pdf/metered/
---
## Clase Metered

Proporciona métodos para establecer la clave medida.

```csharp
public class Metered
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Metered](metered/)() | El constructor predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | Obtiene el nombre del producto. |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | Establece la clave pública y privada medida. Si compras una licencia medida, al iniciar la aplicación, esta API debe ser llamada, normalmente, esto es suficiente. Sin embargo, si siempre falla al cargar los datos de consumo y excede las 24 horas, la licencia se establecerá en estado de evaluación, para evitar tal caso, debes verificar regularmente el estado de la licencia, si está en estado de evaluación, llama a esta API nuevamente. |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | Obtiene el crédito de consumo. |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | Obtiene el tamaño del archivo de consumo. |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | Verifica si la licencia medida está activa. |

## Ejemplos

En este ejemplo, se intentará establecer la clave pública y privada medida.

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

Muestra cómo activar una licencia medida y rastrear crédito/consumo.

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

### Ver También

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)