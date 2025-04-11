---
title: Matrix.Transform
second_title: Aspose.PDF for .NET API Reference
description: Matris yöntemi. Bu matrisi kullanarak noktayı dönüştürür
type: docs
weight: 210
url: /tr/net/aspose.pdf/matrix/transform/
---
## Transform(Point) {#transform}

Bu matrisi kullanarak noktayı dönüştürür.

```csharp
public Point Transform(Point p)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| p | Nokta | Dönüştürülecek nokta. |

### Dönüş Değeri

Dönüşüm sonucu.

## Örnekler

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### Ayrıca Bakınız

* sınıf [Point](../../point/)
* sınıf [Matrix](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

Bu matrisi kullanarak koordinatları dönüştürür.

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | Çift | X koordinatı. |
| y | Çift | Y koordinatı. |
| x1 | Çift& | Dönüştürülmüş X koordinatı. |
| y1 | Çift& | Dönüştürülmüş Y koordinatı. |

## Örnekler

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### Ayrıca Bakınız

* sınıf [Matrix](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

Dikdörtgeni dönüştürür. Açı 90 * N derece değilse, o zaman sınırlayıcı dikdörtgen döndürülür.

```csharp
public Rectangle Transform(Rectangle rect)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Dikdörtgen | Dönüştürülecek dikdörtgen. |

### Dönüş Değeri

Dönüştürülmüş dikdörtgen.

## Örnekler

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### Ayrıca Bakınız

* sınıf [Rectangle](../../rectangle/)
* sınıf [Matrix](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)