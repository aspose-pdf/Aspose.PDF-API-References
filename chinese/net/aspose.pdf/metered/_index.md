---
title: "类 Metered"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Metered 类。提供设置计量密钥的方法"
type: docs
weight: 7100
url: /zh/net/aspose.pdf/metered/
---
## Metered class

提供设置计量密钥的方法。

```csharp
public class Metered
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Metered](metered/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | 获取产品名称。 |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | 设置计量公钥和私钥。如果您购买了计量许可证，在启动应用程序时应调用此 API，通常这就足够了。然而，如果始终无法上传消耗数据且超过 24 小时，许可证将被设置为评估状态。为避免这种情况，您应定期检查许可证状态，如果是评估状态，请再次调用此 API。 |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | 获取消耗额度。 |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | 获取消耗文件大小。 |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | 检查计量是否已授权。 |

## 示例

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

展示如何激活计量许可证并跟踪额度/消耗。

```csharp
[C#]

// 设置计量公钥和私钥
var metered = new Aspose.Pdf.Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");
//获取当前消耗额度和数量
var wasCredit = Metered.GetConsumptionCredit();
var wasQuantity = Metered.GetConsumptionQuantity();
//使用 Aspose.Pdf 进行操作
var doc = new Document();
doc.Pages.Add();
doc.Save(dataDir + "example.pdf");
//稍作等待以确保事务已完成
System.Threading.Thread.Sleep(10000);
//获取当前消耗额度和数量
var nowCredit = Metered.GetConsumptionCredit();
var nowQuantity = Metered.GetConsumptionQuantity();
//显示信息
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

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


