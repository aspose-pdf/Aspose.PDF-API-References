---
title: Matrix.Scale
second_title: Aspose.PDF for .NET API Reference
description: Matris yöntemi. Aşağıdaki formülü kullanarak matris ile x ve y'yi ölçeklendirir: x1 = A*x + C*y; y1 = B*x + D*y
type: docs
weight: 190
url: /tr/net/aspose.pdf/matrix/scale/
---
## Ölçek(double, double, out double, out double)

Aşağıdaki formülü kullanarak matris ile x ve y'yi ölçeklendirir: x1 = A*x + C*y; y1 = B*x + D*y;

```csharp
public void Scale(double x, double y, out double x1, out double y1)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | Double | Girdi X koordinatı |
| y | Double | Girdi Y koordinatı |
| x1 | Double& | Çıktı X koordinatı |
| y1 | Double& | Çıktı Y koordinatı |

### Ayrıca Bakınız

* sınıf [Matrix](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Ölçek(double, double, Matrix)

Verilen matrise ölçeklendirme uygular.

```csharp
public static Matrix Scale(double sx, double sy, Matrix source)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sx | Double | X ekseni için ölçekleme faktörü. |
| sy | Double | Y ekseni için ölçekleme faktörü. |
| source | Matrix | Ölçeklendirilecek matris. |

### Dönüş Değeri

Kaynak matrisin ölçeklendirilmesi sonucu elde edilen yeni bir matris.

### Ayrıca Bakınız

* sınıf [Matrix](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)