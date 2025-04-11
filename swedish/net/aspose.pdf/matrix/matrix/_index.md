---
title: Matrix.Matrix
second_title: Aspose.PDF for .NET API Reference
description: Matrix-konstruktör. Konstruktören skapar en standard 1 till 1 matris  A B C D E F    1 0 0 1 0 0
type: docs
weight: 10
url: /sv/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

Konstruktören skapar en standard 1 till 1 matris: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

## Exempel

```csharp
Matrix m = new Matrix();
```

### Se Även

* klass [Matrix](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

Konstruktören accepterar en matris med följande array-representation: [ A B C D E F ]

```csharp
public Matrix(double[] matrixArray)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrixArray | Double[] | Matrisdata-array. |

## Exempel

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### Se Även

* klass [Matrix](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

Konstruktören accepterar en matris med följande array-representation: [ A B C D E F ]

```csharp
public Matrix(float[] matrixArray)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrixArray | Single[] | Matrisdata-array. |

### Se Även

* klass [Matrix](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

Konstruktören accepterar en matris för att skapa en kopia

```csharp
public Matrix(Matrix matrix)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | Matrix | Matrisobjekt. |

### Se Även

* klass [Matrix](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

Initierar transformationsmatrisen med angivna koefficienter.

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | Double | A matrisvärde. |
| b | Double | B matrisvärde. |
| c | Double | C matrisvärde. |
| d | Double | D matrisvärde. |
| e | Double | E matrisvärde. |
| f | Double | F matrisvärde. |

## Exempel

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### Se Även

* klass [Matrix](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)