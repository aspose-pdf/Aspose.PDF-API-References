---
title: Matrix.Multiply
second_title: Aspose.PDF for .NET API Reference
description: Método de matriz. Multiplica la matriz por otra matriz
type: docs
weight: 170
url: /es/net/aspose.pdf/matrix/multiply/
---
## Método Matrix.Multiply

Multiplica la matriz por otra matriz.

```csharp
public Matrix Multiply(Matrix other)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | Matrix | Matriz multiplicadora. |

### Valor de Retorno

Resultado de la multiplicación.

## Ejemplos

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### Ver También

* clase [Matrix](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)