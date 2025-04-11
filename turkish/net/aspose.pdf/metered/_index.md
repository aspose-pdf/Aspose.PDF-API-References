---
title: Class Metered
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Metered sınıfı. Metered anahtarını ayarlamak için yöntemler sağlar
type: docs
weight: 6960
url: /tr/net/aspose.pdf/metered/
---
## Metered Sınıfı

Metered anahtarını ayarlamak için yöntemler sağlar.

```csharp
public class Metered
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [Metered](metered/)() | Varsayılan yapıcı. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [GetProductName](../../aspose.pdf/metered/getproductname/)() | Ürün Adını alır. |
| [SetMeteredKey](../../aspose.pdf/metered/setmeteredkey/)(string, string) | Metered genel ve özel anahtarını ayarlar. Metered lisansı satın alırsanız, uygulama başladığında bu API çağrılmalıdır, genellikle bu yeterlidir. Ancak, tüketim verilerini yüklemede sürekli başarısız olursanız ve 24 saati aşarsanız, lisans değerlendirme durumuna ayarlanacaktır. Böyle bir durumu önlemek için, lisans durumunu düzenli olarak kontrol etmelisiniz; eğer değerlendirme durumundaysa, bu API'yi tekrar çağırmalısınız. |
| static [GetConsumptionCredit](../../aspose.pdf/metered/getconsumptioncredit/)() | Tüketim kredisi alır. |
| static [GetConsumptionQuantity](../../aspose.pdf/metered/getconsumptionquantity/)() | Tüketim dosya boyutunu alır. |
| static [IsMeteredLicensed](../../aspose.pdf/metered/ismeteredlicensed/)() | Metered'in lisanslı olup olmadığını kontrol eder. |

## Örnekler

Bu örnekte, meter public ve private anahtarını ayarlama girişiminde bulunulacaktır.

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

Metered lisansını nasıl etkinleştireceğinizi ve kredi/tüketimi nasıl takip edeceğinizi gösterir.

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

### Ayrıca Bakınız

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)