---
title: Enum LoadOptions.MarginsAreaUsageModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsMarginsAreaUsageModes enum. Dönüşüm sırasında kenar boşluğu alanının kullanım modunu temsil eder, kenar boşluklarının kullanımıyla ilgili olarak içe aktarılan formatın talimatlarının işlenmesini tanımlar.
type: docs
weight: 6130
url: /tr/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## LoadOptions.MarginsAreaUsageModes enumerasyonu

Dönüşüm sırasında kenar boşluğu alanının kullanım modunu temsil eder (HTML, EPUB vb. gibi), kenar boşluklarının kullanımıyla ilgili olarak içe aktarılan formatın talimatlarının işlenmesini tanımlar.

```csharp
public enum MarginsAreaUsageModes
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | Bu modda dönüştürücü, kenar boşluğu alanının kullanımında içe aktarılan belgenin formatına (örneğin, içe aktarılan HTML'nin CSS'si) uyar. Yani, içe aktarılan belgenin formatı, render için kenar boşluğu alanının kullanımını gerektiriyorsa, dönüştürücü buna izin verecektir. |
| NeverPutContentOnMarginArea | `1` | Bu mod, kenar boşluğu alanının kullanımını kesinlikle yasaklar, bu nedenle dönüştürücü, kaynak belgenin CSS'si veya formatı buna izin verse bile, render için kenar boşluğu alanını asla kullanmayacaktır. |

### Ayrıca Bakınız

* sınıf [LoadOptions](../loadoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)