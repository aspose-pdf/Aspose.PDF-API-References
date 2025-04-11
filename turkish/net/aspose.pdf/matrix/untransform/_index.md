---
title: Matrix.UnTransform
second_title: Aspose.PDF for .NET API Reference
description: Matris metodu. Aşağıdaki formülü kullanarak x1 ve y1'i geri dönüştürür ve matris dönüşümünden önce x ve y'yi döndürür: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).
type: docs
weight: 230
url: /tr/net/aspose.pdf/matrix/untransform/
---
## Matrix.UnTransform metodu

Aşağıdaki formülü kullanarak x1 ve y1'i geri dönüştürür ve matris dönüşümünden önce x ve y'yi döndürür: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

```csharp
public void UnTransform(double x1, double y1, out double x, out double y)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x1 | Double | Girdi X koordinatı |
| y1 | Double | Girdi Y koordinatı |
| x | Double& | Çıktı X koordinatı |
| y | Double& | Çıktı Y koordinatı |

### Ayrıca Bakınız

* sınıf [Matrix](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)