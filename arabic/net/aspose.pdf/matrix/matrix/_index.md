---
title: "Matrix.Matrix"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "منشئ Matrix. المنشئ ينشئ مصفوفة قياسية 1 إلى 1  A B C D E F    1 0 0 1 0 0"
type: docs
weight: 10
url: /ar/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

المنشئ ينشئ مصفوفة قياسية 1 إلى 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

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

المنشئ يقبل مصفوفة بالتمثيل الصفيفي التالي: [ A B C D E F ]

```csharp
public Matrix(double[] matrixArray)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| matrixArray | Double[] | مصفوفة بيانات Matrix. |

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

المنشئ يقبل مصفوفة بالتمثيل الصفيفي التالي: [ A B C D E F ]

```csharp
public Matrix(float[] matrixArray)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| matrixArray | Single[] | مصفوفة بيانات Matrix. |

### انظر أيضًا

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

المنشئ يقبل مصفوفة لإنشاء نسخة

```csharp
public Matrix(Matrix matrix)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| matrix | Matrix | كائن Matrix. |

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

| معامل | النوع | الوصف |
| --- | --- | --- |
| a | Double | قيمة مصفوفة. |
| b | Double | قيمة مصفوفة B. |
| c | Double | قيمة مصفوفة C. |
| d | Double | قيمة مصفوفة D. |
| e | Double | قيمة مصفوفة E. |
| f | Double | قيمة المصفوفة F. |

## أمثلة

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### انظر أيضًا

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


