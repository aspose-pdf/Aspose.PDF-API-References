---
title: Matrix.GetAngle
second_title: Aspose.PDF for .NET API Reference
description: Metode Matrix. Menerjemahkan rotasi menjadi derajat sudut
type: docs
weight: 240
url: /id/net/aspose.pdf/matrix/getangle/
---
## Metode Matrix.GetAngle

Menerjemahkan rotasi menjadi sudut (derajat)

```csharp
public static double GetAngle(Rotation rotation)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rotation | Rotasi | Nilai rotasi. |

### Nilai Kembali

Nilai sudut.

## Contoh

```csharp
double angle = Matrix.GetAngle(Rotation.on90);
Matrix m = Matrix.Rotation(angle);
```

### Lihat Juga

* enum [Rotasi](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)