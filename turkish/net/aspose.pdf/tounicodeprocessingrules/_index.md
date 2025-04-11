---
title: Class ToUnicodeProcessingRules
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ToUnicodeProcessingRules sınıfı. Bu sınıf, Adobe Preflight hatası "Metin Unicode'a eşlenemiyor" sorununu çözmek için kullanılabilecek kuralları tanımlar.
type: docs
weight: 11110
url: /tr/net/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules sınıfı

Bu sınıf, Adobe Preflight hatası "Metin Unicode'a eşlenemiyor" sorununu çözmek için kullanılabilecek kuralları tanımlar.

```csharp
public class ToUnicodeProcessingRules
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | `ToUnicodeProcessingRules` sınıfının yeni bir örneğini başlatır. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | CMap adlarından boşlukları kaldırma seçeneği ile `ToUnicodeProcessingRules` sınıfının yeni bir örneğini başlatır. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | Belirtilen seçeneklerle `ToUnicodeProcessingRules` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | Bazı yazı tipleri, bazı metin sembolleri için unicode bilgisi sağlamaz. Bu bilgi eksikliği "Metin Unicode'a eşlenemiyor" hatasına neden olur. Bu bayrağı kullanarak, bağlantılı olmayan sembolleri unicode "boşluk" (kod 32) üzerinde eşleyebilirsiniz. |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | Bazı yazı tiplerinin isimlerinde boşluklar bulunan ToUnicode karakter kodu haritaları vardır. Bu boşluklar, unicode metin eşlemesi ile hatalara neden olabilir. Bu bayrak, ToUnicode karakter kodu haritalarının isimlerinden boşlukları kaldırmayı emreder. Varsayılan olarak false. |

### Ayrıca Bakınız

* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)