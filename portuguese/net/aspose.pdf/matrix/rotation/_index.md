---
title: Matrix.Rotation
second_title: Aspose.PDF for .NET API Reference
description: Método de matriz. Cria matriz para o ângulo de rotação dado
type: docs
weight: 20
url: /pt/net/aspose.pdf/matrix/rotation/
---
## Rotation(double) {#rotation_1}

Cria matriz para o ângulo de rotação dado.

```csharp
public static Matrix Rotation(double alpha)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| alpha | Double | Ângulo de rotação em radianos. |

### Valor de Retorno

Matriz de transformação.

## Exemplos

```csharp
Matrix m = Matrix.Rotation(Math.PI / 2);
```

### Veja Também

* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Rotation(Rotation) {#rotation}

Cria matriz para a rotação dada.

```csharp
public static Matrix Rotation(Rotation rotation)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rotation | Rotation | Rotação. Valores válidos são: None, on90, on180, on270 |

### Valor de Retorno

Matriz com rotação.

### Veja Também

* enum [Rotation](../../rotation/)
* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)