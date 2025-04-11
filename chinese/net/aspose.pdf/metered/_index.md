---
title: Class Metered
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Metered class. 提供设置计量密钥的方法
type: docs
weight: 6960
url: /zh/net/aspose.pdf/metered/
---
## Metered class

提供设置计量密钥的方法。

```csharp
public class Metered
```

## Constructors

| Name | Description |
| --- | --- |
| [Metered](metered/)() | 默认构造函数。 |

## Methods

| Name | Description |
| --- | --- |
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | 获取产品名称。 |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | 设置计量公钥和私钥。如果您购买了计量许可证，当启动应用程序时，应调用此API，通常这就足够了。然而，如果始终无法上传消费数据并超过24小时，许可证将被设置为评估状态，为避免这种情况，您应该定期检查许可证状态，如果它是评估状态，请再次调用此API。 |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | 获取消费信用。 |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | 获取消费文件大小。 |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | 检查计量是否已获得许可。 |

## Examples

在此示例中，将尝试设置计量公钥和私钥。

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

展示如何激活计量许可证并跟踪信用/消费。

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