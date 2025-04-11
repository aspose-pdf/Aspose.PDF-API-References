---
title: Matrix.Rotation
second_title: Aspose.PDF for .NET API Reference
description: Matrismetod. Skapar matris för given rotationsvinkel
type: docs
weight: 20
url: /sv/net/aspose.pdf/matrix/rotation/
---
## Rotation(double) {#rotation_1}

Skapar matris för given rotationsvinkel.

```csharp
public static Matrix Rotation(double alpha)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alpha | Dubbel | Rotationsvinkel i radianer. |

### Returvärde

Transformationsmatris.

## Exempel

```csharp
Matrix m = Matrix.Rotation(Math.PI / 2);
```

### Se Även

* klass [Matrix](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Rotation(Rotation) {#rotation}

Skapar matris för given rotation.

```csharp
public static Matrix Rotation(Rotation rotation)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotation | Rotation | Rotation. Giltiga värden är: None, on90, on180, on270 |

### Returvärde

Matris med rotation.

### Se Även

* enum [Rotation](../../rotation/)
* klass [Matrix](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)