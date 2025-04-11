---
title: Matrix.Matrix
second_title: Aspose.PDF for .NET API Reference
description: Matrix-Konstruktor. Der Konstruktor erstellt eine Standard-1-zu-1-Matrix  A B C D E F    1 0 0 1 0 0
type: docs
weight: 10
url: /de/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

Der Konstruktor erstellt eine Standard-1-zu-1-Matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

## Beispiele

```csharp
Matrix m = new Matrix();
```

### Siehe auch

* Klasse [Matrix](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

Der Konstruktor akzeptiert eine Matrix mit folgender Array-Darstellung: [ A B C D E F ]

```csharp
public Matrix(double[] matrixArray)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrixArray | Double[] | Matrix-Datenarray. |

## Beispiele

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### Siehe auch

* Klasse [Matrix](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

Der Konstruktor akzeptiert eine Matrix mit folgender Array-Darstellung: [ A B C D E F ]

```csharp
public Matrix(float[] matrixArray)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrixArray | Single[] | Matrix-Datenarray. |

### Siehe auch

* Klasse [Matrix](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

Der Konstruktor akzeptiert eine Matrix, um eine Kopie zu erstellen

```csharp
public Matrix(Matrix matrix)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | Matrix | Matrix-Objekt. |

### Siehe auch

* Klasse [Matrix](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

Initialisiert die Transformationsmatrix mit den angegebenen Koeffizienten.

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | Double | A-Matrixwert. |
| b | Double | B-Matrixwert. |
| c | Double | C-Matrixwert. |
| d | Double | D-Matrixwert. |
| e | Double | E-Matrixwert. |
| f | Double | F-Matrixwert. |

## Beispiele

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### Siehe auch

* Klasse [Matrix](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)