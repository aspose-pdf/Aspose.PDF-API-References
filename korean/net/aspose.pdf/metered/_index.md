---
title: "클래스 Metered"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Metered 클래스. 메터링 키를 설정하는 메서드를 제공합니다"
type: docs
weight: 7100
url: /ko/net/aspose.pdf/metered/
---
## Metered class

계량 키를 설정하는 메서드를 제공합니다.

```csharp
public class Metered
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Metered](metered/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | 제품 이름을 가져옵니다. |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | 메터링 공개키와 비공개키를 설정합니다. 메터링 라이선스를 구매한 경우, 애플리케이션을 시작할 때 이 API를 호출해야 하며, 일반적으로 이것만으로 충분합니다. 그러나 사용량 데이터를 업로드하는 데 계속 실패하고 24시간을 초과하면 라이선스가 평가 상태로 전환됩니다. 이러한 상황을 방지하려면 라이선스 상태를 정기적으로 확인하고, 평가 상태인 경우 다시 이 API를 호출해야 합니다. |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | 소비 크레딧을 가져옵니다. |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | 소비 파일 크기를 가져옵니다. |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | 메터링이 라이선스가 있는지 확인합니다. |

## 예제

이 예제에서는 메터링 공개키와 비공개키를 설정하려고 시도합니다.

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

Metered 라이선스를 활성화하고 크레딧/소비를 추적하는 방법을 보여줍니다.

```csharp
[C#]

// 메터링 공개키와 비공개키를 설정합니다
var metered = new Aspose.Pdf.Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");
//현재 소비 크레딧 및 양을 가져옵니다
var wasCredit = Metered.GetConsumptionCredit();
var wasQuantity = Metered.GetConsumptionQuantity();
//Aspose.Pdf를 사용하여 작업합니다
var doc = new Document();
doc.Pages.Add();
doc.Save(dataDir + "example.pdf");
//트랜잭션이 완료되었는지 확인하기 위해 잠시 대기합니다
System.Threading.Thread.Sleep(10000);
//현재 소비 크레딧 및 양을 가져옵니다
var nowCredit = Metered.GetConsumptionCredit();
var nowQuantity = Metered.GetConsumptionQuantity();
//정보 표시
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

### 또 보기

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


