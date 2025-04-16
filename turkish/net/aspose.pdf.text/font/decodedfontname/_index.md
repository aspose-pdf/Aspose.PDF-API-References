---
title: Font.DecodedFontName
second_title: Aspose.PDF for .NET API Reference
description: Font özelliği. Bazen PDF fontları belirli bir font adına sahip olabilir. Bu ad, PDF font özelliği "BaseFont" değeridir ve bazen bu özellik onaltılık biçimde temsil edilebilir. Bu adı doğrudan okursanız, okunamaz bir biçimde temsil edilebilir. Okunabilir bir biçim elde etmek için, bu font için belirli kurallara göre font adını çözmek gereklidir. Bu özellik, çözülmüş font adını döndürür, bu nedenle okunamaz bir [`FontName`](../fontname/) ile karşılaştığınızda bunu kullanın. Eğer [`FontName`](../fontname/) özelliği okunabilir bir biçime sahipse, bu özellik [`FontName`](../fontname/) ile aynı olacaktır, bu nedenle font adını okunabilir bir biçimde almak istediğiniz her durumda bu özelliği kullanabilirsiniz.
type: docs
weight: 20
url: /tr/net/aspose.pdf.text/font/decodedfontname/
---
## Font.DecodedFontName özelliği

Bazen PDF fontları (genellikle Çince/Japonca/Korece fontlar) belirli bir font adına sahip olabilir. Bu ad, PDF font özelliği "BaseFont" değeridir ve bazen bu özellik onaltılık biçimde temsil edilebilir. Bu adı doğrudan okursanız, okunamaz bir biçimde temsil edilebilir. Okunabilir bir biçim elde etmek için, bu font için belirli kurallara göre font adını çözmek gereklidir. Bu özellik, çözülmüş font adını döndürür, bu nedenle okunamaz bir [`FontName`](../fontname/) ile karşılaştığınızda bunu kullanın. Eğer [`FontName`](../fontname/) özelliği okunabilir bir biçime sahipse, bu özellik [`FontName`](../fontname/) ile aynı olacaktır, bu nedenle font adını okunabilir bir biçimde almak istediğiniz her durumda bu özelliği kullanabilirsiniz.

```csharp
public string DecodedFontName { get; }
```

### Ayrıca Bakınız

* sınıf [Font](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)