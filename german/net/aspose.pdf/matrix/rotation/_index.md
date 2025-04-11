---
title: Matrix.Rotation
second_title: Aspose.PDF for .NET API Reference
description: Matrixmethode. Erstellt eine Matrix für den gegebenen Rotationswinkel
type: docs
weight: 20
url: /de/net/aspose.pdf/matrix/rotation/
---
## Rotation(double) {#rotation_1}

Erstellt eine Matrix für den gegebenen Rotationswinkel.

```csharp
public static Matrix Rotation(double alpha)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alpha | Double | Rotationswinkel in Bogenmaß. |

### Rückgabewert

Transformationsmatrix.

## Beispiele

```csharp
Matrix m = Matrix.Rotation(Math.PI / 2);
```

### Siehe auch

* Klasse [Matrix](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Rotation(Rotation) {#rotation}

Erstellt eine Matrix für die gegebene Rotation.

```csharp
public static Matrix Rotation(Rotation rotation)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotation | Rotation | Rotation. Gültige Werte sind: None, on90, on180, on270 |

### Rückgabewert

Matrix mit Rotation.

### Siehe auch

* Enum [Rotation](../../rotation/)
* Klasse [Matrix](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)