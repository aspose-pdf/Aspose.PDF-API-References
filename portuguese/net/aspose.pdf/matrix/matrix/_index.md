---
title: Matrix.Matrix
second_title: Aspose.PDF for .NET API Reference
description: Construtor de Matrix. O construtor cria uma matriz padrão 1 para 1 A B C D E F 1 0 0 1 0 0
type: docs
weight: 10
url: /pt/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

O construtor cria uma matriz padrão 1 para 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

## Exemplos

```csharp
Matrix m = new Matrix();
```

### Veja Também

* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

O construtor aceita uma matriz com a seguinte representação de array: [ A B C D E F ]

```csharp
public Matrix(double[] matrixArray)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| matrixArray | Double[] | Array de dados da matriz. |

## Exemplos

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### Veja Também

* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

O construtor aceita uma matriz com a seguinte representação de array: [ A B C D E F ]

```csharp
public Matrix(float[] matrixArray)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| matrixArray | Single[] | Array de dados da matriz. |

### Veja Também

* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

O construtor aceita uma matriz para criar uma cópia

```csharp
public Matrix(Matrix matrix)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| matrix | Matrix | Objeto matriz. |

### Veja Também

* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

Inicializa a matriz de transformação com os coeficientes especificados.

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | Double | Valor da matriz A. |
| b | Double | Valor da matriz B. |
| c | Double | Valor da matriz C. |
| d | Double | Valor da matriz D. |
| e | Double | Valor da matriz E. |
| f | Double | Valor da matriz F. |

## Exemplos

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### Veja Também

* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)