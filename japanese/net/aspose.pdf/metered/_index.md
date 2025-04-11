---
title: Class Metered
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Metered クラス。メーターキーを設定するためのメソッドを提供します
type: docs
weight: 6960
url: /ja/net/aspose.pdf/metered/
---
## Metered クラス

メーターキーを設定するためのメソッドを提供します。

```csharp
public class Metered
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Metered](metered/)() | デフォルトのコンストラクタ。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | 製品名を取得します。 |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | メーターの公開キーとプライベートキーを設定します。メーターライセンスを購入した場合、アプリケーションを開始するときにこのAPIを呼び出す必要があります。通常、これで十分です。ただし、消費データのアップロードが常に失敗し、24時間を超える場合、ライセンスは評価ステータスに設定されます。このような事態を避けるために、定期的にライセンスのステータスを確認し、評価ステータスである場合は再度このAPIを呼び出してください。 |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | 消費クレジットを取得します。 |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | 消費ファイルサイズを取得します。 |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | メーターがライセンスされているかどうかを確認します。 |

## 例

この例では、メーターの公開キーとプライベートキーを設定しようとします。

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

メーターライセンスをアクティブにし、クレジット/消費を追跡する方法を示します。

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

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)