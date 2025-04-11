---
title: Matrix3D.Matrix3D
second_title: Aspose.PDF for .NET API Reference
description: Construtor Matrix3D. O construtor cria uma matriz padrão 1 para 1 A B C D E F G H I Tx Ty Tz 1 0 0 0 1 0 0 0 1 0 0 0
type: docs
weight: 10
url: /pt/net/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D() {#constructor}

O construtor cria uma matriz padrão 1 para 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]

```csharp
public Matrix3D()
```

## Exemplos

```csharp
Matrix3D m = new Matrix3D();
```

### Veja Também

* classe [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double[]) {#constructor_3}

O construtor aceita uma matriz com a seguinte representação de array: [ A B C D E F G H I Tx Ty Tz]

```csharp
public Matrix3D(double[] matrix3DArray)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| matrix3DArray | Double[] | Array de dados da matriz. |

## Exemplos

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 };
Matrix3D m = new Matrix3D(c);
```

### Veja Também

* classe [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(Matrix3D) {#constructor_1}

O construtor aceita uma matriz para criar uma cópia

```csharp
public Matrix3D(Matrix3D matrix)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| matrix | Matrix3D | Objeto Matrix3D. |

### Veja Também

* classe [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

Inicializa a matriz de transformação com os coeficientes especificados.

```csharp
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, 
    double i, double tx, double ty, double tz)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| a | Double | Valor da matriz A. |
| b | Double | Valor da matriz B. |
| c | Double | Valor da matriz C. |
| d | Double | Valor da matriz D. |
| e | Double | Valor da matriz E. |
| f | Double | Valor da matriz F. |
| g | Double | Valor da matriz G. |
| h | Double | Valor da matriz H. |
| i | Double | Valor da matriz I. |
| tx | Double | Valor da matriz TX. |
| ty | Double | Valor da matriz TY. |
| tz | Double | Valor da matriz TZ. |

## Exemplos

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### Veja Também

* classe [Matrix3D](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)