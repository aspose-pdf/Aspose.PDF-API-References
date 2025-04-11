---
title: Matrix.Rotation
second_title: Aspose.PDF for .NET API Reference
description: Método de matriz. Crea una matriz para el ángulo de rotación dado
type: docs
weight: 20
url: /es/net/aspose.pdf/matrix/rotation/
---
## Rotation(double) {#rotation_1}

Crea una matriz para el ángulo de rotación dado.

```csharp
public static Matrix Rotation(double alpha)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alpha | Doble | Ángulo de rotación en radianes. |

### Valor de Retorno

Matriz de transformación.

## Ejemplos

```csharp
Matrix m = Matrix.Rotation(Math.PI / 2);
```

### Ver También

* clase [Matrix](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)

---

## Rotation(Rotation) {#rotation}

Crea una matriz para la rotación dada.

```csharp
public static Matrix Rotation(Rotation rotation)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotation | Rotación | Rotación. Los valores válidos son: Ninguno, on90, on180, on270 |

### Valor de Retorno

Matriz con rotación.

### Ver También

* enum [Rotation](../../rotation/)
* clase [Matrix](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)