---
title: TrySubstitute
second_title: Aspose.PDF for .NET API Referansı
description: Orijinal yazı tipini başka bir yazı tipiyle değiştirir.
type: docs
weight: 20
url: /tr/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase.TrySubstitute method

Orijinal yazı tipini başka bir yazı tipiyle değiştirir.

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | Orijinal yazı tipi özelliği. |
| substitutionFont | Font& | Değiştirme yazı tipi. |

### Geri dönüş değeri

Değiştirmenin başarılı olması durumunda doğrudur.

### Notlar

Özel yazı tipi değiştirme mantığını uygulamak için CustomFontSubstitutionBase sınıfı devralınmalıdır. TrySubstitute yöntemi düzgün bir şekilde geçersiz kılınmalıdır: Değiştirmenin gerekli olması durumunda doğru döndürülmelidir. substitutionFont, geçerli Font nesnesine ayarlanmalıdır. Değiştirmenin gerekmemesi durumunda false döndürmelidir. substitutionFont null olarak ayarlanabilir.

### Ayrıca bakınız

* class [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification)
* class [Font](../../font)
* class [CustomFontSubstitutionBase](../../customfontsubstitutionbase)
* ad alanı [Aspose.Pdf.Text](../../customfontsubstitutionbase)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->