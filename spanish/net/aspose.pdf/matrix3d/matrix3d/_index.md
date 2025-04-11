---
title: Matrix3D.Matrix3D
second_title: Aspose.PDF for .NET API Reference
description: Constructor de Matrix3D. El constructor crea una matriz estándar 1 a 1 [ A B C D E F G H I Tx Ty Tz ] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]
type: docs
weight: 10
url: /es/net/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D() {#constructor}

El constructor crea una matriz estándar 1 a 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]

```csharp
public Matrix3D()
```

## Ejemplos

```csharp
Matrix3D m = new Matrix3D();
```

### Véase también

* clase [Matrix3D](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)

---

## Matrix3D(double[]) {#constructor_3}

El constructor acepta una matriz con la siguiente representación de array: [ A B C D E F G H I Tx Ty Tz]

```csharp
public Matrix3D(double[] matrix3DArray)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix3DArray | Double[] | Array de datos de la matriz. |

## Ejemplos

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 };
Matrix3D m = new Matrix3D(c);
```

### Véase también

* clase [Matrix3D](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)

---

## Matrix3D(Matrix3D) {#constructor_1}

El constructor acepta una matriz para crear una copia

```csharp
public Matrix3D(Matrix3D matrix)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | Matrix3D | Objeto Matrix3D. |

### Véase también

* clase [Matrix3D](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)

---

## Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

Inicializa la matriz de transformación con los coeficientes especificados.

```csharp
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, 
    double i, double tx, double ty, double tz)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | Double | Valor de la matriz A. |
| b | Double | Valor de la matriz B. |
| c | Double | Valor de la matriz C. |
| d | Double | Valor de la matriz D. |
| e | Double | Valor de la matriz E. |
| f | Double | Valor de la matriz F. |
| g | Double | Valor de la matriz G. |
| h | Double | Valor de la matriz H. |
| i | Double | Valor de la matriz I. |
| tx | Double | Valor de la matriz TX. |
| ty | Double | Valor de la matriz TY. |
| tz | Double | Valor de la matriz TZ. |

## Ejemplos

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### Véase también

* clase [Matrix3D](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)