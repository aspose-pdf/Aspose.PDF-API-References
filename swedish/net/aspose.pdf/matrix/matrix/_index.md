---
title: "Matrix.Matrix"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Matrix-konstruktor. Konstruktorn skapar en standard 1 till 1-matris  A B C D E F    1 0 0 1 0 0"
type: docs
weight: 10
url: /sv/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

Konstruktorn skapar en standard 1 till 1-matris: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

## Exempel

```csharp
Matrix m = new Matrix();
```

### Se även

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

Konstruktorn accepterar en matris med följande arrayrepresentation: [ A B C D E F ]

```csharp
public Matrix(double[] matrixArray)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrixArray | Double[] | Matrix-dataarray. |

## Exempel

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### Se även

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

Konstruktorn accepterar en matris med följande arrayrepresentation: [ A B C D E F ]

```csharp
public Matrix(float[] matrixArray)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrixArray | Single[] | Matrix-dataarray. |

### Se även

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

Konstruktorn accepterar en matris för att skapa en kopia

```csharp
public Matrix(Matrix matrix)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | Matrix | Matrix-objekt. |

### Se även

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

Initierar transformationsmatris med angivna koefficienter.

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | Double | Ett matrisvärde. |
| b | Double | B matrisvärde. |
| c | Double | C matrisvärde. |
| d | Double | D matrisvärde. |
| e | Double | E matrisvärde. |
| f | Double | F matrisvärde. |

## Exempel

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### Se även

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


