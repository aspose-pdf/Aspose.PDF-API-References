---
title: "Matrix3D.Matrix3D"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "منشئ Matrix3D. المنشئ ينشئ مصفوفة قياسية 1 إلى 1  A B C D E F G H I Tx Ty Tz   1 0 0 0 1 0 0 0 1 0 0  0"
type: docs
weight: 10
url: /ar/net/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D() {#constructor}

المُنشئ ينشئ مصفوفة قياسية 1 إلى 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]

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

المُنشئ يقبل مصفوفة بالتمثيل التالي: [ A B C D E F G H I Tx Ty Tz]

```csharp
public Matrix3D(double[] matrix3DArray)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| matrix3DArray | Double[] | مصفوفة بيانات Matrix. |

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

المنشئ يقبل مصفوفة لإنشاء نسخة

```csharp
public Matrix3D(Matrix3D matrix)
```

| معامل | النوع | الوصف |
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

| معامل | النوع | الوصف |
| --- | --- | --- |
| a | Double | قيمة مصفوفة. |
| b | Double | قيمة مصفوفة B. |
| c | Double | قيمة مصفوفة C. |
| d | Double | قيمة مصفوفة D. |
| e | Double | قيمة مصفوفة E. |
| f | Double | قيمة المصفوفة F. |
| g | Double | قيمة مصفوفة G. |
| h | Double | قيمة مصفوفة H. |
| i | Double | قيمة مصفوفة I. |
| tx | Double | قيمة مصفوفة TX. |
| ty | Double | قيمة مصفوفة TY. |
| tz | Double | قيمة مصفوفة TZ. |

## أمثلة

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### انظر أيضًا

* class [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


