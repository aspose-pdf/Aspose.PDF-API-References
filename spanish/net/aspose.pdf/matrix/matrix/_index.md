---
title: Matrix
second_title: Referencia de API de Aspose.PDF para .NET
description: Constructor crea matriz estándar 1 a 1  ABCDEF    1 0 0 1 0 0
type: docs
weight: 10
url: /es/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

Constructor crea matriz estándar 1 a 1: [ ABCDEF ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

### Ejemplos

```csharp
Matrix m = new Matrix();
```

### Ver también

* class [Matrix](../../matrix)
* espacio de nombres [Aspose.Pdf](../../matrix)
* asamblea [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

Constructor acepta una matriz con la siguiente representación de matriz: [ ABCDEF ]

```csharp
public Matrix(double[] matrixArray)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| matrixArray | Double[] | Matriz de matriz de datos. |

### Ejemplos

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### Ver también

* class [Matrix](../../matrix)
* espacio de nombres [Aspose.Pdf](../../matrix)
* asamblea [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

Constructor acepta una matriz con la siguiente representación de matriz: [ ABCDEF ]

```csharp
public Matrix(float[] matrixArray)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| matrixArray | Single[] | Matriz de matriz de datos. |

### Ver también

* class [Matrix](../../matrix)
* espacio de nombres [Aspose.Pdf](../../matrix)
* asamblea [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

Constructor acepta una matriz para crear una copia

```csharp
public Matrix(Matrix matrix)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| matrix | Matrix | Objeto matriz. |

### Ver también

* class [Matrix](../../matrix)
* espacio de nombres [Aspose.Pdf](../../matrix)
* asamblea [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

Inicializa la matriz de transformación con los coeficientes especificados.

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| a | Double | Un valor de matriz. |
| b | Double | Valor de la matriz B. |
| c | Double | Valor de la matriz C. |
| d | Double | Valor de la matriz D. |
| e | Double | Valor de la matriz E. |
| f | Double | Valor de la matriz F. |

### Ejemplos

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### Ver también

* class [Matrix](../../matrix)
* espacio de nombres [Aspose.Pdf](../../matrix)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->