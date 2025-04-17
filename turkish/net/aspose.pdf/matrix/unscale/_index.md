---
title: Matrix.UnScale
second_title: Aspose.PDF for .NET API Reference
description: Matrix metodu. x1 ve y1'i geri ölçeklendirir ve matris dönüşümünden önce x ve y'yi aşağıdaki formülü kullanarak döndürür x = D * x1 - C * y1 / A * D - C * B; y = A* y1 - B* x1 / A* D - C* B;
type: docs
weight: 220
url: /tr/net/aspose.pdf/matrix/unscale/
---
## Matrix.UnScale metodu

x1 ve y1'i geri ölçeklendirir ve matris dönüşümünden önce x ve y'yi aşağıdaki formülü kullanarak döndürür: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);

```csharp
public void UnScale(double x1, double y1, out double x, out double y)
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