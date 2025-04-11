---
title: Matrix3D.Matrix3D
second_title: Aspose.PDF for .NET API Reference
description: Constructeur Matrix3D. Le constructeur crée une matrice standard 1 à 1 A B C D E F G H I Tx Ty Tz 1 0 0 0 1 0 0 0 1 0 0 0
type: docs
weight: 10
url: /fr/net/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D() {#constructor}

Le constructeur crée une matrice standard 1 à 1 : [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]

```csharp
public Matrix3D()
```

## Exemples

```csharp
Matrix3D m = new Matrix3D();
```

### Voir aussi

* classe [Matrix3D](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double[]) {#constructor_3}

Le constructeur accepte une matrice avec la représentation de tableau suivante : [ A B C D E F G H I Tx Ty Tz]

```csharp
public Matrix3D(double[] matrix3DArray)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| matrix3DArray | Double[] | Tableau de données de la matrice. |

## Exemples

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 };
Matrix3D m = new Matrix3D(c);
```

### Voir aussi

* classe [Matrix3D](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(Matrix3D) {#constructor_1}

Le constructeur accepte une matrice pour créer une copie

```csharp
public Matrix3D(Matrix3D matrix)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| matrix | Matrix3D | Objet Matrix3D. |

### Voir aussi

* classe [Matrix3D](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

Initialise la matrice de transformation avec les coefficients spécifiés.

```csharp
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, 
    double i, double tx, double ty, double tz)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| a | Double | Valeur de la matrice A. |
| b | Double | Valeur de la matrice B. |
| c | Double | Valeur de la matrice C. |
| d | Double | Valeur de la matrice D. |
| e | Double | Valeur de la matrice E. |
| f | Double | Valeur de la matrice F. |
| g | Double | Valeur de la matrice G. |
| h | Double | Valeur de la matrice H. |
| i | Double | Valeur de la matrice I. |
| tx | Double | Valeur de la matrice TX. |
| ty | Double | Valeur de la matrice TY. |
| tz | Double | Valeur de la matrice TZ. |

## Exemples

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### Voir aussi

* classe [Matrix3D](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)