---
title: Matrix3D.Matrix3D
second_title: Aspose.PDF for .NET API Reference
description: Costruttore Matrix3D. Il costruttore crea una matrice standard 1 a 1 A B C D E F G H I Tx Ty Tz 1 0 0 0 1 0 0 0 1 0 0 0
type: docs
weight: 10
url: /it/net/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D() {#constructor}

Il costruttore crea una matrice standard 1 a 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]

```csharp
public Matrix3D()
```

## Esempi

```csharp
Matrix3D m = new Matrix3D();
```

### Vedi Anche

* classe [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double[]) {#constructor_3}

Il costruttore accetta una matrice con la seguente rappresentazione dell'array: [ A B C D E F G H I Tx Ty Tz]

```csharp
public Matrix3D(double[] matrix3DArray)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix3DArray | Double[] | Array di dati della matrice. |

## Esempi

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 };
Matrix3D m = new Matrix3D(c);
```

### Vedi Anche

* classe [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(Matrix3D) {#constructor_1}

Il costruttore accetta una matrice per creare una copia

```csharp
public Matrix3D(Matrix3D matrix)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | Matrix3D | Oggetto Matrix3D. |

### Vedi Anche

* classe [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

Inizializza la matrice di trasformazione con i coefficienti specificati.

```csharp
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, 
    double i, double tx, double ty, double tz)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | Double | Valore della matrice A. |
| b | Double | Valore della matrice B. |
| c | Double | Valore della matrice C. |
| d | Double | Valore della matrice D. |
| e | Double | Valore della matrice E. |
| f | Double | Valore della matrice F. |
| g | Double | Valore della matrice G. |
| h | Double | Valore della matrice H. |
| i | Double | Valore della matrice I. |
| tx | Double | Valore della matrice TX. |
| ty | Double | Valore della matrice TY. |
| tz | Double | Valore della matrice TZ. |

## Esempi

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### Vedi Anche

* classe [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)