---
title: Class Metered
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Metered. Предоставляет методы для установки метерного ключа
type: docs
weight: 6960
url: /ru/net/aspose.pdf/metered/
---
## Класс Metered

Предоставляет методы для установки метерного ключа.

```csharp
public class Metered
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Metered](metered/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | Получить имя продукта. |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | Устанавливает метерный публичный и приватный ключ. Если вы покупаете метерную лицензию, при запуске приложения этот API должен быть вызван, как правило, этого достаточно. Однако, если постоянно не удается загрузить данные о потреблении и превышает 24 часа, лицензия будет установлена в статус оценки, чтобы избежать такого случая, вы должны регулярно проверять статус лицензии, если это статус оценки, вызовите этот API снова. |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | Получает кредит потребления. |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | Получает размер файла потребления. |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | Проверяет, лицензирован ли метерный. |

## Примеры

В этом примере будет предпринята попытка установить метерный публичный и приватный ключ.

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

Показывает, как активировать метерную лицензию и отслеживать кредит/потребление.

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

### См. также

* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)