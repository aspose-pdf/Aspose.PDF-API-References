---
title: Class Metered
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Metered. توفر طرقًا لتعيين المفتاح المقاس
type: docs
weight: 6960
url: /ar/net/aspose.pdf/metered/
---
## Metered class

يوفر طرقًا لتعيين المفتاح المقاس.

```csharp
public class Metered
```

## Constructors

| Name | Description |
| --- | --- |
| [Metered](metered/)() | المُنشئ الافتراضي. |

## Methods

| Name | Description |
| --- | --- |
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | الحصول على اسم المنتج. |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | تعيين المفتاح العام والخاص المقاس. إذا قمت بشراء ترخيص مقاس، عند بدء التطبيق، يجب استدعاء هذه الواجهة البرمجية، عادةً، هذا يكفي. ومع ذلك، إذا فشلت دائمًا في تحميل بيانات الاستهلاك وتجاوزت 24 ساعة، سيتم تعيين الترخيص إلى حالة التقييم، لتجنب مثل هذه الحالة، يجب عليك التحقق بانتظام من حالة الترخيص، إذا كانت في حالة التقييم، استدعِ هذه الواجهة البرمجية مرة أخرى. |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | الحصول على رصيد الاستهلاك. |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | الحصول على حجم ملف الاستهلاك. |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | التحقق مما إذا كان المقاس مرخصًا. |

## Examples

في هذا المثال، سيتم محاولة تعيين المفتاح العام والخاص المقاس.

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

يوضح كيفية تفعيل ترخيص مقاس وتتبع الرصيد/الاستهلاك.

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

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)