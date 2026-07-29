---
title: "LoadOptions.PageSizeAdjustmentModes"
linktitle: "LoadOptions.PageSizeAdjustmentModes"
second_title: "Aspose.PDF for Java API Referansı"
description: "DİKKAT! Özellik uygulanmış ancak örnek belge için OSHARED katmanında ortaya çıkan engelleyici sorun nedeniyle henüz genel API'ye eklenmedi. Sayfa boyutunun kullanım modunu temsil eder."
type: docs
weight: 2810
url: /tr/java/com.aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes

```
public static final class LoadOptions.PageSizeAdjustmentModes extends com.aspose.ms.System.Enum
```

ATTENTION! Özellik uygulanmış ancak örnek belge için OSHARED katmanında ortaya çıkan engelleyici sorun nedeniyle henüz genel API'ye eklenmemiştir. Dönüşüm sırasında sayfa boyutunun kullanım modunu temsil eder. HTML, EPUB vb. gibi formatlar genellikle akış tasarımına sahiptir, bu yüzden gerekli sayfa boyutuna sığdırmaya izin verir. Ancak bazen içerik, yatay konumları veya boyutu belirttiği için içeriği gerekli sayfa boyutuna yerleştirmeye izin vermez. Böyle bir durumda ne yapılması gerektiğini tanımlayabiliriz (ör. içeriğin boyutu, sonuç PDF belgesinin başlangıç sayfa boyutuna uymadığında).

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [EnlargeRequiredViewportWidthAndDoConversionAgain](#EnlargeRequiredViewportWidthAndDoConversionAgain) | Bu mod şu davranışı tanımlar: dönüşüm sonucu alındıktan ve bazı içeriğin kesildiği tespit edildikten sonra, portview genişliği içeriğe sığacak şekilde artırılır ve dönüşüm tekrarlanır. Bu mod, böyle bir durumda sonuçta daha az sayfa elde edilmesini sağlar ancak tekrar tekrar render edilmesini (ve dolayısıyla daha fazla işlem süresi) gerektirir. |
| [NoAjustmentAllwaysUsePredefinedSize](#NoAjustmentAllwaysUsePredefinedSize) | Bu modda sonuç sayfaları, LoadOptions içinde tanımlanan gerekli sayfa boyutuna sahip olacaktır, dönüşüm sonrası içerik sayfa sınırlarının dışına çıkıp çıkmadığına bakılmaksızın. |

### EnlargeRequiredViewportWidthAndDoConversionAgain {#EnlargeRequiredViewportWidthAndDoConversionAgain}
```
public static final int EnlargeRequiredViewportWidthAndDoConversionAgain
```

Bu mod şu davranışı tanımlar: dönüşüm sonucu alındıktan ve bazı içeriğin kesildiği tespit edildikten sonra, portview genişliği içeriğe sığacak şekilde artırılır ve dönüşüm tekrarlanır. Bu mod, böyle bir durumda sonuçta daha az sayfa elde edilmesini sağlar ancak tekrar tekrar render edilmesini (ve dolayısıyla daha fazla işlem süresi) gerektirir.

### NoAjustmentAllwaysUsePredefinedSize {#NoAjustmentAllwaysUsePredefinedSize}
```
public static final int NoAjustmentAllwaysUsePredefinedSize
```

Bu modda sonuç sayfaları, LoadOptions içinde tanımlanan gerekli sayfa boyutuna sahip olacaktır, dönüşüm sonrası içerik sayfa sınırlarının dışına çıkıp çıkmadığına bakılmaksızın.
