---
title: RenderingOptions.AnalyzeFonts
second_title: Aspose.PDF for .NET API Reference
description: RenderingOptions özelliği. Metindeki tüm karakterlerin görüntülenebilmesini sağlamak için gerekli olduğunda fontları değiştirir. Font değiştirme algoritması şu adımları izler 1. Kullanıcı açıkça DefaultFontName özelliğini ayarlarsa, belirtilen fontun istenen karakterleri görüntüleyip görüntüleyemeyeceğini kontrol edin. 2. Kullanıcı tanımlı bir font ayarlanmamışsa, !FontRepository.Sources aracılığıyla eklenen fontlar arasında arama yapın. 3. Metni analiz ederek alfabesini veya yazı sistemini tanımlayın ve buna göre font isimleri önerin. Bu fontları sistemden bulmaya ve kullanmaya çalışın. 4. Yedek olarak, gerekli karakterleri görüntüleyebilen herhangi bir font için sistemi arayın.
type: docs
weight: 20
url: /tr/net/aspose.pdf/renderingoptions/analyzefonts/
---
## RenderingOptions.AnalyzeFonts özelliği

Metindeki tüm karakterlerin görüntülenebilmesini sağlamak için gerekli olduğunda fontları değiştirir. Font değiştirme algoritması şu adımları izler: 1. Kullanıcı açıkça DefaultFontName özelliğini ayarlarsa, belirtilen fontun istenen karakterleri görüntüleyip görüntüleyemeyeceğini kontrol edin. 2. Kullanıcı tanımlı bir font ayarlanmamışsa, !:FontRepository.Sources aracılığıyla eklenen fontlar arasında arama yapın. 3. Metni analiz ederek alfabesini veya yazı sistemini tanımlayın ve buna göre font isimleri önerin. Bu fontları sistemden bulmaya ve kullanmaya çalışın. 4. Yedek olarak, gerekli karakterleri görüntüleyebilen herhangi bir font için sistemi arayın.

```csharp
public bool AnalyzeFonts { get; set; }
```

### Ayrıca Bakınız

* class [RenderingOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)