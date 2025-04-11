---
title: Matrix.Multiply
second_title: Aspose.PDF for .NET API Reference
description: Método da matriz. Multiplica a matriz por outra matriz
type: docs
weight: 170
url: /pt/net/aspose.pdf/matrix/multiply/
---
## Método Matrix.Multiply

Multiplica a matriz por outra matriz.

```csharp
public Matrix Multiply(Matrix other)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | Matrix | Matriz multiplicadora. |

### Valor de Retorno

Resultado da multiplicação.

## Exemplos

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### Veja Também

* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)