---
title: Matrix3D.Matrix3D
second_title: Aspose.PDF for .NET API Reference
description: مُنشئ Matrix3D. يُنشئ المُنشئ مصفوفة قياسية 1 إلى 1  A B C D E F G H I Tx Ty Tz   1 0 0 0 1 0 0 0 1 0 0  0
type: docs
weight: 10
url: /ar/net/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D() {#constructor}

يُنشئ المُنشئ مصفوفة قياسية 1 إلى 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]

```csharp
public Matrix3D()
```

## أمثلة

```csharp
Matrix3D m = new Matrix3D();
```

### انظر أيضًا

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double[]) {#constructor_3}

يقبل المُنشئ مصفوفة بالتمثيل التالي: [ A B C D E F G H I Tx Ty Tz]

```csharp
public Matrix3D(double[] matrix3DArray)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| matrix3DArray | Double[] | مصفوفة بيانات المصفوفة. |

## أمثلة

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 };
Matrix3D m = new Matrix3D(c);
```

### انظر أيضًا

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(Matrix3D) {#constructor_1}

يقبل المُنشئ مصفوفة لإنشاء نسخة

```csharp
public Matrix3D(Matrix3D matrix)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| matrix | Matrix3D | كائن Matrix3D. |

### انظر أيضًا

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

يُهيئ مصفوفة التحويل بالمعاملات المحددة.

```csharp
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, 
    double i, double tx, double ty, double tz)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| a | Double | قيمة المصفوفة A. |
| b | Double | قيمة المصفوفة B. |
| c | Double | قيمة المصفوفة C. |
| d | Double | قيمة المصفوفة D. |
| e | Double | قيمة المصفوفة E. |
| f | Double | قيمة المصفوفة F. |
| g | Double | قيمة المصفوفة G. |
| h | Double | قيمة المصفوفة H. |
| i | Double | قيمة المصفوفة I. |
| tx | Double | قيمة المصفوفة TX. |
| ty | Double | قيمة المصفوفة TY. |
| tz | Double | قيمة المصفوفة TZ. |

## أمثلة

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### انظر أيضًا

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)