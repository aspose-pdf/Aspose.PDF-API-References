---
title: Matrix3D.Matrix3D
second_title: Aspose.PDF for .NET API Reference
description: Matrix3D-konstruktör. Konstruktören skapar standard 1 till 1 matris  A B C D E F G H I Tx Ty Tz   1 0 0 0 1 0 0 0 1 0 0  0
type: docs
weight: 10
url: /sv/net/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D() {#constructor}

Konstruktören skapar standard 1 till 1 matris: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]

```csharp
public Matrix3D()
```

## Exempel

```csharp
Matrix3D m = new Matrix3D();
```

### Se Även

* klass [Matrix3D](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double[]) {#constructor_3}

Konstruktören accepterar en matris med följande array-representation: [ A B C D E F G H I Tx Ty Tz]

```csharp
public Matrix3D(double[] matrix3DArray)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix3DArray | Double[] | Matrisdata-array. |

## Exempel

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 };
Matrix3D m = new Matrix3D(c);
```

### Se Även

* klass [Matrix3D](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(Matrix3D) {#constructor_1}

Konstruktören accepterar en matris för att skapa en kopia

```csharp
public Matrix3D(Matrix3D matrix)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | Matrix3D | Matrix3D-objekt. |

### Se Även

* klass [Matrix3D](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

Initierar transformationsmatrisen med angivna koefficienter.

```csharp
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, 
    double i, double tx, double ty, double tz)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | Double | A matrisvärde. |
| b | Double | B matrisvärde. |
| c | Double | C matrisvärde. |
| d | Double | D matrisvärde. |
| e | Double | E matrisvärde. |
| f | Double | F matrisvärde. |
| g | Double | G matrisvärde. |
| h | Double | H matrisvärde. |
| i | Double | I matrisvärde. |
| tx | Double | TX matrisvärde. |
| ty | Double | TY matrisvärde. |
| tz | Double | TZ matrisvärde. |

## Exempel

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### Se Även

* klass [Matrix3D](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)