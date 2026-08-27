---
title: "Класс Metered"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Metered. Предоставляет методы для установки ключа учёта."
type: docs
weight: 7100
url: /ru/net/aspose.pdf/metered/
---
## Metered class

Предоставляет методы для установки измеряемого ключа.

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
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | Получить название продукта. |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | Устанавливает публичный и приватный ключ учёта. Если вы приобретаете лицензию с учётом, при запуске приложения этот API должен быть вызван, обычно этого достаточно. Однако если постоянно не удаётся загрузить данные о потреблении и проходит более 24 часов, лицензия будет переключена в режим оценки; чтобы избежать этого, следует регулярно проверять статус лицензии, и если он находится в режиме оценки, вызвать этот API снова. |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | Получает кредит потребления. |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | Получает размер файла потребления. |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | Проверяет, лицензирован ли учёт. |

## Примеры

В этом примере будет предпринята попытка установить измеряемый публичный и приватный ключ.

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

Показывает, как активировать измеряемую лицензию и отслеживать кредит/потребление.

```csharp
[C#]

// Установить измеряемые публичный и приватный ключи
var metered = new Aspose.Pdf.Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");
//Получить текущий кредит потребления и количество
var wasCredit = Metered.GetConsumptionCredit();
var wasQuantity = Metered.GetConsumptionQuantity();
//Работать с использованием Aspose.Pdf
var doc = new Document();
doc.Pages.Add();
doc.Save(dataDir + "example.pdf");
//Небольшая пауза, чтобы убедиться, что транзакция завершена
System.Threading.Thread.Sleep(10000);
//Получить текущий кредит потребления и количество
var nowCredit = Metered.GetConsumptionCredit();
var nowQuantity = Metered.GetConsumptionQuantity();
//Показать информацию
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

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


