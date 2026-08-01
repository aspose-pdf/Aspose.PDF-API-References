---
title: "Metered クラス"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Metered クラス。メータキーを設定するメソッドを提供します。"
type: docs
weight: 7100
url: /ja/net/aspose.pdf/metered/
---
## Metered class

メーターキーを設定するメソッドを提供します。

```csharp
public class Metered
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Metered](metered/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | 製品名を取得します。 |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | メーターパブリックキーとプライベートキーを設定します。メータライセンスを購入した場合、アプリケーション起動時にこの API を呼び出す必要があります。通常はこれだけで十分です。ただし、消費データのアップロードが常に失敗し、24 時間を超えると、ライセンスは評価ステータスに設定されます。そのような事態を防ぐために、ライセンスステータスを定期的に確認し、評価ステータスであれば再度この API を呼び出してください。 |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | 消費クレジットを取得します。 |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | 消費ファイルサイズを取得します。 |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | メータがライセンスされているか確認します。 |

## 例

この例では、メーターパブリックキーとプライベートキーの設定を試みます。

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

メータライセンスを有効化し、クレジット/消費を追跡する方法を示します。

```csharp
[C#]

// メーターパブリックキーとプライベートキーを設定する
var metered = new Aspose.Pdf.Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");
//現在の消費クレジットと数量を取得する
var wasCredit = Metered.GetConsumptionCredit();
var wasQuantity = Metered.GetConsumptionQuantity();
//Aspose.Pdf を使用して操作する
var doc = new Document();
doc.Pages.Add();
doc.Save(dataDir + "example.pdf");
//トランザクションが完了したことを確認するために少し待ちます
System.Threading.Thread.Sleep(10000);
//現在の消費クレジットと数量を取得する
var nowCredit = Metered.GetConsumptionCredit();
var nowQuantity = Metered.GetConsumptionQuantity();
//情報を表示する
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

### 関連項目

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


