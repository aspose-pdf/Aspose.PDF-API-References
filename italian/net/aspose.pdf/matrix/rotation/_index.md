---
title: Matrix.Rotation
second_title: Aspose.PDF for .NET API Reference
description: Metodo matrice. Crea matrice per l'angolo di rotazione dato
type: docs
weight: 20
url: /it/net/aspose.pdf/matrix/rotation/
---
## Rotation(double) {#rotation_1}

Crea matrice per l'angolo di rotazione dato.

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

### Vedi Anche

* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Rotation(Rotation) {#rotation}

Crea matrice per la rotazione data.

```csharp
public static Matrix Rotation(Rotation rotation)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotation | Rotation | Rotazione. I valori validi sono: None, on90, on180, on270 |

### Valore di ritorno

Matrice con rotazione.

### Vedi Anche

* enum [Rotation](../../rotation/)
* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)