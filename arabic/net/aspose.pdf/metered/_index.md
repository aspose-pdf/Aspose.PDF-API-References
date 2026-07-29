---
title: "فئة Metered"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Metered. توفر طرقًا لتعيين المفتاح المتعقب."
type: docs
weight: 7100
url: /ar/net/aspose.pdf/metered/
---
## Metered class

يوفر طرقًا لتعيين المفتاح المقيس.

```csharp
public class Metered
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Metered](metered/)() | البناء الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | احصل على اسم المنتج. |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | يضبط المفتاح العام والخاص للترخيص المتعقب. إذا قمت بشراء ترخيص متعقب، عند بدء التطبيق يجب استدعاء هذه الـ API، عادةً يكون ذلك كافيًا. ومع ذلك، إذا فشل دائمًا تحميل بيانات الاستهلاك وتجاوزت 24 ساعة، سيتم تعيين الترخيص إلى حالة التقييم؛ لتجنب هذه الحالة، يجب عليك فحص حالة الترخيص بانتظام، إذا كانت في حالة التقييم، استدعِ هذه الـ API مرة أخرى. |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | يحصل على رصيد الاستهلاك. |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | يحصل على حجم ملف الاستهلاك. |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | تحقق مما إذا كان الترخيص المتعقب مفعلًا. |

## أمثلة

في هذا المثال، سيتم محاولة ضبط المفتاح العام والخاص المتقن.

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

يوضح كيفية تفعيل ترخيص مقاس وتتبع الائتمان/الاستهلاك.

```csharp
[C#]

// ضبط المفاتيح العامة والخاصة المتقاسة
var metered = new Aspose.Pdf.Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");
//احصل على رصيد الاستهلاك الحالي والكمية
var wasCredit = Metered.GetConsumptionCredit();
var wasQuantity = Metered.GetConsumptionQuantity();
//التعامل باستخدام Aspose.Pdf
var doc = new Document();
doc.Pages.Add();
doc.Save(dataDir + "example.pdf");
//انتظار بسيط للتأكد من إكمال العملية
System.Threading.Thread.Sleep(10000);
//احصل على رصيد الاستهلاك الحالي والكمية
var nowCredit = Metered.GetConsumptionCredit();
var nowQuantity = Metered.GetConsumptionQuantity();
//عرض المعلومات
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

### انظر أيضًا

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


