---
title: Document.EmbedStandardFonts
second_title: Aspose.PDF for .NET API Reference
description: Belge özelliği. Belgenin, IsEmbedded bayrağı true olarak ayarlanmış tüm standart Type1 yazı tiplerini gömmesi gerektiğini belirten özellik. Tüm PDF yazı tipleri, IsEmbedded bayrağını true olarak ayarlayarak belgeye gömülebilir, ancak PDF standart Type1 yazı tipleri bu kuralın bir istisnasıdır. Standart Type1 yazı tipi gömme işlemi çok zaman alır, bu nedenle bu yazı tiplerini gömmek için yalnızca belirtilen yazı tipi için IsEmbedded bayrağını true olarak ayarlamakla kalmayıp, aynı zamanda belgenin düzeyinde ek bir bayrak - EmbedStandardFonts = true; ayarlamak da gereklidir. Bu özellik, tüm yazı tipleri için yalnızca bir kez ayarlanabilir. Varsayılan olarak false.
type: docs
weight: 150
url: /tr/net/aspose.pdf/document/embedstandardfonts/
---
## Document.EmbedStandardFonts özelliği

Belgenin, IsEmbedded bayrağı true olarak ayarlanmış tüm standart Type1 yazı tiplerini gömmesi gerektiğini belirten özellik. Tüm PDF yazı tipleri, IsEmbedded bayrağını true olarak ayarlayarak belgeye gömülebilir, ancak PDF standart Type1 yazı tipleri bu kuralın bir istisnasıdır. Standart Type1 yazı tipi gömme işlemi çok zaman alır, bu nedenle bu yazı tiplerini gömmek için yalnızca belirtilen yazı tipi için IsEmbedded bayrağını true olarak ayarlamakla kalmayıp, aynı zamanda belgenin düzeyinde ek bir bayrak - EmbedStandardFonts = true; ayarlamak da gereklidir. Bu özellik, tüm yazı tipleri için yalnızca bir kez ayarlanabilir. Varsayılan olarak false.

```csharp
public bool EmbedStandardFonts { get; set; }
```

### Ayrıca Bakınız

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)