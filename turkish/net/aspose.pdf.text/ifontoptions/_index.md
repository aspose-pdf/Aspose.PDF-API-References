---
title: Interface IFontOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.IFontOptions arayüzü. Font davranışını ayarlamak için yararlı özellikler
type: docs
weight: 10610
url: /tr/net/aspose.pdf.text/ifontoptions/
---
## IFontOptions arayüzü

Font davranışını ayarlamak için yararlı özellikler

```csharp
public interface IFontOptions
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | Bazen istenen fontu belgeye gömmek mümkün olmayabilir. Bunun birçok nedeni vardır, örneğin lisans kısıtlamaları veya istenen fontun hedef bilgisayarda bulunmaması. Bu durum ortaya çıktığında, tespit etmek kolay değildir çünkü istenen font, Font.IsEmbedded = true; özelliği ile gömülür. Elbette bu özelliği ayarlandıktan hemen sonra okumak mümkündür ama bu pratik bir yaklaşım değildir. NotifyAboutFontEmbeddingError bayrağı, font gömme girişiminin başarısız olduğu durumlar için istisna mekanizmasını zorunlu kılar. Bu bayrak ayarlandığında, [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/) türünde bir istisna fırlatılacaktır. Varsayılan olarak false. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)