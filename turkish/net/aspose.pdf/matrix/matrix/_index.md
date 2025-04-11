---
title: Matrix.Matrix
second_title: Aspose.PDF for .NET API Reference
description: Matrix yapıcısı. Yapıcı standart 1'e 1 matris oluşturur A B C D E F    1 0 0 1 0 0
type: docs
weight: 10
url: /tr/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

Yapıcı standart 1'e 1 matris oluşturur: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

## Örnekler

```csharp
Matrix m = new Matrix();
```

### Ayrıca Bakınız

* sınıf [Matrix](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

Yapıcı, aşağıdaki dizi temsiline sahip bir matris kabul eder: [ A B C D E F ]

```csharp
public Matrix(double[] matrixArray)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrixArray | Double[] | Matris veri dizisi. |

## Örnekler

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### Ayrıca Bakınız

* sınıf [Matrix](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

Yapıcı, aşağıdaki dizi temsiline sahip bir matris kabul eder: [ A B C D E F ]

```csharp
public Matrix(float[] matrixArray)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrixArray | Single[] | Matris veri dizisi. |

### Ayrıca Bakınız

* sınıf [Matrix](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

Yapıcı, bir kopya oluşturmak için bir matris kabul eder

```csharp
public Matrix(Matrix matrix)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | Matrix | Matris nesnesi. |

### Ayrıca Bakınız

* sınıf [Matrix](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

Belirtilen katsayılarla dönüşüm matrisini başlatır.

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | Double | A matris değeri. |
| b | Double | B matris değeri. |
| c | Double | C matris değeri. |
| d | Double | D matris değeri. |
| e | Double | E matris değeri. |
| f | Double | F matris değeri. |

## Örnekler

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### Ayrıca Bakınız

* sınıf [Matrix](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)