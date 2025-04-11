---
title: Matrix.Matrix
second_title: Aspose.PDF for .NET API Reference
description: مُنشئ المصفوفة. يُنشئ المُنشئ مصفوفة قياسية 1 إلى 1  A B C D E F    1 0 0 1 0 0
type: docs
weight: 10
url: /ar/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

يُنشئ المُنشئ مصفوفة قياسية 1 إلى 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

## أمثلة

```csharp
Matrix m = new Matrix();
```

### انظر أيضًا

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

يقبل المُنشئ مصفوفة بالتمثيل التالي: [ A B C D E F ]

```csharp
public Matrix(double[] matrixArray)
```

| Parameter | Type | Description |
| --- | --- | --- |
| matrixArray | Double[] | مصفوفة بيانات المصفوفة. |

## أمثلة

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### انظر أيضًا

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

يقبل المُنشئ مصفوفة بالتمثيل التالي: [ A B C D E F ]

```csharp
public Matrix(float[] matrixArray)
```

| Parameter | Type | Description |
| --- | --- | --- |
| matrixArray | Single[] | مصفوفة بيانات المصفوفة. |

### انظر أيضًا

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

يقبل المُنشئ مصفوفة لإنشاء نسخة

```csharp
public Matrix(Matrix matrix)
```

| Parameter | Type | Description |
| --- | --- | --- |
| matrix | Matrix | كائن المصفوفة. |

### انظر أيضًا

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

يُهيئ مصفوفة التحويل بالمعاملات المحددة.

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| Parameter | Type | Description |
| --- | --- | --- |
| a | Double | قيمة المصفوفة A. |
| b | Double | قيمة المصفوفة B. |
| c | Double | قيمة المصفوفة C. |
| d | Double | قيمة المصفوفة D. |
| e | Double | قيمة المصفوفة E. |
| f | Double | قيمة المصفوفة F. |

## أمثلة

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### انظر أيضًا

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)