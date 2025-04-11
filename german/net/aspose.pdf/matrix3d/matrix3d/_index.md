---
title: Matrix3D.Matrix3D
second_title: Aspose.PDF for .NET API Reference
description: Matrix3D-Konstruktor. Der Konstruktor erstellt eine Standard-1-zu-1-Matrix A B C D E F G H I Tx Ty Tz 1 0 0 0 1 0 0 0 1 0 0 0
type: docs
weight: 10
url: /de/net/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D() {#constructor}

Der Konstruktor erstellt eine Standard-1-zu-1-Matrix: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]

```csharp
public Matrix3D()
```

## Beispiele

```csharp
Matrix3D m = new Matrix3D();
```

### Siehe auch

* Klasse [Matrix3D](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Matrix3D(double[]) {#constructor_3}

Der Konstruktor akzeptiert eine Matrix mit folgender Array-Darstellung: [ A B C D E F G H I Tx Ty Tz]

```csharp
public Matrix3D(double[] matrix3DArray)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix3DArray | Double[] | Matrixdaten-Array. |

## Beispiele

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 };
Matrix3D m = new Matrix3D(c);
```

### Siehe auch

* Klasse [Matrix3D](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Matrix3D(Matrix3D) {#constructor_1}

Der Konstruktor akzeptiert eine Matrix, um eine Kopie zu erstellen

```csharp
public Matrix3D(Matrix3D matrix)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | Matrix3D | Matrix3D-Objekt. |

### Siehe auch

* Klasse [Matrix3D](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

Initialisiert die Transformationsmatrix mit den angegebenen Koeffizienten.

```csharp
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, 
    double i, double tx, double ty, double tz)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | Double | Ein Matrixwert. |
| b | Double | B Matrixwert. |
| c | Double | C Matrixwert. |
| d | Double | D Matrixwert. |
| e | Double | E Matrixwert. |
| f | Double | F Matrixwert. |
| g | Double | G Matrixwert. |
| h | Double | H Matrixwert. |
| i | Double | I Matrixwert. |
| tx | Double | TX Matrixwert. |
| ty | Double | TY Matrixwert. |
| tz | Double | TZ Matrixwert. |

## Beispiele

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### Siehe auch

* Klasse [Matrix3D](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)