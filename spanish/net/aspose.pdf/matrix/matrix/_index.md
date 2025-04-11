---
title: Matrix.Matrix
second_title: Aspose.PDF for .NET API Reference
description: Constructor de Matrix. El constructor crea una matriz estándar 1 a 1 A B C D E F 1 0 0 1 0 0
type: docs
weight: 10
url: /es/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

El constructor crea una matriz estándar 1 a 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

## Ejemplos

```csharp
Matrix m = new Matrix();
```

### Véase también

* clase [Matrix](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

El constructor acepta una matriz con la siguiente representación de array: [ A B C D E F ]

```csharp
public Matrix(double[] matrixArray)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrixArray | Double[] | Array de datos de la matriz. |

## Ejemplos

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### Véase también

* clase [Matrix](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

El constructor acepta una matriz con la siguiente representación de array: [ A B C D E F ]

```csharp
public Matrix(float[] matrixArray)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrixArray | Single[] | Array de datos de la matriz. |

### Véase también

* clase [Matrix](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

El constructor acepta una matriz para crear una copia

```csharp
public Matrix(Matrix matrix)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | Matrix | Objeto de matriz. |

### Véase también

* clase [Matrix](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

Inicializa la matriz de transformación con los coeficientes especificados.

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | Double | Valor de la matriz A. |
| b | Double | Valor de la matriz B. |
| c | Double | Valor de la matriz C. |
| d | Double | Valor de la matriz D. |
| e | Double | Valor de la matriz E. |
| f | Double | Valor de la matriz F. |

## Ejemplos

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### Véase también

* clase [Matrix](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)