---
title: "Matrix.Matrix"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Costruttore Matrix. Il costruttore crea una matrice standard 1 a 1  A B C D E F    1 0 0 1 0 0"
type: docs
weight: 10
url: /it/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

Il costruttore crea una matrice standard 1 a 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

## Esempi

```csharp
Matrix m = new Matrix();
```

### Vedi anche

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

Il costruttore accetta una matrice con la seguente rappresentazione di array: [ A B C D E F ]

```csharp
public Matrix(double[] matrixArray)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrixArray | Double[] | Array di dati Matrix. |

## Esempi

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### Vedi anche

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

Il costruttore accetta una matrice con la seguente rappresentazione di array: [ A B C D E F ]

```csharp
public Matrix(float[] matrixArray)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrixArray | Single[] | Array di dati Matrix. |

### Vedi anche

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

Il costruttore accetta una matrice per creare una copia

```csharp
public Matrix(Matrix matrix)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | Matrix | Oggetto Matrix. |

### Vedi anche

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

Inizializza la matrice di trasformazione con i coefficienti specificati.

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | Double | Un valore di matrice. |
| b | Double | Valore di matrice B. |
| c | Double | Valore di matrice C. |
| d | Double | Valore di matrice D. |
| e | Double | Valore di matrice E. |
| f | Double | Valore della matrice F. |

## Esempi

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### Vedi anche

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


