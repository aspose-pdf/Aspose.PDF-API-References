---
title: Enum Permissions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Permissions enum. Bu enum, bir pdf için kullanıcı izinlerini temsil eder.
type: docs
weight: 8480
url: /tr/net/aspose.pdf/permissions/
---
## İzinler enumerasyonu

Bu enum, bir pdf için kullanıcının izinlerini temsil eder.

```csharp
[Flags]
public enum Permissions
```

### Değerler

| İsim | Değer | Açıklama |
| --- | --- | --- |
| PrintDocument | `4` | (Revizyon 2'nin güvenlik işleyicileri) Belgeyi yazdır. (Revizyon 3 veya daha büyük güvenlik işleyicileri) Belgeyi yazdır (Yazdırma Kalitesi de ayarlanmışsa, en yüksek kalite seviyesinde olmayabilir). |
| ModifyContent | `8` | ModifyTextAnnotations, FillForm ve 11 tarafından kontrol edilmeyen işlemlerle belgenin içeriğini değiştirin. |
| ExtractContent | `10` | (Revizyon 2'nin güvenlik işleyicileri) Belgeden metin ve grafik kopyalayın veya başka şekilde çıkarın, engelli kullanıcıların erişimi için veya diğer amaçlar için metin ve grafik çıkarma dahil. (Revizyon 3 veya daha büyük güvenlik işleyicileri) ExtractContentWithDisabilities tarafından kontrol edilmeyen işlemlerle belgeden metin ve grafik kopyalayın veya başka şekilde çıkarın. |
| ModifyTextAnnotations | `20` | Metin notları ekleyin veya değiştirin, etkileşimli form alanlarını doldurun ve, ModifyContent de ayarlanmışsa, etkileşimli form alanlarını (imza alanları dahil) oluşturun veya değiştirin. |
| FillForm | `100` | (Revizyon 3 veya daha büyük güvenlik işleyicileri) Mevcut etkileşimli form alanlarını (imza alanları dahil) doldurun, ModifyTextAnnotations açık olsa bile. |
| ExtractContentWithDisabilities | `200` | (Revizyon 3 veya daha büyük güvenlik işleyicileri) Metin ve grafik çıkarın (engelli kullanıcıların erişimi için veya diğer amaçlar için). |
| AssembleDocument | `400` | (Revizyon 3 veya daha büyük güvenlik işleyicileri) Belgeyi birleştirin (sayfaları ekleyin, döndürün veya silin ve yer imleri veya küçük resim görüntüleri oluşturun), ModifyContent açık olsa bile. |
| PrintingQuality | `800` | (Revizyon 3 veya daha büyük güvenlik işleyicileri) PDF içeriğinin sadık bir dijital kopyasının oluşturulabileceği bir temsile belgeyi yazdırın. Bu bit açık olduğunda (ve bit 3 ayarlandığında), yazdırma, görünümün düşük seviyeli bir temsil ile sınırlıdır, muhtemelen kalitesi düşmüş olabilir. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)