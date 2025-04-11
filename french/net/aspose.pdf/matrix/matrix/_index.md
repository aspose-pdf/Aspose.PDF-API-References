---
title: Matrix.Matrix
second_title: Aspose.PDF for .NET API Reference
description: Constructeur de Matrix. Le constructeur crée une matrice standard 1 à 1 A B C D E F 1 0 0 1 0 0
type: docs
weight: 10
url: /fr/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

Le constructeur crée une matrice standard 1 à 1 : [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

## Exemples

```csharp
Matrix m = new Matrix();
```

### Voir aussi

* classe [Matrix](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

Le constructeur accepte une matrice avec la représentation de tableau suivante : [ A B C D E F ]

```csharp
public Matrix(double[] matrixArray)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| matrixArray | Double[] | Tableau de données de la matrice. |

## Exemples

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### Voir aussi

* classe [Matrix](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

Le constructeur accepte une matrice avec la représentation de tableau suivante : [ A B C D E F ]

```csharp
public Matrix(float[] matrixArray)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| matrixArray | Single[] | Tableau de données de la matrice. |

### Voir aussi

* classe [Matrix](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

Le constructeur accepte une matrice pour créer une copie

```csharp
public Matrix(Matrix matrix)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | Matrix | Objet matrice. |

### Voir aussi

* classe [Matrix](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

Initialise la matrice de transformation avec les coefficients spécifiés.

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| a | Double | Valeur de la matrice A. |
| b | Double | Valeur de la matrice B. |
| c | Double | Valeur de la matrice C. |
| d | Double | Valeur de la matrice D. |
| e | Double | Valeur de la matrice E. |
| f | Double | Valeur de la matrice F. |

## Exemples

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### Voir aussi

* classe [Matrix](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)