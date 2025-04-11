---
title: Class Metered
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Metered 클래스. 미터 키를 설정하는 방법을 제공합니다.
type: docs
weight: 6960
url: /ko/net/aspose.pdf/metered/
---
## Metered 클래스

미터 키를 설정하는 방법을 제공합니다.

```csharp
public class Metered
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Metered](metered/)() | 기본 생성자입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | 제품 이름을 가져옵니다. |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | 미터 공개 및 비공개 키를 설정합니다. 미터 라이센스를 구매하면 애플리케이션 시작 시 이 API를 호출해야 하며, 일반적으로 이것으로 충분합니다. 그러나 소비 데이터를 업로드하는 데 항상 실패하고 24시간을 초과하면 라이센스가 평가 상태로 설정됩니다. 이러한 경우를 피하기 위해 라이센스 상태를 정기적으로 확인해야 하며, 평가 상태인 경우 이 API를 다시 호출해야 합니다. |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | 소비 크레딧을 가져옵니다. |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | 소비 파일 크기를 가져옵니다. |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | 미터가 라이센스가 있는지 확인합니다. |

## 예제

이 예제에서는 미터 공개 및 비공개 키를 설정하려고 시도합니다.

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

미터 라이센스를 활성화하고 크레딧/소비를 추적하는 방법을 보여줍니다.

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

### 참조

* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)