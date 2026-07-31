---
title: "Matrix.Rotation"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Matrix metodo. Crea la matrice per l'angolo di rotazione fornito"
type: docs
weight: 20
url: /it/net/aspose.pdf/matrix/rotation/
---
## Rotation(double) {#rotation_1}

Crea una matrice per l'angolo di rotazione specificato.

```csharp
public static Matrix Rotation(double alpha)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alpha | Double | Angolo di rotazione in radianti. |

### Valore di ritorno

Matrice di trasformazione.

## Esempi

```csharp
Matrix m = Matrix.Rotation(Math.PI / 2);
```

### Vedi anche

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Rotation(Rotation) {#rotation}

Crea una matrice per la rotazione specificata.

```csharp
public static Matrix Rotation(Rotation rotation)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotazione | Rotazione | Rotazione. I valori validi sono: None, on90, on180, on270 |

### Valore di ritorno

Matrice con rotazione.

### Vedi anche

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


