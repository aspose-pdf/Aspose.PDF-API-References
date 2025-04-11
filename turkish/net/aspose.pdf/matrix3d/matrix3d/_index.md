---
title: Matrix3D.Matrix3D
second_title: Aspose.PDF for .NET API Reference
description: Matrix3D yapıcısı. Yapıcı standart 1'e 1 matris oluşturur A B C D E F G H I Tx Ty Tz   1 0 0 0 1 0 0 0 1 0 0  0
type: docs
weight: 10
url: /tr/net/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D() {#constructor}

Yapıcı standart 1'e 1 matris oluşturur: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]

```csharp
public Matrix3D()
```

## Örnekler

```csharp
Matrix3D m = new Matrix3D();
```

### Ayrıca Bakınız

* sınıf [Matrix3D](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Matrix3D(double[]) {#constructor_3}

Yapıcı aşağıdaki dizi temsiline sahip bir matris kabul eder: [ A B C D E F G H I Tx Ty Tz]

```csharp
public Matrix3D(double[] matrix3DArray)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix3DArray | Double[] | Matris veri dizisi. |

## Örnekler

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 };
Matrix3D m = new Matrix3D(c);
```

### Ayrıca Bakınız

* sınıf [Matrix3D](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Matrix3D(Matrix3D) {#constructor_1}

Yapıcı bir kopya oluşturmak için bir matris kabul eder

```csharp
public Matrix3D(Matrix3D matrix)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | Matrix3D | Matrix3D nesnesi. |

### Ayrıca Bakınız

* sınıf [Matrix3D](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

Belirtilen katsayılarla dönüşüm matrisini başlatır.

```csharp
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, 
    double i, double tx, double ty, double tz)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | Double | A matris değeri. |
| b | Double | B matris değeri. |
| c | Double | C matris değeri. |
| d | Double | D matris değeri. |
| e | Double | E matris değeri. |
| f | Double | F matris değeri. |
| g | Double | G matris değeri. |
| h | Double | H matris değeri. |
| i | Double | I matris değeri. |
| tx | Double | TX matris değeri. |
| ty | Double | TY matris değeri. |
| tz | Double | TZ matris değeri. |

## Örnekler

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### Ayrıca Bakınız

* sınıf [Matrix3D](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)