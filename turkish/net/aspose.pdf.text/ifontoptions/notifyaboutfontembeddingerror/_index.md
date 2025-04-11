---
title: IFontOptions.NotifyAboutFontEmbeddingError
second_title: Aspose.PDF for .NET API Reference
description: IFontOptions özelliği. Bazen istenen yazı tipini belgeye gömmek mümkün değildir. Bunun birçok nedeni vardır, örneğin lisans kısıtlamaları veya istenen yazı tipinin hedef bilgisayarda bulunmaması. Bu durum ortaya çıktığında, istenen yazı tipi, Font.IsEmbedded = true; özelliği bayrağı aracılığıyla gömüldüğü için bunu tespit etmek kolay değildir. Elbette bu özelliği ayarlandıktan hemen sonra okumak mümkündür, ancak bu pratik bir yaklaşım değildir. NotifyAboutFontEmbeddingError bayrağı, yazı tipini gömme girişiminin başarısız olduğu durumlar için istisna mekanizmasını zorlar. Bu bayrak ayarlandığında, [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) türünde bir istisna fırlatılacaktır. Varsayılan olarak false.
type: docs
weight: 10
url: /tr/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## IFontOptions.NotifyAboutFontEmbeddingError özelliği

Bazen istenen yazı tipini belgeye gömmek mümkün değildir. Bunun birçok nedeni vardır, örneğin lisans kısıtlamaları veya istenen yazı tipinin hedef bilgisayarda bulunmaması. Bu durum ortaya çıktığında, istenen yazı tipi, Font.IsEmbedded = true; özelliği bayrağı aracılığıyla gömüldüğü için bunu tespit etmek kolay değildir. Elbette bu özelliği ayarlandıktan hemen sonra okumak mümkündür, ancak bu pratik bir yaklaşım değildir. NotifyAboutFontEmbeddingError bayrağı, yazı tipini gömme girişiminin başarısız olduğu durumlar için istisna mekanizmasını zorlar. Bu bayrak ayarlandığında, [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) türünde bir istisna fırlatılacaktır. Varsayılan olarak false.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### Ayrıca Bakınız

* arayüz [IFontOptions](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)