---
title: CustomFontSubstitutionBase.TrySubstitute
second_title: Aspose.PDF for .NET API Reference
description: CustomFontSubstitutionBase metodu. Orijinal fontu başka bir font ile değiştirir
type: docs
weight: 20
url: /tr/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase.TrySubstitute metodu

Orijinal fontu başka bir font ile değiştirir.

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | Orijinal font spesifikasyonu. |
| substitutionFont | Font& | Değiştirme fontu. |

### Dönüş Değeri

Değiştirmenin başarılı olması durumunda true döner.

## Açıklamalar

CustomFontSubstitutionBase sınıfı, özel font değiştirme mantığını uygulamak için miras alınmalıdır. TrySubstitute metodu düzgün bir şekilde geçersiz kılınmalıdır: Değiştirmenin gerekli olması durumunda true döndürmelidir. substitutionFont geçerli bir Font nesnesine ayarlanmalıdır. Değiştirmenin gerekli olmadığı durumlarda false döndürmelidir. substitutionFont null olarak ayarlanabilir.

### Ayrıca Bakınız

* sınıf [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* sınıf [Font](../../font/)
* sınıf [CustomFontSubstitutionBase](../)
* ad alanı [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../../)